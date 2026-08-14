# BTC PAF 12C Market Cycle｜市场周期（第 3/3 部分）

## 课程定位

| 字段 | 内容 |
|---|---|
| 精确课程 stem | `BTC PAF 12C Market Cycle` |
| 显示标题 | Market Cycle（市场周期，第 3/3 部分） |
| 课程位置 | Market Cycle 三课中的收束课：Pullback、Trading Range 与 Binary Decisions |
| 视频时长 | 00:19:48.281 |
| 分析日期 | 2026-08-13 |
| 工作流版本 | v3 |
| QA 状态 | ready；0 个开放未决项 |
| 学习目标 | 用“当前状态 → 二元分类 → 对应交易倾向”快速缩小决策空间，同时保留概率、周期与失效边界 |
| 前置课程 | [BTC PAF 12A Market Cycle](<BTC PAF 12A Market Cycle.md>)；[BTC PAF 12B Market Cycle](<BTC PAF 12B Market Cycle.md>) |

| 时间 | 课程推进 | 复习定位 |
|---|---|---|
| 00:00–00:34 | 开场与三部分路线 | Pullback → Trading Range → Binary Decisions |
| 00:34–05:16 | Pullback 的概率定义、最小几何、提前开始与状态演化 | 回调不是只看一根反向 K |
| 05:16–07:05 | Trend、Swing、Leg、Pullback 的重叠尺度 | 名称服务于背景和交易用途 |
| 07:05–09:49 | TR 可小至一根；困惑、20 根与 Breakout Mode | 从趋势延续预期转向方向中性 |
| 09:49–12:23 | 不同市场周期阶段要采用不同交易方式 | 强突破单向；TR 双向；通道居中 |
| 12:23–14:42 | 二元决策框架及弱化牛通道案例 | Trend/TR 是第一问 |
| 14:42–17:03 | Breakout/Channel、Tight/Broad、Major/Minor 的保守默认 | 看不清时先采用更安全的单向假设 |
| 17:03–19:03 | 强突破、宽通道、TR、极窄 TR 的执行矩阵 | 从单向参与逐步过渡到双向或不交易 |
| 19:03–19:48 | 口头复盘与片尾 | 用四个快速问题结束决策 |

## 核心结论

1. [Brooks/课件] Pullback（回调；熊趋势中为反弹）是趋势中的暂停和小型 Trading Range，名称内含“原趋势较可能恢复”的判断；它不是仅由某一根反向 K 的外形决定。
2. [Brooks/课件] Pullback 可以在趋势真正结束前开始，也可以随着反向 bars、legs 与结构破坏发展成 Trading Range 或趋势反转；约 20 根只是 Brooks 开始改用 TR 语言的常见软尺度，不是自动换系统的硬阈值。
3. [Brooks/课件] Trend、Swing、Leg 与 Pullback 没有互斥的严格边界：同一段下跌可以同时是原牛趋势的 50% Pullback、一段 Bear Leg，以及足以产生 swing profit 的 Bear Swing。
4. [Brooks/课件] 市场状态决定交易倾向：强 Breakout 或 Tight Channel 主要顺势；Broad Channel 可顺势也可逆势；成熟 TR 以低买高卖和快速兑现为主；极窄、利润空间不足的 TR 应不交易。
5. [Brooks/课件] Binary Decision（Binary Decisions，二元决策）不是预测下一根 K，而是依次只回答两个选项：Trend/TR → Breakout/Channel → Tight/Broad → Major/Minor Reversal，从而把含糊图表映射到一组较窄的候选行动。
6. [分析推断] 本课的保守默认可以理解为“在证据不足时，先避免逆强势交易”：Breakout 与 Channel 分不清时先按 Breakout；Tight 与 Broad 分不清时先按 Tight；紧密趋势里的首次反转先按 Minor。它是临时工作假设，后续必须由结构、离区与 follow-through 更新，而不是永久标签。
7. [分析推断] 课程给出的“只买/只卖”“逢高加仓”“区间两端剥头皮”等是状态内的方向倾向，不是完整订单系统；若缺 entry、结构 stop、最大总仓位、成本与退出规则，不能直接机械执行。

## 知识讲解

### Pullback 是概率化状态，不只是反向几何｜00:34–05:16｜[Brooks/课件]

