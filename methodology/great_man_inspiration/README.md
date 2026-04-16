# great_man_inspiration

这个 README 现在承担一个“总索引板”的作用：
- 对照 `https://www.marxists.org/chinese/maozedong/index.htm` 的真实主文章列表
- 标记当前仓库里已经完成了哪些毛泽东原文的 inspiration 转译
- 把已经写好的 inspiration 文件与对应原文做成可跳转的索引关联

说明：
- 下表中的“真实文章列表”按 marxists.org `index.htm` 的 0—5 主分卷、只统计带编号的主文章条目。
- 当前 `inspiration_on_today_life/indexes/000-mao-anthology-sequential-reading-overview.md` 的顺序覆盖窗口已经补齐到 001—026。
- 除了这条顺序主线外，仓库里还有少量“非顺序先写”的拓展条目，例如 `《改造我们的学习》`。

## 1. 当前覆盖状态总览

| 指标 | 当前结果 |
|---|---|
| marxists.org 主文章总数（编号主条目） | 229 |
| 当前已建立原文关联的毛文标题数 | 27 |
| 当前已建立 `原文对应` 的 inspiration 文件数 | 116 |
| 顺序学习已连续覆盖范围 | 001—026 |
| 顺序覆盖段标题核对结果 | 26/26 与 marxists.org 标题一致 |
| 顺序概览是否连续 | 是 |
| 顺序主线的下一篇 | 027《论持久战》 |

## 2. 与真实文章列表的比对结论

### 2.1 顺序主线当前已确认对齐

- 当前顺序主线已经和 marxists.org 的真实主文章列表对齐到 `026《抗日游击战争的战略问题》`。
- 在 `001—026` 这段里，仓库顺序标题与 marxists.org 原始标题逐条核对一致。
- 当前下一篇尚未纳入顺序主线的是 `027《论持久战》`：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193805b.htm

### 2.2 这次补齐后，顺序主线开头缺口已被补上

| 顺序号 | 原文 | 真实链接 | 当前状态 |
|---|---|---|---|
| 001 | 《中国社会各阶级的分析》 | [marxists.org](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19251201.htm) | 已纳入顺序主线，已建立 5 个主题转译文件 |
| 002 | 《湖南农民运动考察报告》 | [marxists.org](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-192703.htm) | 已纳入顺序主线，已建立 5 个主题转译文件 |

### 2.3 一个简单的覆盖示意图

```text
001—026 顺序主线已建立关联        [##########################]
027 论持久战                         [NEXT]
060 改造我们的学习                  [EXTRA] 非顺序拓展
```

## 3. 主题缩写图例

| 缩写 | 主题目录 |
|---|---|
| TL | `inspiration_on_today_life/` |
| SD | `inspiration_on_software_development/` |
| RC | `inspiration_on_running_a_company/` |
| SI | `inspiration_on_stock_investing/` |
| MM | `inspiration_on_making_money/` |
| EC | `inspiration_on_embedded_coding/` |

## 4. 原文 -> inspiration 文件 关联矩阵

提示：表格里的缩写都是可点击链接，点进去就是对应的 inspiration 文件。

