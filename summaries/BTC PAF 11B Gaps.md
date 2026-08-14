# BTC PAF 11B Gaps｜均线缺口K线与竭尽缺口的确认

## 课程定位

| 字段 | 内容 |
|---|---|
| 精确课程 stem | `BTC PAF 11B Gaps` |
| 显示标题 | Gaps（缺口，第 2/4 部分） |
| 课程位置 | 承接 11A 的 Gap 路径分类，集中展开 Moving Average Gap Bar 与 Exhaustion Gap |
| 视频时长 | 00:34:29.502 |
| 分析日期 | 2026-08-09 |
| 工作流版本 | v3 |
| QA 状态 | ready；0 个开放未决项 |
| 学习目标 | 区分“首次回到均线的 20-Gap 顺势机会”与“整根 K 穿到均线另一侧的 MA Gap Bar”；用 gap 是否关闭、跟进和结构回收判断后段大 K 是 Measuring 还是 Exhaustion |
| 前置课程 | BTC PAF 01；BTC PAF 07A Starting Out；BTC PAF 10A Buying and Selling Pressure；BTC PAF 11A Gaps |

这节课把“缺口”从静态形状变成两个状态更新器。第一个是均线关系：价格长期位于均线一侧后，整根 K 线首次落到另一侧，常表示原趋势已进入最后一段，但第一次反转仍经常失败。第二个是趋势后段的大 K 与 breakout-point gap：大 K 出现时只能提出 Measuring 与 Exhaustion 两个竞争假设，只有后续把相应 gap 关闭、强 K 缺少跟进，才能把它升级为竭尽证据。课程重点是识别与概率路径，不是完整入场系统。

课程时间线：

| 时间 | 内容 |
|---|---|
| 00:00–00:31 | 本课两类主题：Moving Average Gap Bars 与 Exhaustion Gaps |
| 00:31–02:12 | Bull Moving Average Gap Bar 的几何、趋势位置与 40/60 路径 |
| 02:12–05:35 | 强多头趋势的首次均线测试、20-Gap Buy 与后来的真正 MA Gap Bar |
| 05:35–08:18 | 第一轮反转失败、最后一段上涨、MTR 尝试与 Double Top / Wedge 背景 |
| 08:28–11:48 | Bear Moving Average Gap Bar 的镜像定义与实例 |
| 11:53–15:01 | 可能的 Bull Exhaustion：后段大 K、阻力/MM、第二腿陷阱 |
| 15:06–19:43 | 多头案例一：多个 gap 字段、关闭后的事后诊断与 Climax 目标 |
| 19:53–22:47 | 多头案例二：最大 bull bar、10 bars / two legs 与差跟进确认 |
| 22:57–26:10 | 空头案例一：大 bear bar、短小第二腿与 gap 关闭 |
| 26:15–28:15 | 60/40 空头路径、Measured Move 候选及顺势第二腿边界 |
| 28:26–32:50 | 多个 bear gaps、最高 breakout point 被收复及 Big Down–Big Up → TR |
| 32:54–34:29 | 两类缺口复习与片尾 |

## 核心结论

1. **Moving Average Gap Bar 不是“碰到均线”，而是整根 K 线已经越到均线另一侧。** Bull 版本要求先有至少约 20 根 K 主要在均线上方，随后一根或多根 K 的高点仍低于均线，即 `bar.high < MA`；Bear 版本镜像为 `bar.low > MA`。它提示原趋势成熟与反向力量出现，却不是立即反手信号。[Brooks/课件] 00:31–02:12；08:28–10:09

2. **第一次越过均线的反转尝试通常仍会失败，原趋势常再走最后一段。** 课程把该最后一段之后的路径拆成两个不同分母：趋势恢复后，约 60% 的情形会给反方一次 Major Trend Reversal 尝试；在已经出现 MTR 尝试的情形中，约 40% 发展为反向 swing，约 60% 只形成原趋势旗形或 Trading Range。两个百分比不能相乘成一个未经课程陈述的总胜率。[Brooks/课件] 01:20–02:12；32:54–34:19