Brooks 先把 Pullback 定义为趋势中的任何 pause，因此它同时是一个小型 Trading Range。之所以仍叫“回调”，是因为交易者预期原趋势较可能恢复。课件在牛趋势图上写明 `Low falls below low of prior bar`，这是当前周期最常见的最小技术几何；熊趋势镜像为某根 K 的 high 高于前一根 high。但 Brooks 随即扩宽定义：牛趋势里一根 bear body 即使没有跌破前低，也可以是 pause；在熊趋势中，一根当前周期尚未高于前高的 bull bar，也可能在低周期展开成真实 Pullback，当前周期可称 Implied/Inferred Pullback。

[画面事实] 01:49–02:29 的绿色 Wedge Bull Flag 高亮从一根 bear bar 开始，而后面仍出现更高高点；课件标题直接写 `Pullback: Can Begin before End of Trend`。这说明“趋势最后一个高点”和“回调已经开始”可以同时成立：前者描述价格极值，后者描述状态归属。实战上不能等到最终高点事后出现才承认回调，但也不能把第一根逆色 K 自动升级成反转。

[Brooks/课件] 02:54–03:16 展示回调继续向下、跌破先前牛突破底部后，交易者不再称市场为 Bull Trend，而先在 TR 与 Bear Trend 之间重判。随后 Brooks 又强调分类仍依相对强弱：如果先前牛突破明显强于后续弱熊通道，他仍可能把整段下跌看成那次牛突破的 Pullback，并寻找向上反转买入。边界是强度比较与当前状态必须一致；`might buy` 不是无条件买，也不提供止损、仓位或保证第二腿。

### Trend、Swing、Leg、Pullback 是可重叠尺度｜05:16–07:05｜[Brooks/课件]

[画面事实] EURUSD 5 分钟图依次把同一张图的区域标成 Bull Trend、Bear Swing and Leg、Bull Swing、Bear Swing，并把牛摆动内部一段小下跌标成 `Bear leg and PB`。Brooks 的语言规则是：任何方向移动都可以叫 Leg；只要幅度足以获得 swing profit，就可以叫 Swing；占据更大图表尺度并支持大 swing 时也可称 Trend；若背景仍预期父趋势恢复，则逆向段还可叫 Pullback。

图中第一段下跌约为先前上涨的 50% retracement，既有很多 bear bars、可能一度 Always In Short，又仍可被描述为原 Bull Trend 的 50% Pullback。随后一段上涨能给 swing profit，却没有强到让 Brooks 称为新 Bull Trend，更像 TR 中的 Bull Leg/Bull Swing。交易含义是先确定父结构与交易目的，再选名字；不能因为一段叫 Swing 就自动设固定持有根数，也不能因为叫 Pullback 就忽略它内部足以伤害逆势仓位的独立趋势。

### 从一根 TR 到 Breakout Mode｜07:05–09:49｜[Brooks/课件]

Trading Range 可以小到一根 K，也可以覆盖整屏。若这一根或这一小段不足以改变左侧趋势的方向预期，Brooks 仍称其为 Pullback。真正的状态门不是数字本身，而是交易者是否开始对“原趋势恢复还是反转”感到困惑。

[画面事实] 07:58–08:57 的例子先有 Sell Climax，随后强反转、两根回调，再出现三根收在高位的 bull bars。课件从 `Possible start of Trading Range` 更新为 `More sideways to up likely`。这里的核心不是“三根必反转”，而是 Big Down 之后出现足够强的 Big Up，使空头需要更多信息才愿意再卖；双方预期开始接近，横向范围更可能继续生长。

[Brooks/课件] 大约 20 根后，多空逐步趋于平衡，市场进入 Breakout Mode。课程同时给出三组不能混合的数字：第一次突破约 50% 会失败；最终向上与向下各约 50%；约 20、30、40 根后，旧熊趋势恢复与向上反转的概率趋于相同。三者的事件和分母不同，且都未给样本、市场或统计方法。它们用于表示“旧趋势信息衰减”，不是生成下一笔固定胜率。

### 先识别周期位置，再选择交易方式｜09:49–12:23｜[Brooks/课件]

Brooks 反对等待“完美入场”：每根 K 都有机构买卖，关键问题不是有没有唯一完美形态，而是当前属于 Breakout、Channel 还是 Trading Range，以及对应如何进入、管理。小周期上的“崩盘”往往只是更大 TR 内的一条腿；不能因为局部幅度吓人就自动把父状态改成趋势。

