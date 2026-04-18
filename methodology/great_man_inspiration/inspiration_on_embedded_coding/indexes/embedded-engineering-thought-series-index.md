# 嵌入式软件工程思想笔记专栏

日期：2026-04-14

说明：
这个专栏尝试把一些经典思想文本中的方法论，转换成面向现代嵌入式软件工程的工作语言。

目标不是生搬硬套原始语境，更不是把历史文本当成管理口号，而是做三件事：

1. 提炼其中仍然有效的分析框架
2. 映射到嵌入式编码、调试、联调、量产和维护场景
3. 形成可执行、可讨论、可复用的工程方法笔记

我希望这个专栏最终能逐步沉淀成一组适合嵌入式研发团队阅读和讨论的研究日志。

## 已完成

### 1. 从《论持久战》看长周期嵌入式软件工程的方法论启示

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/engineering_strategy/001-on-protracted-war-long-cycle-embedded-software.md`

核心主题：
- 反对工程中的“亡国论”和“速胜论”
- 用阶段论管理长周期项目
- 在全局持久中争取局部速决
- 用主动性、灵活性、计划性争取工程主动权
- 把个人英雄主义转化为团队持续作战能力

### 2. 从《实践论》看嵌入式调试中的“知行闭环”

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/debugging_and_fieldwork/002-on-practice-debugging-closed-loop.md`

核心主题：
- 调试中的教条主义与经验主义
- 现象—假设—实验—反馈—修正的闭环
- 如何从感性材料走向可验证结论
- 为什么真正可靠的理解必须回到实践中检验

### 3. 从《矛盾论》看复杂固件系统的主次矛盾与故障排序

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/system_analysis_and_architecture/003-on-contradiction-firmware-fault-ordering.md`

核心主题：
- 不要孤立、静止地看待复杂固件问题
- 如何识别主要矛盾与非主要矛盾
- 如何判断主要矛盾方面
- 如何建立更接近系统结构的故障优先级排序方法

### 4. 从《反对本本主义》看驱动开发中的资料主义与实机主义

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/debugging_and_fieldwork/004-against-book-worship-driver-development.md`

核心主题：
- 为什么驱动开发最容易陷入资料主义
- 为什么文档、SDK、参考设计不能直接替代真机调查
- 如何把“没有调查，没有发言权”转化为驱动开发方法
- 为什么真机行为而不是纸面理解应成为最终裁决依据

### 5. 从《改造我们的学习》看工程团队的知识沉淀与技术复盘

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/005-rectify-learning-knowledge-retrospective.md`

核心主题：
- 为什么工程团队最常见的问题不是没人干活，而是干完没留下
- 如何把“研究现状、研究历史、反对理论和实际分离”转化为知识管理方法
- 为什么技术复盘要从情绪和口号层升级为结构分析与动作沉淀
- 如何把一次问题处理转化为案例库、调试手册、checklist 和组织能力


### 6. 从《和中央社、扫荡报、新民报三记者的谈话》看嵌入式团队：不要把一起扛板级问题的人先当异己，要把工程自力更生、联合调试和边界自卫做成下一阶段准备反攻的结构

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/006-dont-treat-debug-allies-as-outsiders-build-engineering-self-reliance-and-defend-boundaries.md`

核心主题：
- 为什么嵌入式团队在相持阶段不能把准备反攻误成全面重构或舒服停摆
- 为什么工程自力更生不是少数高手继续硬扛，而是现场信息、责任边界和调试机制的内部升级
- 为什么硬件、驱动、测试、FAE、工厂与供应商接口人不能先被当成异己，而应按友军逻辑组织联合调试
- 为什么联调磨擦既不能无限放大，也不能无限忍让，而要落到严格自卫的工程边界治理

### 7. 从《反对自由主义》看嵌入式团队：别拿表面和气换工程真相，板级异常、现场坏信号和质量问题必须进机制

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/007-dont-trade-surface-harmony-for-embedded-truth-and-discipline.md`

核心主题：
- 为什么嵌入式项目常死于被纵容的坏信号，而不是单个公开大故障
- 为什么板级异常、现场噪音、版本回归和证据缺口必须进入正式机制
- 为什么不能让情面、资历和关系覆盖工程事实与质量纪律
- 为什么跨层协作必须把反馈、升级和纠偏做成真相保护系统

### 8. 从《陕甘宁边区政府第八路军后方留守处布告》看嵌入式团队：协作期别让临时支援、未授权改动和关系型插手重开工程混乱

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/008-dont-let-unbounded-support-reopen-your-embedded-order.md`

核心主题：
- 为什么版本、板卡、产测和 patch 准入规则是嵌入式项目的既得工程成果
- 为什么真正的支援不会要求团队拆掉已经修好的工程系统
- 为什么联合调试和量产收敛最怕未经授权的介入与入口失守
- 为什么协作稳定不只靠好意，还要靠权限、边界、记录和升级处理机制