3. **“20-Gap Buy/Sell”与“Moving Average Gap Bar”必须分开。** 前者是在强趋势至少约 20 根未触及均线后，价格第一次回到均线附近的顺势候选；后者是整根 K 已处于均线另一侧，用于识别可能的最后一腿与随后 MTR 窗口。二者方向、几何和决策位置不同。[分析推断] 02:12–05:35

4. **趋势后段的大 K 只能生成 Exhaustion 候选，不能当场确诊。** 背景包括趋势已走约 10 根以上、末端出现一根或连续两三根大趋势 K、接近阻力/支撑或 Measured Move；但同一大 K 也可能是 Measuring Gap 并继续推动。课程反复要求等待 gap 关闭与跟进失败，才把解释更新为 Exhaustion。[Brooks/课件] 11:53–15:01；19:53–22:47

5. **Gap 关闭是关系证据，第一结论通常是原趋势暂停或进入 TR，而非自动建立反向趋势。** Bull Exhaustion 要观察价格跌破相关 breakout point；Bear Exhaustion 镜像为反弹越过相关 breakout point。关闭后可把 Buy/Sell Climax 起点、约 10 bars / two legs 或其他结构作为观察目标，但反向趋势仍需独立 breakout 与 follow-through。[分析推断] 15:06–19:43；22:57–32:50

6. **多个 gap 可以同时成立，必须记录各自端点和层级。** 一段强移动可能留下 close-to-prior-high/low、pullback-to-breakout-point 等多个关系。较浅 gap 被关闭不必然否定全部趋势；当最重要或最高层级的 breakout point 也被收复，且出现 Big Down–Big Up，TR 假设才显著增强。[Brooks/课件] 17:14–19:43；28:26–32:50

## 知识讲解

### 1. Moving Average Gap Bar：几何必须写到 high / low

[Brooks/课件] Bull Moving Average Gap Bar 的背景是一段强多头趋势：至少约 20 根 K 主要位于均线上方，期间没有整根 K 穿到均线下方。随后出现一根或多根完全在均线下方的 K；“完全”意味着该 K 的最高点也低于均线，因而 gap 的两端是均线与 `bar.high`。Bear 版本完全镜像：一段至少约 20 根 K 的空头趋势后，一根或多根 K 完全位于均线上方，gap 位于 `bar.low` 与均线之间。

这个名称容易被误读成“价格与均线有距离”。真正增量在于**K 线已经穿过均线，而且连最靠近均线的一端也没有触及它**。多头中的普通回调 K 若低点碰到均线、或 K 穿越均线但高点仍碰到均线，都不是课件定义的 bull MA Gap Bar。镜像地，空头回调中只要低点仍碰到均线，也不构成 bear MA Gap Bar。

它表达的不是方向触发，而是趋势阶段变化。强趋势第一次出现这种反方完全越线，说明市场终于产生足够大的反向力度；然而在强趋势背景中，第一次逆势尝试仍通常不足以翻转 Always-In 方向。因此它更像“最后一段原趋势 + 后续 MTR 观察窗”的状态标记，而不是看到 gap bar 就用市价反手。[分析推断] 实盘记录应至少写明趋势方向、此前未越线的大致根数、gap bar 的极值字段、反转尝试是否有跟进，而不能只写“出现 MA gap”。复习时间：00:31–02:12；08:28–10:09。

### 2. 首次均线测试与 MA Gap Bar 是两个相邻但不同的 setup

课程的第一个完成图显示，强多头趋势长期不碰均线后，第一次回到均线附近可形成所谓 20-Gap Bar Buy。这里的核心仍是顺势：价格在大约 20 根或更多 K 后首次测试均线，多头可能把均线当支撑，至少期待回测前高。图中这一轮买入成功，市场重新上涨；但它并没有立刻证明趋势会永久持续。

后面价格再次转弱，才出现整根 K 位于均线下方的 bull MA Gap Bars。第一次反转尝试失败后，市场形成最后一段上涨；完成图随后给了反方 MTR 尝试，部分例子发展为 swing down，另一些只形成 Double Bottom Bull Flag 或 Trading Range。换言之：

