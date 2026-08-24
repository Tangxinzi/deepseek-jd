# Mission-led JD Style Guide

This guide distills the writing decisions found in the user-provided DeepSeek job descriptions. It is a pattern library, not copy to reproduce verbatim. Replace every example with facts from the team being described.

## Mode Selection

Before writing, identify the requested output:

- **Full JD:** mission plus role content and evidence.
- **Mission only:** the mission and a short assumptions note, without a full role template.
- **Mission critique:** diagnosis first, then a focused rewrite.
- **Role adaptation:** one shared mission, different role-specific responsibilities and evidence.
- **Variant set:** 2-3 versions that differ in emotional register, not just synonyms.

Keep the output proportionate. A mission-only request should not be buried under a full JD.

## Fact Lock

Use this compact pre-draft table mentally or explicitly:

| Field | Question |
| --- | --- |
| Object | What is this team changing, building, measuring, or protecting? |
| Beneficiary | Who becomes more capable, safe, informed, or free because of it? |
| Now | What changed so this problem matters at this moment? |
| Friction | What is genuinely hard, uncertain, or in tension? |
| Agency | What can this team actually control or deliver? |
| Evidence | What would prove a candidate can do the work? |
| Boundaries | Which claims, scales, technologies, or promises are not confirmed? |

If the object, friction, or agency is unknown, ask for it or state an assumption. Never use “AI”, “未来”, or “改变世界” to hide an empty field.

## The Core Movement

A strong team mission usually makes five moves:

1. **Name the larger reality.** Start with a real change in the world, industry, user behavior, or technical landscape. The opening can be broad, but it must be recognizable rather than mystical.
2. **Raise the stakes.** Explain what becomes possible or what fails if the problem remains unsolved. Make the tension legible: scale versus reliability, speed versus safety, capability versus trust, intelligence versus access, research versus deployment.
3. **Name the frontier.** State the hard problem this team is willing to work on. Mention the real systems, users, constraints, or artifacts involved.
4. **Give the team agency.** Say what this team will build, measure, change, or protect. The team should be the subject of active verbs, not a passive beneficiary of a grand trend.
5. **Invite the right people.** Close with a grounded invitation that identifies the kind of curiosity, judgment, persistence, or craft the work needs.

Useful compression:

> larger reality -> consequence -> technical or operational frontier -> team's agency -> invitation

The order can change when the role is more human-centered or more research-oriented, but all five moves should be present across the mission, not necessarily in every paragraph.

## The Mission Thesis

DeepSeek's strongest missions often contain one memorable conceptual reframe before the detailed explanation. It gives the reader a proposition to remember and gives the rest of the mission something to prove.

Useful forms:

- **Foundation:** “[X] 是 [Y] 的基石/底座/原生感官。”
- **Redefinition:** “我们不只是 [ordinary task]，更是在 [higher-order responsibility]。”
- **Transformation:** “我们要把 [raw resource] 变成 [reliable capability]。”
- **Equation:** “[A] + [B] = [new capability]。”
- **Boundary:** “当 [scale/change] 到来，过去的 [assumption] 不再成立。”

Choose one thesis, not a pile of slogans. It must be followed by specific systems, constraints, users, or failure modes that make it true. Avoid copying a source company's exact metaphor when the new team's facts do not support it.

## Emotional Architecture

The feeling should be **earned urgency**, not hype. A practical way to create it is:

`emotional force = stakes × specificity × agency`

- **Stakes:** Why does this matter to people, knowledge, safety, capability, or the future of the product?
- **Specificity:** What exact systems, data, failure modes, or decisions make the work difficult?
- **Agency:** What can this team actually do about it?

If any factor is zero, the prose becomes a slogan. “We are changing the world” has stakes but no specificity or agency. “We maintain a queue” has specificity but no visible stakes. A strong mission connects both.

### Emotional register

Offer a controllable register when the user has a preference:

- **史诗感:** historical or civilizational change, large systems, long horizons;
- **技术感:** bottlenecks, architecture, performance, failure and trade-offs;
- **人文感:** people, knowledge, relationships, dignity and capability;
- **克制感:** sparse metaphor, direct claims, evidence-forward prose.

Default to a balanced blend: one memorable image or thesis, followed by concrete work and constraints. Do not let the register override factual accuracy.

## Paragraph Patterns

Use one or two patterns; do not stack every pattern in one mission.

### Civilizational or industry premise

Use for infrastructure, research, and platform teams.

> 每一代人都会遇到属于自己的 [基础设施/技术/知识] 变革。今天，[具体变化] 正在把 [旧边界] 推向 [新边界]。

Follow immediately with the real consequence and the team's responsibility. The opening is only a door; do not leave it as a free-floating manifesto.

### Human capability premise

Use for product, data, experience, and user-facing teams.

> [人类行为/需求] 一直是 [领域] 的核心问题。随着 [technology or behavior change]，我们需要重新回答 [specific question]。

Then explain how the team turns that question into a product, evaluation system, or user experience.

### Contrast and redefinition

DeepSeek's examples often redefine a familiar role:

> 我们不只是 [ordinary description]，更是在 [higher-order responsibility]。

Use at most once or twice per section. The second half must be supported by concrete work; otherwise it reads as inflated positioning.

### Resource-to-capability transformation

Use for data, research, and operations roles.

> [Raw resource] 是 [capability] 的底座。真正困难的不是拥有它，而是把它 [clean/measure/organize/operate] 成可以稳定产生 [outcome] 的系统。

This pattern makes invisible work feel consequential without pretending that it is glamorous.

### Invitation to a frontier

Use as a closing rather than a headline:

> 如果你愿意在 [specific unknown or difficult context] 中持续拆解问题、做出判断并把结果交付出来，我们期待与你一起 [concrete outcome]。

