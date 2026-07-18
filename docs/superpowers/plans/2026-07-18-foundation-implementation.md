# Design Intelligence Foundation Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build the complete production-grade foundation for `master-landing-designer` as a constitutional Design Intelligence operating system for Codex.

**Architecture:** Place `CONSTITUTION.md` at the top of the authority hierarchy, keep `SKILL.md` as a compact decision orchestrator, and use repository collections as progressively disclosed intelligence layers. Encode important choices through Decision Records and evaluate future landing pages through a twelve-dimension Design Review Framework before code generation.

**Tech Stack:** Markdown, YAML frontmatter, Git, PowerShell-based structural validation, Codex skill validation.

## Global Constraints

- Implement foundation documentation only; do not add components, demos, design tokens, code generators, production assets, detailed knowledge articles, or framework guidance.
- Treat `CONSTITUTION.md` as the highest repository authority.
- Require reasoning before implementation, principles over trends, evidence over opinion, originality over imitation, and systems over isolated components.
- Treat accessibility as mandatory and performance as a feature.
- Require every recommendation to explain why and every pattern to document trade-offs.
- Require every future knowledge document to answer the complete eight-part Knowledge Document Contract.
- Require material design choices to use the complete eight-part Decision Record format.
- Require every future landing page to pass the twelve-dimension Design Review Framework and constitutional compliance gate.
- Keep `prompts/` limited to diagnostic inquiry protocols; do not establish a prompt collection.
- Use imperative language in `SKILL.md` and only `name` and `description` in its YAML frontmatter.
- Do not leave required directories empty or use placeholder/filler documentation.
- Extract transferable principles from Apple, Stripe, Linear, Vercel, Raycast, Framer, and Notion without copying their expression.

---

### Task 1: Establish constitutional governance

**Files:**

- Create: `CONSTITUTION.md`
- Create: `AGENTS.md`
- Create: `CONTRIBUTING.md`
- Create: `CHANGELOG.md`
- Create: `LICENSE`
- Create: `.gitignore`

**Interfaces:**

- Consumes: authority hierarchy and constitutional requirements from `docs/superpowers/specs/2026-07-18-foundation-design.md`.
- Produces: root governance rules that `SKILL.md`, `README.md`, and every collection index must inherit.

- [x] **Step 1: Write `CONSTITUTION.md`**

Include purpose, authority order, all eleven immutable principles, constitutional violations, blocking enforcement, and the formal amendment process. State that ordinary contributions cannot override the Constitution and that constitutional violations cannot be accepted as residual risk.

- [x] **Step 2: Write `AGENTS.md`**

Translate the Constitution into operational instructions for Codex: inspect context, reason from evidence, record material decisions, avoid generic AI aesthetics, review the whole system, learn from review findings, and stop on constitutional violations.

- [x] **Step 3: Write open-source governance files**

Create a professional contribution workflow with evidence and review requirements, a `v0.1.0` changelog entry dated 2026-07-18, the MIT license for 2026 and copyright holder `wjeasz4`, and a `.gitignore` covering operating-system, editor, environment, dependency, build, cache, log, and Codex workspace artifacts.

- [x] **Step 4: Verify constitutional coverage**

Run:

```powershell
rg -n "Reason before implementation|Principles over trends|Evidence over opinion|Originality over imitation|Systems over isolated components|Accessibility is mandatory|Performance is a feature|Every recommendation must explain why|Every pattern must document trade-offs|Every review finding must improve future decisions|living knowledge system" CONSTITUTION.md
```

Expected: all eleven principles appear exactly once as constitutional headings or list items.

---

### Task 2: Build the Codex decision engine

**Files:**

- Create: `SKILL.md`

**Interfaces:**

- Consumes: `CONSTITUTION.md` and the approved Design Intelligence architecture.
- Produces: the complete pre-code decision pipeline, Decision Record protocol, Design Review Framework, and constitutional gate.

- [x] **Step 1: Write valid skill metadata**

Use exactly this frontmatter shape:

```yaml
---
name: master-landing-designer
description: A constitutional Design Intelligence system for reasoning about, directing, and reviewing premium landing pages before implementation. Use when Codex must design, redesign, plan, critique, or generate a landing page and needs product-aware decisions for visual language, typography, spacing, color, hierarchy, layout, interaction, motion, accessibility, performance, conversion, originality, and brand consistency.
---
```

- [x] **Step 2: Encode the operating sequence**

Require Codex to load the Constitution, understand product and audience, determine emotional tone and visual language, choose typography, spacing, color, hierarchy, layout, interaction, motion, accessibility, and performance, capture material choices, synthesize the system, run both reviews, and only then generate code.

- [x] **Step 3: Encode reasoning artifacts and gates**

Include the eight Decision Record fields, all twelve Design Review Framework dimensions, four review outcomes, uncertainty handling, constitutional blocking behavior, and selective loading guidance for every collection.

