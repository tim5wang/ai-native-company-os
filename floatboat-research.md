# Floatboat 博客研究报告

> 研究对象：https://floatboat.ai/blog  
> 研究时间：2026-05-08  
> 目的：理解 Floatboat 对 AI Workspace Agent、Solo Operator、一人公司工作流自动化的产品叙事、核心概念、差异化定位，并提炼对 ANC 产品计划的启发。

---

## 1. 总体结论

Floatboat 的博客不是单纯的产品更新博客，而是一套围绕 **AI Workspace Agent for One-Person Companies** 的市场教育内容体系。它持续向目标用户灌输几个核心判断：

1. **一人公司 / Solo Operator 是一种独立的工作形态**，不是“小团队的缩小版”。
2. 这类用户的核心瓶颈不是单个任务效率，而是：
   - 上下文切换成本；
   - AI 工具之间割裂；
   - 每次对 AI 重新解释背景；
   - 重复工作无法沉淀为可复用执行能力。
3. 传统 Chat Assistant 适合问答和短任务，但不适合长期、跨文件、跨工具、跨项目的工作。
4. Workflow Builder 适合高频、确定性、触发式流程，但不适合每天变化、需要判断、上下文很重的知识工作。
5. Workspace Agent 的机会在于：
   - 进入用户真实工作环境；
   - 访问文件、浏览器、桌面工具；
   - 保持跨会话记忆；
   - 将用户做过的工作沉淀成 reusable skills / Combo Skills。

Floatboat 当前公开叙事里最重要的产品定位可以概括为：

> 面向一人公司和非技术专业人士的 AI 原生工作空间，让 AI 住在用户真实工作环境中，学习用户工作方式，并把重复工作转化为可复用的 Combo Skills。

这与 ANC 的长期方向存在明显交集：二者都强调 **Agent Native Workspace / Company**、**可复用工作流**、**非技术用户驱动构建**。但差异也很明显：

- Floatboat 更偏个人 / 一人公司 / 桌面工作空间。
- ANC 更偏企业级业务系统 / 内部应用生成 / 流程编排 / 确定性运行。

---

## 2. Floatboat 博客内容结构观察

Floatboat Blog 的定位语是：

> Automation tips, workflow strategies, and product updates for non-technical professionals.

从博客列表看，内容主要分为几类：

### 2.1 Workspace Agent 类

代表文章：

- `What Are AI Workspace Agents? A Plain-Language Guide`
- `AI Workspace Agents vs Chat Assistants: What's Different`
- `Workspace Agents vs Workflow Builders: A Clear Comparison`
- `Why One-Person Companies Need a Workspace Agent`
- `How to Stop Context Switching with a Workspace Agent`

这是 Floatboat 最核心的市场教育内容，用来定义新品类：AI Workspace Agent。

### 2.2 Persistent Agent / Memory 类

代表文章：

- `What Is a Persistent AI Agent — and Why Does It Matter?`
- `Why Your AI Forgets Everything Between Sessions`
- `Should a Solo Operator Use an AI Agent?`

这类文章围绕“AI 不记得你”的痛点展开，强调持久上下文、工作记忆、执行记忆的重要性。

### 2.3 Solo Founder / One-Person Company 类

代表文章：

- `AI Workflow for Solo Founders: What Actually Works`
- `How to Scale a One-Person Business Without Hiring`
- `OpenAI 4-Day Work Week: Rise of One-Person Companies`
- `How to Get Your First 100 Customers as a Solo Founder`

这类文章把目标人群从普通 AI 用户明确收敛到：solo founder、solo operator、one-person company、independent consultant、creator-operator。

### 2.4 AI 模型与工具趋势类

代表文章：

- `Meta Muse Spark vs GPT-5.4`
- `DeepSeek V4 API`
- `Grok 3 API`
- `OpenAI GPT-6`
- `Claude Managed Agents`
- `Claude Code on Linux`

这类文章主要借热点获取流量，但叙事最终仍然会回到“这些技术对一人公司意味着什么”。

### 2.5 创作者与内容生产类

代表文章：

- `GPT Image 2 vs Midjourney vs Nano Banana 2 for Creators`
- `GPT Image 2 for Manga and Comic Creators`
- `Can One Person Build a Full Storyboard with GPT Image 2?`

