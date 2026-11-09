---
name: consulting-diagnostic-ppt
description: Create, revise, or review Chinese management consulting presentations in the user's on-site delivery style. Use for 按我的咨询风格做PPT, 现状诊断, 改进建议, AS IS / TO BE, 专项方案, or client action plans. Applies the user's approved templates and uses PPT Master for native editable PowerPoint delivery.
---

# Consulting Diagnostic PPT

## Personal Entry and PowerPoint Delivery

- This skill owns the consulting storyline, evidence, page choices, and personal style. Use the current [style guide](references/style-guide.md) as the baseline. Follow the user's explicit direction and the fixed visual rules of the approved template for this job. Scale the report structure to the source material and meeting purpose.
- For editable PowerPoint, load the installed [PPT Master](https://github.com/hugohe3/ppt-master) skill and follow its routing, integrity check, and selected workflow. Use its native PPTX export and visual checks. Set up PPT Master and its Python requirements from its upstream instructions before the first PPTX export. Keep text, tables, and process diagrams editable where supported. For another explicitly requested deliverable, apply this consulting guidance in that destination's workflow.
- Classify any PPTX input by purpose. Use a style example to infer page and writing choices. When asked to fill a supplied PPTX or make a targeted edit preserving the latest deck's design, use PPT Master's Edit Native PPTX route. When asked to turn a template into a reusable workspace, use Create Template. For a new deck, pass the exact approved template workspace root if one applies, then follow Generate PPTX. Explicit quick requests use the Quick profile when its routing conditions are met. With no applicable reusable workspace, use the documented consulting style for a new deck.
- Deliver the verified PPTX as a new copy for a new or revised deck unless the user explicitly requests replacement. Check that any requested Master/Layout was applied, labels remain readable on dense pages, and native objects survive export.

## Select a Page by Its Logic

When the user asks to choose a slide by content relationship or to fill an existing page, use their supplied template if available. Use [the Blue Series page index](references/blue-layout-index.md) for exact slide numbers only when the corresponding 101-slide PPTX is supplied for the task or exists at `assets/blue-series-template.pptx` relative to this skill. Otherwise use the documented consulting style and choose a layout that expresses the same relationship. Select by the relationship, number of branches or stages, text capacity, and needed evidence. An explicitly named source page takes priority. Use the actual slide and its native objects to verify fit and editability. Apply the current job's visual template or palette to the filled page, carrying semantic status colors through the change. Use the PowerPoint delivery route above for a requested PPTX.

## Style Calibration

When the user asks to learn from a template and representative decks, extract fixed rules from the template and compare the selected slides for recurring choices in conclusion titles, evidence placement, swimlanes, comparisons, and action tables. Treat client-specific branding and content as scoped to the source project. Record a reusable template's exact workspace root and scope only after review and approval.

Use the new rules on a small set of pages before promoting them to the style guide. Choose representative page types for the work, such as a process page, a rule comparison, and a diagnosis-to-action page. Use user feedback to distinguish stable preferences from one-off project choices, then spot-check an unrelated topic. Keep client content in the source project and carry forward only approved reusable rules and template assets.

## Learn from Finalized Decks

When the user confirms that a deck made or revised with this skill is final, review the available initial draft, their comments and revision requests, and the final deck. Include any manual changes visible in the user's supplied final version. Identify the evidence available for each inference.

Send a short list of candidate preferences in the chat for explicit confirmation. For each, state the observed change, the proposed rule, and the page types or situations it applies to. Label client requirements and one-off decisions as project-specific. Treat finalizing the deck as the trigger to propose preferences. Obtain a separate confirmation of the candidate rules before changing the skill.

Write only the explicitly approved, reusable rules to the [style guide](references/style-guide.md). Update [the Blue Series page index](references/blue-layout-index.md) when the user confirms a reusable page-selection preference tied to a specific template page. Keep project-specific details within the project.

## Core Positioning

Build dense, evidence-led consulting delivery decks for client workshops and steering meetings. Treat the deck as a working diagnosis and change roadmap, not as a marketing presentation.

Optimize for:

- Clear executive storyline
- Traceable diagnosis-to-suggestion logic
- Practical management mechanisms, process rules, and implementation actions
- High-density but controlled consulting pages
- Chinese B2B client delivery tone: professional, direct, grounded, and action-oriented

## Workflow

1. Clarify the delivery objective, client context, audience, and meeting use case.
2. Read the source materials and build the report skeleton before choosing templates or writing slides. Use the sections below as applicable.
   - Meeting agenda or report purpose
   - Project review and work path
   - Diagnostic framework and core findings
   - Detailed diagnosis by domain or business process
   - Root-cause summary
   - Improvement recommendations and TO BE design
   - Special topic list or专项方案
   - Next-step action plan
   - Appendix for detailed evidence, rules, and templates

   **Standard mode for new decks.** Present the overall storyline, the order of the key sections, and the proposed logic for each key section, such as conclusion with supporting parts (总分), progression (递进), or comparison (对比). Ask focused questions wherever ambiguity in the material or section logic would change how the deck tells the story. Wait for the user's explicit confirmation of the storyline and key-section logic before selecting a template or slide layouts and before drafting slides.

   **Quick mode.** When the user explicitly requests a quick first draft and the Quick profile applies, infer the storyline and section logic from the materials and the request, then choose layouts and deliver a first draft directly.
3. Convert findings into numbered diagnostic statements.
4. For each major issue, connect observed facts, the issue, supported causes, and the proposed action. Label unverified causes or effects as hypotheses and identify the evidence needed to test them.
5. Add benchmark practices only when they help define an operating mechanism, rule, form, or role.
6. End with accountable next actions, owners, timing, and handoff topics.

## Deck Architecture

Use one of these structures.

### Full Diagnostic Report

Use for broad management/marketing/system diagnosis.

1. 会议议程 / 报告目的
2. 项目回顾
3. 核心诊断发现
4. 建议专项破题清单
5. 下一步行动计划
6. 附录：按领域展开诊断与改进建议

Typical domains:

- 战略
- 管理体系
- 流程体系
- IT / 数智化
- 人才 / 组织能力

### Special Topic Report

Use for supply-demand, process, order, inventory, production, procurement, or cross-functional collaboration topics.

1. 业务体系分析
2. 现状问题分析
3. 业绩差距分析
4. 根因分析
5. 总体解决思路与专项方案
6. 下一步行动计划

## Page Patterns

Use the patterns in `references/style-guide.md` when producing slides.

Core page types:

- 章节页: section number + short section title
- 框架总览页: diagnostic framework, process framework, or solution map
- 核心发现页: 3-8 numbered findings, grouped by domain
- 现状诊断页: evidence, stakeholder quotes, data, screenshots, or process fragments
- 差距分析页: target vs actual, gap by festival/product/region/person/customer
- 能力定位页: locate which capability caused the gap
- 根因总结页: compress many symptoms into 2-4 root-cause categories
- AS IS / TO BE 对照页: old workflow on the left/top, new workflow on the right/bottom
- 改进建议页: management-side and system-side actions plus expected value
- 标杆实践页: benchmark mechanism translated into agenda, form, metric, or rule
- 专项方案页: one topic, one operating rule, one implementation method
- 行动计划页: tracking items, responsible departments, schedule, and deliverables

## Writing Rules

- Use conclusion-first slide titles.
- Prefer titles like:
  - `D3：渠道统筹主责人缺失，渠道深耕高度依赖个人能力`
  - `改进建议：成立渠道市场部，统筹渠道规划，强化渠道策略管理`
  - `核心根因：计划模式及产销平衡机制需优化，各环节模式规则需明确`
  - `总体解决思路#1：澄清顶层计划模式并制定相应管理规则`
- Number findings with `D1`, `D2`, etc. in full diagnostic reports.
- Use `AS IS`, `TO BE`, `问题`, `根因`, `改进方向`, `效用与愿景` as repeated anchors.
- Keep recommendations operational, not generic. Name the rule, meeting, form, role, process, KPI, system function, or management mechanism.
- Use client language and concrete business nouns: 销售计划、需求计划、计划订单、常规订单、产销平衡会议、安全库存、渠道市场部、经营分析例会、费用台账.
- Use short quotes from interviews when they sharpen evidence, but do not overuse them.

## Visual Style

- 16:9 widescreen.
- Use a light background, consulting-blue accents, black/dark-gray body text, and red for problems or emphasis.
- Prefer Microsoft YaHei / 微软雅黑 or equivalent Chinese sans-serif.
- Use dense professional pages with tables, swimlanes, matrices, process maps, and annotated screenshots.
- Avoid decorative illustration, playful icons, large gradients, and marketing-style hero pages.
- Keep chapter pages simple: large section number/title and one supporting image or brand element.
- Use thick section headers, light-blue content bands, and thin divider lines.
- Use tables and process diagrams as the dominant visual language.

## Quality Bar

Before delivery, check:

- Every recommendation is tied to a diagnosis or gap.
- Every process redesign has a clear owner or rule.
- AS IS and TO BE pages use consistent roles, lines, and terminology.
- Dense pages remain scannable through grouping, numbering, and color emphasis.
- There is a practical next-step plan, not just conceptual advice.
- No page is only a generic framework without client-specific implication.