- 20-Gap Buy 的观察方向仍是原多头趋势，依据是长时间未测试均线后的首次支撑测试；
- Bull MA Gap Bar 记录的是空方已经把整根 K 压到均线下方，提示多头趋势后段；
- 最后一段上涨结束后才进入 MTR 评估，且 MTR 尝试与 MTR 成功不是同一事件。

[Brooks/课件] 空头镜像同理：第一次回到均线附近可以是顺势卖出背景；真正 bear MA Gap Bar 则要求整根 K 在线上方，随后空头往往还有最后一段下跌，再给多头 MTR 尝试。英文字幕在 09:43 附近说成 “bears will get MTR attempt”，但画面、镜像定义、前后文与中文均指向 bulls；本笔记按结构一致性纠正为多头获得尝试。复习时间：02:12–11:48。

### 3. 概率树：先分清事件，再保留条件分母

课件的概率不是一条“反转胜率”。第一层事件是：MA Gap Bar 后第一次逆势尝试通常失败，原趋势恢复并走最后一段。第二层事件是：原趋势恢复之后，约 60% 的情形会让反方获得一次 Major Trend Reversal attempt。第三层事件才是 MTR 尝试的结果：课程页面写约 40% 成为 opposite swing，约 60% 成为 original-trend flag 或 Trading Range。

因此安全读法是一个条件树，而不是把 60% 与 40% 相乘得到 24%。课程没有明确说这三个数字来自同一个样本，也没有提供市场、周期、样本期、交易成本、触发和退出定义。它们可以用来校准先验：不要在第一次越线就假定成功反转，也不要在最后一腿后排除反方 MTR；但不能直接转换成可下单的期望值。

图例中的约 40 根 K、20/30 根 K、四五根某类 K、两腿或 Wedge 1-2-3 等，是趋势成熟度和具体结构说明，不是 MA Gap Bar 定义的一部分。[分析推断] 比较不同图时，应先固定事件：是“出现 MTR 尝试”，还是“尝试后形成 opposite swing”，还是“只进入 TR/flag”；只有事件与分母一致，数字才可比较。复习时间：01:20–02:12；04:58–07:04；09:50–11:48；32:54–34:19。

### 4. Exhaustion 候选：位置、大 K、阻力与第二腿陷阱

[Brooks/课件] Bull Exhaustion 的候选背景通常是一段已经走了约 10 根以上的趋势，末端出现一根大 bull bar，或连续两三根大 bull bars，收盘接近高点，并处在阻力、Measured Move 或其他目标附近。Bear Exhaustion 镜像为后段大 bear bar、接近低点收盘、位于支撑/MM 附近。连续大 K 表示高潮强度，但也能是强 breakout 的开始，所以“最大 K”“第 20 根附近”“到达 MM”都只能提高警觉，不能独自确认竭尽。

课程还展示 Second Leg Trap：在 Trading Range 边缘，第一腿和回调之后突然出现很强的第二腿，趋势交易者容易把它当成区间突破并追入；若随后的 gap 关闭、价格回到区间，追随者便被困。陷阱来自**背景与后续失败**，不是因为第二腿本身“太强就必反转”。强第二腿仍可能先有一个很小的同向延伸，尤其在 bear 例子中，一根 doji 或小 K 也可完成第二腿，然后才反弹。

[分析推断] 使用 Exhaustion 标签时应维持两个并行假设。Measuring 假设的支持证据是 gap 维持、回调浅、突破点未被收复、同向跟进和继续向目标推进；Exhaustion 假设的支持证据是 gap 被关闭、强 K 后跟进差、价格重回旧区间、出现相反方向强 K 或双向交易。复习时间：11:53–15:01；22:57–28:15。

### 5. Gap field：关闭哪一个关系，决定你能说多强

这节课的 Exhaustion 诊断依赖具体 gap 字段。强 bull breakout 可以留下至少两类空隙：某根收盘到先前高点的 close gap，以及后续回调低点到 breakout point 高点之间的 pullback gap。只要价格仍在相应 breakout point 上方，市场仍可能把该点当支撑；跌破该点，才算关闭该 gap。Bear 版本把 high/low 与方向镜像：反弹超过 breakout point 的低点，关闭向下 breakout 留下的 gap。