这部分说明 Floatboat 的目标用户不只是 SaaS 创业者，也包括内容创作者、设计师、独立顾问等多角色知识工作者。

---

## 3. Floatboat 对 Workspace Agent 的定义

Floatboat 对 AI Workspace Agent 的定义非常清晰：

> An AI workspace agent is software that acts like a coworker who lives inside your actual work environment — your files, your apps, your browser — and carries context across sessions instead of starting fresh every time you open it.

中文可理解为：

> AI Workspace Agent 是一个住在用户真实工作环境里的 AI 同事。它能访问文件、应用、浏览器，并且能跨会话保留上下文，而不是每次打开都从零开始。

这个定义包含两个关键点：

### 3.1 Workspace：工作发生在哪里，AI 就在哪里

Floatboat 强调，Workspace 不只是一个聊天窗口，而是用户真实工作的环境：

- 本地文件；
- 浏览器标签；
- 文档；
- 电子表格；
- 打开的页面；
- 桌面应用；
- 用户正在处理的项目上下文。

这和传统 ChatGPT 类产品的区别是：

- Chat Assistant 需要用户把上下文复制进去；
- Workspace Agent 直接读取工作环境中的上下文。

### 3.2 Agent：不只是回答，而是执行多步骤任务

Floatboat 对 Agent 的理解是：

- 不只是回答问题；
- 能读取文件；
- 能打开网页；
- 能整理资料；
- 能生成文档；
- 能把结果放回用户正在工作的地方；
- 能在任务过程中判断下一步。

它的核心表述是：

> Chat assistant responds. Workspace agent operates.

即：

> 聊天助手负责响应，工作空间 Agent 负责操作。

---

## 4. Floatboat 的核心痛点叙事

Floatboat 反复强调的痛点不是“AI 不够聪明”，而是“AI 没有进入真实工作流”。

### 4.1 上下文切换成本

在 `How to Stop Context Switching with a Workspace Agent` 中，Floatboat 把一人公司的瓶颈定义为：

> The bottleneck isn't the tools, the AI, or even the ideas. It's the cost of moving between them.

核心观点：

- 一人公司用户经常同时承担销售、运营、内容、客服、财务等多个角色；
- 问题不是单个任务不会做，而是在多个任务、多个工具、多个上下文之间切换；
- 每次切换都需要重新加载自己的工作状态；
- 工具越多，切换成本越高。

这类用户常见工作状态是：

- 多个浏览器标签；
- 多个 AI 工具；
- 多个文档；
- 多个项目；
- 多个上下文互不相通。

Floatboat 把这种现象称为类似 **AI tab fatigue**：AI 能力散落在很多窗口里，用户反而成了这些 AI 工具之间的“人工集成层”。

### 4.2 Stateless AI 的“重解释税”

在 `Why Your AI Forgets Everything Between Sessions` 和 `What Is a Persistent AI Agent` 中，Floatboat 把传统 AI 工具的问题概括为：

> Every single session starts from zero.

即每次新会话都从零开始。

它将用户每次重新解释背景的成本称为：

- reset tax；
- re-onboarding tax；
- context loading cost。

典型场景：

- 昨天已经告诉 AI 客户是谁；
- 今天又要重新解释客户背景；
- 上次已经调好了写作风格；
- 新会话又变成通用风格；
- 项目已经推进三周；
- AI 只记得当前 prompt。

Floatboat 认为长上下文窗口不能根治这个问题，因为：

- 长上下文只是延迟问题，不是解决问题；
- 上下文会腐化；
- 检索成本会上升；
- 无法形成真正的工作记忆和执行记忆。

### 4.3 工具碎片化

在 `AI Workflow for Solo Founders` 中，Floatboat 批评常见的 DIY AI 工作流：

- ChatGPT 用于写作；
- Zapier 用于自动化；
- Notion 用于项目管理；
- 单独研究工具用于搜索；
- 邮件、浏览器、本地文件分散在其他地方。

表面上能力齐全，实际上问题是：

> You become the integration layer.

用户自己变成了集成层。

每个工具只知道一小块上下文，没有一个工具理解“用户的工作整体是如何连接起来的”。

### 4.4 Workflow Builder 不适合未定义工作

Floatboat 并不否认 Zapier、Make、Gumloop 等 workflow builder 的价值，但它明确区分两类工作：

