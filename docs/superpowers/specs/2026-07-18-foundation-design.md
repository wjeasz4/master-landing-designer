# Foundation Architecture Design

Date: 2026-07-18  
Status: Approved for implementation

## Purpose

Establish `master-landing-designer` as a design reasoning system for Codex. The repository must teach why premium landing pages work, how to choose among valid approaches, and how to review the consequences of those choices before generating code.

This sprint creates the operating model, decision language, knowledge contracts, and quality gates that later knowledge can extend. It does not create implementation guidance, UI components, demos, or a library of copy-and-paste prompts.

## North Star

Build a design operating system, not a recipe book.

The repository must help Codex form judgment. Recipes optimize for repetition; judgment adapts principles to a product, an audience, and a moment. Trends are temporary expressions of deeper forces such as attention, comprehension, trust, motivation, and effort. The repository therefore treats principles as durable and trends as contextual evidence, never as default answers.

The system prefers:

- reasoning over recipes;
- evidence over taste claims;
- explicit trade-offs over universal rules;
- product truth over decorative novelty;
- coherent decisions over isolated polish;
- reviewable rationale over unexplained output; and
- principles that outlive trends over imitation of current aesthetics.

## Repository Constitution

`CONSTITUTION.md` is the root governance document and highest authority in the repository. Every skill instruction, agent behavior, knowledge document, pattern, example, diagnostic prompt, template, checklist, asset policy, reference, contribution, and review must comply with it.

The authority order is:

1. `CONSTITUTION.md`
2. `SKILL.md` and `AGENTS.md`
3. repository governance documents
4. collection indexes
5. individual knowledge artifacts

When two documents conflict, the higher authority wins. The lower-authority document must be corrected; contributors must not resolve the conflict by weakening or silently reinterpreting the Constitution.

### Immutable Principles

1. **Reason before implementation.** Understand the product, audience, evidence, constraints, and intended effect before generating code or prescribing form.
2. **Principles over trends.** Use durable truths about people, perception, communication, systems, and technology to evaluate trends; never treat popularity as proof.
3. **Evidence over opinion.** Distinguish research, standards, observed behavior, expert practice, inference, and hypothesis. Do not present preference as fact.
4. **Originality over imitation.** Derive the design from product truth and audience needs. Extract principles from references without reproducing another product's expression.
5. **Systems over isolated components.** Judge every choice by how it affects hierarchy, rhythm, meaning, behavior, accessibility, performance, brand, and conversion as a whole.
6. **Accessibility is mandatory.** Treat inclusive perception, understanding, navigation, and interaction as design requirements, not optional polish.
7. **Performance is a feature.** Treat speed, responsiveness, stability, and resource discipline as part of the user experience and brand promise.
8. **Every recommendation must explain why.** Connect advice to context, evidence, intended effect, and success criteria.
9. **Every pattern must document trade-offs.** State gains, costs, failure modes, contraindications, and the conditions that change the recommendation.
10. **Every review finding must improve future decisions.** Trace findings to their underlying decisions and feed reusable learning back into the knowledge system when evidence supports it.
11. **The repository is a living knowledge system.** Revise lower-level knowledge when evidence changes, preserve provenance, expose uncertainty, and prevent stale guidance from becoming doctrine.

These principles are immutable under ordinary contribution. The repository may evolve without compromising them. A constitutional amendment requires a dedicated Decision Record, evidence that the existing principle harms the mission, an impact analysis covering all subordinate documents, explicit maintainer approval, a changelog entry, and a versioned migration plan. Amendments must never be hidden inside unrelated changes.

### Constitutional Violations

A contribution or skill behavior violates the Constitution when it:

- copies or closely imitates an existing product's layout, typography, components, copy, motion, or signature visual treatment;
- provides generic AI design advice that is not grounded in product, audience, context, or evidence;
- presents unsupported design claims, personal taste, or trend popularity as universal truth;
- recommends a decision without rationale, intended effect, or observable review criteria;
- introduces a pattern without trade-offs, contraindications, risks, or failure modes;
- contradicts higher-authority guidance or creates unresolved guidance conflicts;
- generates code before product understanding, material decisions, accessibility, performance, synthesis, and review gates are complete;
- treats accessibility or performance as optional, deferred, or expendable polish;
- optimizes an isolated component while damaging the coherence of the wider system;
- adds prompt, template, checklist, example, or asset volume without increasing reusable design intelligence; or
- suppresses uncertainty, provenance, review findings, or evidence that should change future guidance.

### Enforcement

Constitutional compliance is a blocking gate, not a review suggestion.

