---
name: deepseek-jd
description: "Create, rewrite, or critique Chinese job descriptions and team missions with a grounded, mission-led voice inspired by the supplied DeepSeek examples; use for JD writing, employer-brand copy, role narratives, and mission analysis."
---

# DeepSeek JD Writer

Use this skill when the user wants a Chinese job description, team mission, recruitment page, employer-brand narrative, or a rewrite that should make the work feel consequential and invite capable people into a difficult, unfinished project. Do not use it for generic marketing copy unless the user explicitly asks for the JD-style mission-led treatment.

The target is not a literal imitation of DeepSeek wording. Reuse the underlying decisions visible in the supplied examples: human stakes, technical specificity, a clear frontier, and an honest invitation to take ownership. Preserve the user's facts, brand, industry, and level of ambition; never invent impact, scale, products, benefits, or hiring conditions.

## Mode Routing

Choose the smallest mode that satisfies the request:

- **Full JD:** write or rewrite the complete role description.
- **Mission only:** write or rewrite only the team mission, then briefly state the factual assumptions used.
- **Mission critique:** identify why an existing mission works or fails, then provide targeted rewrites.
- **Role adaptation:** preserve a shared mission while adapting responsibilities and evidence for a new function or seniority.
- **Variant set:** produce 2-3 distinct mission versions with explicit tone labels when the user asks for options.

Do not output a full JD when the user asks for only a mission or critique. If the desired mode is unclear and the missing choice materially changes the result, ask one concise question; otherwise infer from the request.

## Direct Output

When the user explicitly invokes `$deepseek-jd` and sends only a role or function name, treat it as a request for a first draft. Output the result directly, without explaining the mode, fact lock, assumptions, or writing process.

For a role-only prompt such as “产品经理”, use a concise default shape:

- one-sentence role positioning;
- a short team mission or role mission;
- 4-5 outcome-oriented responsibilities;
- 4-5 core requirements.

Use neutral wording when company, product, users, or scale are unknown. Do not invent those facts and do not pause for clarification unless the role itself is genuinely ambiguous. Keep the response focused; do not add a preamble or explain the writing process.

End every direct-output response with a useful close:

- If there is a concrete improvement, add `【建议】` followed by 1-3 specific recommendations.
- If there is no separate recommendation, add `【下一步】` followed by one practical direction, such as the most valuable missing context or a directly useful variant to produce next.

For a JD intended for publication, the recommendations may also identify missing publishing fields. Select only the relevant items rather than listing everything:

- salary range, compensation structure, performance bonus, or equity;
- work location, office/remote arrangement, or travel expectations;
- benefits and leave policies;
- employment type, level, reporting line, headcount, or start date;
- application channel, hiring process, contact, or other required form fields.

Do not invent any of these details. Keep the close concise: at most three short lines or 1-2 sentences. Do not use empty courtesy or generic offers to help.

Put the complete JD in one standalone plain-text block. In chat, use a `text` fenced block only as the visual container. The contents of the block must be suitable for direct pasting into forms: use section labels such as `【团队使命】`, `【工作职责】`, and `【核心要求】`, and use `1、` style enumeration. Do not use Markdown syntax inside the block, including `#` headings, bold or italic markers, bullet markers, tables, links, blockquotes, horizontal rules, or nested code fences. Keep `【建议】` or `【下一步】` outside the block so the JD remains easy to scan and copy.

## Workflow

1. Build a fact lock before drafting. Capture:
   - object of change, beneficiary, current state, and desired state;
   - why now and the real bottleneck, tension, or trade-off;
   - the systems, data, users, constraints, and scale the team actually controls;
   - role scope, seniority, location, employment type, technologies, and evidence expected;
   - claims that are confirmed, assumptions, and facts that must not be invented.
   If essential facts are missing, ask up to three focused questions or label assumptions visibly. Do not fill gaps with grand language.
2. Select one mission thesis: a memorable proposition that redefines the team's object (for example, “X is the foundation of Y”, “we do not merely X; we make Y possible”, or “A + B = C”). The thesis must be supported by the team's actual work.
3. Write the team mission first. Move from a human or industry-level premise, through why the moment matters, to the concrete system/problem this team owns. End with a credible invitation to people who want to do this work. A mission should make the job feel important without claiming that every role single-handedly changes the world.
4. Write the role as an execution path from mission to evidence:
   - one short role summary;
   - 4-7 outcome-oriented responsibilities;
   - 3-6 core requirements tied to observable evidence;
   - optional bonus items that genuinely differentiate candidates;
   - optional directions or tracks when the role has real variants.
5. Calibrate the voice with an explicit profile when useful: **史诗感** (时代和基础设施), **技术感** (系统和约束), **人文感** (用户、知识和人的能力), or **克制感** (少修辞、强事实). Default to a balanced blend. Use first-person plural for the team, concrete nouns and verbs, controlled contrast ("不只是……更是……"), and technical details that prove the story is real. Mix long-range purpose with the texture of daily work. Keep the candidate as an agent, not an audience being sold to.
6. Draft in two passes. Pass one establishes facts, thesis, stakes, frontier, agency, and candidate challenge. Pass two improves rhythm, imagery, contrast, and invitation without adding new claims.
7. Act as a skeptical candidate after drafting. Remove unsupported scale, empty prestige, repeated adjectives, generic “改变世界” claims, and any sentence that cannot connect to a real responsibility. Then deliver the requested mode, not the internal analysis.

## Quality Bar

- The mission can be reduced to one clear "we exist to..." sentence.
- It contains a real object, constraint, user, system, or failure mode rather than only values.
- It explains why this team's work is the necessary next step, not merely desirable.
- At least one sentence connects the mission to the actual responsibilities.
- The invitation names the mindset or capability needed, without gatekeeping through vague prestige signals.
- "改变世界" is earned through scale, stakes, or a concrete frontier; it is not used as decoration.
- Requirements describe evidence of ability, not personality adjectives alone.
- Benefits, slogans, interview instructions, and application calls are kept separate from the mission unless the user asks for them.
- No unsupported claims about users, revenue, scale, market position, technology, or social impact.

For the detailed narrative patterns, role archetypes, sentence scaffolds, and review checklist, read [references/style-guide.md](references/style-guide.md) when drafting or critiquing a JD.