| 顺序号 | 原文 | 真实原文 | TL | SD | RC | SI | MM | EC | 文件数 |
|---|---|---|---|---|---|---|---|---|---|
| 001 | 《中国社会各阶级的分析》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19251201.htm) | [TL](./inspiration_on_today_life/judgement_and_decision/001-dont-misread-allies-by-surface-labels.md) | [SD](./inspiration_on_software_development/user_research_and_requirements/001-dont-segment-product-roles-by-surface-labels.md) | [RC](./inspiration_on_running_a_company/organization_design/001-dont-judge-org-allies-by-title-and-posture.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/001-dont-read-companies-by-sector-labels-alone.md) | [MM](./inspiration_on_making_money/monetization_models/001-dont-judge-side-hustle-opportunities-by-surface-status.md) | — | 5 |
| 002 | 《湖南农民运动考察报告》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-192703.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/002-dont-misjudge-bottom-up-change-as-mere-chaos.md) | [SD](./inspiration_on_software_development/team_process_and_quality/002-dont-treat-bottom-up-product-change-as-mere-chaos.md) | [RC](./inspiration_on_running_a_company/organization_design/002-dont-treat-bottom-up-correction-as-loss-of-control.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/002-dont-mistake-structural-repricing-for-mere-chaos.md) | [MM](./inspiration_on_making_money/execution_and_delivery/002-dont-dismiss-new-monetization-order-as-mere-chaos.md) | — | 5 |
| 003 | 《中国的红色政权为什么能够存在？》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19281005.htm) | [TL](./inspiration_on_today_life/survival_strategy/003-red-political-power-foothold-thinking.md) | — | — | — | — | — | 1 |
| 004 | 《井冈山的斗争》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19281125.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/004-jinggangshan-struggle-core-zone-and-anti-fragmentation.md) | — | — | — | — | — | 1 |
| 005 | 《关于纠正党内的错误思想》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-192912.htm) | [TL](./inspiration_on_today_life/judgement_and_decision/005-rectify-internal-chaos-before-chasing-opportunity.md) | [SD](./inspiration_on_software_development/team_process_and_quality/005-rectifying-thought-errors-in-product-teams.md) | [RC](./inspiration_on_running_a_company/organization_design/005-rectify-internal-cognitive-noise-in-organizations.md) | — | — | — | 3 |
| 006 | 《星星之火，可以燎原》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19300105.htm) | [TL](./inspiration_on_today_life/long_term_growth/006-small-sparks-compounding-and-anti-premature-despair.md) | [SD](./inspiration_on_software_development/product_strategy/006-small-spark-product-wedge-and-wave-expansion.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/006-local-strongholds-and-strategic-wave-expansion.md) | — | — | — | 3 |
| 007 | 《反对本本主义》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193005.htm) | [TL](./inspiration_on_today_life/judgement_and_decision/007-investigate-before-judging-major-decisions.md) | [SD](./inspiration_on_software_development/user_research_and_requirements/007-investigation-first-product-discovery.md) | [RC](./inspiration_on_running_a_company/organization_design/007-no-investigation-no-organizational-voice.md) | — | — | [EC](./inspiration_on_embedded_coding/debugging_and_fieldwork/004-against-book-worship-driver-development.md) | 4 |
| 008 | 《必须注意经济工作》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19330812.htm) | [TL](./inspiration_on_today_life/survival_strategy/008-economic-basics-before-big-moves.md) | [SD](./inspiration_on_software_development/iteration_and_delivery/008-resource-flow-and-sustained-delivery.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/008-economic-foundation-and-war-chest-discipline.md) | [SI](./inspiration_on_stock_investing/risk_and_position_management/008-cash-and-supply-lines-before-big-bets.md) | — | — | 4 |
| 009 | 《怎样分析农村阶级》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193310.htm) | [TL](./inspiration_on_today_life/judgement_and_decision/009-see-through-labels-to-real-life-structure.md) | [SD](./inspiration_on_software_development/user_research_and_requirements/009-segment-users-by-real-behavior-and-interests.md) | [RC](./inspiration_on_running_a_company/organization_design/009-classify-roles-by-real-function-and-incentives.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/009-classify-businesses-by-cashflow-source-and-control.md) | [MM](./inspiration_on_making_money/monetization_models/009-classify-side-hustles-by-income-structure.md) | — | 5 |
| 010 | 《我们的经济政策》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193401.htm) | [TL](./inspiration_on_today_life/survival_strategy/010-build-a-self-sustaining-life-economy.md) | [SD](./inspiration_on_software_development/architecture_and_engineering/010-build-core-capacity-and-healthy-ecosystem.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/010-operating-system-balance-production-trade-and-discipline.md) | [SI](./inspiration_on_stock_investing/market_structure_and_cycles/010-real-production-before-policy-premium.md) | [MM](./inspiration_on_making_money/execution_and_delivery/010-side-hustle-needs-production-channels-and-discipline.md) | — | 5 |
| 011 | 《关心群众生活，注意工作方法》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19340127.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/011-real-support-comes-from-solving-concrete-problems.md) | [SD](./inspiration_on_software_development/team_process_and_quality/011-user-pain-and-practical-methods-over-slogans.md) | [RC](./inspiration_on_running_a_company/leadership_and_talent/011-win-followership-by-solving-real-problems.md) | — | [MM](./inspiration_on_making_money/execution_and_delivery/011-earn-trust-by-solving-real-customer-pain.md) | — | 4 |
| 012 | 《论反对日本帝国主义的策略》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19351227.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/012-dont-fight-every-difference-build-a-broad-alliance.md) | [SD](./inspiration_on_software_development/product_strategy/012-broaden-the-alliance-around-the-main-product-battle.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/012-realign-the-company-around-the-main-threat-and-broad-alliance.md) | — | — | — | 3 |
| 013 | 《中国革命战争的战略问题》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193612.htm) | [TL](./inspiration_on_today_life/survival_strategy/013-dont-defend-every-inch-preserve-strength-and-counterattack-when-odds-shift.md) | [SD](./inspiration_on_software_development/iteration_and_delivery/013-dont-turn-every-front-into-trench-war-concentrate-for-decisive-software-battles.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/013-preserve-core-strength-and-concentrate-for-the-decisive-company-battle.md) | [SI](./inspiration_on_stock_investing/risk_and_position_management/013-dont-defend-every-position-preserve-capital-for-high-odds-counterattacks.md) | [MM](./inspiration_on_making_money/execution_and_delivery/013-dont-stretch-every-side-project-line-concentrate-on-the-one-you-can-win.md) | — | 5 |
| 014 | 《关于蒋介石声明的声明》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19361228.htm) | [TL](./inspiration_on_today_life/judgement_and_decision/014-judge-turning-points-by-actions-not-statements.md) | [SD](./inspiration_on_software_development/team_process_and_quality/014-dont-confuse-stakeholder-statements-with-execution-support.md) | [RC](./inspiration_on_running_a_company/leadership_and_talent/014-trust-turnarounds-only-after-real-costly-actions.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/014-verify-management-turnarounds-by-actions-not-guidance.md) | [MM](./inspiration_on_making_money/execution_and_delivery/014-verify-support-in-side-hustle-collaboration-by-actions.md) | — | 5 |
| 015 | 《中国共产党在抗日时期的任务》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370503.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/015-build-a-broad-front-without-losing-your-own-direction.md) | [SD](./inspiration_on_software_development/team_process_and_quality/015-broaden-support-without-surrendering-product-judgment.md) | [RC](./inspiration_on_running_a_company/organization_design/015-broaden-the-alliance-without-giving-away-the-strategic-core.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/015-broaden-your-information-front-without-losing-research-independence.md) | [MM](./inspiration_on_making_money/execution_and_delivery/015-broaden-support-without-losing-your-side-hustle-direction.md) | — | 5 |
| 016 | 《为争取千百万群众进入抗日民族统一战线而斗争》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370508.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/016-dont-just-be-right-turn-direction-into-organized-support.md) | [SD](./inspiration_on_software_development/team_process_and_quality/016-turn-correct-product-direction-into-shared-execution-structure.md) | [RC](./inspiration_on_running_a_company/organization_design/016-turn-strategy-into-a-shared-company-mission.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/016-build-a-research-system-not-just-a-right-opinion.md) | [MM](./inspiration_on_making_money/execution_and_delivery/016-organize-support-so-your-side-hustle-can-scale.md) | — | 5 |
| 017 | 《实践论》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193707.htm) | [TL](./inspiration_on_today_life/long_term_growth/017-real-understanding-grows-from-action-reflection-and-verification.md) | [SD](./inspiration_on_software_development/user_research_and_requirements/017-product-understanding-grows-from-research-build-verify-repeat.md) | [RC](./inspiration_on_running_a_company/organization_design/017-organizational-understanding-grows-from-field-contact-and-revalidation.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/017-investment-understanding-grows-from-contact-testing-and-revision.md) | [MM](./inspiration_on_making_money/execution_and_delivery/017-side-hustle-understanding-grows-through-doing-and-revising.md) | [EC](./inspiration_on_embedded_coding/debugging_and_fieldwork/002-on-practice-debugging-closed-loop.md) | 6 |
| 018 | 《矛盾论》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193708.htm) | [TL](./inspiration_on_today_life/judgement_and_decision/018-find-the-main-contradiction-before-spending-your-life-force.md) | [SD](./inspiration_on_software_development/product_strategy/018-find-the-main-product-contradiction-before-escalating-everything.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/018-find-the-main-operating-contradiction-before-fighting-on-all-fronts.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/018-find-the-main-market-contradiction-before-weighting-every-variable-equally.md) | [MM](./inspiration_on_making_money/execution_and_delivery/018-find-the-main-monetization-contradiction-before-fixing-everything-at-once.md) | [EC](./inspiration_on_embedded_coding/system_analysis_and_architecture/003-on-contradiction-firmware-fault-ordering.md) | 6 |
| 019 | 《反对日本进攻的方针、办法和前途》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370723.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/019-dont-just-know-the-right-direction-build-the-people-and-methods.md) | [SD](./inspiration_on_software_development/team_process_and_quality/019-dont-just-agree-on-strategy-mobilize-people-process-and-resources.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/019-dont-just-set-strategy-build-the-org-and-resource-system.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/019-dont-just-be-right-build-the-research-and-positioning-system.md) | [MM](./inspiration_on_making_money/execution_and_delivery/019-dont-just-have-the-right-side-hustle-direction-build-the-system.md) | — | 5 |
| 020 | 《为动员一切力量争取抗战胜利而斗争》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370825.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/020-major-life-battles-need-full-mobilization-not-half-measures.md) | [SD](./inspiration_on_software_development/team_process_and_quality/020-key-product-battles-need-full-organizational-mobilization.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/020-company-crucial-phases-need-full-mobilization-not-partial-effort.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/020-big-investment-opportunities-need-full-preparation.md) | [MM](./inspiration_on_making_money/execution_and_delivery/020-side-hustle-critical-phases-need-full-system-mobilization.md) | — | 5 |
| 021 | 《反对自由主义》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370907.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/021-dont-trade-principled-feedback-for-surface-harmony.md) | [SD](./inspiration_on_software_development/team_process_and_quality/021-dont-trade-surface-harmony-for-team-truth-and-discipline.md) | [RC](./inspiration_on_running_a_company/organization_design/021-dont-trade-surface-harmony-for-organizational-truth.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/021-dont-trade-research-truth-for-surface-consensus.md) | [MM](./inspiration_on_making_money/execution_and_delivery/021-dont-trade-surface-harmony-for-sustainable-side-hustle-collaboration.md) | — | 5 |
| 022 | 《国共合作成立后的迫切任务》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370929.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/022-dont-stop-at-formal-cooperation-build-shared-rules-and-real-support.md) | [SD](./inspiration_on_software_development/team_process_and_quality/022-dont-confuse-cross-functional-alignment-with-real-execution-capacity.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/022-dont-confuse-top-level-reconciliation-with-operating-turnaround.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/022-dont-confuse-sentiment-recovery-with-structural-turnaround.md) | [MM](./inspiration_on_making_money/execution_and_delivery/022-dont-confuse-willing-collaboration-with-a-real-side-hustle-system.md) | — | 5 |
| 023 | 《和英国记者贝特兰的谈话》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19371025.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/023-dont-fight-major-life-battles-as-a-one-person-defensive-war.md) | [SD](./inspiration_on_software_development/iteration_and_delivery/023-dont-run-key-projects-as-a-passive-defensive-war.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/023-dont-run-company-critical-phases-as-a-passive-defensive-war.md) | [SI](./inspiration_on_stock_investing/trading_and_execution/023-dont-trade-market-opportunities-as-a-passive-defensive-war.md) | [MM](./inspiration_on_making_money/execution_and_delivery/023-dont-run-side-hustle-growth-as-a-passive-defensive-war.md) | — | 5 |
| 024 | 《上海太原失陷以后抗日战争的形势和任务》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19371112.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/024-dont-mistake-partial-turning-points-for-a-real-life-system-upgrade.md) | [SD](./inspiration_on_software_development/team_process_and_quality/024-dont-mistake-partial-org-alignment-for-a-real-project-turnaround.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/024-dont-mistake-partial-operating-relief-for-a-real-company-turnaround.md) | [SI](./inspiration_on_stock_investing/research_and_thesis/024-dont-mistake-partial-market-repair-for-a-real-thesis-turnaround.md) | [MM](./inspiration_on_making_money/execution_and_delivery/024-dont-mistake-partial-side-hustle-momentum-for-a-real-system-takeoff.md) | — | 5 |
| 025 | 《陕甘宁边区政府第八路军后方留守处布告》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19380515.htm) | [TL](./inspiration_on_today_life/cooperation_and_organization/025-dont-let-chaotic-helpers-reopen-your-hard-won-life-order.md) | [SD](./inspiration_on_software_development/team_process_and_quality/025-dont-let-unbounded-support-disrupt-your-engineering-order.md) | [RC](./inspiration_on_running_a_company/organization_design/025-dont-let-coordination-reopen-your-operating-chaos.md) | [SI](./inspiration_on_stock_investing/risk_and_position_management/025-dont-let-soft-bullish-signals-break-your-risk-discipline.md) | [MM](./inspiration_on_making_money/execution_and_delivery/025-dont-let-favors-and-intros-break-your-side-hustle-boundaries.md) | — | 5 |
| 026 | 《抗日游击战争的战略问题》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193805.htm) | [TL](./inspiration_on_today_life/survival_strategy/026-build-life-base-areas-and-fight-flexibly-under-long-pressure.md) | [SD](./inspiration_on_software_development/iteration_and_delivery/026-build-engineering-base-areas-and-upgrade-under-long-pressure.md) | [RC](./inspiration_on_running_a_company/strategy_and_execution/026-build-business-base-areas-and-grow-main-force-under-long-pressure.md) | [SI](./inspiration_on_stock_investing/risk_and_position_management/026-build-investment-base-areas-and-stay-flexible-under-long-pressure.md) | [MM](./inspiration_on_making_money/execution_and_delivery/026-build-side-hustle-base-areas-and-grow-under-long-pressure.md) | — | 5 |
| 060 | 《改造我们的学习》 | [原文](https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19410519.htm) | — | — | — | — | — | [EC](./inspiration_on_embedded_coding/team_process_and_knowledge/005-rectify-learning-knowledge-retrospective.md) | 1 |

