# BTC PAF 04 My Setup — 课程知识笔记

## 课程定位

- **精确课程 stem：** `BTC PAF 04 My Setup`
- **时长：** 00:06:57.750
- **主题：** Brooks 的工作环境、屏幕布局、图表数据身份与均线显示配置。
- **核心消歧：** 本课的 `setup` 是“配置”，不是 BTC PAF 01 中可能形成交易的 `trade setup`。全片没有 Signal Bar、Entry Bar、方向、止损、目标、仓位或持仓管理规则。
- **市场范围：** 画面涉及 S&P 500 ES E-mini、EURUSD 和 S&P 500 cash index；文件名前缀 `BTC PAF` 不能解释为 Bitcoin 课程。
课程只有不到 7 分钟，但知识主线很清晰：先降低干扰，再统一图表输入，最后用透明、可解释的方式把高周期背景带到 5 分钟主图。配置的价值是减少读图错误，不是制造交易信号。

## 核心结论

1. **同为 5 分钟图，不等于输入相同。** RTH/day session 与 ETH/Globex 纳入不同 bars；单季度合约与 continuation contract series 也会形成不同价格序列。比较 bars 或 EMA 前，必须先统一图表身份。
2. **Brooks 的 TradeStation plotter 与普通长周期 EMA 不是同一种实现。** 可见代码使用 5 分钟图的 `C`，以 60/240 根 5 分钟 close 初始化，并在 15/60 分钟时间边界递推状态、边界之间显示临时值。它是高周期 EMA 的程序化递推/仿真；课程称其相当准确，但画面没有证明它读取独立的 15/60 分钟数据源，也没有证明数值等价。
3. **EMA50/EMA220 是更简单的 proxy。** `3×20=60→50`、`12×20=240→220` 是 Brooks 给出的经验修正，不是数学恒等式、跨平台真值或默认交易参数。
4. **高周期线的权重依市场而变。** Brooks 在股票日线上增加 50/100/150/200 SMA，因为许多股票交易者关注这些线；他对 Forex 日/周/月图上的同组 SMA 关注少得多。
5. **工作站设计服务于注意力与 Context。** 两台电脑、关闭百叶窗、减少电话电视新闻和他人意见，都是输入过滤。第二台电脑用于 chat room，并放有额外的 15 分钟、60 分钟和日线图；这些周期来自旁白，办公室照片的小屏幕不足以逐项确认。
6. **均线和屏幕布局都只是信息组织。** 无论代码型 plotter、EMA50/220 proxy，还是股票 SMA 触线图例，都不能替代价格行为 setup、触发、风险与管理。

## 知识讲解

### 3.1 工作环境：减少叙事输入，保留价格反馈（00:11–01:07）

Brooks 使用两台笔记本：一台交易，另一台用于 chat room，并显示额外的 15m、60m 和 daily charts。他关闭百叶窗，除孩子来电外不接电话，不看电视，总是过滤新闻和电视评论者，也不希望受到他人意见干扰。

这段内容的可迁移原则是**注意力管理**：减少盘中改变计划的叙事输入，让决策回到价格结构和实际反应。它不等于事件风险不存在，也不要求所有交易者屏蔽必要的系统、流动性或事件监控。

Brooks 随后用“双方都试图从对方账户获利”的 game 语言强化竞争意识。其合理含义是认真准备和保持纪律，不是提高仓位、攻击性加仓或过度交易。

### 3.2 主图与多周期信息布局（01:07–01:55；02:50–03:48）

Brooks 全天主要观察 5 分钟图。ES 与 EURUSD 5 分钟图都显示：

- 当前 5m EMA20；
- 15m EMA20 的显示线；
- 60m EMA20 的显示线。

交易室截图另有 60m、15m、day、week、month 窗格。Brooks 同时高度关注 trend lines、Measured Moves 和 prior highs/lows；录制时的当前布局因为拥挤，已经删去周线和月线窗。