[Brooks/课件] 课程声称只有约 10% 的 bars 处于强 Breakout，约 90% 位于 Channel 或 TR。本课没有提供这组总体比例的独立统计。它表达的操作差异更重要：[画面事实] 强 Bear Breakout 的红色区域标为 `only sell`，强 Bull Breakout 的绿色区域标为 `only buy`，Broad Bull Channel 与 TR 的蓝色区域则标为 `Buy and sell`。一旦明确是 TR，Brooks 倾向切换到限价单：bar 下方买、bar 上方卖并 scalp；但该倾向必须被真实强离区与跟进覆盖。

### Binary Decisions：逐层二分，而非一次猜完｜12:23–14:42｜[Brooks/课件]

二元决策按层级展开：第一问是 Trend 还是 TR；若为 Trend，再问 Breakout 还是 Channel；若为 Channel，再问 Tight 还是 Broad；出现反转时，再问 Major 还是 Minor。每次只比较两个候选，能减少同一时间堆叠十几个形态名所造成的迟疑。

[画面事实] 12:35–14:37 的牛走势虽然不断抬高，但课件逐步标出：没有连续大 bull trend bars；每次 bull bar 和新高后的 follow-through 令人失望；有多根收在中点下方的大 bear bars、明显 tails；空头卖新高可以赚钱；Pullback 回到或穿过 Breakout Point，所有 gaps 被关闭。Brooks 因此把它判断成将来 TR 里的一条 Bull Leg，而不是可长期维持的强 Bull Trend。

交易含义是：HH/HL 只说明方向结构，不能独自决定 regime。反向限价单是否能在趋势中重复赚钱，是趋势质量下降的行为证据。边界在于本图“将成为 TR”仍是概率判断；若随后重新出现强牛突破并持续跟进，必须推翻该降级预期。

### 看不清时的保守默认｜14:42–17:03｜[Brooks/课件]

Breakout 与 Tight Channel 的边界有时很模糊。课件给出 `If Unclear, Assume BO`，因为 Tight Channel 在更高周期本来就会压缩成 Breakout。图中牛通道的 pullbacks 只有一根或几根，K 线间仍保持开放的 gap，因此 Brooks 只寻找买入。这里“只买”是方向过滤，不代表任意价格、任意仓位都买，也不排除等待回调或放弃。

Tight 与 Broad Channel 分不清时，课件给出 `If Unclear, Assume Tight`。熊例虽然有重叠、呈 stairs，且多头能在低位 scalp，但反弹只有 1、1、3、3 根，整体仍很紧；Brooks 宁愿只卖，常在一段下跌约一半的反弹位置寻找卖出。课程没有提供“紧密”的固定斜率、ATR 或线宽算法，`about halfway` 也只是本例相对位置。

在紧密熊通道里，首次向上反转通常先按 Minor Reversal：它更可能成为 Bear Flag、TR 中的 Bull Leg，或 Bear Channel 内部的 Bull Leg。若逆势买这种 minor reversal，Brooks 建议只 scalp。只有反向强 Breakout、主要结构越界与 follow-through 出现后，才有理由升级为 Major Reversal 或新趋势。

### 从强突破到“不交易”的执行矩阵｜17:03–19:03｜[Brooks/课件]

[画面事实] 最后一张综合图把四种状态放在同一序列中：强牛 Breakout 标为只买，可按 close、market、bar 上方或下方参与，并可 scalp 或 swing；Broad Bull Channel 中多头仍买 pullbacks，但深回调让空头也能在高位卖并 scale in for scalps；Trading Range 中多头低买、空头高卖，双方主要 scalp；最右侧 Tight Trading Range 直接写 `Do not trade`。

Broad Channel 中“逆势方能赚钱”意味着趋势在变弱并可能很快进入 TR，但并不等于立刻形成反向趋势。TR 的 bottom third/top third 是区间位置启发式，不是精确成交边界。极窄 TR 的 bars 很小、利润空间连限价单都不足时，等待本身就是决策。课程展示了 scale-in 的课堂路径，却没有给最大次数、总仓位、灾难止损、费用与尾部风险；这些缺口不能由图中最终回归突破点的结果反推为安全规则。

## 决策模型

