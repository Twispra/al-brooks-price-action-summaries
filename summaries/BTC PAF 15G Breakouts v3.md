# BTC PAF 15G Breakouts v3：止盈陷阱与弱 Setup 反向交易

## 课程定位

| 字段 | 内容 |
|---|---|
| 精确课程 stem | BTC PAF 15G Breakouts v3 |
| 显示标题 | Breakouts（突破，第 7/8 部分）：5-Tick / 11-Pip Traps 与 Fade Weak Setups |
| 课程位置 | Breakouts 系列第 7/8 部分 |
| 视频时长 | 00:27:22.719 |
| 分析日期 | 2026-09-01 |
| 工作流版本 | v3 |
| QA 状态 | ready；0 个开放未决项，0 个阻断未决项 |
| 学习目标 | 理解止损入场、限价止盈与“触及但未成交”如何形成差一个最小单位的 trap；识别弱 setup 上的反向限价交易、双方订单叠加与 scale-in 风险边界 |
| 前置课程 | BTC PAF 08D Candles Setups and Signal Bars；BTC PAF 15A–15D Breakouts；BTC PAF 15F Breakouts v2 |

| 时间 | 课程推进 | 复习重点 |
|---|---|---|
| 00:00–00:32 | 开场与 Main Points | 两条主线：5-tick / 11-pip trap；fade weak setups |
| 00:32–06:30 | Emini 止盈阶梯与 5/9/13/17-tick traps | Stop-entry 与 limit-exit 的额外价格位；差 1 tick 未成交后的被套回补 |
| 06:34–13:30 | 提前止盈、反向 scalper 与订单重合 | 不自信者少拿 1 tick；对手盘在目标附近 fade；利润目标成为条件性 S/R |
| 13:35–19:32 | Forex 11-pip trap 及执行边界 | 10-pip scalp 通常需 12-pip 行程；broker、mini-pip、Ask 与真实成交差异 |
| 19:34–22:58 | Fade 弱买入 setup | 弱 bull flag 上方的限价卖出、保护止损、两笔卖出的管理 |
| 23:02–26:51 | 弱卖出 setup 的多头镜像 | Bad sell signal、买低与加仓、约 30 pips 风险、快速回补及第一/第二入口管理 |
| 26:55–27:22 | Review 与结尾 | 重新压缩为“目标位附近的订单簇＋背景化的弱 setup 反向交易” |

## 核心结论

1. **[Brooks/课件] Trap 的关键不是“价格没到目标”，而是“止盈单被触及附近却通常没有得到成交”。** Emini 例中，stop-entry 比信号 K 极值多 1 tick，预定利润是 4/8/12/16 ticks，休眠限价止盈单通常还需要再多 1 tick 才更可能成交，所以从信号 K 极值计算的示例行程是 6/10/14/18 ticks；只走到 5/9/13/17 ticks 再反转，就可能留下被套的 scalper。

2. **[Brooks/课件] 同一止盈区域会把两类不同目的的订单叠到同一方向。** 原持仓者为兑现利润而平仓，对手方 scalper 则押注 stop-entry 一方拿不到目标而反向入场。多头止盈与空头新卖单共同形成卖压，空头止盈与多头新买单共同形成买压；这解释了课程为何把 scalp profit targets 视为条件性支撑/阻力。

3. **[分析推断] “5-tick trap / 11-pip trap”应读成执行与参与者行为模型，不是跨市场固定距离信号。** 最小报价单位、入场方式、目标距离、spread、broker feed、显示的是 Bid/Ask 还是实际 trade，以及订单队列都会改变触及与成交。可迁移的是“名义目标前的订单拥挤＋未成交者被迫退出”，不是数字本身。

4. **[Brooks/课件] Fade weak setup 依赖 Context 对 setup 的否决，而不只是信号 K 难看。** 弱买入例位于强 bear bar / sell climax 后，buy signal 带 bear body；弱卖出镜像位于 Wedge Bottom、弱 bear bars 与 bull body 附近。课程的反向限价参与，是在预期 stop-entry 追随者只做 scalp、且原方向延续证据不足时执行。