这里的重点不是“线越多越好”，而是给主执行尺度提供必要的高周期背景。多窗口或多均线一旦遮挡 bars、降低可读性，就违背了配置的目的。

### 3.3 图表身份：Session template 与 contract series（01:55–02:50）

Slide 4 对比了两类输入：

| 用户可能使用的图 | Brooks 的图 |
|---|---|
| 24-hour data / ETH / Globex | day session / RTH |
| quarterly contracts | continuation contracts |
| 课件写 `may be above the MA` | 课件写 `many bars below the MA` |

RTH 与 ETH 是否纳入隔夜 bars，会改变价格结构和 EMA。Brooks 特别指出，开盘后第一个小时左右差异往往明显。Quarterly contract 指 December、March、June、September 中某一交割月份的合约序列，不是三个月周期 K 线；continuation series 则跨合约拼接，但本课没有定义换月、主力选择、拼接或复权算法。

因此，复盘或比较课程图时，图表身份至少要记录：

`品种 + 聚合周期 + session + contract series + 平台/时区 + 均线来源`

任一关键字段未知时，线位和形态比较都应降级。

### 3.4 两种 EMA 显示方法（03:48–05:39）

#### A. Brooks 的程序化 plotter

两页 TradeStation 代码都运行在 5 分钟图的语境中：

- 60m 页用 `XAverage(C,240)` 初始化，在代码预设的 60 分钟边界或指定 session end 递推 `_length(20)` 状态；
- 15m 页用 `XAverage(C,60)` 初始化，在 15 分钟边界递推 `_length(20)` 状态；
- 边界之间继续用当前 5 分钟 close 计算临时显示值。

所以它与单纯把 5 分钟 EMA period 设成 60 或 240 不同：它把更新时间节奏写进了程序。但画面只证明算法意图，**不能把它写成读取独立高周期 bars 的“真值”**。代码未在本项目中编译、运行或与独立 15m/60m 数据序列做数值对比。

#### B. 普通平台 EMA proxy

无法使用代码时，Brooks 给出更简单的近似：

- `15/5=3`，`3×20=60`，但课程称 50 通常比 60 更好；
- `60/5=12`，`12×20=240`，但课程称 220 比 240 更好。

英文的 `that number is always too high` 指 **period 参数 240 过大**，不是“EMA240 的输出价格一定偏高”。`overlapping bars` 指 K 线 high-low 区间重叠，也不等于收盘价重复。

程序化 plotter 与普通 EMA50/220 proxy 都需要验证，但二者不可合并：

- 前者按高周期时间边界递推状态；
- 后者仍是每根 5 分钟 bar 更新的普通长周期 EMA；
- 课程没有提供两者的误差研究、样本、平台范围或跨市场验证。

### 3.5 股票与 Forex 的均线权重（05:39–06:48）

Brooks 经常看日线 EMA20。交易股票时，他还增加 50/100/150/200 SMA，因为许多股票交易者关注它们。S&P 500 cash-index 日线图展示了价格多次接近 100 SMA，以及一次跌破 100 后在 150 附近转涨。

画面只支持“接近、交叠或穿越后的历史反应”，不支持 `low == 150 SMA` 的精确等式，更不支持触线必买。均线至多是 Context/S/R 候选，仍需市场状态、bar 质量和 follow-through。

Forex 段的旁白谈日、周、月图，但画面只显示 EURUSD daily。Brooks 说自己通常会看这四条 SMA，不过关注度明显低于股票；这是带有 `typically` 和 `I think` 的个人判断，不是“Forex 均线完全无用”的普遍定理。

## 决策模型

### 4.1 比较图表

`准备复现课程图或比较 EMA`  
→ 核对品种、5m 聚合、RTH/ETH、单季度/连续合约、平台与时区  
→ 统一输入后再比较 bars、价格和均线  
→ 若 session 或 contract 构造未知，则降级线位结论  
→ 不把数据身份差异误判成价格行为信号。