| 背景/市场状态 | 观察证据 | 候选行动 | 确认条件 | 失效条件 | 风险含义 | 来源层 |
|---|---|---|---|---|---|---|
| 趋势中的短 pause | 原趋势结构仍在；小 TR；牛趋势中某 bar 的 low<prior bar low，熊趋势镜像为 high>prior bar high，或低周期存在隐含回调 | 仍按 Pullback 观察原趋势恢复；等待合适的顺势恢复信号 | 原方向重新突破并有 follow-through | 反向 bars/legs 扩大、破坏关键结构，状态进入 TR/反向趋势 | Pullback 名称只表示相对概率，不保证第二腿或盈利 | [Brooks/课件] 00:34–05:16 |
| Pullback 增长到约 20+ bars | 双向腿增多，旧趋势距离变远，多空对恢复/反转更均衡 | 切换为 TR/Breakout Mode 思考，等待真实离区 | 一侧强突破、离开范围并持续跟进 | 突破快速失败回区，或旧趋势重新强恢复 | 20、30、40 与 50/50 都是课程软尺度/先验，不是下单阈值 | [Brooks/课件] 07:46–09:46 |
| 尚未判定 Trend/TR | 是否同时有合理多空交易；是否持续单向推进；是否有重叠、tails、反向盈利 | 先完成 Trend/TR 二分，再解释局部形态 | 单向结构与跟进持续，或双向边缘反应重复 | 强离区及跟进否决旧 TR；结构破坏否决旧 Trend | 仅一组 HH/HL 或 LL/LH 不能单独定状态 | [Brooks/课件] 12:23–14:37 |
| Trend 中分不清 Breakout/Channel | 回调很短；gap 仍开；更高周期可把 Tight Channel 压缩成 Breakout | 暂按 Breakout，只保留趋势方向候选 | 同向推进、浅回调、gap/突破点保持 | 深回调、gaps 全关、反向交易可重复盈利、坏跟进 | “只买/只卖”是方向过滤，不等于任意入场 | [Brooks/课件] 14:42–15:28 |
| Channel 中分不清 Tight/Broad | 回调短、通道线相近；反向 scalp 虽可赚钱但结构仍紧 | 暂按 Tight，只按趋势方向；等待回调而非逆势押大反转 | 原方向恢复并继续新极值 | 回调深久、Always-In 可翻转、双方都能稳定赚钱 | 缺固定宽度算法；约 50% 反弹只是例中候选区 | [Brooks/课件] 15:32–16:19 |
| 紧密趋势出现首次反转 | 反向腿存在，但原趋势通道很紧、主要结构未破 | 先按 Minor；若逆势参与只考虑 scalp，或等待失败后的顺势机会 | Minor：原趋势恢复；Major：反向强突破、结构越界与跟进 | 只有局部形态、单根反转或坏跟进 | Minor 仍可能扩大成 TR；scalp 也需独立止损与成本计划 | [Brooks/课件] 16:23–16:58 |
| Broad Channel | 原方向 HH/HL 或 LL/LH 仍在；回调深；逆势方能在极值附近盈利 | 顺势买回调/卖反弹；熟练者可逆势 scalp | 原方向恢复，或逆势 scalp 快速兑现 | 主要结构破坏并进入 TR/反趋势；逆势仓未按计划退出 | 允许双向不等于方向中性；scale-in 风险参数未给 | [Brooks/课件] 17:18–18:04 |
| 成熟 TR / 极窄 TR | Big Up–Big Down、困惑、边缘反转；或 bars 极小、空间不足 | 普通 TR 低买高卖并 scalp；极窄 TR 不交易 | 边缘回区，或成功 breakout+follow-through 后切换状态 | 强离区后继续使用旧区间 fade；极窄区强行追求微利 | top/bottom third 是软区域；成本可吞没微小空间 | [Brooks/课件] 18:05–19:00 |
| 准备用课堂倾向实盘下单 | 课程只给状态和候选方向，未闭合 entry、stop、总仓位、费用与退出 | 补齐可验证交易计划；无法补齐则放弃 | 所有风险字段事前定义，结构失效可执行 | 临场补造规则、无限 scale-in、用课堂概率代替统计 | 这是风险工程，不应误归因于 Brooks 本课逐字规则 | [分析推断] |

## 关键概念