- [x] **Step 4: Validate the skill**

Run:

```powershell
$validatorPython = 'C:\Users\Akın\.cache\codex-runtimes\codex-primary-runtime\dependencies\python\python.exe'
$validatorDeps = 'work\validator-deps'
& $validatorPython -m pip install --target $validatorDeps PyYAML
$env:PYTHONPATH = (Resolve-Path $validatorDeps).Path
$env:PYTHONUTF8 = '1'
& $validatorPython 'C:\Users\Akın\.codex\skills\.system\skill-creator\scripts\quick_validate.py' .
```

Expected: `Skill is valid!`. The dependency remains inside the ignored local `work/` directory. Also inspect the frontmatter directly and confirm it contains only `name` and `description`.

---

### Task 3: Define the public project contract

**Files:**

- Create: `README.md`

**Interfaces:**

- Consumes: `CONSTITUTION.md`, `SKILL.md`, and the approved architecture.
- Produces: the public explanation of vision, mission, goals, architecture, roadmap, installation, usage, philosophy, contributing, and license.

- [x] **Step 1: Write the README narrative**

Lead with the distinction between a design operating system and a prompt or template collection. Explain Design Intelligence, the constitutional authority hierarchy, progressive disclosure, Decision Records, and the review feedback loop.

- [x] **Step 2: Complete required user guidance**

Provide concrete installation instructions for cloning or copying the repository into a Codex skills directory, a usage workflow that begins with product evidence, a foundation-only roadmap, and links to all root governance files and collection indexes.

- [x] **Step 3: Verify required sections**

Run:

```powershell
rg -n "^## (Vision|Mission|Goals|Repository Architecture|Roadmap|Installation|Usage|Design Philosophy|Contributing|License)$" README.md
```

Expected: all ten required README sections are present.

---

### Task 4: Establish intelligence collection contracts

**Files:**

- Create: `knowledge/index.md`
- Create: `patterns/index.md`
- Create: `examples/index.md`
- Create: `prompts/index.md`
- Create: `templates/index.md`
- Create: `checklists/index.md`
- Create: `assets/index.md`
- Create: `references/index.md`

**Interfaces:**

- Consumes: the Constitution, Knowledge Document Contract, Decision Record format, and Design Review Framework.
- Produces: non-empty, non-overlapping collection boundaries for future work.

- [x] **Step 1: Create all eight collection directories and indexes**

Each index must explain purpose, what belongs, what does not belong, how Codex should use the collection, contribution requirements, and its relationship to the wider decision system.

- [x] **Step 2: Apply collection-specific safeguards**

Require the eight-part Knowledge Document Contract in `knowledge/`; contextual forces and trade-offs in `patterns/`; annotated reasoning rather than copy-ready designs in `examples/`; diagnostic protocols rather than prompt accumulation in `prompts/`; reasoning-artifact structures rather than finished pages in `templates/`; verification after reasoning in `checklists/`; provenance, licensing, accessibility, and optimization in `assets/`; and source quality plus claim traceability in `references/`.

- [x] **Step 3: Verify directory completeness**

Run:

```powershell
$requiredCollections = @('knowledge','patterns','examples','prompts','templates','checklists','assets','references')
$missingIndexes = $requiredCollections | Where-Object { -not (Test-Path "$($_)\index.md") }
if ($missingIndexes.Count -gt 0) { throw "Missing indexes: $($missingIndexes -join ', ')" }
```

Expected: no exception and every collection contains a substantive `index.md`.

---

### Task 5: Perform repository-wide review and release

**Files:**

- Modify: any foundation file that fails review.

**Interfaces:**

- Consumes: all completed foundation documents.
- Produces: a coherent, validated `v0.1.0` foundation committed and published to `wjeasz4/master-landing-designer`.

- [x] **Step 1: Run structural and unfinished-content checks**

Verify every required path, scan for empty Markdown files, and reject unfinished markers, filler language, prompt sprawl, and generic AI recommendations.

- [x] **Step 2: Run cross-document contract checks**

Confirm constitutional authority, all eight Knowledge Document Contract questions, all eight Decision Record fields, all twelve review dimensions, the eighteen-stage skill pipeline, and the code-generation gate are consistent across the repository.

- [x] **Step 3: Review links, whitespace, and Git scope**

Run `git diff --check`, validate every relative Markdown link, inspect `git diff --stat`, and confirm local `outputs/`, `work/`, secrets, caches, and build artifacts are excluded.

- [x] **Step 4: Conduct maintainer self-review**

Read every changed file as a system. Improve vague, repetitive, contradictory, or generic sections. Confirm each file has one clear responsibility and that no future-sprint payload was introduced.

- [ ] **Step 5: Commit and publish**

Commit the reviewed foundation with:

```text
feat: establish constitutional design intelligence foundation
```

Publish the complete `main` history to `https://github.com/wjeasz4/master-landing-designer` and verify the remote head and repository file tree.