5. **[Brooks/课件] Scale-in 是高风险高级路径，课程明确说多数交易者不应使用。** Forex 弱卖出镜像中，多头可在坏 sell signal 低点买，再低 10 pips 加仓；示例可能要求从第一入口承担约 30 pips、约为最低 10-pip scalp 的三倍价格风险。课程没有给账户风险比例、最大次数、总仓位、共同灾难止损、成本或跳空处理，因此不能据完成图复制订单系统。

6. **[分析推断] 本课真正的执行优势是把“setup、入场、名义目标、可成交目标、退出反应”分开。** 目标被触及不等于成交；未成交也不自动要求反手。只有当原 premise 本来就弱、价格从目标附近回到入场、同向跟进没有出现，才把被套方退出与对手方 fade 合并为状态更新。

## 知识讲解

### 1. Stop-entry 到 limit-exit：目标距离为何多出两个最小单位（00:32–01:49）[Brooks/课件；画面事实]

Emini scalper 常把 1、2、3、4 points 作为课程示例目标；在该合约课件换算中分别是 4、8、12、16 ticks。若多头用 buy stop 在信号 K 高点上方 1 tick 入场，他的 4-tick 利润限价单位于入场价上方 4 ticks，也就是信号 K 高点上方 5 ticks。Brooks 随即增加成交边界：价格通常还要再走 1 tick，休眠卖出限价单才更可能被成交，因此从信号 K 高点观察，1-point scalp 的示例行程是 6 ticks。2/3/4 points 镜像成 10/14/18 ticks。[画面事实] Slide 2 同时打印了目标阶梯和所需行程，并用图上箭头逐步标注。

这里必须分开三种价位：**stop 触发价、名义利润价、较可靠的成交行程**。课程不是说市场物理上“必须”超过目标；它说在 stop-entry＋resting-limit-exit 的示例机制下，触及目标价可能没有足够交易让大多数订单成交。市场、订单类型和队列不同，成交边界也不同。

**交易含义：** 复盘时不要只写“最高走了 4 ticks”。应记录从哪个锚点量、入场是否在极值外 1 tick、目标相对入场还是信号 K、以及图表触及是否能证明成交。**失效边界：** 若用 market exit、不同 entry、不同最小报价单位，或有可验证的成交回报，这套 1＋目标＋1 的几何不能原样搬用。

### 2. 5/9/13/17-tick trap：差一格如何变成反向订单（01:51–06:30）[Brooks/课件；画面事实]

当价格只到比“较可靠成交行程”少 1 tick 的位置后反转，stop-entry scalper 可能仍在仓内。课程逐个展示：

- 目标 1 point：从信号 K 极值只走 5 而非 6 ticks，形成 5-tick trap；
- 目标 3 points：只走 13 而非 14 ticks，空头限价止盈触及附近却未成交；
- 目标 4 points：只走 17 而非 18 ticks，部分多头会怀疑自己被套；
- 9-tick trap 是同一阶梯中 2-point 目标的镜像名称，虽然本课画面重点落在 5、13、17。

[Brooks/课件] 被套多头在价格从目标附近回落时卖出，被套空头在价格回升时买回；这些退出订单可以加强反转。Brooks 同时强调，反转并不只有一个原因：例如 Lower High、bear channel continuation、Wedge/Spike-and-Channel、Double Bottom 等 Context 也在画面中参与。不能把随后反转全部归因于“精确差一 tick”。

课程还给出主动规避：若交易者不相信完整目标会成交，可以少拿 1 tick，例如把 4-point 目标改为 3¾ points（15 ticks）。这会把平仓订单提前，反过来增加目标前一格的订单密度。**边界：** “提前一格”只是课程中的执行选择，不等于所有交易都应缩小目标；Brooks 明说自己不会为了方便把 Emini 的计划性最低 scalp 从 1 point 降成 3 ticks。

### 3. 提前止盈与对手方 fade 共同制造条件性 S/R（06:34–13:30）[Brooks/课件；画面事实]

课程把订单簇拆成两组：

1. **原方向 scalper 提前平仓。** 不确定行情能否走满 4 points 的多头可能少拿 1 tick；不确定能否走满 3 points 的空头可能在潜在 Double Bottom 上方提前买回。
2. **相反方向 scalper 在目标附近入场。** 多头预期空头只拿 1-point scalp，就可能在空头目标前用 buy limit 接货；空头预期多头只拿 4-point scalp，就可能在多头目标前用 sell limit 做空。