多个 breakout points 可以同时存在，所以图上可能有几条 gap 线。关闭较近的一条只削弱一层结构；若更高层级的 gap 仍开放，趋势尚未被完全否定。后面的 bear 案例先标出多处 gap，再观察反弹依次穿过。价格最终越过最高、最关键的 breakout point，意味着所有被监控的 bear gaps 均已关闭；随后 Big Down 接 Big Up，市场更像进入 Trading Range。

[Brooks/课件] 课程用 “diagnosed after gap closes” 强调事后更新：不是先看见大 K 就命名 Exhaustion，再把任何回调当验证；而是先记录 gap 端点，等后续真的穿回。这个方法也保护了“局部关闭”与“结构级失效”的区别。[分析推断] 每条 gap 记录可写成 `{方向, 起点字段, 终点字段, breakout point, 是否开放, 关闭时间}`，避免多个箭头被压缩成一个含糊标签。复习时间：15:06–19:43；28:26–32:10。

[Brooks/课件] 18:20–18:24 的事件是：在该 bull Exhaustion 候选中，**约一半（about half）**会在反转前先多走一个很小的同向腿；分母是 Brooks 对这一类后段走势的经验描述，课程没有给样本数、市场或周期，不能与 MA Gap 的 40/60 路径合并。[Brooks/课件] 18:48–18:56 的另一个数字只针对当时完成图：大 bear bar 收近低点后，**该 bull gap 至少有 50/50 的关闭机会**；这不是“所有 gap 有一半会关闭”的总体胜率。随后画面才逐步更新各 gap 端点并显示完全关闭。

### 6. 关闭之后：Climax 起点与 Ten Bars, Two Legs 是观察框架

Bull gap 被关闭后，课件常把 Buy Climax 的底部作为第一观察目标；Bear gap 关闭后则镜像地观察 Sell Climax 顶部。另一个反复出现的框架是约 10 bars、two legs：高潮之后，市场经常需要一段时间与两腿修正来消化原方向仓位。图中可见 1–pullback–2、Wedge 或很小的第二腿；这说明“两腿”按价格结构识别，不要求第二腿与第一腿同样大。

这些是路径和目标候选，不是时钟式保证。课程的“10”有时是约数；图例也可能先出现一腿、短暂停顿，再有一根小 K 完成第二腿。若 gap 关闭后出现强反向 breakout 与 follow-through，反向 swing 概率提高；若只出现重叠、弱反向 K 和快速被买回/卖回，则更适合按 TR 或原趋势旗形管理预期。

特别重要的是：Exhaustion 表示原方向单边力量耗尽或暂停，不等于另一方已经取得趋势控制。Big Down–Big Up 常意味着 confusion 与双向交易；它支持 TR，而不是自动给出 long 或 short。课程没有提供统一止损、仓位或持有规则，因此把 Climax 起点/TBTL 目标转为交易计划仍需独立的信号 K、入场触发与风险预算。[分析推断] 复习时间：16:34–19:43；20:48–22:47；25:13–32:50。

### 7. Bear 案例的 60/40：大 K 之后仍可能有一个小第二腿

[Brooks/课件] 26:29–26:43，后段最大的 bear bar 出现时，Brooks 给出约 60% 的 Exhaustion/趋势结束路径——有时先再走一个同向小腿——以及约 40% 的更强下跌 swing 路径。这里的 60/40 仍是课程经验概率，没有独立样本。

[Brooks/课件] 26:59–27:07 说的是明确的条件句：**如果**空头随后得到第二根大 bear bar，才 `probably (better than 50%)` 会从 Double Top / Triangle 获得 Measured Move down。[画面事实] 该图并未满足这个前件；27:37 之后实际出现的是 `Weak follow-through`、`A big doji`，随后 `The market reversed up`。这个 doji 或短小下探仍可能构成很小的第二腿，因此“还有第二腿”不等于此前大 K 不是竭尽；反过来，一根反弹也不能单独确认竭尽。真正决定分类的是结构关系：是否越过 breakout point、是否关闭 gap、第二腿是否扩展、以及反弹是否形成持续买盘。