| 类型 | 更适合工具 |
|---|---|
| 高频、稳定、确定性、触发式流程 | Workflow Builder |
| 低频、多变、判断密集、上下文重的工作 | Workspace Agent |

Floatboat 的一个关键判断是：

> Workflow builders are for the work you already understand. Workspace agents are for the work that's still partly undefined.

即：

> 工作流工具适合你已经完全理解的工作；Workspace Agent 适合仍然部分未定义的工作。

---

## 5. Floatboat 的产品能力推断

根据官网与博客内容，Floatboat 的公开产品能力大致包括以下几个方面。

### 5.1 桌面 AI Workspace

Floatboat 官网标题为：

> Floatboat | AI Agent Workspace for One-Person Companies

描述中提到：

> Floatboat is the all-in-one AI workspace for one-person companies. It learns your workflows, connects to 3500+ tools, and turns your repeatable work into reusable Combo Skills. Download for Mac & Windows.

可以推断它是一个 Mac / Windows 桌面应用，主打：

- 一人公司工作空间；
- 本地文件 / 浏览器 / 工具连接；
- AI Agent 原生体验；
- 非技术用户可用。

### 5.2 Combo Skills

Floatboat 多次提到 `Combo Skills`。这是其产品叙事中非常关键的概念。

根据博客描述，Combo Skills 的含义接近：

> 将多步骤 AI 任务封装为可复用的执行流程。

例如：

- 读取文档；
- 分析材料；
- 提炼结构；
- 生成 deck；
- 保持用户语气；
- 输出可编辑结果。

官网示例：

> Turn Voice notes to a Tailor-Made Deck in 10 mins

输入：

- Documents；
- Voice notes；
- Call recordings；
- Raw thoughts。

输出：

- Clear narrative；
- Structured slides；
- Client-ready；
- Your tone。

这个能力可以理解为：

> 把用户反复执行的知识工作，从“每次重新 prompt”变成“可复用的技能”。

### 5.3 学习用户工作方式

Floatboat 的核心主张之一是：

> learns your workflows

博客里把这种能力分成几层：

1. **Memory**：记住用户偏好和事实；
2. **Context**：知道用户当前在处理什么项目、文件、浏览器内容；
3. **Reusable Execution**：学习用户如何完成某类工作，并在新输入上复用。

Floatboat 认为真正有价值的不是记住“用户喜欢 bullet points”，而是记住：

- 用户如何写 proposal；
- 用户如何处理客户 brief；
- 用户如何做竞品调研；
- 用户如何把访谈录音转为销售材料；
- 用户的语气、结构、判断标准是什么。

### 5.4 连接 3500+ 工具

官网描述提到 Floatboat connects to 3500+ tools。博客中没有展开技术细节，但这是其与纯桌面文件工具的差异点。

它试图同时覆盖：

- 本地文件；
- 浏览器；
- 桌面工具；
- SaaS 工具集成；
- 多步骤 AI 任务。

这也是它区别于纯 Chat Assistant 和纯 Workflow Builder 的关键。

---

## 6. Floatboat 的竞品分类框架

Floatboat 博客反复使用比较法建立新品类认知。

### 6.1 Chat Assistant vs Workspace Agent

| 维度 | Chat Assistant | Workspace Agent |
|---|---|---|
| 主要界面 | 单一聊天窗口 | 文件、浏览器、工具组成的工作空间 |
| 输入方式 | 用户输入 / 粘贴 / 上传 | Agent 读取已经打开的上下文 |
| 时间跨度 | 秒到分钟 | 分钟到小时 |
| 会话状态 | 大多重置，少量偏好记忆 | 持久项目上下文 |
| 工具使用 | 被聊天窗口约束 | 工作空间本身就是工具环境 |
| 擅长 | 快速问答、短任务、一次性生成 | 多步骤、跨工具、上下文重的任务 |
| 失效场景 | 需要真实上下文和多步骤执行 | 简单问题，设置成本高于收益 |

Floatboat 的核心判断：

- Chat Assistant 是 conversation-shaped；
- Workspace Agent 是 environment-shaped。

### 6.2 Workflow Builder vs Workspace Agent