[画面事实] Slide 4 标出空头在弱买入目标附近分层卖出，Slide 5/6 又展示多头在坏 sell signal 下方买入；随后课件明确写出“bulls and bears buying at same time”“bulls and bears selling at same time”。因此，多头 profit target 可成为阻力，因为旧多头卖出止盈、空头也卖出开仓；空头 profit target 可成为支撑，因为旧空头买回、多头也买入开仓。

这不是 Level-2 或账户级订单流实测，而是 Brooks 对可见价格行为的参与者解释。[分析推断] 实战中应把目标位视作**候选订单密集区**：如果价格快速穿越、强收盘并有 follow-through，说明候选 S/R 没有守住；若触及后停顿、反向 K 增加且原目标方迟迟不能完成，才提高 trap/fade 权重。

### 4. Forex 11-pip trap：镜像机制与数据源边界（13:35–19:32）[Brooks/课件；画面事实]

Forex 课件把常见示例目标写成 10、20、30、50 pips。若用 stop-entry 进场，目标与成交边界合并后，Slide 7 给出 12、22、32、52 pips 的示例行程；少 1 pip 则形成 11、21、31、51-pip trap 候选。主案例中，多头在 buy signal 高点上方 1 pip 入场，想赚 10 pips，价格通常需从信号 K 高点上涨约 12 pips；若只到 11 pips 后回落，多头可能未成交而被套。空头镜像完全相同。

[Brooks/课件] 在较小日内波幅里，许多参与者可能选择 10-pip scalp；空头可以在多头 10-pip 目标附近卖，多头也可以在空头 10-pip 目标附近买。若不自信，原持仓方会提前 1 pip 平仓，与反向限价方在同一带叠加。Slide 8 的 11-pip 下跌后反转正是这一组合的图示。

但 Slide 9 明确限制精度：不同 broker 有不同数据；mini-pip 可能让行程表现为 11.3 或 11.9 pips；某些图只显示 Ask/Offer 而非实际 trades，所以看起来触及也可能没有成交。Brooks 进一步说，多数 Forex 交易者不应做这种极快 scalp；经验交易者也只有能快速思考、快速决策时才可能执行。**边界：** 11 pips 是本课历史图例的标签，不是当期平台或所有货币对的固定参数。

### 5. Fade weak buy setup：限价反向交易必须带 Context 与失效位（19:34–22:58）[Brooks/课件；画面事实]

Brooks 先给最短定义：**Fading means doing the opposite**。弱买入 setup 上，反向方是卖方。画面中市场先有很强的 bear bar / sell climax，随后 buy signal 本身带 bear body，位置与外观都不足以证明强反转。空头因此可在 buy signal 高点用 sell limit 反向参与，而不是等 sell stop 追低。

[画面事实] Slide 11 画出三层结构：初始限价卖出、再高 4 ticks 的第二卖出（价格要反弹 5 ticks 才成交），以及 Sell Climax / bear trend 顶部之外的 protective stop。Brooks 的口述还允许在上方 1 或 2 points 加仓；这是示例距离，不是统一参数。

多头自己知道 setup 弱，很多人只想拿 4 ticks。若价格上行 5 ticks 触及他们的卖出限价单，却没有很快成交，随后又回到 entry，他们会担心 5-tick trap 并卖出离场。与此同时空头正因 weak buy 而卖，所以 4/5-tick 区域聚集卖单，价格可能快速下跌。注意英文是**条件句**：若没有很快成交并开始回落，多头才快速退出；中文字幕把它局部写成“大部分订单无法成交”的既成事实，不能据此把所有弱 buy 的触及都当作必跌。

两笔空头仓位的课程管理是：价格回到第一 sell entry 时，第一笔可接近 breakeven，第二笔拿 1-point 示例利润；若大级别 bear context 足够强，可保留部分 swing。**失效边界：** 若 buy breakout 真正离开结构、强收盘并持续跟进，weak-buy fade premise 已破坏，应尊重保护止损，不能用继续 scale-in 抵抗。

### 6. 弱 sell setup 的镜像、30-pip 风险与“多数人不该做”（23:02–26:51）[Brooks/课件；画面事实]

弱卖出例先处于 bear trend，但缺少连续大 bear bars，出现较好的 bull reversal bar 与第二根 bull bar；sell signal 带 bull body，并靠近 Wedge Bottom / 弱 bear bars。多头把它视为 bad sell signal，在该 K 低点用 buy limit 押注 bear breakout 失败，并可能在低 10 pips 再买。画面实际下跌 14 pips，所以第二入口可成交。

