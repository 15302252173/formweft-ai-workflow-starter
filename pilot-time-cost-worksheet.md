# AI pilot time and cost worksheet / AI 试点工时与成本记录表

Before expanding an AI workflow, compare the whole job: preparation, review, corrections, failed attempts and operating costs. Copy this worksheet for one recurring task.

This is a FORMWEFT learning resource. All numbers in the worked example are fictional teaching inputs, not customer results, market prices or FORMWEFT quotes.

[中文说明](#中文说明) · [Workflow starter](README.md) · [FORMWEFT learning resources](https://formweft.com/en/resources?utm_source=github&utm_medium=resource&utm_campaign=pilot_worksheet)

## 1. Define a fair comparison

| Field | Your entry |
| --- | --- |
| One task and its owner | |
| Measurement period and eligible workload | |
| Same case mix for baseline and pilot | |
| Required quality checks and acceptable error limits | |
| Human approval and exception owner | |
| Tool/model version and measurement date | |

Use the same completion criteria in both paths. A failed attempt still consumes time and money: include recovery or manual fallback. Do not count unfinished drafts as completed work. Use matched historical samples where repeating the same case would create a learning effect; record how the samples differ.

## 2. Record time and money separately

| Measure | Baseline | Pilot | Evidence / notes |
| --- | --- | --- | --- |
| Eligible cases and final completed cases | | | Keep the denominator visible |
| Total active human minutes | | | Include preparation, review, correction and fallback |
| Shared operating minutes | | | Monitoring and administration, counted once |
| Waiting time / turnaround | | | Track separately from active labor |
| Quality failures and unresolved cases | | | Include failures in the time/cost totals |
| Recurring cash cost for the period | | | Model calls including retries, hosting, storage, other services |
| One-time cash cost | | | Setup, integration, migration and training |
| One-time internal hours | | | Record separately; do not hide them in recurring time |

For comparable completed workloads:

- **Baseline human minutes** = case work + shared operating minutes.
- **Pilot human minutes** = preparation + review + corrections + fallback + shared operating minutes.
- **Observed time difference** = baseline human minutes − pilot human minutes. A negative result means the pilot used more time.
- **Recurring cash difference** = pilot recurring cash cost − baseline recurring cash cost. A positive result means additional spend.

Use one currency and period, state tax treatment, and attach dated quotes or billing records. Keep unknown costs as **unknown**, not zero. Avoid counting review or monitoring twice. If completion or quality differs materially, show that difference before comparing efficiency.

## 3. Worked example — fictional

A fictional team completes the same 100 eligible cases in a week. Baseline work takes 10 active minutes per case, with no additional shared operating time in this simplified example. The pilot also completes all 100 cases after the corrections and fallback below; both paths meet the same predefined quality checks.

| Pilot case group | Cases | Human minutes per case, including all handling | Total minutes |
| --- | ---: | ---: | ---: |
| Routine review | 60 | 5 | 300 |
| Needs correction | 30 | 7 | 210 |
| Failed AI attempt, completed manually | 10 | 9 | 90 |
| Shared monitoring | — | — | 60 |
| **Pilot total** | **100** | | **660** |

Baseline: 100 × 10 = **1,000 minutes**. Pilot: 300 + 210 + 90 + 60 = **660 minutes**. Observed time difference: **340 minutes, or 5 hours 40 minutes** for this fictional week.

Assume recurring cash cost was 0 currency units before the pilot and 20 during it: 12 for model calls, including failed attempts, plus 8 for hosting/storage. Additional recurring spend is **20 units per week**. Separately record **300 units of one-time setup** and **5 internal onboarding hours**. These are invented arithmetic inputs, not price estimates.

The 5 hours 40 minutes represents available capacity, not automatic payroll savings or revenue. This example establishes neither ROI nor payback. If average pilot handling rises to 10 minutes per case while monitoring remains 60 minutes, pilot work becomes 1,060 minutes: **60 minutes more than baseline**.

## 4. Make the next decision explicit

- **Continue a limited pilot:** quality checks pass and comparable observations justify another measurement period.
- **Revise:** review, exceptions or operating costs erase the expected benefit. Change one factor and repeat comparable cases.
- **Pause:** required permissions, acceptance criteria or cost evidence are missing, or a critical error remains unresolved.

Record the decision owner, supporting evidence, next review date and rollback owner. One successful week is not proof of lasting production value.

## 中文说明

这张表用于回答：一项 AI 工作流跑起来以后，整个任务到底用了多少人工时间、增加了哪些费用？先选一个重复任务，记录同一周期、相近难度的工作量，并事先约定质量要求。

### 可直接复制的记录表

| 项目 | 原流程 | AI 试点 | 依据 |
| --- | --- | --- | --- |
| 统计周期、应处理数量、最终完成数量 | | | |
| 准备、审核、修改、失败后人工补做的总分钟数 | | | |
| 监控及日常管理分钟数，只算一次 | | | |
| 等待时长、质量问题、未完成事项 | | | |
| 当期实际运行费用，含失败调用和重试 | | | |
| 一次性开发、对接、迁移和培训费用 | | | |
| 一次性内部投入小时数 | | | |
| 工具版本、日期、复核人 | | | |

先比较相同完成标准下的人工总分钟数。试点必须包含资料准备、复核、返工、失败兜底与维护时间。未完成草稿不能充当已完成任务；如果完成率或质量不同，应先说明差异。重复做同一题会产生熟悉效应时，用难度匹配的历史样例并记录差别。

**虚构算例：** 每周 100 件任务，原流程每件 10 分钟，共 1,000 分钟。试点中，60 件各用 5 分钟，30 件修改后各用 7 分钟，10 件 AI 失败后人工完成各用 9 分钟；再加 60 分钟监控，共 660 分钟。两种流程均按同一质量要求完成全部任务，差值为 **340 分钟，即 5 小时 40 分钟**。

假设原流程当期运行支出为 0，试点模型调用含重试为 12、托管及存储为 8，则新增每周支出 20 个货币单位。另记一次性费用 300 和内部培训 5 小时。所有数字均为教学假设，不是市场价格、FORMWEFT 报价或客户案例。

腾出的时间不等于工资支出下降，也不等于新增收入。如果试点每件人工处理变为 10 分钟，仍需 60 分钟监控，总耗时就是 1,060 分钟，反而多出 60 分钟。不要据此直接宣称 ROI 或回本周期。

保持币种、统计周期和含税口径一致；费用未知就写“待确认”。质量达标且证据充分时继续小范围试点；返工或成本过高时调整；权限、验收标准或关键证据缺失时暂停。写清决策人、下一次复查日期和恢复原流程的负责人。

## Discuss your workflow / 带着记录讨论下一步

Bring this worksheet, one recurring task and its acceptance criteria to a scope discussion. FORMWEFT provides custom enterprise AI workspaces and practical FDE training. Delivery, model services and maintenance are assessed separately; enterprise work is quoted by project scope.

带上这张记录表、一个重复任务和验收要求，再讨论系统对接、培训与维护范围。FORMWEFT 提供企业 AI 工作台定制及 FDE 实战培养，企业项目按范围评估报价。

[Explore FORMWEFT](https://formweft.com/en/?utm_source=github&utm_medium=resource&utm_campaign=pilot_worksheet) · [中文官网](https://formweft.com/?utm_source=github&utm_medium=resource&utm_campaign=pilot_worksheet) · [Practice acceptance tests](customer-follow-up-acceptance.md)

Published: 2026-09-13. This worksheet is educational; replace every fictional input with evidence from your own pilot.