## 5. 已建立关联的原文标题清单（按真实顺序）

### 001《中国社会各阶级的分析》
- 真实索引位置：第一卷 第一次国内革命战争时期 / 本卷第 1 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19251201.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/judgement_and_decision/001-dont-misread-allies-by-surface-labels.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/user_research_and_requirements/001-dont-segment-product-roles-by-surface-labels.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/001-dont-judge-org-allies-by-title-and-posture.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/001-dont-read-companies-by-sector-labels-alone.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/monetization_models/001-dont-judge-side-hustle-opportunities-by-surface-status.md`

### 002《湖南农民运动考察报告》
- 真实索引位置：第一卷 第一次国内革命战争时期 / 本卷第 2 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-192703.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/002-dont-misjudge-bottom-up-change-as-mere-chaos.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/002-dont-treat-bottom-up-product-change-as-mere-chaos.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/002-dont-treat-bottom-up-correction-as-loss-of-control.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/002-dont-mistake-structural-repricing-for-mere-chaos.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/002-dont-dismiss-new-monetization-order-as-mere-chaos.md`

### 003《中国的红色政权为什么能够存在？》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 3 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19281005.htm
- 已关联 inspiration 文件数：1
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/survival_strategy/003-red-political-power-foothold-thinking.md`

### 004《井冈山的斗争》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 4 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19281125.htm
- 已关联 inspiration 文件数：1
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/004-jinggangshan-struggle-core-zone-and-anti-fragmentation.md`