[Brooks/课件] 这条路径只适用于参与者有把握结构会转为 Trading Range，甚至出现 rally，而不是 bear trend 继续。第一入口到可解释的风险区可能约 30 pips；若每根 K 约 10 pips，高级参与者甚至可能计划再低 20 pips，但课程立刻给出禁止性边界：多数交易者不应这样做，更不应 scale in；只有经验交易者经常采用。

后续管理与空头镜像一致。弱 sell 的空头若目标触及却未成交，价格开始返回 entry，就会迅速买回；空头止盈买单与多头新买单共同构成支撑。多头两笔入口可在第一 buy entry 附近整体退出：第一笔 breakeven，第二笔约 10-pip profit；也有人只等低 10 pips 的第二入口，或直接在新低用限价买。若 Context 足够好，部分仓位可 swing；若 K 线幅度小、影线显著、区间窄，课程判断参与者主要仍在 scalp。

[画面事实] Slide 17 把第二笔误写成 “2nd sell”，但标题、图中两个 buy 入口和 26:07–26:17 英文旁白都明确是 **second buy**；该课件标签错误不能改变方向。

## 决策模型

| 背景/市场状态 | 观察证据 | 候选行动 | 确认条件 | 失效条件 | 风险含义 | 来源层 |
|---|---|---|---|---|---|---|
| 已计划 stop-entry scalp | 写明信号 K 极值、stop 触发、名义利润、resting limit 位置与最小报价单位 | 先计算从信号 K 到较可靠成交所需的完整行程 | 真实成交回报，或价格明显穿过目标而非只触及 | 入场/退出方式、合约 tick/pip、spread 或数据源不同 | 图表触及不能替代成交；目标与行程分母不能混写 | [Brooks/课件] 00:32–01:49 |
| 行程停在目标前一格后反转 | 原方向止盈单可能未成交；出现反向 K、回到 entry、原跟进消失 | 标记 profit-target trap 候选；原持仓方准备退出，对手方可观察 fade | 价格远离目标、被套方退出方向与反向跟进一致 | 价格重新穿过目标并获得同向 follow-through | 名称不证明因果；不能从精确 tick/pip 自动反手 | [Brooks/课件] 01:51–06:30；13:35–18:54 |
| 预期对手只做 scalp，且目标附近有结构重合 | 原持仓止盈与反向限价在同一区域同向叠加 | 把 profit target 当候选 S/R，观察是否停顿/反转 | 两类行为都与后续价格反应一致；区外没有强接受 | 强 breakout 穿越候选区并持续跟进 | 参与者身份是解释，不是订单量实测 | [Brooks/课件] 06:34–13:30 |
| 弱 buy setup，左侧 bear pressure 强，signal 带 bear body | 买方只求小 scalp；高点附近有卖出目标和反向空头 | 高级 scalper 可在信号 K 高点 fade；保护止损放在 sell climax / bear trend 结构外 | 触及目标未快速成交，价格回到 entry，弱买 premise 继续 | 强 bull breakout、连续跟进或结构止损被触发 | Scale-in 增加总风险；不是默认补救 | [Brooks/课件] 19:48–22:58 |
| 弱 sell setup，Wedge Bottom / bull reversal 与弱 bear bars | sell signal 带 bull body；空头目标区可能聚集买单 | 高级 scalper 可在低点买，必要时按预案低 10 pips 加仓 | Bear breakout 不能延续，价格回到第一入口 | Bear trend 恢复、强跟进或共同结构失效 | 第一入口风险可约 30 pips；多数交易者不应采用 | [Brooks/课件] 23:02–26:51 |
| 任何 fade/scale-in 方案准备落地 | 课程缺少账户比例、最大次数、总仓位、成本与灾难止损 | 只把它保留为观察模型；若实盘，另行完成账户级风险工程 | 每笔与合并仓位都能在共同失效位下满足预定最大亏损 | 无法定义总风险，或需无限加仓才能“等回来” | 完成图不能证明 expectancy；放弃也是有效行动 | [分析推断] |

## 关键概念

