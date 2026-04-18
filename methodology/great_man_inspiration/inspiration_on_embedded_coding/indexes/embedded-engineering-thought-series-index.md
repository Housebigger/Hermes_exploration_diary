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

## 后续候选主题

- `029《统一战线中的独立自主问题》`：合作面扩大时，如何既借力又不丢固件主线判断和执行主动权。
- `034《必须制裁反动派》`：对重复破坏版本纪律、接口边界和证据链的人，为什么不能只讲合作不讲后果。
- `035《关于国际新形势对新华日报记者的谈话》`：新阶段不是舒服停摆，而是围绕主线升级准备反攻结构。
- `033《反对投降活动》`：别让妥协逻辑拆掉嵌入式主线、主联盟和验证纪律。

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