- Identify the violated principle and the conflicting artifact or behavior.
- Stop publication, merge, recommendation, or code generation while the violation is material.
- Correct the subordinate guidance or decision; do not create an exception through wording alone.
- Record recurring violations as evidence for improving indexes, heuristics, checks, or skill behavior.
- Require a constitutional amendment process when a proposed change genuinely challenges an immutable principle.

Reviews must report constitutional violations separately from ordinary refinements so that severity and authority remain clear.

## Design Intelligence

Design Intelligence is the system's ability to translate product and audience evidence into coherent design decisions, anticipate their effects, and review whether the resulting experience serves its purpose.

It combines five capabilities:

1. **Comprehension** — understand the product, audience, task, market context, constraints, and desired outcome.
2. **Interpretation** — connect evidence to durable design principles and relevant psychological effects.
3. **Judgment** — compare plausible options, choose deliberately, and acknowledge trade-offs and risks.
4. **Synthesis** — make typography, spacing, color, hierarchy, composition, interaction, motion, accessibility, performance, and conversion decisions operate as one system.
5. **Review** — test the system from visual, functional, human, brand, and business perspectives before accepting it.

Design Intelligence is not visual taste alone. A visually impressive page that obscures the offer, excludes users, damages performance, or contradicts the brand is a failed design decision.

## Success Criteria

The foundation is complete when:

- the repository has a clear human entry point, a compact Codex decision kernel, and global agent instructions;
- the Repository Constitution exists as the explicit highest authority and every subordinate artifact defines or inherits its compliance obligation;
- every required knowledge area has a non-empty index defining its responsibility and evidence standard;
- every future knowledge document is required to explain why, context, limits, effects, trade-offs, mistakes, expert observations, and heuristics;
- important design decisions use one stable Decision Record format;
- every future landing page is subject to the repository-wide Design Review Framework;
- code generation is impossible within the documented workflow until product understanding, design synthesis, accessibility, performance, and review gates pass;
- principles are separated from trends and inspiration is separated from imitation;
- contributors can add knowledge without duplication, contradiction, prompt sprawl, or context bloat; and
- the finished foundation passes structural, content, link, ambiguity, and placeholder checks.

## Operating Architecture

Use a compact decision kernel with progressive disclosure.

`CONSTITUTION.md` defines non-negotiable system invariants. `SKILL.md` is the subordinate orchestrator: it enforces those invariants through sequence, required outputs, evidence thresholds, uncertainty handling, Decision Records, the Design Review Framework, and the final code-generation gate. It must remain concise enough to load reliably.

Supporting collections do not behave as chapters in a handbook. They behave as specialized intelligence layers loaded only when a decision needs them:

1. Load the Constitution and reject any instruction or source that would violate it.
2. Product and audience evidence enters the decision kernel.
3. The kernel identifies the design questions that materially affect the outcome.
4. Relevant principles, patterns, examples, and references are loaded selectively.
5. Important choices are evaluated and captured as Decision Records.
6. Decisions are synthesized into one coherent direction.
7. The direction is tested through the Design Review Framework and a constitutional compliance check.
8. Failed or weak review dimensions return to the relevant decision, not directly to cosmetic revision.
9. Code may be generated only after both gates pass or the product owner explicitly accepts a documented non-constitutional residual risk. Constitutional violations cannot be accepted as residual risk.

This feedback loop is essential: review diagnoses decision quality, not merely surface defects.

## Repository Responsibilities

| Path | System responsibility |
| --- | --- |
| `CONSTITUTION.md` | Define immutable principles, authority order, violations, enforcement, and the formal amendment process. |
| `README.md` | Explain the vision, Design Intelligence model, operating architecture, usage, roadmap, philosophy, and contribution path. |
| `SKILL.md` | Enforce the Constitution while orchestrating evidence gathering, reasoning, Decision Records, synthesis, review, and the code-generation gate. |
| `AGENTS.md` | Translate constitutional authority into repository-wide reasoning discipline, originality standards, self-review, and continuous improvement. |
| `CONTRIBUTING.md` | Define how knowledge claims, reasoning tools, and governance changes are proposed and reviewed. |
| `CHANGELOG.md` | Record the `v0.1.0` foundation release using a stable changelog format. |
| `LICENSE` | Provide the MIT license. |
| `.gitignore` | Exclude operating-system, editor, dependency, build, cache, environment, and local workspace artifacts. |
| Collection `index.md` files | Define scope, exclusions, required content structure, evidence expectations, and relationships to the decision system. |

The repository serves three audiences:

1. Skill users, who need a trustworthy way to invoke and evaluate the system.
2. Codex, which needs a compact operating protocol and discoverable knowledge.
3. Contributors and agents, which need stable boundaries and a high bar for new claims.

## Knowledge Document Contract

Every future knowledge document must help Codex reason, not merely remember. It must answer all of the following:

1. **Why this principle exists** — identify the human, perceptual, cognitive, brand, technical, or business problem it addresses.
2. **When to use it** — describe the evidence and conditions that make it relevant.
3. **When not to use it** — identify contraindications, misleading contexts, and competing priorities.
4. **Trade-offs** — state what the choice improves, what it may weaken, and what it costs.
5. **Psychological effect** — explain its likely influence on attention, comprehension, trust, emotion, motivation, or perceived effort without presenting speculation as certainty.
6. **Common beginner mistakes** — identify superficial or mechanical applications that miss the principle.
7. **Expert observations** — capture nuanced signals, edge cases, and interactions visible through experienced practice.
8. **Decision heuristics** — provide conditional guidance that helps choose, never an unexplained rule.

A document that cannot answer these questions is not yet repository knowledge. Unsupported claims must be labeled as hypotheses or excluded. Examples must expose reasoning and consequences rather than offer designs to copy.

## Decision Record

Use a Decision Record for every choice that materially changes user understanding, emotional response, brand expression, interaction, accessibility, performance, or conversion behavior.

Each record must contain:

### Context

State the relevant product, audience, journey stage, evidence, constraints, and dependencies.

### Problem

Define the decision that must be made and why it matters now.

### Options Considered

List credible alternatives. Describe the conditions under which each option would be valid.

### Decision

State the selected direction precisely enough to guide later work.

### Rationale

Connect the decision to evidence, principles, audience needs, and the intended effect.

### Trade-offs

State what is gained, what is sacrificed, and which competing values were prioritized.

### Risks

Identify assumptions, failure modes, accessibility or performance concerns, and signals that would invalidate the decision.

### Review Checklist

Define observable checks that can confirm whether the decision works in the resulting experience.

Decision Records are reasoning artifacts, not bureaucracy. Combine tightly coupled choices in one record when separation would hide their interaction. Split records when decisions can change independently.

## Design Review Framework

Every generated landing page must later be reviewed across all twelve dimensions. A review must state the evidence observed, the consequence, the severity, and the decision that should be revisited. It must not stop at preference statements such as “make it cleaner” or “add more polish.”

| Dimension | Review question |
| --- | --- |
| Visual hierarchy | Does attention move through the page in the intended order, and does prominence match importance? |
| Typography | Do type choices, scale, measure, rhythm, and contrast support voice, comprehension, and scanning? |
| Spacing | Does spatial rhythm clarify relationships, pacing, density, and section transitions across viewports? |
| Color | Does the semantic color system express the brand, distinguish roles and states, and avoid decorative noise? |
| Contrast | Are text, controls, states, focus indicators, and key distinctions perceivable in realistic conditions? |
| Composition | Does the arrangement create balance, direction, emphasis, and responsive coherence without becoming formulaic? |
| Motion | Does motion explain change, guide attention, or reinforce character without delay, distraction, or reduced-motion failure? |
| Accessibility | Can people with varied sensory, motor, cognitive, and technological needs perceive, navigate, understand, and act? |
| Performance | Does the experience respect defined budgets and preserve responsiveness, stability, and fast access to core value? |
| Conversion | Does the page reduce uncertainty, establish relevance and trust, and make the next action clear without manipulation? |
| Originality | Does the design emerge from product-specific reasoning rather than trend assembly, template mimicry, or generic AI patterns? |
| Brand consistency | Do voice, visuals, behavior, and emphasis express the same brand character across the complete experience? |

A page does not pass because every dimension is maximized. Premium work balances them according to context. A deliberate quiet page may use little motion; a high-consideration product may prioritize trust and explanation over immediate action. The review tests coherence and fitness, not stylistic intensity.

Review findings must produce one of four outcomes:

- **Pass** — evidence supports the decision and no material change is needed.
- **Refine** — the decision is sound but its expression needs adjustment.
- **Reconsider** — evidence challenges the rationale or selected option.
- **Blocked** — missing information or an unresolved risk prevents responsible acceptance.

## Knowledge Boundaries

- `knowledge/`: durable principles and conceptual models that satisfy the Knowledge Document Contract.
- `patterns/`: contextual decision patterns with forces, alternatives, trade-offs, failure modes, and heuristics.
- `examples/`: annotated reasoning traces that show how context changes decisions; never copy-ready demos.
- `prompts/`: a deliberately small set of diagnostic inquiry protocols for obtaining missing evidence or conducting reviews; never a prompt collection or growth target.
- `templates/`: stable structures for Decision Records, reviews, knowledge documents, and other reasoning artifacts; never finished landing pages.
- `checklists/`: concise quality gates used after reasoning; never substitutes for reasoning.
- `assets/`: future source materials used in outputs, subject to provenance, licensing, accessibility, and optimization requirements.
- `references/`: external standards, research notes, citations, and provenance used to support or challenge knowledge claims.