| 维度 | Workflow Builder | Workspace Agent |
|---|---|---|
| 工作方式 | 预先定义流程 | 描述目标，Agent 动态决定步骤 |
| 适合任务 | 重复、稳定、高频 | 多变、上下文重、判断密集 |
| 可靠性 | 高 | 中等，依赖模型判断 |
| 设置成本 | 高，需要设计节点和分支 | 低，直接描述任务 |
| 运行方式 | 触发器 + 节点 + 条件 | 在工作环境中多步骤执行 |
| 失败模式 | 刚性，边界场景容易断 | 判断不稳定，可能跑偏 |
| 用户 | 团队流程、系统集成、运营自动化 | solo operator、顾问、创作者、知识工作者 |

Floatboat 对 workflow builder 的态度是：

- 不否认其价值；
- 明确其适用边界；
- 强调 Workspace Agent 不是替代，而是补充。

它给出的决策规则很直接：

> 如果某件事每月以同样方式发生 20 次以上，用 workflow builder；如果只发生一两次且每次形态不同，用 workspace agent。

### 6.3 Self-hosted Agent vs Workspace-native Agent

Floatboat 还区分了两类 AI Agent：

1. **Self-hosted, Developer-optimized Agent**
   - 例如 Hermes Agent；
   - 优点：强控制、可自托管、数据掌控、可定时运行；
   - 缺点：需要服务器、配置、运维、调试。

2. **Workspace-native, Operator-optimized Agent**
   - 例如 Floatboat；
   - 优点：下载即用、面向非技术用户、无基础设施负担；
   - 缺点：可定制性和控制力弱于自托管方案。

这个分类对 ANC 很有启发：不同用户需要不同形态的 Agent 基建。

---

## 7. Floatboat 的目标用户画像

Floatboat 的核心目标用户不是传统企业 IT，也不是开发者，而是：

### 7.1 Solo Operator / One-Person Company

典型特征：

- 一个人承担多个职能；
- 既要做战略，又要做执行；
- 同时处理销售、内容、客服、运营、财务；
- 没有团队帮助分摊上下文；
- 对工具配置和维护的容忍度低。

### 7.2 Independent Consultant

典型任务：

- 分析客户材料；
- 写 proposal；
- 做会议纪要；
- 准备 deck；
- 维护客户沟通；
- 处理多个客户项目上下文。

### 7.3 Creator-Operator

典型任务：

- 内容调研；
- 草稿生成；
- 多平台发布；
- 视觉素材生成；
- 长内容拆短内容；
- 项目和素材管理。

### 7.4 非技术专业人士

Floatboat 博客明确面向 non-technical professionals。它反复强调：

- 不需要会编程；
- 不需要自托管；
- 不需要管理服务器；
- 但需要能清楚表达自己的工作。

这意味着 Floatboat 不是面向“不会用 AI 的小白”，而是面向已经感受到 AI 工具上限的进阶非技术用户。

---

## 8. Floatboat 的产品叙事优势

### 8.1 它没有直接卖功能，而是在定义一个新品类

Floatboat 博客的大量内容都在解释：

- 什么是 workspace agent；
- 它和 chatbot 有什么不同；
- 它和 workflow builder 有什么不同；
- 为什么一人公司需要它；
- 为什么 memory 和 context continuity 很重要。

这是一种典型的 category design 内容策略。

### 8.2 它的痛点表达非常具体

Floatboat 很少抽象地说“提高效率”，而是说：

- 47 个打开的标签；
- 每天重新向 AI 解释项目；
- 写 proposal 前要复制一堆背景；
- AI 工具很多但互相不知道；
- 用户自己变成 integration layer；
- 工作流工具配置成本比手工做还高。

这些表达比“自动化”“智能化”更容易打动目标用户。

### 8.3 它的边界感较强

Floatboat 没有宣称 Agent 能解决一切。它明确说：

- Agent 不能替代用户判断；
- Agent 不能解决业务本身不清晰的问题；
- 高风险领域需要人工审批；
- 长任务可靠性仍然有限；
- 安全和权限控制还不成熟；
- 2026 年仍是 experimentation year。

这种克制反而增强了可信度。

### 8.4 它把“记忆”升级为“执行记忆”

很多 AI 产品说 memory，只是记偏好。Floatboat 把 memory 拆成：

- 事实记忆；
- 项目上下文；
- 工作标准；
- 可复用执行过程。

其中最有价值的是 reusable execution / Combo Skills。这一点与 ANC 的“把 AI 构建期成果沉淀为可运行资产”高度相关。

---

## 9. 对 ANC 的启发