The invitation should describe the work's temperament, not flatter the reader with “天才”“顶尖”等 empty labels.

## Role Archetypes

### Research and frontier

Emphasize the boundary of knowledge, the hypothesis or paradigm under examination, the cost of being wrong, and the freedom to form and test ideas. Responsibilities should show a loop: define problem -> design experiment -> build data/system -> measure -> revise.

### Infrastructure and systems

Start from what the infrastructure makes possible for others. Name physical or systems constraints: latency, throughput, reliability, energy, capacity, isolation, recovery, observability. Make routine operations part of the larger reliability story.

### Data and evaluation

Treat data as an asset only when the JD explains how quality, provenance, diversity, feedback, or evaluation turns it into better model or product behavior. Avoid calling every annotation task “intelligence infrastructure” without describing the pipeline.

### Product and experience

Start from the user's changing capability or expectation. Describe the gap between what the model/system can do and what a person can reliably accomplish. The mission should end in a better decision, workflow, relationship, or experience, not in “more features.”

### People, operations, and support

Show the hidden system that lets the core team do difficult work: trust, speed, clarity, compliance, staffing, or a frictionless environment. Do not apologize for operational work; show its leverage and the people it protects.

## JD Skeleton

Use this as a flexible shape, not a fixed form. The body is intentionally plain text so it can be pasted into forms that do not support Markdown:

```text
【职位名称】
产品经理

团队/职能： [team or function]
地点： [location]
工作性质： [实习/全职]

【团队使命】
[2-4 paragraphs: larger reality, stakes, frontier, agency, invitation]

【岗位类别】
[type]

【招聘方向】
[tracks, if any]

【工作职责】
1、[Outcome and the system or user it affects]
2、[Hard problem or recurring decision]
3、[Collaboration and delivery loop]

【核心要求】
1、[Capability] + [observable evidence]
2、[Capability] + [observable evidence]
3、[Judgment, craft, or communication requirement]

【加分项】
1、[Relevant differentiator]
```

For multiple tracks, write a shared mission and shared requirements first, then give each track its own responsibilities and evidence. Do not repeat the same mission paragraph under every sub-role.

## Sentence Tools

These are scaffolds to adapt, not phrases to paste mechanically:

- “真正困难的不是 [surface task]，而是 [systemic bottleneck]。”
- “当 [scale or change] 继续扩大，过去默认的 [assumption] 可能不再成立。”
- “我们要做的，是把 [resource/technology] 变成 [reliable capability]。”
- “每一次 [daily action]，都会影响 [user/system outcome]。”
- “这里没有实验室里的标准答案；你需要在 [constraint] 下建立可验证的判断。”
- “你的工作不会停留在 [local task]，而会连接到 [larger outcome]。”

Use concrete nouns after the scaffold. “影响未来” is weak; “让数万台设备在故障和变更中持续可观测、可恢复” is strong when true.

## Micro Examples

These examples illustrate the transformation, not copy.

### Infrastructure

**Weak:** 我们负责建设稳定可靠的基础设施，支持公司业务发展。

**Mission-led:** 算力集群不是模型研发的背景板，而是把电力、网络和计算转化为智能的系统。随着训练规模扩大，单点故障、通信抖动和资源浪费都会被放大；我们要做的是让这套系统在更大规模下仍然可观测、可恢复、可持续优化。

### Data

**Weak:** 我们负责数据清洗和数据标注，提升模型效果。

**Mission-led:** 数据不是模型的燃料清单，而是模型认识世界的路径。真正困难的不是收集更多样本，而是从噪声、重复和偏差中提炼出可追溯、可评估、能稳定改变模型行为的数据资产。

### Product

**Weak:** 我们打造优秀的 AI 产品，为用户提供更好的体验。

**Mission-led:** 模型会回答问题，不等于人已经完成了任务。我们要把模型的能力转成用户可以信任、复用并交付结果的工作流，在每一次失败、犹豫和等待中重新定义人与 AI 协作的方式。

The stronger versions work because they contain a thesis, a real gap, and a team-owned transformation. Their claims should still be replaced with the new team's facts.

## Two-pass Drafting and Review

Use two passes even when the final answer is short:

1. **Factual pass:** write the object, beneficiary, why-now, friction, frontier, agency, and candidate challenge. Remove all unsupported adjectives.
2. **Narrative pass:** improve rhythm, contrast, image, and invitation. Add no new factual claims.

Then run a skeptical-candidate review:

- Can I tell what I would actually do in the first months?
- Does every emotional peak have a concrete anchor?
- Is the mission distinct from a generic AI company statement?
- Does the candidate have agency, or am I only being asked to admire the team?
- Are the requirements evidence-based and proportional to the role?
- Did any metaphor, equation, or “改变世界” phrase survive without proof?

## What to Remove or Separate

- Mission paragraphs that could describe any AI company.
- Consecutive adjectives (“极致、顶尖、伟大、颠覆”) without evidence.
- Prestige requirements that replace proof of ability.
- Generic “we are a family” culture copy.
- Benefits disguised as mission.
- Interview instructions, application buttons, or recruiting logistics inside the mission.
- Technical keyword dumps that are not connected to a responsibility.
- A closing invitation that asks for passion but never says what the person will actually do.

## Review Checklist

Before delivery, check:

- Can a reader name the team's object of change after one read?
- Does the mission contain at least one real constraint or failure mode?
- Is there a visible bridge from mission to the first responsibility?
- Would a qualified candidate know what evidence to show in an application?
- Are the emotional peaks supported by facts from the team's context?
- Does the prose invite ownership rather than demand worship?
- Have unsupported company-specific claims been removed or marked as assumptions?
- Are the mission, role content, requirements, bonus items, and logistics clearly separated?