### 4.2 选择 EMA 显示

`需要在 5m 主图显示 15m/60m EMA20 背景`  
→ 先判断平台能否提供独立高周期数据或经过验证的多周期实现  
→ 若采用 Brooks 式 plotter，明确它基于 5m close、按高周期边界递推  
→ 若采用普通 EMA50/220，明确标为 proxy  
→ 在相同 session、contract series 和历史窗口上与独立高周期基准比较误差  
→ 关键区域偏差不可接受时，改看独立高周期图，不把任一近似称为真值。

### 4.3 使用 SMA Context

`股票日线接近 50/100/150/200 SMA`  
→ 检查实际是 low、body、close 还是大致区域接触  
→ 结合市场状态、前高低和 follow-through  
→ 只把均线列为可能受关注的 Context  
→ 另行要求 trade setup、trigger、stop、size 和 management  
→ 持续穿越且无反应时降低该线权重。

### 4.4 过滤输入

`盘中叙事输入影响执行`  
→ 关闭非必要电话、电视、评论和意见流  
→ 保留系统、流动性和必要事件风险通道  
→ 以价格结构、实际反应和预先计划更新判断  
→ 若过滤导致风险盲区，立即恢复必要监控。

## 关键概念

| 英文术语 | 推荐中文 | 本课识别与边界 |
|---|---|---|
| Setup | 配置/工作站与图表设置 | 本课是 Sense B，不是交易形态；不产生 Signal/Entry、方向或风险参数 |
| Day session / RTH | 日盘/常规交易时段 | 决定哪些 bars 进入图表与 EMA；本课未给通用精确时钟 |
| Globex / ETH / 24-hour data | Globex/延长时段数据 | 纳入日盘外 bars；课件的 `24 hour` 是类别表述，不能直接等同固定交易小时数 |
| Quarterly contract chart | 单季度交割合约图 | 指某个交割月份的合约序列，不是季度 K 线 |
| Continuation contract series | 连续合约序列 | 跨合约拼接；本课未定义换月、主力、拼接或复权算法 |
| Programmed HTF EMA plotter | 程序化高周期 EMA 递推显示 | 在 5m close 上初始化并按 15/60m 边界递推；未证明读取独立 HTF 数据源或数值等价 |
| EMA proxy | EMA 代理近似 | 普通 5m EMA50/220 近似 15m/60m EMA20；无误差研究 |
| EMA period parameter | EMA 周期参数 | 50、60、220、240 是输入 period，不是均线输出价格 |
| Overlapping bars | 区间重叠的 K 线 | high-low 区间重叠，不要求 close 相同 |
| Simple Moving Average / SMA | 简单移动平均线 | 股票日线另看 50/100/150/200；历史触线不是自动 entry |

## 案例与反例

| 时间 | 案例 | 正确读取 | 被否决的读法 |
|---|---|---|---|
| 00:11–00:53 | 两台笔记本与抗干扰 | 一台交易；第二台用于 chat room 和额外 15m/60m/daily 图；减少干扰 | “直播”是英文原词；照片足以辨认第二台每个周期 |
| 01:07–01:55 | ES 5m 三线 | 5m EMA20 加两条程序化高周期显示线 | 三条都是普通 5m 长周期 EMA |
| 01:55–02:50 | ETH/quarterly 对比 RTH/continuation | 图表身份可解释 bars 与 EMA 差异 | 同为 5m 就必须完全一致；左图每根 low 都严格在 EMA 上方 |
| 03:48–04:22 | 两页 TradeStation 代码 | 代码基于 5m close 并按 15/60m 时间边界递推 | 已证明读取独立高周期 bars；可直接复制并跨版本部署 |
| 04:22–05:39 | 50/60/220/240 | 课程经验 proxy；参数需本地误差验证 | EMA220 精确等于 60m EMA20；240 表示输出价格偏高 |
| 05:39–06:24 | S&P 500 四 SMA | 有限历史互动，可能形成 Context 候选 | 触及 100/150 SMA 就必然反弹或应立即买入 |
| 06:24–06:48 | EURUSD 四 SMA | Brooks 个人降低权重；画面只展示 daily | 标题写 Daily/Weekly/Monthly 就表示画面有三张图；Forex 均线完全无用 |