### 005《关于纠正党内的错误思想》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 5 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-192912.htm
- 已关联 inspiration 文件数：3
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/judgement_and_decision/005-rectify-internal-chaos-before-chasing-opportunity.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/005-rectifying-thought-errors-in-product-teams.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/005-rectify-internal-cognitive-noise-in-organizations.md`

### 006《星星之火，可以燎原》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 6 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19300105.htm
- 已关联 inspiration 文件数：3
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/long_term_growth/006-small-sparks-compounding-and-anti-premature-despair.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/product_strategy/006-small-spark-product-wedge-and-wave-expansion.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/006-local-strongholds-and-strategic-wave-expansion.md`

### 007《反对本本主义》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 7 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193005.htm
- 已关联 inspiration 文件数：4
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/judgement_and_decision/007-investigate-before-judging-major-decisions.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/user_research_and_requirements/007-investigation-first-product-discovery.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/007-no-investigation-no-organizational-voice.md`
  - EC: `methodology/great_man_inspiration/inspiration_on_embedded_coding/debugging_and_fieldwork/004-against-book-worship-driver-development.md`

### 008《必须注意经济工作》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 8 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19330812.htm
- 已关联 inspiration 文件数：4
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/survival_strategy/008-economic-basics-before-big-moves.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/iteration_and_delivery/008-resource-flow-and-sustained-delivery.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/008-economic-foundation-and-war-chest-discipline.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/risk_and_position_management/008-cash-and-supply-lines-before-big-bets.md`

