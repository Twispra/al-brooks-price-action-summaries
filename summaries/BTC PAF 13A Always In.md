# BTC PAF 13A Always In — 课程总结

## 课程定位

| 字段 | 内容 |
|---|---|
| 精确课程 stem | BTC PAF 13A Always In |
| 显示标题 | Always In（始终在场方向，第 1/3 部分） |
| 课程位置 | Price Action Fundamentals；13A；Always In 三部曲第 1/3 部分 |
| 视频时长 | 00:23:46.448 |
| 分析日期 | 2026-08-13 |
| 工作流版本 | v3 |
| QA 状态 | ready；0 个开放未决项 |
| 学习目标 | 把 Trend/TR 状态、Always-In 方向、反转确认和 Trader’s Equation 串成一套可撤销的方向—风险判断 |
| 前置课程 | BTC PAF 12A/12B/12C Market Cycle；08B/08D Candles Setups and Signal Bars |

| 时间 | 课程推进 |
|---|---|
| 00:00–00:38 | 开场、三项主线：Trend/TR、Always-In 方向、Trader’s Equation |
| 00:38–04:21 | Market Inertia；Trend 与 TR 的不同先验；困惑和“等不到回调”作为状态线索 |
| 04:24–09:56 | Always-In 定义、反转所需强度、模糊时回看最近一次明确方向 |
| 09:59–14:42 | AIL/AIS 下的设置筛选；当前 swing、保护止损、1R/2R 目标 |
| 14:46–16:26 | Trader’s Equation：Risk、Reward、Probability 与等距比较 |
| 16:30–21:53 | 一根、两根或若干同向 K 如何在合适 Context 中建立 AIL/AIS |
| 21:57–22:55 | 盘面主导特征如何穿越一段横向整理而继续提供方向倾斜 |
| 22:59–23:42 | 复习、片尾口播与结束页 |

本课不是“看到一根大 K 就追”的形态课。它把 Always In 定义为一个持续更新的概率问题：**如果这一刻必须始终在市场中，哪一侧更可能赚钱？** 文件名前缀仅是本地课程命名，不能据此推断图表市场。

## 核心结论

1. **[Brooks/课件]** 市场在任一周期上不是 Trend 就是 Trading Range；但两种状态使用不同先验：趋势中课程称约 80% 的反转尝试失败，TR 中课程称约 80% 的成趋势突破尝试失败。两个 80% 的事件和分母不同，也都未由本课给出样本或统计方法。
2. **[Brooks/课件]** `Always In Long/Short (AIL/AIS)` 不是“价格必然单边上涨/下跌”，而是“若必须持续在场，当前更愿意持多还是持空”；Slide 15 进一步把它写成当前 `swing direction`。
3. **[分析推断]** Always-In 是可撤销的状态压缩器：先用最近的强突破、连续收盘、结构位置和 follow-through 给方向倾斜；反向证据不足时保留旧方向，反向证据足够时才翻转。它缩小候选设置，不代替 Setup、Entry、Stop、Size 与 Management。
4. **[Brooks/课件]** 一根巨大收高/收低 K、两根较强同向 K，或若干较小连续同向 K，都可能建立 AIL/AIS；课件把共同前提写为 `if context is good`，所以根数不是跨市场硬阈值。
5. **[Brooks/课件]** Trader’s Equation 同时比较 Risk、Reward、Probability：先知道结构止损在哪里，再评估目标至少是否能达到风险大小；本课把 swing 简化为寻求约 2R，并称高概率交易在 1R 退出也可能数学上合理。
6. **[分析推断]** “方向较高概率”与“这笔交易值得做”是两层判断。即使方向判断正确，若止损太远、剩余 reward 不足、成本吞噬优势或触发质量差，交易仍可放弃；本课没有提供仓位公式、成本模型或普适的 60% 估计方法。

## 知识讲解

### 00:38–04:21｜先判 Trend 还是 TR：同一惯性，不同逆向先验 [Brooks/课件]