ANC 当前方向是 AI Agent Native 的企业级编排系统 / AI 原生公司基建。Floatboat 对 ANC 的启发主要有以下几点。

### 9.1 ANC 可以借鉴“Workspace Agent”叙事，但要升级为“Company Agent Workspace”

Floatboat 面向个人工作空间。ANC 可以面向企业工作空间：

> Floatboat: AI workspace for one-person companies  
> ANC: AI-native company workspace / AI-native business operating system

Floatboat 解决的是：一个人的工作如何被 AI 持续理解和协助。

ANC 可以解决的是：

- 一个公司的流程如何被 AI 理解；
- 一个公司的应用如何被 AI 构建；
- 一个公司的数据和流程如何被 Agent 编排；
- 一个公司的业务系统如何自维护、自演化。

### 9.2 ANC 的核心痛点也可以从“上下文断裂”切入

目前 proposal 更多强调传统 OA/ERP 的僵化、AI 断层、维护黑洞。Floatboat 提供了另一个更用户体感的切入点：

> 企业里的 AI 和业务系统互相不知道彼此在做什么。

在企业场景中，这表现为：

- 业务流程在 OA；
- 数据在 ERP；
- 沟通在飞书 / 钉钉 / 企微；
- 文档在网盘；
- 客户信息在 CRM；
- AI 在独立聊天窗口；
- 每次用 AI 都要人工搬运上下文。

ANC 可以把这个问题定义为：

> 企业级上下文断裂。

对应解决方案：

> 让 Agent 住进企业业务系统，理解应用、流程、数据和权限，而不是只在聊天窗口里回答问题。

### 9.3 “Combo Skills” 对 ANC 的 Skill / Template / App 设计很有启发

Floatboat 的 Combo Skills 是个人工作流程的可复用封装。

ANC 可以设计企业级对应物：

| Floatboat | ANC 对应概念 |
|---|---|
| Combo Skill | Business Skill / Process Skill / App Skill |
| 个人重复任务 | 企业重复流程 |
| 文件 + 浏览器 + 内容生成 | 数据模型 + 表单 + 工作流 + 连接器 + 权限 |
| 用户教 AI 一次 | 管理员 / 业务负责人让 Builder Agent 构建一次 |
| 下次复用 | 作为企业应用模板反复运行 |

ANC 可以把“应用生成”拆成可复用技能资产：

- 采购审批 Skill；
- 报销 Skill；
- 入职 Skill；
- 库存盘点 Skill；
- 客户跟进 Skill；
- 合同归档 Skill。

这些 Skill 不只是 prompt，而是包含：

- 数据模型；
- 页面；
- 流程；
- 连接器；
- 权限；
- 审计；
- 运行代码；
- 测试用例。

这比 Floatboat 的 Combo Skill 更重，但更符合 ANC 的企业级定位。

### 9.4 ANC 应保留 Workflow Builder 的确定性优势，同时吸收 Workspace Agent 的自然体验

Floatboat 的区分是：

- Workflow Builder：确定性、可重复，但需要预定义；
- Workspace Agent：灵活、上下文丰富，但可靠性较低。

ANC 的机会正好是把二者结合：

1. 用户体验上像 Workspace Agent：
   - 用户用自然语言描述目标；
   - Builder Agent 澄清需求；
   - 不要求用户一开始画流程图。

2. 运行时像 Workflow Builder：
   - 编译成确定性流程；
   - 有审计；
   - 有权限；
   - 有测试；
   - 可回滚；
   - 成本可预测。

这与 ANC proposal 里的“构建期 AI + 运行期确定性”高度一致。

### 9.5 ANC 的 MVP 也可以借鉴 Floatboat 的“一个具体高频任务”打法

Floatboat 官网示例没有泛泛地说“提升生产力”，而是给出：

> Turn Voice notes to a Tailor-Made Deck in 10 mins

这是一个非常具体的场景。

ANC 的 MVP 也应该避免“什么企业应用都能生成”的泛化表达，可以选择一个强场景，例如：

- “用一句话生成一个采购申请与审批应用”；
- “把资产盘点流程生成成 H5 扫码应用 + 后台”；
- “把入职流程生成成跨部门协同应用”；
- “把仓库出入库需求生成成移动端操作应用 + 管理后台”。

Floatboat 的经验说明：新品类需要用非常具体的任务让用户理解。