[分析推断] 这使决策从二元标签变成顺序更新：候选大 K → 允许小第二腿 → 检查 gap/follow-through → Exhaustion/TR 或 Measuring/continuation。该顺序能避免在最强 K 末端追单，也避免仅因一根反向 K 过早做反转。复习时间：24:05–28:15。

## 决策模型

| 背景/市场状态 | 观察证据 | 候选行动 | 确认条件 | 失效条件 | 风险含义 | 来源层 |
|---|---|---|---|---|---|---|
| 强多头趋势，约 20+ 根主要在 MA 上方 | 一根或多根 K 完全在 MA 下方，`bar.high < MA` | 标记 Bull MA Gap Bar；预期第一次反转可能失败，等待最后一腿与后续 MTR 窗口 | 多头恢复、再测高；随后出现 Double Top/Wedge、强空头 breakout 或清晰 MTR 结构 | K 仍触及 MA；或没有原趋势恢复便直接形成持续空头控制 | 不因首次越线直接 short；课程未给入场、止损或仓位 | [分析推断]（基于 Brooks/课件，00:31–08:18） |
| 强空头趋势，约 20+ 根主要在 MA 下方 | 一根或多根 K 完全在 MA 上方，`bar.low > MA` | 镜像标记 Bear MA Gap Bar；等待最后一段下跌与多头 MTR 候选 | 空头恢复后出现终局腿；其后多头获得结构化反转尝试 | K 仍触及 MA；或空头未恢复而多头已形成强突破跟进 | 不把课件中的概率改写成必然反转 | [分析推断]（基于 Brooks/课件，08:28–11:48） |
| 强趋势约 20+ 根未测试 MA，首次回到 MA | 首次 MA 测试、趋势仍强、顺势信号出现 | 只作为 20-Gap 顺势候选，和 MA Gap Bar 分开记录 | MA 支撑/阻力有效、原趋势恢复并测试前高/低 | 整根 K 穿到另一侧且形成强反向跟进；或趋势结构已变为 TR | 名称相近但方向相反；不能用一个 setup 的概率代替另一个 | [分析推断]（基于 Brooks/课件，02:12–05:35） |
| 趋势后段出现一根或连续大趋势 K | 约 10+ 根背景、接近 S/R 或 MM、末端大 K/大 K 序列 | 并列保留 Measuring 与 Exhaustion 假设；标注全部相关 gap 字段 | gap 维持且同向跟进支持 Measuring；gap 关闭且跟进差支持 Exhaustion | 用“最大 K”当场确诊；未定义端点便声称 gap 已关 | 追在高潮末端有反转与 TR 风险；逆势过早也可能遭遇第二腿 | [分析推断]（基于 Brooks/课件，11:53–15:01） |
| Bull Exhaustion 候选 | 回落跌破相关 breakout-point high，close/pullback gap 被关闭 | 下调多头延续预期；观察 Buy Climax 底部、TBTL 与 TR | 强空头 K、持续跟进、更多关键 gap 被关闭 | 只关浅层 gap 后迅速恢复上涨；关键 breakout point 仍守住 | “gap closed”首先支持暂停/TR；反向趋势需另证 | [分析推断]（基于 Brooks/课件，15:06–22:47） |
| Bear Exhaustion 候选 | 反弹越过相关 breakout-point low；多个 gap 依次关闭 | 下调空头延续预期；观察 Sell Climax 顶部、TBTL 与 TR | 最高层级 breakout point 被收复，Big Down–Big Up 或持续多头跟进 | gap 保持开放、反弹浅且继续向下 MM | 允许一个小同向第二腿；不因一根反弹提前 long | [分析推断]（基于 Brooks/课件，22:57–32:50） |

课程将 setup（成熟趋势与大 K）、signal（gap 关闭/跟进失败）、entry（未给统一规则）、management（目标候选与状态降级）和 outcome（swing、flag 或 TR）分开。任何实盘化都需要补上具体触发、保护止损、仓位、成本与退出逻辑。[分析推断]

## 关键概念