| 英文术语 | 推荐中文 | 本课增量含义 | 使用边界 | 来源时间 |
|---|---|---|---|---|
| Profit-Target Trap / 5-Tick Trap / 11-Pip Trap | 止盈目标陷阱 / 5-tick 陷阱 / 11-pip 陷阱 | Stop-entry scalper 的名义目标附近被触及但未成交，价格随后反转，使其被迫退出；数字是示例行程的“差一格”标签 | 不等于每次到该距离必反转；必须绑定市场规格、入场、目标、成交与数据源 | 00:32–06:30；13:35–18:54 |
| Resting Limit Order Fill | 休眠限价单成交 | 课程区分目标价被触及与订单实际成交；通常需价格穿过一格才更有机会成交 | 队列、流动性、broker、Bid/Ask/trade 数据均会改变结果 | 01:09–01:28；14:22–14:37；18:59–19:16 |
| Fade / Fading a Weak Setup | 反向交易 / 反做弱 setup | 对弱 buy 卖、对弱 sell 买；利用 stop-entry 追随者只求 scalp、目标附近订单簇和弱 Context | 不等于任何丑 K 都反做；强 breakout/follow-through 出现时 premise 失效 | 19:34–26:51 |
| Opposite Scalper | 反向剥头皮交易者 | 在 stop-entry 一方的利润目标附近，以相反方向限价入场，押注对手拿不到完整目标 | 是 Brooks 行为解释；不能从 K 线验证账户身份或数量 | 07:23–13:30；16:41–18:54 |
| Scale-In Scalper | 分批加仓的剥头皮交易者 | 在弱 setup 上以预定间距增加第二入口，期望回到第一入口时形成“一笔保本＋一笔盈利” | 课程未给完整仓位/总风险系统；多数交易者不应使用 | 11:35–12:50；20:35–22:58；23:46–26:17 |
| Mini-Pip / Quote-Side Caveat | 小数 pip / 报价侧边界 | 11-pip 图例可能表现为 11.3/11.9；只显示 Ask/Offer 的图不证明实际成交 | 不能把历史课件数字当成所有 broker 的实时执行规格 | 18:59–19:32 |

## 案例与反例

| 时间 / Claim ID | 画面或课程事实 | Brooks/课件解释 | 实战含义 | 排除的机械读法 |
|---|---|---|---|---|
| 00:32–01:49 / PAF15G-V01 | Slide 2 同列 1–4 points、4/8/12/16 ticks 与 6/10/14/18 行程 | Stop-entry 与限价止盈成交边界使完整行程多出两个最小单位 | 先明确锚点和成交模型，再讨论目标 | “涨 4 ticks 就必然拿到 1 point” |
| 01:51–06:30 / PAF15G-V02 | 图中出现 5、13、17-tick 行程后反转，被套多空回补 | 差一格未成交者的退出可加强反转 | Trap 是被套与退出过程，不只是距离标签 | 每个 5/13/17-tick 点都必反转 |
| 06:34–13:30 / PAF15G-V03 | 提前止盈者与 opposite scalper 在同一区域同向下单 | 双方同买或同卖让 profit targets 形成候选 S/R | 观察订单簇是否真正守住，而非预设精确线 | Profit target 是永久、绝对 S/R |
| 13:35–19:32 / PAF15G-V04 | Forex 图示 11-pip trap，课件同时列 broker、mini-pip、Ask caveat | 同一机制可迁移，但数字与成交不可脱离数据源 | 结构逻辑可迁移，参数必须重新校准 | 所有货币对固定 11 pips；图上触及等于成交 |
| 19:48–22:14 / PAF15G-V05、PAF15G-V06 | 弱 buy signal、反向 sell limit、4/5-tick 卖单区与快速下跌 | 弱买方止盈/退出与空头 fade 同向叠加 | 只在 Context 与后续 non-fill/return 条件闭合时 fade | 看到 bear-bodied buy signal 就无限做空加仓 |
| 23:02–26:51 / PAF15G-V08、PAF15G-V10 | 坏 sell signal 上的多头两入口、约 30-pip 风险；Slide 17 “2nd sell” 与旁白冲突 | 课程方向是 first/second **buy**；多数交易者不应 scale in | 先修正课件标签，再保留高级路径的风险禁区 | 把 typo 当空头管理；把完成图当无风险摊平 |

## 知识连接