[Brooks/课件] Slide 2 把价格运动分成 Trend 与 Trading Range。趋势之后可进入 TR，TR 之后的新趋势既可能向上也可能向下；`Market Inertia` 指当前状态倾向延续，而不是保证下一根 K 同向。课程随后给出三个相关但不能混用的口述数字：趋势中的反转尝试约 80% 失败；TR 中成趋势的突破尝试约 80% 失败；图上约 80% 的 K 继续市场此前正在做的事。它们是 Brooks 的教学先验，不是本课独立统计结果。

[画面事实] Slide 3 的强熊例以多个红箭头标出逆势尝试，课件文字为 `80% of attempts to reverse will fail` 与 `Trade in direction of trend`。Slide 4 的区间例则同时标出靠近底部的 buy reversal 与靠近顶部的 sell reversal，强调在 TR 中反向处理突破尝试。前者的事件是“趋势反转尝试”，后者是“TR 突破成为趋势的尝试”；不能把二者合并成“任何 setup 都有 80% 失败率”。

[Brooks/课件] 状态不清时，课程给出两个实用诊断。若图表上下反复、令你困惑，先把它当作早期 TR；若价格持续单向推进，你一直等待的 pullback 始终不来，则更可能处于趋势。03:14–03:24 的图例是 8-bar bull Micro Channel，画面与旁白的精确几何是：每根 K 的 low 大于或等于前一根 low，因此当前周期没有 pullback。

适用边界：困惑只是触发状态复核，不是独立交易信号；“等不到回调”也不能证明任意市价追入都有好 R/R。强趋势下 Brooks 对 Always-In trader 说可在市场买入或等 bull close，但那是“必须持续在场”的假设语境，并不取消结构止损、仓位限制或放弃权。

### 04:24–09:56｜Always-In 是当前方向判断，不是客观单边标签 [Brooks/课件]

[Brooks/课件] Always-In 问句是：如果全天必须保持 long 或 short，现在选择哪一侧？多数时候选择较清楚；市场越横向，选择越困难，但通常仍可形成一个轻微倾斜。中文字幕反复把 AIL/AIS 译为“单边上涨/单边下跌”，会把概率判断强化成客观趋势事实；本总结统一保留 AIL/AIS，解释为“始终在场偏多/偏空状态”。

[画面事实] 04:59–07:57 的 Slide 11 是本课最重要的反例。熊趋势中先出现较好的 bull reversal bar，随后 Micro Double Bottom、High 2 与强反弹；反弹还突破了一个 minor high。可是画面中的绿色水平线和红字表明，该 rally 仍低于更强熊腿顶部的 major high。课件明确写：需要再有一根 bull follow-through bar 才能确认 breakout 与 reversal；否则更可能只是 bear trend 或 TR 中的 bull leg，仍可判 AIS。Claim ID：`PAF13A-V03`。

[Brooks/课件] 这并不要求死守空仓。Brooks 说他可能在强 bull breakout 后先退出 short 并等待；若随后出现 bear bar、向下交易且多头没有取得控制，则再恢复 short。这里要分开三个动作：**退出旧方向、确认新方向、建立新方向仓位**。退出 short 不等于 AIL 已确认；同样，一根令人失望的 follow-through 也不自动给出通用反手公式。

[Brooks/课件] 当局部进入 TR、方向难判时，回看最近一次清楚的 breakout/Always-In 方向；若它尚未被反转，可继续保留原倾斜。课程又给出软时间边界：pullback 少于约 20 bars 时旧趋势恢复仍较可能；超过约 20 bars 后接近 50/50，但通常仍对旧方向保留轻微优势。它不是第 20 根自动清零，也不是必须持仓的命令。

### 09:59–14:42｜方向筛选、当前 Swing 与结构化 Stop/Target [Brooks/课件]

[Brooks/课件] AIL 环境中多头更容易赚钱，因此优先寻找 buy setups；AIS 环境中优先寻找 sell setups。课程列举了 pullback、pullback breakout、逆色 K 收盘、极值外订单等多种同向入场理由。