| 英文术语 | 推荐中文 | 本课增量含义 | 使用边界 | 来源时间 |
|---|---|---|---|---|
| Moving Average Gap Bar | 均线缺口K线 | Bull：整根 K 在 MA 下方，`high < MA`；Bear：整根 K 在 MA 上方，`low > MA`。位于约 20+ 根单边趋势后的成熟阶段 | 不是普通触线/穿线，不是即时反手触发；首次反转常失败 | 00:31–02:12；08:28–10:09 |
| 20-Gap Bar Buy / Sell | 20-Gap 首次均线测试顺势机会 | 强趋势约 20+ 根未碰 MA 后，首次回到 MA 的顺势候选 | 与 MA Gap Bar 不同；“20”是课程 setup 语言，不能脱离趋势质量机械计数 | 02:12–04:33 |
| Major Trend Reversal Attempt | 主要趋势反转尝试；MTR 尝试 | 最后一腿后反方获得尝试，与最终 opposite swing 是两个事件 | 尝试不等于成功；课程 40/60 需保留条件分母 | 01:20–02:12；32:54–34:19 |
| Exhaustion Gap | 竭尽缺口 | 后段大 K 留下的 gap 在后续被关闭、且原方向跟进变差后的事后诊断 | 最大 K、根数或到达 MM 只能生成候选；关闭通常先指向 TR | 11:53–22:47；22:57–32:50 |
| Breakout-Point Gap | 突破点缺口 | pullback 极值与先前 breakout point 之间的可监控空间；可有多个层级 | 必须写明 high/low/close 与具体 BO 点；局部关闭不等于全部结构失效 | 15:06–19:43；28:26–32:10 |
| Second Leg Trap | 第二腿陷阱 | TR 边缘的强第二腿吸引追随者，随后 gap 关闭并回区间 | “强第二腿”本身不是反转信号；仍可能先有小同向延伸 | 13:33–15:01 |
| Ten Bars, Two Legs | 十根K、两腿修正；TBTL | Climax/Exhaustion 后用于组织暂停与修正路径，第二腿可很小 | 约数与结构框架，不是固定等待计时器或目标保证 | 16:34–17:51；21:17–21:54；25:45–26:10 |
| Buy / Sell Climax | 买入/卖出高潮 | gap 关闭后，高潮起点/底部或顶部可成为第一观察目标 | 目标候选不等于必达；高潮不保证立即反向趋势 | 16:34–19:43；25:13–32:50 |

## 案例与反例

| 时间 / Claim ID | 画面或课程事实 | Brooks/课件解释 | 实战含义 | 排除的机械读法 |
|---|---|---|---|---|
| 00:31–02:12 / PAF11B-V01 | Slide 2 把 20+ 根 MA 上方趋势、整根 K 在线下、MA 到 K 高点的 gap 与 40/60 路径放在同页 | 第一次反转多失败；最后上涨后才评估 MTR，MTR 成功与尝试分母不同 | 先按字段确认 `high < MA`，再分阶段更新 | 排除“碰 MA 就是 MA Gap Bar”和“出现即转空” |
| 02:25–08:18 / PAF11B-V02 | 完成图先显示长期未碰 MA 后的首次测试和 20-Gap Buy，后来才出现真正 MA Gap Bars 与反转结构 | 首次均线测试可以是顺势机会；真正越线后原趋势仍常有最后一腿 | 将两个相邻 setup 分开回测、分开统计 | 排除把 20-Gap Buy 与 bull MA Gap Bar 当同一信号 |
| 11:53–15:01 / PAF11B-V04 | 后段大 bull bars 出现在阻力/MM 附近；TR 边缘的强第二腿随后可能失败 | 先叫 possible Exhaustion；Second Leg Trap 要靠后续回区间确认 | 大 K 时建立竞争假设，不抢先命名 | 排除“第二腿越强越应立即反手” |
| 15:06–19:43 / PAF11B-V05 | 图上同时标出多个 bull gap；价格跌破相关 breakout point 后，课件才写 diagnosed after gap closes | gap 关闭把解释转向 Exhaustion，Climax 底部与 TBTL 成为观察目标 | 用明确 BO 点验证，而不是凭视觉觉得“回调很多” | 排除“大 K 当场确诊”和“关闭即必然 bear trend” |
| 22:57–28:15 / PAF11B-V07 | 大 bear bar 后仍有小第二腿；完成图展示 gap 关闭、反弹与 60/40 路径 | 大 K 约 60% 是 exhaustion/end（可再有一腿），约 40% 开始更强 swing；后续决定 | 允许同向小延伸，再看 gap 与跟进 | 排除“一有第二腿就不是 exhaustion”或“一反弹就已确认” |
| 28:26–32:50 / PAF11B-V08 | 多条 bear gap 线逐层被反弹穿回，最高关键 BO 点也被收复，随后 Big Down–Big Up | 所有关键 gaps 关闭后 Exhaustion/TR 解释增强 | 记录 gap 层级；结构级回收比单条线更有信息 | 排除“关闭任意一条 gap 就无条件做多” |

