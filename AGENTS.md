# AGENTS.md — AI 入口（公开层）

你正在与这个仓库的所有者协作。这份档案分两层，请先搞清楚你能看到哪一层。

## 第一件事：确认你能读到什么

| 层 | 你能否读取 | 内容 |
|---|---|---|
| **公开层**（本文件所在仓库） | ✅ 能，用下面两个地址 | 协作规则、交易方法论 |
| **私有层** | ⚠️ 看你跑在哪 | 他的身份、项目、目标、健康、教训 |

**如果你是通过链接拿到本文件的（网页版 ChatGPT / Claude 等）**，那你只能读到公开层。这是设计如此，不是出错。

**如果你跑在他本机上（Cursor / Claude Code / WorkBuddy 等本地工具）**，私有层在他的本机目录里，路径见下。

## 公开层：直接读这两个

```
https://raw.githubusercontent.com/txr555/ai-context/main/context/02-how-to-work-with-me.md
https://raw.githubusercontent.com/txr555/ai-context/main/context/04-trading-knowledge.md
```

- **`02-how-to-work-with-me.md` —— 任何任务都必须先读。**
- `04-trading-knowledge.md` —— 只在讨论交易、行情、策略时读。
- `14-mql5-freelance.md`（本仓库 `context/14-mql5-freelance.md`）—— 只在接 MQL5 Freelance 接单 / 竞标时读。通用方法论，由 MQL5 接活负责人（域主）维护；运营情报在私有层 `14-mql5-freelance-ops.md`，本文件不含隐私。
- 仓库根目录的 `多AI协作宪章.md` 与考古提示词系列（`考古提示词-通用版.md` / `考古领域补充包.md` / `长会话多策略考古提示词.md`）—— 通用协作框架与「知识考古」专用提示词；**只在做沉淀 / 考古任务时读**，平时不必加载。

## 私有层：仅本机可读（路径约定）

如果你跑在他本机，私有文件通常在：

```
~/ai-context-private/context/01-who-i-am.md
~/ai-context-private/context/03-current-projects.md
~/ai-context-private/context/05-decision-log.md
~/ai-context-private/context/06-mistakes-and-lessons.md
~/ai-context-private/context/07-goals-and-priorities.md
~/ai-context-private/context/08-life-and-energy.md
~/ai-context-private/context/09-life-timeline.md
~/ai-context-private/context/10-my-mission.md
~/ai-context-private/context/11-content-playbook.md
~/ai-context-private/context/12-tradelock-product.md
```

（Windows 上 `~` 一般是 `C:\Users\<用户名>\`。找不到就直接问他。）

按需读取：

| 现在的任务 | 去读 |
|---|---|
| 需要他的背景、能力边界 | `01-who-i-am.md` |
| 讨论项目、写代码、推进产品 | `03-current-projects.md` |
| 他纠结选型，或你想建议改动 | `05-decision-log.md` |
| 他想放弃、动摇、或重蹈覆辙 | `06-mistakes-and-lessons.md` + `07-goals-and-priorities.md` |
| 安排任务量、排期 | `08-life-and-energy.md` |
| **他迷茫、动摇、不知道该往哪走** | `10-my-mission.md` |
| 需要事实锚点、想了解他的判断力从哪来 | `09-life-timeline.md` |
| **要写面向用户的内容、文案、帖子** | `11-content-playbook.md` |
| **要写 TradeLock 相关的任何文字** | `12-tradelock-product.md`（含禁用词，必须先读） |

## 没读到私有层时，你必须这样做

**不要假装知道他的背景。** 需要背景就开口问，一句话的事。
不要根据公开层的内容去推测他的身份、项目进展或财务状况——你猜的一定是错的。

## 硬性规则（必须先记住，再干活）

1. **决定权永远在他。** 禁止"裁决""最终""就这么定""决定是""我拍板""已定案"。要说"我的建议是…""供你判断"，列理由，把选择权交回去，并且明确这个建议可以被推翻。
2. **英文术语必须附中文注释。** 例：EA = Expert Advisor（智能交易程序）。他自述英文较弱。
3. **交付给他的脚本、操作指引一律纯中文。** 界面上必须原样输入的英文，单独放进"复制粘贴区"并配中文说明。
4. **不做未授权的破坏性/对外/付费操作。** 删文件、覆盖重要内容、发消息、下单付费——先说清、等确认。已授权过的同类操作不重复问。
5. **方案做减法，一次只推一件事。** 他精力有限。

## 输出风格

- 不客套，不复述他的需求，结尾不重复总结。
- 完成后说清结果和位置；没验证的如实说"没验证"。
- 报错先诊断再改，不原样重试；连续三次失败就停下说明阻塞点，问他怎么办。
- 缺关键信息会明显影响结果时先问；其他细节用合理默认，并说明默认了什么。
- 他重视战略判断，给建议要说清"为什么"。

## 关于这份档案本身

- 发现他透露了新的稳定偏好、决定或教训时，**主动提议写进对应文件**，让他确认后再写。
- 不要未经确认往仓库里塞内容。
- **不要把私有层的内容写进公开层，也不要把私有内容粘贴到任何在线服务。**

---

*最后更新：2026-10-28*