| 英文术语 | 推荐中文 | 本课增量含义 | 使用边界 | 来源时间 |
|---|---|---|---|---|
| Pullback | 回调；熊趋势中为反弹 | 趋势中的小 TR，名称同时表达原趋势较可能恢复；可在最终极值出现前开始 | 当前周期几何、低周期隐含结构与父趋势概率要分开；可继续发展为 TR/反转 | 00:34–05:16 |
| Trading Range | 震荡区间；TR | 可小至一根；当 Big Down–Big Up 造成困惑、双方等待更多信息时，范围会生长 | 一根 TR 在趋势中仍可称 Pullback；约 20 根是软命名线 | 07:05–09:49 |
| Binary Decision | 二元决策 | 依次只在两个状态间选择，以快速缩小候选行动 | 不是二元预测、自动分类器或“只剩买/卖”口令；每层需后续证据更新 | 12:23–14:42 |
| Breakout vs Channel Default | 突破/通道默认 | 分不清时先按 Breakout，因为 Tight Channel 在高周期就是 Breakout | 只用于暂时限制逆势交易；深回调、gap 关闭和坏跟进会否决 | 14:42–15:28 |
| Tight vs Broad Channel Default | 紧密/宽幅通道默认 | 分不清时先按 Tight，并只考虑趋势方向 | 没有固定线宽或根数算法；反向腿深化与双方盈利会升级为 Broad/TR | 15:32–16:19 |
| Minor Reversal | 次要反转 | 紧密趋势中的首次反转通常只通向旗形、TR 腿或通道内腿 | `probably minor` 不是必败；强反向突破与跟进可升级 | 16:23–16:58 |
| Confusion | 困惑/方向冲突 | Big Down–Big Up、强反向压力与多空都需要更多信息，是 TR 的状态线索 | 主观感受必须绑定可见双向结构，不能把任何犹豫都称为 TR | 07:58–09:07 |
| Tight Trading Range | 极窄震荡区间；TTR | 空间小到连限价单也缺利润潜力时，课程明确建议不交易 | 等待真实离区；不要把“不交易”改写成课程未说的具体突破订单 | 18:48–19:00 |

## 案例与反例

| 时间 / Claim ID | 画面或课程事实 | Brooks/课件解释 | 实战含义 | 排除的机械读法 |
|---|---|---|---|---|
| 01:15 / PAF12C-V01 | 课件写明牛趋势 pause 是小 TR，标注某根 low 低于前一根 low | 原趋势预期恢复，所以称 Pullback | 先读父趋势，再读最小回调几何 | 见到 low<prior low 就自动做空 |
| 02:05–02:25 / PAF12C-V02 | 绿色 Wedge Bull Flag 从最终高点前的一根 bear bar 开始 | Pullback 可在 trend end 前开始 | 状态起点与最终价格极值可重叠 | 只有出现最终高点后才算回调 |
| 03:10–03:15 / PAF12C-V03 | 红色下跌区跌破先前牛突破底部 | 旧 Bull Trend 结束，先在 TR/Bear Trend 间重判 | 结构破坏触发状态降级 | 一跌破就自动确认完整熊趋势 |
| 04:20–05:05 / PAF12C-V04 | 熊趋势中标出当前周期真实反弹；另一页写跌破牛突破底部仍可能是该牛腿的 Pullback | 周期与相对强度都参与命名，部分多头会等向上反转 | 允许标签多层共存，但必须保留 `might` | 画面有 Wedge 就无条件买 |
| 05:35–06:45 / PAF12C-V05 | 同图叠加 Trend、Swing、Leg 与 PB 多个区域 | 术语无严格互斥边界，取决于尺度和可交易利润 | 先明确父结构和持仓目的 | 固定根数决定唯一标签 |
| 08:02–09:45 / PAF12C-V06 | Sell Climax 后强反转、三根 bull bars；约 20 根后课件写 Neutral/Breakout Mode | 困惑使 TR 生长，旧趋势影响衰减 | 从单向延续改为等待真实突破 | 第 20 根自动精确 50/50 或反手 |
| 12:40–14:20 / PAF12C-V08 | 二元问题清单；牛走势又显示坏跟进、bear bars、tails、空头卖高能盈利、gaps 全关 | 更像未来 TR 中 Bull Leg | HH/HL 与趋势质量证据分开 | 只要创新高就是强牛趋势 |
| 17:10–18:58 / PAF12C-V11 | 综合图依次标出强突破只顺势、宽通道双向、TR 低买高卖、TTR 不交易 | 交易方式随周期位置变化 | 等待也是完整行动；双向权限随状态增加 | 同一入场法适用于所有阶段 |