## 知识连接

- **BTC PAF 01：**该课只给出 Moving Average Gap Bar 的术语级定义；本课补齐 bull/bear 几何、趋势成熟背景、最后一腿与 MTR 的概率路径。概念库中的旧条目应以本课作为主要增量来源。
- **BTC PAF 07A Starting Out：**TBTL、Wedge 与 MTR 在这里不再只是通用反转语言，而被放进“gap 关闭后的修正路径”。截至本课分析时，它们仍是概率框架，不是固定根数计时器。
- **BTC PAF 10A Buying and Selling Pressure：**价格与均线/突破点之间的空间继续采用 Brooks 的广义 Gap 定义；本课把这个关系进一步操作化为 `bar.high < MA`、`bar.low > MA` 与 breakout point 是否被收复。
- **BTC PAF 11A Gaps：**11A 说 Measuring/Exhaustion 是由后续路径决定的分类，并强调 gap 关闭常先进入 TR；11B 用多个完整 bull/bear 图例给出诊断顺序和具体字段，强化而非推翻 11A。
- **长期易错点：**本课继续出现 body 被译为“体积”、`possible/probably/hope` 被强化、根数范围变形、译者加入 EMA20，以及一处 MTR 多空代词错误。知识层只采用英语、课件几何与上下文共同支持的版本，不把这些课程级纠错提升为新策略。

## 复习提纲

压缩记忆链：**成熟趋势 → 第一次整根越过 MA → 原趋势常有最后一腿 → 反方获得 MTR 窗口；后段大 K → 同时保留 Measuring/Exhaustion → 明确 gap 字段 → 等关闭与跟进 → 优先更新为 TR/暂停，反向趋势另证。**

主动回忆：

1. Bull 与 Bear MA Gap Bar 的 high/low 不等式分别是什么？为什么普通 MA touch 不够？
2. 20-Gap 顺势 setup 与 MA Gap Bar 在方向、位置和预期上有什么不同？
3. 课程中的 60%、40%、60% 各自对应什么事件和分母？为什么不能直接相乘？
4. 一根趋势后段最大 K 出现时，Measuring 与 Exhaustion 各需要什么后续证据？
5. 多个 gap 同时存在时，关闭浅层 gap 与收复最高层级 breakout point 的含义有何差别？
6. 为什么 Exhaustion 常先导向 TR，而不是自动建立相反趋势？
7. “10 bars, two legs”如何作为观察框架？一个 doji 或小 K 能否构成第二腿？

建议重看：00:31–02:12（定义与概率树）、02:25–05:35（20-Gap 与 MA Gap Bar 区分）、11:53–15:01（候选与陷阱）、15:06–19:43（多个 gap 与确认）、22:57–28:15（bear 60/40 和小第二腿）、28:26–32:50（层级关闭与 TR）。

## 证据边界

整体信心：高

英语字幕、中文字幕、完整课件时间线与定向原分辨率画面在核心几何、状态更新和概率路径上相互支持；一处英文多空代词错误与若干中文限定词/数字/术语偏差均可由镜像课件和上下文安全消歧。

无开放未决项。课程概率没有独立样本验证，也未提供完整 entry、stop、position sizing、成本或 expectancy；本总结因此只保留识别、条件概率与状态更新，不把它包装为可直接执行的交易系统。完整来源身份、字幕差异、数字分母、视觉映射与工具 QA 见[课程审计](<../audits/BTC PAF 11B Gaps.md>)。