- **连接 [BTC PAF 08D Candles Setups and Signal Bars](<BTC PAF 08D Candles Setups and Signal Bars.md>)：** 08D 把 Setup 拆为 Signal Bar＋Context，并对“Signal 与 Context 都弱”给出等待第二信号/强突破/跟进的默认路径。本课补充另一条仅适合熟练 scalper 的路径：若弱 setup 的对侧背景、目标订单簇、保护止损与管理都可定义，可以 fade。两课不冲突；“等待”是低执行风险默认，“fade＋scale-in”是高技能、高风险分支。

- **连接 [BTC PAF 15A Breakouts](<BTC PAF 15A Breakouts.md>) 与 [BTC PAF 15D Breakouts v2](<BTC PAF 15D Breakouts v2.md>)：** 15A/15D 用突破、follow-through、回区与 Context 判断 accepted/failed breakout；本课把失败前的微观执行过程补全：目标前未成交、止盈与反向限价叠加，会让弱突破更易退回。Trap 不能取代 accepted/failed 的结构验证。

- **连接 [BTC PAF 15F Breakouts v2](<BTC PAF 15F Breakouts v2.md>)：** 15F 强调失败突破后可能恢复、反转或回到 neutral/TR；本课的 weak-setup fade 正是在“原突破缺乏接受、对手只求 scalp”的局部环境中工作。若突破重新获得强跟进，fade premise 必须退出。

- **连接 [BTC PAF 10B Buying and Selling Pressure](<BTC PAF 10B Buying and Selling Pressure.md>)：** 10B 用逆向压力、坏跟进与 TR 化更新状态；本课把 profit target 作为压力来源之一。目标位只是一条候选证据，持续离区和实际跟进仍优先。

- **截至本课分析时：** 长期知识库已有 Scaling In 的总风险护栏；本课新增的是“profit-target trap＋weak-setup fade”之间的连接，以及 broker/成交数据对精确距离的否决条件。

## 复习提纲

**一分钟回放：** Stop-entry 在信号 K 极值外触发，resting profit limit 又可能需要价格穿过目标才成交，所以“目标差一格”会留下被套 scalper。原持仓者提前止盈/认赔，与 opposite scalper 在同一区域同向下单，形成候选 S/R。弱 setup 可被熟练交易者 fade，但必须由 Context、保护止损和后续 non-fill/return 条件支持；scale-in 只是高风险管理分支，多数交易者不应使用。

**主动回忆：**

1. 为什么 Emini 的 4-tick 利润示例会对应信号 K 高点上方约 6 ticks，而不是 4 或 5？
2. 名义目标、触及目标与实际成交分别需要什么证据？
3. 被套多头退出与新空头入场为何能在同一价位共同形成卖压？空头镜像是什么？
4. 11-pip trap 的哪些部分可跨市场迁移，哪些必须按 broker、spread 和数据源重算？
5. 08D 的“等待弱 setup”与本课的“fade 弱 setup”如何同时成立？
6. 弱 buy fade 的确认、失效和保护止损分别是什么？
7. 为什么第一入口 breakeven＋第二入口盈利不等于 scale-in 有正 expectancy？
8. Slide 17 的 “2nd sell” 为什么必须改读为 “second buy”？

**推荐重看片段：** 00:32–01:49（目标与成交行程）；03:09–04:23（17-tick trap 与提前一格）；07:23–10:06（opposite scalper）；13:35–18:54（11-pip 镜像）；18:59–19:32（数据源边界）；19:48–22:14（弱 buy fade）；23:02–24:56（弱 sell＋30-pip 风险）；26:00–26:17（第二 buy 与课件 typo）。

## 证据边界

整体信心：高。 本课两条核心机制——固定目标附近的订单聚集，以及弱 setup 上的条件化反向交易——均由英文讲解与对应课件画面互证。

- 课程全部 tick/pip 距离、最低 scalp 与参与者行为均是 Brooks/课件在所示历史市场与执行模型中的主张，未做外部成交统计或当期 broker 规格验证。
- 中译的概率强化、译者新增年份/风险解释、“or even a rally”误译、small bars→“体积”以及 Slide 17 的方向 typo 已在正文采用英文与画面纠正；无仍会改变安全结论的开放未决点。
- 完整哈希、字幕差异、数字清单、帧映射、工具链与源文件不变性见[课程审计](<../audits/BTC PAF 15G Breakouts v3.md>)。