Each index must state what belongs in its collection, what does not, how content interacts with the decision kernel, and how a contribution earns inclusion. The indexes must be useful immediately even though the collections intentionally contain no domain payload in this sprint.

## Skill Decision Pipeline

The skill must require the following order:

1. Understand the product, value proposition, constraints, evidence, and desired outcome.
2. Understand the primary audience, context, intent, awareness, objections, and accessibility needs.
3. Determine the emotional tone appropriate to the product and journey stage.
4. Determine a visual language that expresses product and brand truthfully.
5. Choose typography based on voice, readability, hierarchy, language, and delivery constraints.
6. Choose a spacing system based on rhythm, density, relationships, and responsive behavior.
7. Choose a semantic color system based on brand meaning, role clarity, states, and contrast.
8. Choose the information and visual hierarchy based on user priorities and conversion logic.
9. Choose layout and composition principles based on content, attention flow, and responsive constraints.
10. Choose interaction behavior and feedback based on user intent, device context, and state change.
11. Choose a motion strategy based on explanatory value, emotional tone, performance, and reduced-motion needs.
12. Choose an accessibility strategy spanning content, semantics, perception, navigation, interaction, and testing.
13. Choose a performance strategy with explicit budgets and asset, rendering, loading, and interaction priorities.
14. Capture material choices as Decision Records.
15. Synthesize all decisions and identify contradictions, unsupported assumptions, and cumulative risk.
16. Apply the complete Design Review Framework.
17. Revisit failed decisions until the direction passes or the product owner explicitly accepts a documented residual risk.
18. Generate code only after the decision system is coherent and the review gate passes.

Each phase must produce a concise decision, rationale, evidence level, and unresolved risk. Missing evidence triggers a focused question, research need, or explicit assumption. It never triggers arbitrary styling.

## Uncertainty and Conflict Handling

- When product or audience evidence is missing, ask only questions that can materially change a decision.
- When principles conflict, prioritize the user's task, accessibility, comprehension, and product truth; record the trade-off.
- When research is uncertain, distinguish established evidence, expert practice, inference, and hypothesis.
- When a trend conflicts with a durable principle, preserve the principle unless context provides a defensible reason not to.
- When review dimensions conflict, return to the intended outcome and Decision Records rather than averaging opinions.
- When a direction cannot be justified, do not hide uncertainty behind visual polish.

## Design Philosophy

The repository extracts transferable principles rather than appearances:

- Apple: focus and disciplined reduction.
- Stripe: clarity for complex products.
- Linear: purposeful density and operational speed.
- Vercel: coherent systems and precise hierarchy.
- Raycast: efficiency and immediate feedback.
- Framer: expressive composition and intentional motion.
- Notion: flexible structure and calm usability.

No brand's layout, typography, components, copy, motion signature, or visual treatment may be reproduced. Inspiration must be translated into an abstract principle, tested against the current product and audience, and documented through reasoning. Brand resemblance is not evidence of quality.

## Quality Gates

Before completing the foundation sprint:

1. Confirm every required file and directory exists and no required directory is empty.
2. Confirm `CONSTITUTION.md` is declared as the highest authority, contains every immutable principle, defines violations, and provides a formal amendment path.
3. Confirm every subordinate document either directly enforces or explicitly inherits constitutional compliance.
4. Validate `SKILL.md` frontmatter, triggering description, imperative language, progressive disclosure, decision ordering, and constitutional gate.
5. Confirm the Knowledge Document Contract appears consistently wherever future knowledge contributions are governed.
6. Confirm the Decision Record structure is exact, usable, and connected to the skill workflow.
7. Confirm all twelve Design Review Framework dimensions and constitutional compliance are required before code acceptance.
8. Scan for placeholders, filler, vague promises, unsupported absolutes, copied brand language, prompt sprawl, generic design prescriptions, and constitutional contradictions.
9. Check internal links, terminology, authority boundaries, ownership boundaries, and cross-document consistency.
10. Confirm the workflow cannot reach code generation before accessibility, performance, Decision Record, synthesis, design review, and constitutional gates.
11. Review the complete diff as a maintainer, improve weak sections, and repeat the checks.
12. Commit only the reviewed foundation; do not extend scope into implementation or later-sprint knowledge.

## Deliberate Exclusions

This sprint does not create components, code generators, framework instructions, design tokens, production assets, finished prompts, landing-page templates, demos, case studies, or detailed knowledge articles. Those additions require separate, evidence-backed future sprints and must strengthen the design operating system rather than turn it into a content warehouse.