---

## 10. ANC 与 Floatboat 的定位差异

| 维度 | Floatboat | ANC |
|---|---|---|
| 目标用户 | 一人公司、独立顾问、创作者、非技术专业人士 | 一人公司到多人公司、企业管理员、业务负责人、IT/运维 |
| 产品形态 | 桌面 AI Workspace | 企业级 AI Agent Native 编排与应用生成平台 |
| 核心对象 | 文件、浏览器、个人项目、Combo Skills | App、Workflow、Data Model、Connector、Agent、Deployment |
| 主要价值 | 减少上下文切换，沉淀个人重复工作 | 构建和维护企业业务系统，替代/增强 OA/ERP/内部应用 |
| 执行方式 | Agent 在 workspace 中动态执行 | 构建期 Agent 生成，运行期确定性执行为主 |
| 风险重点 | 文件访问、个人隐私、长任务可靠性 | 权限、审计、企业数据安全、流程可靠性、系统集成 |
| 商业化 | 个人/小团队订阅 | SaaS + 私有部署 + 企业订阅 + 模板/连接器生态 |
| 差异化概念 | Combo Skills | Compiled Business Apps / Business Skills / Self-growing Company OS |

---

## 11. 建议 ANC 后续吸收的概念

### 11.1 概念一：Company Context

Floatboat 讲个人上下文，ANC 可以讲企业上下文。

Company Context 包括：

- 组织结构；
- 角色与权限；
- 业务流程；
- 数据模型；
- 历史操作；
- 审批规则；
- 外部系统连接；
- 企业知识库；
- 运行日志；
- 业务指标。

ANC 的 Agent 不只是理解一次 prompt，而是理解企业持续运转的上下文。

### 11.2 概念二：Business Skill

建议 ANC 设计类似 Floatboat Combo Skills 的企业级技能概念。

Business Skill 可以定义为：

> 一组可复用的企业业务能力，包含数据、页面、流程、连接器、权限、测试和运维策略，可由 Builder Agent 生成、部署、复用和持续优化。

例如：

- Reimbursement Skill；
- Procurement Skill；
- Onboarding Skill；
- Inventory Check Skill；
- Contract Lifecycle Skill。

### 11.3 概念三：从“AI 聊天入口”升级为“业务工作空间”

ANC 不应只做一个“和 Builder Agent 对话”的入口，而应该逐步形成业务工作空间：

- 应用列表；
- 流程画布；
- 数据模型；
- 运行状态；
- 权限配置；
- Agent 建议；
- 版本历史；
- 日志与审计；
- 可视化数据流。

这与 Floatboat 的“AI 住在 workspace 中”是一致的，只是 ANC 的 workspace 是企业业务系统层面的。

### 11.4 概念四：Reusable Execution，而不是 Prompt Library

Floatboat 强调：用户需要的不是更好的 prompt，而是可复用执行。

ANC 也应避免把模板做成“提示词模板”，而应做成真正可运行资产：

- 可部署；
- 可测试；
- 可审计；
- 可回滚；
- 可配置；
- 可被 Agent 维护。

这可以成为 ANC 区别于普通 AI 应用平台的重要卖点。

---

## 12. 对 ANC 产品计划的具体建议

### 12.1 产品叙事建议

当前 ANC 可形成这样的叙事：

> ChatGPT 让 AI 会回答问题，Floatboat 让 AI 住进个人工作空间，ANC 要让 AI 住进公司的业务系统。

更正式的表述：

> ANC 是一个 AI-native company workspace。业务负责人用自然语言描述需求，Builder Agent 将需求转化为可运行的业务应用、流程、数据模型和连接器；运行期以确定性代码执行，Agent 持续监控、诊断和优化。

### 12.2 MVP 场景建议

建议 MVP 选择一个能够展示以下闭环的场景：

1. 自然语言提出需求；
2. Agent 澄清业务规则；
3. 生成数据模型；
4. 生成表单和列表页面；
5. 生成审批/流转流程；
6. 发布应用；
7. 运行中产生日志和审计；
8. Agent 根据反馈提出修改。

候选场景优先级：

#### 方案 A：采购审批应用

优点：

- 规则明确；
- 有审批；
- 有权限；
- 有通知；
- 有数据模型；
- 适合展示确定性运行。

风险：

- 容易被认为只是 AI OA。