[分析推断] Always-In 在这里首先是方向过滤器，不是一份完整交易规格。它本身不能确认 setup quality、trigger、entry price、protective stop、position size 或可接受的账户风险；这些字段仍须逐项评估。因此 `buy/sell for any reason` 不能被解释为脱离价格、规模和风险任意执行。

[画面事实] Slide 13 用绿色方框和箭头标出牛趋势中的 buy signal bars 及其高点上方触发；Slide 14 镜像标出熊趋势中的 sell signal bars 及低点下方触发。两张图显示的是候选触发位置，不是每一标记都保证成交或盈利。趋势中的逆色收盘和回调可以买/卖，是在押注较小反转失败；强反向 breakout 与 follow-through 出现后，这个前提会失效。

[Brooks/课件] 11:20 起，课程把 swing trade 简化为“寻找至少 2 倍初始风险的 reward”；若当前 move 看起来可能达到 2R，就可称为 swing。Slide 15 直接写 `Always In Short means current swing is down`。Slide 16 把层级拆开：bear breakout → follow-through → sell the close；保护止损在突破结构上方；2R 目标在下方。这一图不是说所有 AIS 都使用同一个 stop 或 target，而是展示方向判断如何进入一笔完整计划。

[Brooks/课件] 对多头镜像例，先找最近 bull breakout 的底部或整段 bull leg 起点作为结构止损候选，再比较入场到止损的风险距离。课件目标是 reward 至少等于 risk，swing 时更偏好 2R；只要仍为 AIL，swing trader 可以穿越普通 pullback 持有。失效条件不是“出现一根 bear bar”，而是原方向结构、概率或管理前提被足够强的新证据推翻。

### 14:46–16:26｜Trader’s Equation：三变量必须在同一事件上比较 [Brooks/课件]

[Brooks/课件] Trader’s Equation 有三个变量：Risk、Reward、Probability。Risk 是从 entry 到 protective stop 的损失距离，Reward 是从 entry 到 target 的潜在收益，Probability 必须绑定明确事件，例如“先上涨 X 距离还是先下跌同样 X 距离”。课件依次用 0.1%、0.8%、可见课件上的 3%、10 ticks、20 pips 说明：距离单位可变，但比较必须是同一入场点、同一上下距离、同一先后事件。

[画面事实] Slide 20 写 `0.8%, 3%, 10 ticks, 20 pips — Does not matter`，目标是交易较高概率方向，因为通常更容易赚钱。这不是说幅度或市场微观结构永远不重要，而是说 Always-In 的方向测试可以先比较等距上/下路径，避免把更近目标与更远止损混成伪概率优势。

[Brooks/课件] Brooks 在本图口述约 60% 概率先向上，并称如果 60% 获得与风险相等的 reward，系统会盈利。[分析推断] 忽略成本且输赢幅度均为 1R 时，毛期望为 `0.60×1R − 0.40×1R = 0.20R`；这是独立可核的算术。不能反过来证明本图真实概率就是 60%，也不能忽略佣金、滑点、跳空、未成交和收益分布。

### 16:30–21:53｜Always-In 翻转来自证据簇，不来自固定根数 [Brooks/课件]

[Brooks/课件] 从不清楚的横向背景开始，AIL 可能由三种镜像尺度建立：一根巨大 bull bar 且 close on high；两根较强/中等 bull bars 且收在高位；或若干较小连续 bull bars。AIS 则是一根巨大收低 bear bar、两根较强收低 bear bars、或若干较小连续 bear bars。课件总前提是 `if context is good`。

[画面事实] AIL 图例中，大 bull bar 收盘远高于过去约 20、30、40 根 K 的高点；两根 bull bars 是屏幕上最大的两根并收于各自高位；3–5 根较小 bull bars 在更高周期可聚合为一根大 K。熊方三张课件完全镜像。画面事实是突出 K 的相对大小、方向、收盘位置和离开旧区间的程度；“更高周期一根大 K”是固定聚合关系的解释，不表示任意滑动窗口都能事后拼接。