### 009《怎样分析农村阶级》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 9 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193310.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/judgement_and_decision/009-see-through-labels-to-real-life-structure.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/user_research_and_requirements/009-segment-users-by-real-behavior-and-interests.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/009-classify-roles-by-real-function-and-incentives.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/009-classify-businesses-by-cashflow-source-and-control.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/monetization_models/009-classify-side-hustles-by-income-structure.md`

### 010《我们的经济政策》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 10 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193401.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/survival_strategy/010-build-a-self-sustaining-life-economy.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/architecture_and_engineering/010-build-core-capacity-and-healthy-ecosystem.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/010-operating-system-balance-production-trade-and-discipline.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/market_structure_and_cycles/010-real-production-before-policy-premium.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/010-side-hustle-needs-production-channels-and-discipline.md`

### 011《关心群众生活，注意工作方法》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 11 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19340127.htm
- 已关联 inspiration 文件数：4
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/011-real-support-comes-from-solving-concrete-problems.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/011-user-pain-and-practical-methods-over-slogans.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/leadership_and_talent/011-win-followership-by-solving-real-problems.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/011-earn-trust-by-solving-real-customer-pain.md`

### 012《论反对日本帝国主义的策略》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 12 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19351227.htm
- 已关联 inspiration 文件数：3
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/012-dont-fight-every-difference-build-a-broad-alliance.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/product_strategy/012-broaden-the-alliance-around-the-main-product-battle.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/012-realign-the-company-around-the-main-threat-and-broad-alliance.md`