#### 方案 B：资产盘点 / 仓储出入库应用

优点：

- 更能体现“生成应用”而非“生成流程”；
- 可包含移动端/H5 扫码页面；
- 更贴近 README 中的应用形态；
- 与传统 OA 差异更明显。

风险：

- 业务对象和状态机略复杂。

#### 方案 C：HR 入职流程应用

优点：

- 跨部门协同明显；
- 并行任务和依赖关系清晰；
- Human-in-the-loop 自然。

风险：

- 集成系统较多，MVP 可能需要 mock。

综合建议：

> MVP 可以优先选择“资产盘点/出入库”或“采购审批”，前者更能体现应用生成，后者更容易快速跑通。

### 12.3 功能优先级建议

受 Floatboat 启发，MVP 不一定优先做复杂画布，而应优先做“从需求到可运行资产”的链路：

1. Builder Agent 对话入口；
2. 结构化需求规格；
3. App / Workflow / Data Model / Page 的中间表示；
4. 运行时工作流引擎；
5. 表单与列表页面生成；
6. 权限与审批；
7. 日志与审计；
8. 应用版本与修改；
9. 简单连接器。

画布可以作为后续增强，而不是 MVP 的主入口。

### 12.4 风险提醒

Floatboat 对自身品类的风险判断也适用于 ANC，但 ANC 的企业级风险更高：

- Agent 长任务跑偏；
- 生成流程不符合真实业务规则；
- 权限边界不清晰；
- 企业数据暴露；
- 自动修改系统导致事故；
- 运行时 LLM 成本不可控；
- 用户以为“AI 能做一切”，但实际需要大量业务澄清。

ANC 需要用以下机制降低风险：

- 构建期验证；
- 人工审批门禁；
- 沙箱预览；
- 测试用例生成；
- 灰度发布；
- 版本回滚；
- 审计日志；
- 权限最小化；
- 运行期确定性优先。

---

## 13. 可引用的 Floatboat 关键观点

以下是后续产品计划中可以吸收或改写的观点：

1. **AI 不应该只是一个聊天窗口，而应该住在工作发生的地方。**
2. **Chat Assistant responds; Workspace Agent operates.**
3. **Workflow builders are for work you already understand; workspace agents are for work still partly undefined.**
4. **用户不需要更多 prompt，而需要 reusable execution。**
5. **一人公司最大的成本不是执行任务，而是不断切换角色和重建上下文。**
6. **AI 的记忆不应只记偏好，而应记住项目、标准、工作方式和可复用过程。**
7. **工具越多不一定越高效，用户可能变成工具之间的人工集成层。**
8. **Agent 不应替代判断，只应放大已经清晰的工作方式。**

---

## 14. 参考链接

- Floatboat Blog: https://floatboat.ai/blog
- Floatboat Homepage: https://floatboat.ai/
- What Are AI Workspace Agents?: https://floatboat.ai/blog/ai-workspace-agents
- AI Workspace Agents vs Chat Assistants: https://floatboat.ai/blog/workspace-agents-vs-chat-assistants
- Workspace Agents vs Workflow Builders: https://floatboat.ai/blog/workspace-agents-vs-workflow-builders
- Why One-Person Companies Need a Workspace Agent: https://floatboat.ai/blog/workspace-agents-for-solo-operators
- What Is a Persistent AI Agent: https://floatboat.ai/blog/what-is-persistent-ai-agent
- AI Workflow for Solo Founders: https://floatboat.ai/blog/ai-workflow-solo-founders
- How to Stop Context Switching with a Workspace Agent: https://floatboat.ai/blog/stop-context-switching-workspace-agent
- Why Your AI Forgets Everything Between Sessions: https://floatboat.ai/blog/why-ai-forgets-between-sessions
- Should a Solo Operator Use an AI Agent?: https://floatboat.ai/blog/ai-agent-solo-operators

---

## 15. 一句话总结

Floatboat 的核心启发是：**AI 产品的下一阶段不是更聪明的聊天框，而是能够进入真实工作环境、保留上下文、学习工作方式，并把重复工作沉淀为可复用执行能力的 Agent Workspace。**

对 ANC 来说，这个思路可以升级为：

> 不是让 AI 帮企业回答问题，而是让 AI 进入企业业务系统，持续构建、运行和维护公司的应用、流程、数据与连接器。