[Brooks/课件] 旁白给出的根数比课件更宽：有时 2–3 根小 K，有时 4–6 根很小 K；课件概括为 3–5 smaller bars。这些差异共同说明根数是说明性的证据范围，而不是算法。确认来自持续离区、同向收盘、follow-through，以及错过的一方等回调入场、被套的一方等回调退出所形成的同向压力。

失效条件：单根普通反向 K、两根重叠且收盘差的 K，或连续 K 仍留在旧接受区，不能仅凭根数完成翻转；突破后深回调也不自动否定 AIL/AIS，但若回到旧区、缺乏跟进或相反方向建立更强突破，必须重判。

### 21:57–22:55｜Dominant Feature：在 TR 中保留可撤销的方向记忆 [Brooks/课件]

[Brooks/课件] 最后一图问“盘面唯一主导特征是什么”。答案不是横向区内几根 doji，而是此前非常强的 bull breakout。即使随后已横向约 20 bars，只要空头没有做出足够剧烈的反转，Brooks 仍把下跌腿看作 bull flag/TR 中的 bear legs，并只寻找买入。

[画面事实] Slide 27 的绿色区突出强多头突破，后面的重叠区出现 bear bars、bull body、下影线与坏 follow-through；课件写明 breakout 产生方向概率，市场仍由该 breakout 控制，这就是其所说的 Always In。Claim ID：`PAF13A-V10`。

[分析推断] `dominant feature` 是一种证据加权，不是永久锚定。它要求旧突破仍能解释当前结构、反方向多次无法取得接受；若空头真正向下离区、连续收低并有 follow-through，旧多头主导就失效。约 20 bars 只能提示 TR 权重上升，不能单独决定旧方向保留或清零。

## 决策模型

| 背景/市场状态 | 观察证据 | 候选行动 | 确认条件 | 失效条件 | 风险含义 | 来源层 |
|---|---|---|---|---|---|---|
| 清楚 Trend / Tight Channel | 连续同向 K、极值附近收盘、少重叠；逆势尝试弱 | 只保留 AIL 买或 AIS 卖方向的 setup；可等 pullback、signal close 或 breakout | 原方向继续离区并有 follow-through | 强反向 breakout 越过主要结构并持续接受 | 高方向概率可同时伴随远 stop；方向不等于任意价入场 | [分析推断] |
| 图表令人困惑、双向反复 | 上下腿重叠，双方反转都有机会 | 先按早期 TR；若被迫持续在场，保留最近清楚方向的轻微倾斜 | 新一侧真正 breakout 并得到 follow-through | 旧方向恢复强推进，或新突破快速失败回区 | TR 中 chase 容易遇到失败突破；课程未给固定 fade 风险参数 | [Brooks/课件] |
| 原趋势中出现漂亮反转K或强反弹 | 只越过 minor high/low，仍未越过 major structure；缺一根确认 K | 可先退出旧仓并等待；不要把退出旧方向写成新方向已确认 | 反向再有强 K、主要结构突破与 follow-through | 反向突破失望、回到旧方向，原趋势恢复 | 等确认牺牲价格，但降低把 minor reversal 当 MTR 的风险 | [Brooks/课件] |
| AIL/AIS 已建立 | 一根巨大同向 K、两根较强同向 K，或若干较小同向 K；Context 良好 | 寻找同向 setup，或等待首个可管理的 pullback | 离区保持、收盘质量和后续同向接受持续 | 回到旧区、坏跟进、相反方向建立更强证据簇 | 固定 1/2/3–5 根不是翻转公式；结构 stop 与适配 size 仍需单独设计 | [分析推断] |
| 已有候选 entry | 先能标出结构失效位，再比较等距上/下概率和可得 reward | 目标至少覆盖 risk；swing 候选优先看 2R，或在高概率前提下评估 1R | 目标、止损和概率绑定同一入场与同一事件 | 可得空间不足、方向概率变化或结构 stop 不可承受 | Probability、Risk、Reward 缺一不可；1R/2R 不是跨 setup 固定值 | [Brooks/课件] |
| 课程概率与账户执行之间 | 80%/60% 是无样本课程先验，未含个人成本与误差 | 只作为假设排序；用自己的定义、样本、成本和滑点做验证 | 净期望与尾部风险在独立样本中可接受 | 概率校准失败、成本吞噬优势或回撤超预算 | 不因课程数字直接生成 size；本课未给仓位公式 | [分析推断] |