### 9. 从《抗日游击战争的战略问题》看资源弱势的嵌入式团队：先建工程根据地，用局部快仗和灵活机动穿过长期压力

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/engineering_strategy/009-build-embedded-base-areas-and-grow-under-long-pressure.md`

核心主题：
- 为什么弱势嵌入式团队不能照着强者的正面工程打法平均铺开所有战线
- 为什么工程根据地要落实为稳定版本线、基准板卡、可复现实验面和观测链
- 为什么整体防守中仍要主动创造局部快仗和可收口的小胜
- 为什么多线压力下必须集中主力打穿一路并把小打法升级成主力能力

### 10. 从《战争和战略问题》看嵌入式项目：真正决定成败的不是到处救火，而是识别主战场并围绕主链路组织主力

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/engineering_strategy/010-major-embedded-battles-need-a-main-battlefield-and-main-force.md`

核心主题：
- 为什么嵌入式项目关键阶段不能继续用平均主义方式管理所有问题
- 为什么主战场一旦明确，其它测试、日志、工厂和协同动作都要重新排位
- 为什么没有成建制的工程主力，项目即使知道重点也很难真正改局
- 为什么团队不仅要研究单个故障，还要研究主战场本身的结构、变量与打法

### 11. 从《统一战线中的独立自主问题》看嵌入式团队：联合调试、供应商协作和跨团队借力都可以更宽，但别把固件主线判断、版本节奏和现场主动权交出去

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/011-cooperate-broadly-without-surrendering-embedded-initiative.md`

核心主题：
- 为什么联合调试面越宽，越不能把固件主判断溶解进“大协作气氛”里
- 为什么真正值钱的让步，是为了推进主链路，而不是把嵌入式团队重新降回附属执行层
- 为什么版本、升级、验证和问题升级通道是必须守住的独立阵地
- 为什么借供应商、平台、工厂和现场之力，不应演变成关键判断与调试能力的外包

### 12. 从《反对投降活动》看嵌入式团队：真正危险的不是外部压力本身，而是内部先用“先和一下”的逻辑拆掉主线、主联盟和验证纪律

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/012-dont-let-appeasement-logic-break-your-embedded-mainline-and-alliance.md`

核心主题：
- 为什么嵌入式项目高压期第一问题不是气氛，而是主线还能不能继续守住
- 为什么“先别那么硬”“先把版本发了再说”常是求和逻辑的工程包装
- 为什么压制最坚持证据链和底层约束的人，往往是在为整体退让清场
- 为什么项目真正要防的，是主联盟被拆和验证纪律被慢慢卖掉

### 13. 从《必须制裁反动派》看嵌入式团队：真正的协作不是让守版本纪律和证据链的人一直吃亏，而是保护建设者、让重复破坏者承担后果

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/013-dont-call-it-collaboration-if-repeat-breakers-face-no-consequence.md`

核心主题：
- 为什么判断嵌入式协作是真是假，关键要看组织到底在保护谁、处理谁
- 为什么建设者持续吃亏、破坏者长期零代价时，项目一定会慢慢坏掉
- 为什么限制最有建设性的人，常常不是治理而是在替破坏者清场
- 为什么版本门禁、证据链和接口边界都需要真实的后果结构来保护

### 14. 从《关于国际新形势对新华日报记者的谈话》看嵌入式团队：真正的新阶段，不是终于可以松一口气，而是守住主线、升级结构、把系统整到能反攻

文件：
`methodology/great_man_inspiration/inspiration_on_embedded_coding/engineering_strategy/014-dont-treat-a-new-embedded-stage-as-rest-hold-the-line-and-prepare-counterattack.md`

核心主题：
- 为什么嵌入式项目一旦稍微稳住，最危险的误判往往是“现在终于可以松了”
- 为什么新阶段不会自动变好，而会分叉成继续升级或重新滑回被动两条路
- 为什么“准备反攻”在工程里意味着重整版本、观测、测试、组织和资源结构
- 为什么当前防御战线和未来反攻战线必须同时成立，不能只顾其一

## 后续候选主题

- `019《反对日本进攻的方针、办法和前途》`：把正确方向变成嵌入式动员、资源和打法系统，而不是只停留在方向判断。
- `020《为动员一切力量争取抗战胜利而斗争》`：关键量产与稳定性硬仗，需要全系统动员而不是少数人硬扛。
- `023《和英国记者贝特兰的谈话》`：别把关键嵌入式硬仗打成少数工程师的被动防御战。
- `024《上海太原失陷以后抗日战争的形势和任务》`：别把局部止损误成真实转折，要守住过渡期判断。
- `028《中国共产党在民族战争中的地位》`：先成为能扛板级现实的工程骨干，再谈在系统里占关键位置。
- `031《五四运动》`：新阶段要让理解系统的人真正进入现场承重主体，而不是只停留在表达层。
- `032《青年运动的方向》`：先锋型工程师必须和真实交付、产测、现场与维护主力结合。

## 这个专栏的写法原则

为了避免空泛，我会尽量坚持以下原则：

- 不只谈理念，一定落到工程现场
- 不只谈态度，一定落到方法和动作
- 不只谈成功学，一定讨论局限与误用风险
- 不只写给管理者，也写给一线编码和调试工程师
- 每篇文章都尽量形成“可以拿去团队讨论”的结构

## 临时结语

嵌入式软件工程并不缺技术细节，真正稀缺的往往是：
- 如何判断问题
- 如何安排节奏
- 如何组织知识
- 如何在长周期和高不确定性中保持工程主动权

如果这个专栏能持续写下去，我希望它最终留下来的不是几篇概念文章，而是一套更适合长期工程实践者阅读的思考笔记。