### 013《中国革命战争的战略问题》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 13 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193612.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/survival_strategy/013-dont-defend-every-inch-preserve-strength-and-counterattack-when-odds-shift.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/iteration_and_delivery/013-dont-turn-every-front-into-trench-war-concentrate-for-decisive-software-battles.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/013-preserve-core-strength-and-concentrate-for-the-decisive-company-battle.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/risk_and_position_management/013-dont-defend-every-position-preserve-capital-for-high-odds-counterattacks.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/013-dont-stretch-every-side-project-line-concentrate-on-the-one-you-can-win.md`

### 014《关于蒋介石声明的声明》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 14 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19361228.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/judgement_and_decision/014-judge-turning-points-by-actions-not-statements.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/014-dont-confuse-stakeholder-statements-with-execution-support.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/leadership_and_talent/014-trust-turnarounds-only-after-real-costly-actions.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/014-verify-management-turnarounds-by-actions-not-guidance.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/014-verify-support-in-side-hustle-collaboration-by-actions.md`

### 015《中国共产党在抗日时期的任务》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 15 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370503.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/015-build-a-broad-front-without-losing-your-own-direction.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/015-broaden-support-without-surrendering-product-judgment.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/015-broaden-the-alliance-without-giving-away-the-strategic-core.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/015-broaden-your-information-front-without-losing-research-independence.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/015-broaden-support-without-losing-your-side-hustle-direction.md`