## 关键概念

| 英文术语 | 推荐中文 | 本课增量含义 | 使用边界 | 来源时间 |
|---|---|---|---|---|
| Always In Long / Always In Short | Always-In 多头/空头状态；始终在场偏多/偏空 | 若此刻必须持续持仓，更愿意 long 还是 short；本课明确等同当前概率占优的 swing direction | 不等于客观“单边上涨/下跌”，也不保证下一根同向；必须允许退出、等待和状态翻转 | 04:24–11:16 |
| Current Swing Direction | 当前摆动方向 | 把 Always-In 从抽象倾斜连接到可能达到约 2R 的当前 move | `swing` 是交易目标与管理计划，不由固定根数定义 | 11:20–13:19 |
| Trader’s Equation | 交易员方程 | 用 Risk、Reward、Probability 判断是否值得交易及如何管理 | 本课只给三变量与示例，不含完整公式、成本、仓位或概率估计方法 | 14:46–16:26 |
| Directional Probability | 方向概率 | 强 breakout 可作为盘面主导特征，在一段 TR 中继续提供可撤销倾斜 | 不是方向保证；坏跟进、回区和相反强突破会覆盖旧倾斜 | 21:57–22:55 |
| Dominant Feature | 盘面主导特征 | 与周围 doji/小 K 相比，最异常、最强的突破可支配后续解释 | 不能永远锚定，也不能只看 bar size；须结合收盘、结构与 follow-through | 21:57–22:55 |

## 案例与反例

| 时间 / Claim ID | 画面或课程事实 | Brooks/课件解释 | 实战含义 | 排除的机械读法 |
|---|---|---|---|---|
| 01:10–02:41 / PAF13A-V01 | Slide 3 是强熊趋势与多次弱反转；Slide 4 是上下反转并存的 TR | 趋势中约 80% 反转尝试失败；TR 中约 80% 成趋势突破尝试失败 | 先识别 regime，再选择顺势或区间反向逻辑 | 两个 80% 不是同一分母，也不是任意 setup 胜率 |
| 04:59–08:03 / PAF13A-V03 | 强 bull rally 越过 minor high，但仍低于更强 bear leg 顶部；确认 K 失败 | 可能只是 bear trend/TR 中的 bull leg，仍可 AIS | 退出旧空仓与确认 AIL 分开；主要结构和 FT 决定翻转 | 一根好 reversal bar、H2 或 minor-high breakout 自动反转 |
| 08:06–09:56 / PAF13A-V04 | 大跌后进入宽横向区，最近明确方向仍为空 | 未有清楚 bull breakout 前，若必须在场可保留 short 倾斜 | 模糊时使用“最近清楚方向”作为可撤销默认 | 把默认倾斜写成必须持有或趋势必恢复 |
| 11:20–13:19 / PAF13A-V06 | Slide 16 同时标出 breakout、FT、sell close、stop 与 2R target | AIS 是当前 swing 向下；波段交易者寻找至少 2R | 将方向、触发、止损和目标分层 | AIS 等于任意卖；图示 stop/target 跨市场复制 |
| 16:30–19:35 / PAF13A-V08 | 一根巨大多头K、两根收高多头K、3–5 根较小多头K三组图 | Context 良好时都可能建立 AIL；小 K 可在高周期聚合为大 K | 评价突破强度、收盘和连续性，而非迷信单一外形 | 固定根数必翻转；任意滑动窗口事后拼高周期信号 |
| 21:57–22:55 / PAF13A-V10 | 强 bull breakout 后约 20 根横向；反向 K 多为坏跟进、bull body 或下影线 | 主导特征仍是突破，bear legs 更像 bull flag 内部波动 | TR 内仍可保留旧突破的概率倾斜 | 第 20 根自动 50/50、旧方向必延续或 doji 决定方向 |