## 知识连接

- **BTC PAF 01 Terminology：** `Setup` 在 01 是可能产生交易的价格行为候选；本课是工作站与图表配置。01 的“未限定 MA 通常指 EMA20”与本课明确标注的 SMA 例外并不冲突。
- **BTC PAF 02A Chart Basics and Price Action：** 02A 讲 Time/Volume/Tick bars 与 OHLC 信息边界；本课把 session template 与 contract series 加入 chart identity。
- **BTC PAF 02B Chart Basics and Price Action：** 02B 要看新闻相对预期后的实际价格反应；本课展示 Brooks 过滤新闻和评论的个人工作流。一个管理叙事输入，一个观察价格反馈，层级不同。
- **BTC PAF 02D Chart Basics and Price Action：** 02D 反对指标遮挡 bars 或替代 Context；本课展示用途透明的显示工具。透明不等于已经通过数值 QA，也不等于方向信号。
- **长期库落点：** `Setup` 双义、RTH/ETH、quarterly/continuation、程序化 plotter 与普通 EMA proxy 的区分属于概念层；图表身份预检属于决策树；period/输出混淆属于翻译与机械错误台账。

## 复习提纲

### 一分钟复述

Brooks 的 setup 先从环境开始：两台电脑，第二台用于 chat room 和额外的 15m、60m、日线图；同时减少电话、电视、新闻与他人意见带来的干扰。主交易图是 5 分钟图，并显示 15m/60m EMA20 背景。复现他的图前必须统一 RTH/ETH 和 quarterly/continuation，否则 bars 与 EMA 可能不同。TradeStation 代码是在 5m close 上初始化并按高周期边界递推的程序化显示，未证明使用独立 HTF 数据源；普通 EMA50/220 则是更简单的 proxy。股票的 50/100/150/200 SMA 可能因参与者关注而有参考价值，但 Forex 权重较低，所有均线都不是自动入场。

### 主动回忆

1. 本课的 `setup` 与 trade setup 有何不同？
2. 为什么两个名义相同的 5 分钟图可能有不同 bars 和 EMA？
3. `quarterly contract chart` 为什么不是三个月 K 线图？
4. Brooks 的程序化 plotter 实际使用什么输入、在什么边界更新？
5. 它与普通 EMA50/220 proxy 有何区别？
6. `number too high` 为什么不能译为 EMA 输出价格偏高？
7. 股票 SMA 图为什么不能直接转成 touch-entry？
8. 第二台电脑的额外周期由什么证据支持，画面又有什么限制？

### 推荐回看

- 00:11–00:53：两台电脑、额外图表与抗干扰
- 01:07–01:55：ES 三条 EMA 的线型和来源
- 01:55–02:50：RTH/ETH 与 quarterly/continuation
- 03:01–03:48：六窗布局与主图重点
- 03:48–04:22：两页 TradeStation 代码
- 04:22–05:39：240/220 与 60/50 的完整限定
- 05:39–06:48：股票与 Forex 均线权重边界

## 证据边界

- **总体置信度：高。** 课程主线、图表身份、代码页和均线案例在英文字幕、课件与完整视觉时间线之间相互支持。
- 代码只做画面与算法语义审查，未编译、未执行，也未与独立 HTF 数据序列比较。
- `50/220`、股票 SMA 反应和 Forex 参与者关注度都属于课程主张或有限图例，没有独立统计验证。
- 本课没有订单级交易系统，不能补造 entry、stop、target、size 或 management。
- 源身份、完整字幕差异、数字台账、视觉映射和完成检查见[课程审计台账](<../audits/BTC PAF 04 My Setup.md>)。