## 知识连接

1. 与 [BTC PAF 12A Market Cycle](<BTC PAF 12A Market Cycle.md>) 的连接：12A 建立 Breakout → Tight Channel → Broad Channel → TR 的循环，以及 first pullback 和逆势盈利两道状态门。本课把该循环压缩成可实时提问的二元链，并明确极窄 TR 可直接选择“不交易”。
2. 与 [BTC PAF 12B Market Cycle](<BTC PAF 12B Market Cycle.md>) 的连接：12B 用 Trend/TR、Major/Minor HL/LH 和 breakout/follow-through 管理状态。本课回到 Pullback/TR 的边界，补上“不清楚时先按 Breakout/Tight/Minor”的暂时默认；截至本课分析时，这些默认都不能覆盖 major pivot 与后续跟进。
3. 与 [BTC PAF 09A Pullbacks and Bar Counting](<BTC PAF 09A Pullbacks and Bar Counting.md>)、[BTC PAF 09C Pullbacks and Bar Counting](<BTC PAF 09C Pullbacks and Bar Counting.md>) 的连接：09A/09C 已区分当前/隐含回调、bars/legs 增长和 Endless Pullback。本课再次说明约 20+ bars 会削弱旧趋势语言，但实际离区和跟进仍高于机械计数。
4. 与 [BTC PAF 10B Buying and Selling Pressure](<BTC PAF 10B Buying and Selling Pressure.md>)、[BTC PAF 11D Gaps](<BTC PAF 11D Gaps.md>) 的连接：两课用坏跟进、反向 Pressure、gap 关闭、Stairs 与逆势盈利诊断趋势衰减。本课把这些线索集合进 Binary Decision 的 Trend/TR 与 Tight/Broad 两个节点。
5. 与 [BTC PAF 08D Candles Setups and Signal Bars](<BTC PAF 08D Candles Setups and Signal Bars.md>) 的连接：08D 强调 Setup、Signal、Entry 与 Follow-through 不可合并。本课的“只买/只卖”只筛方向；截至本课分析时，具体 signal、trigger、stop 与 management 仍需独立闭合。

## 复习提纲

一分钟重建：先问 Trend 还是 TR；若为 Trend，再问 Breakout 还是 Channel；若为 Channel，再问 Tight 还是 Broad；若出现反转，再问 Major 还是 Minor。证据不足时暂按 Breakout、Tight、Minor，以减少逆强势交易。随后按状态选行动：强突破/紧通道主要顺势，宽通道允许双向但仍有趋势倾斜，TR 低买高卖，极窄 TR 不交易。任何标签都要被下一次结构破坏、离区和 follow-through 更新。

主动回忆：

1. 为什么 Pullback 同时是一个小 TR，却不与 TR 同义？
2. 回调为什么可能在趋势最终高点/低点出现之前开始？
3. “第一次突破约 50% 失败”和“最终上下各约 50%”为什么不能合并？
4. 同一段行情如何同时成为 Pullback、Leg 与 Swing？
5. 牛走势不断创新高时，哪些证据会把它降级为未来 TR 中的一条腿？
6. `Assume BO`、`Assume Tight`、`probably minor` 分别在防什么错误？
7. 为什么 Broad Channel 中双方都能赚钱仍不等于立刻反向趋势？
8. 极窄 TR 的最优决策为什么可能是不交易？

建议视觉复看：01:15（回调最小几何）；02:05–03:15（提前开始与状态演化）；05:35–06:45（多尺度标签）；08:02–09:45（困惑、20 根与 Breakout Mode）；12:40–14:20（二元判断及弱化牛腿）；15:10–16:50（保守默认与 Minor Reversal）；17:10–18:58（四状态执行矩阵）。

## 证据边界

整体信心：高。 英文字幕、中文字幕、完整视觉时间线与关键原生画面在核心教学上相互闭合；限定词和译者增补均已按英文与课件校正。

无开放未决项。课程中的 10/90、20+、50/50、第一突破失败率、回调根数和比例均为 Brooks/课件主张，未提供可复现样本或独立统计；课程也没有给出完整仓位、成本、灾难止损与 scale-in 上限。完整来源、字幕、数字及画面映射见[课程审计](<../audits/BTC PAF 12C Market Cycle.md>)。