## 知识连接

- **本课回链 12A/12B/12C：** 截至本课分析时，12A 建立 Breakout→Channel→TR 的强弱迁移，12B 用 major/minor pivot 区分旧趋势结束，12C 用 Binary Decisions 给不清楚状态保守默认；13A 把这些关系压缩成一个实时问句——“现在必须在场，哪一侧更合理？”
- **细化 08B/08D：** 08B/08D 已说明巨大结构破坏或 strong breakout + follow-through 可翻转 AIL/AIS。13A 增加了三种可见证据尺度（一根、两根、若干小 K）、“最近清楚方向”默认和 `dominant feature` 的延续记忆。
- **连接 09C 与 12B 的约 20 bars：** 09C/12B 把长 pullback/TR 的两向概率拉近。13A 同时保留旧方向轻微优势，并强调约 20 根后的实际 dominant breakout 仍可能控制概率；这不是冲突，而是“时间削弱旧趋势”与“异常强突破仍有权重”两项证据共同竞争。
- **连接 02D 与长期概率库：** 02D 已区分 Trend 反转 80% 和 TR 突破 80%；13A再次并列展示两种分母，并加入 60% 等距路径与 1R/2R 的 Trader’s Equation 示例。所有百分比仍是未独立验证的课程主张。
- **细化长期 Risk/Reward 节点：** 本课明确先定结构 stop、再要求至少 1R，swing 更偏好 2R；但没有 size、成本或统一 expectancy 公式，因此这些字段仍必须由交易者自己的规则补足。

## 复习提纲

一分钟重建：先问 `Trend or TR?`。清楚趋势中，优先顺 Always-In 方向；清楚 TR 中，对突破失败保持更高警觉。局部出现漂亮反转时，分开处理退出旧仓、确认新方向和反向入场。方向不清就回看最近一次明确 breakout；一根巨大 K、两根较强 K 或若干小 K 只有在 Context、收盘与 follow-through 一致时才可能翻转 AIL/AIS。最后把候选交易放进 `Probability × Reward − Failure Probability × Risk` 的框架，先定结构止损，再检查至少 1R、最好能否有 2R，以及成本和仓位是否允许。

主动回忆：

1. Trend 中的 80% 与 TR 中的 80% 分别绑定什么事件和分母？
2. 为什么“退出 short”与“市场已经 AIL”不是同一件事？
3. Slide 11 的 bull rally 已突破 minor high，为什么仍可判 AIS？
4. 模糊横向区中，“最近一次清楚方向”在什么证据下继续有效，又在什么证据下失效？
5. 一根、两根和多根 K 建立 AIL/AIS 时，共同需要哪些证据？
6. 为什么 60% 与 1R/1R 的毛期望为正，却仍不足以证明一笔真实交易可做？
7. `dominant feature` 与“永远坚持最早趋势”之间有什么区别？

推荐重看：01:10–02:41（两类 80%）；04:59–08:03（反转不足与 AIS）；08:06–09:56（最近清楚方向）；11:20–16:26（current swing、stop、1R/2R、方程）；16:30–21:53（AIL/AIS 三种尺度）；21:57–22:55（dominant feature）。

## 证据边界

整体信心：高。

英文字幕、中文字幕与课件画面相互印证，方向、结构和数字事件均可安全解释。

无开放未决项。需要持续保留的边界是：中文字幕把 Always In 系统性强化为“单边趋势”；`only / have to` 多处只属于“必须持续在场”的假设；80%、60%、20 bars 与根数范围均无独立样本验证；1R/2R 未包含仓位、成本和尾部风险。完整来源哈希、逐 cue 对齐、数字清单、画面映射和工具记录见[课程审计](<../audits/BTC PAF 13A Always In.md>)。