### 016《为争取千百万群众进入抗日民族统一战线而斗争》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 16 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370508.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/016-dont-just-be-right-turn-direction-into-organized-support.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/016-turn-correct-product-direction-into-shared-execution-structure.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/016-turn-strategy-into-a-shared-company-mission.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/016-build-a-research-system-not-just-a-right-opinion.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/016-organize-support-so-your-side-hustle-can-scale.md`

### 017《实践论》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 17 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193707.htm
- 已关联 inspiration 文件数：6
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/long_term_growth/017-real-understanding-grows-from-action-reflection-and-verification.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/user_research_and_requirements/017-product-understanding-grows-from-research-build-verify-repeat.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/017-organizational-understanding-grows-from-field-contact-and-revalidation.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/017-investment-understanding-grows-from-contact-testing-and-revision.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/017-side-hustle-understanding-grows-through-doing-and-revising.md`
  - EC: `methodology/great_man_inspiration/inspiration_on_embedded_coding/debugging_and_fieldwork/002-on-practice-debugging-closed-loop.md`

### 018《矛盾论》
- 真实索引位置：第二次国内革命战争时期 / 本卷第 18 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193708.htm
- 已关联 inspiration 文件数：6
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/judgement_and_decision/018-find-the-main-contradiction-before-spending-your-life-force.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/product_strategy/018-find-the-main-product-contradiction-before-escalating-everything.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/018-find-the-main-operating-contradiction-before-fighting-on-all-fronts.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/018-find-the-main-market-contradiction-before-weighting-every-variable-equally.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/018-find-the-main-monetization-contradiction-before-fixing-everything-at-once.md`
  - EC: `methodology/great_man_inspiration/inspiration_on_embedded_coding/system_analysis_and_architecture/003-on-contradiction-firmware-fault-ordering.md`

### 019《反对日本进攻的方针、办法和前途》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 1 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370723.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/019-dont-just-know-the-right-direction-build-the-people-and-methods.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/019-dont-just-agree-on-strategy-mobilize-people-process-and-resources.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/019-dont-just-set-strategy-build-the-org-and-resource-system.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/019-dont-just-be-right-build-the-research-and-positioning-system.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/019-dont-just-have-the-right-side-hustle-direction-build-the-system.md`

### 020《为动员一切力量争取抗战胜利而斗争》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 2 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370825.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/020-major-life-battles-need-full-mobilization-not-half-measures.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/020-key-product-battles-need-full-organizational-mobilization.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/020-company-crucial-phases-need-full-mobilization-not-partial-effort.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/020-big-investment-opportunities-need-full-preparation.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/020-side-hustle-critical-phases-need-full-system-mobilization.md`

### 021《反对自由主义》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 3 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370907.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/021-dont-trade-principled-feedback-for-surface-harmony.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/021-dont-trade-surface-harmony-for-team-truth-and-discipline.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/021-dont-trade-surface-harmony-for-organizational-truth.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/021-dont-trade-research-truth-for-surface-consensus.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/021-dont-trade-surface-harmony-for-sustainable-side-hustle-collaboration.md`

### 022《国共合作成立后的迫切任务》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 4 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19370929.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/022-dont-stop-at-formal-cooperation-build-shared-rules-and-real-support.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/022-dont-confuse-cross-functional-alignment-with-real-execution-capacity.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/022-dont-confuse-top-level-reconciliation-with-operating-turnaround.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/022-dont-confuse-sentiment-recovery-with-structural-turnaround.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/022-dont-confuse-willing-collaboration-with-a-real-side-hustle-system.md`

### 023《和英国记者贝特兰的谈话》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 5 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19371025.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/023-dont-fight-major-life-battles-as-a-one-person-defensive-war.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/iteration_and_delivery/023-dont-run-key-projects-as-a-passive-defensive-war.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/023-dont-run-company-critical-phases-as-a-passive-defensive-war.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/trading_and_execution/023-dont-trade-market-opportunities-as-a-passive-defensive-war.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/023-dont-run-side-hustle-growth-as-a-passive-defensive-war.md`

### 024《上海太原失陷以后抗日战争的形势和任务》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 6 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19371112.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/024-dont-mistake-partial-turning-points-for-a-real-life-system-upgrade.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/024-dont-mistake-partial-org-alignment-for-a-real-project-turnaround.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/024-dont-mistake-partial-operating-relief-for-a-real-company-turnaround.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/research_and_thesis/024-dont-mistake-partial-market-repair-for-a-real-thesis-turnaround.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/024-dont-mistake-partial-side-hustle-momentum-for-a-real-system-takeoff.md`

### 025《陕甘宁边区政府第八路军后方留守处布告》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 7 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19380515.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/cooperation_and_organization/025-dont-let-chaotic-helpers-reopen-your-hard-won-life-order.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/team_process_and_quality/025-dont-let-unbounded-support-disrupt-your-engineering-order.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/organization_design/025-dont-let-coordination-reopen-your-operating-chaos.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/risk_and_position_management/025-dont-let-soft-bullish-signals-break-your-risk-discipline.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/025-dont-let-favors-and-intros-break-your-side-hustle-boundaries.md`

### 026《抗日游击战争的战略问题》
- 真实索引位置：第二卷 抗日战争时期（上） / 本卷第 8 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-193805.htm
- 已关联 inspiration 文件数：5
  - TL: `methodology/great_man_inspiration/inspiration_on_today_life/survival_strategy/026-build-life-base-areas-and-fight-flexibly-under-long-pressure.md`
  - SD: `methodology/great_man_inspiration/inspiration_on_software_development/iteration_and_delivery/026-build-engineering-base-areas-and-upgrade-under-long-pressure.md`
  - RC: `methodology/great_man_inspiration/inspiration_on_running_a_company/strategy_and_execution/026-build-business-base-areas-and-grow-main-force-under-long-pressure.md`
  - SI: `methodology/great_man_inspiration/inspiration_on_stock_investing/risk_and_position_management/026-build-investment-base-areas-and-stay-flexible-under-long-pressure.md`
  - MM: `methodology/great_man_inspiration/inspiration_on_making_money/execution_and_delivery/026-build-side-hustle-base-areas-and-grow-under-long-pressure.md`

### 060《改造我们的学习》
- 真实索引位置：第三卷 抗日战争时期（下） / 本卷第 2 条
- 原文链接：https://www.marxists.org/chinese/maozedong/marxist.org-chinese-mao-19410519.htm
- 已关联 inspiration 文件数：1
  - EC: `methodology/great_man_inspiration/inspiration_on_embedded_coding/team_process_and_knowledge/005-rectify-learning-knowledge-retrospective.md`

## 6. 使用建议

- 如果要继续顺序学习，请优先看：`inspiration_on_today_life/indexes/000-mao-anthology-sequential-reading-overview.md`
- 如果要从当前边界继续向下推进，下一篇应是：`027《论持久战》`
- 如果要反查某篇 inspiration 对应哪篇毛文，可以先在本 README 的“原文 -> inspiration 文件 关联矩阵”里点链接。
- 如果要反查某篇毛文已经转译到了哪些主题，也可以直接按本 README 第 5 节查看。
