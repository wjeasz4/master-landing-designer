# Master Landing Designer

Master Landing Designer is a constitutional Design Intelligence system for Codex. It helps an agent understand a product, reason about its audience, make coherent landing-page decisions, record why those decisions were made, and review the complete direction before generating code.

It is not a prompt collection, component library, template gallery, or shortcut to a fashionable aesthetic. It is an operating system for design judgment.

## Vision

Enable Codex to create landing pages whose quality comes from disciplined reasoning rather than visual imitation.

Premium landing pages work because their decisions reinforce one another: the promise is clear, attention follows meaning, typography carries voice, spacing reveals relationships, color communicates roles, motion has purpose, interaction earns trust, and accessibility and performance remain part of the design. This repository exists to make that reasoning explicit, reusable, and reviewable.

## Mission

Build a living knowledge system that teaches why design principles exist, when they apply, when they fail, what they cost, how they affect people, and how experts decide among valid alternatives.

The system converts product and audience evidence into:

1. product-specific design direction;
2. documented material decisions;
3. a coherent visual and behavioral system;
4. structured accessibility and performance strategies;
5. repository-wide design review; and
6. implementation constraints that code can trace back to approved reasoning.

## Goals

- Put reasoning before implementation.
- Develop durable Design Intelligence rather than collect recipes.
- Make evidence strength, assumptions, trade-offs, and risks visible.
- Produce original directions grounded in product truth and audience needs.
- Treat typography, spacing, color, hierarchy, composition, interaction, and motion as one system.
- Treat accessibility as mandatory and performance as a feature.
- Record important choices in a consistent Decision Record format.
- Review every direction across visual, human, technical, brand, and conversion dimensions.
- Turn recurring review findings into better future decisions.
- Preserve a foundation that future knowledge can extend without contradiction or context bloat.

## Repository Architecture

The repository follows an authority hierarchy and a progressive-disclosure model.

```text
master-landing-designer/
├── CONSTITUTION.md       # Highest authority and immutable principles
├── SKILL.md              # Codex decision pipeline and code-generation gate
├── AGENTS.md             # Repository-wide agent behavior
├── README.md             # Human entry point
├── CONTRIBUTING.md       # Evidence and review requirements
├── CHANGELOG.md          # Version history
├── LICENSE               # MIT license
├── knowledge/            # Durable principles and conceptual models
├── patterns/             # Contextual decision patterns
├── examples/             # Annotated reasoning traces
├── prompts/              # Limited diagnostic inquiry protocols
├── templates/            # Structures for reasoning artifacts
├── checklists/           # Post-reasoning verification instruments
├── assets/               # Governed source materials for future outputs
├── references/           # Standards, research, citations, and provenance
└── docs/superpowers/     # Approved architecture and implementation records
```

### Authority hierarchy

1. [Repository Constitution](CONSTITUTION.md)
2. [Skill protocol](SKILL.md) and [global agent instructions](AGENTS.md)
3. repository governance documents
4. collection indexes
5. individual knowledge artifacts

Higher authority wins when guidance conflicts. Constitutional compliance is a blocking gate.

### Design Intelligence loop

The system follows a closed reasoning loop:

```text
Product and audience evidence
        ↓
Relevant principles and contextual patterns
        ↓
Options, decisions, rationale, trade-offs, and risks
        ↓
System synthesis
        ↓
Design Review Framework + constitutional review
        ↓
Approved implementation constraints
        ↓
Review findings improve future decisions
```

### Knowledge Document Contract

Every future knowledge document must explain:

- why the principle exists;
- when to use it;
- when not to use it;
- trade-offs;
- psychological effect;
- common beginner mistakes;
- expert observations; and
- decision heuristics.

This contract prevents the repository from becoming a warehouse of unexplained advice.

### Decision Records

Material choices use one structure:

1. Context
2. Problem
3. Options Considered
4. Decision
5. Rationale
6. Trade-offs
7. Risks
8. Review Checklist

Decision Records preserve judgment. They allow a reviewer to challenge the reasoning, trace implementation back to intent, and revise knowledge when evidence changes.

### Design Review Framework

Every future landing page is reviewed through:

- visual hierarchy;
- typography;
- spacing;
- color;
- contrast;
- composition;
- motion;
- accessibility;
- performance;
- conversion;
- originality; and
- brand consistency.

Findings are classified as `Pass`, `Refine`, `Reconsider`, or `Blocked` and must identify the underlying decision to revisit.

## Roadmap

### v0.1 — Constitutional foundation

- Establish the Repository Constitution.
- Define Design Intelligence, Decision Records, and the Design Review Framework.
- Create the complete pre-code skill workflow.
- Establish collection contracts and open-source governance.

### Future knowledge development

Future releases may add evidence-backed principles, contextual patterns, annotated reasoning traces, review instruments, and governed assets. Each addition must satisfy the Constitution and its collection contract. The roadmap intentionally does not prescribe implementation features before their reasoning and evidence exist.

### Future validation maturity

The system may later gain automated contract checks, structured knowledge audits, and forward-testing against realistic design tasks. Automation will verify reasoning discipline; it will not replace judgment.

## Installation

Clone the repository into the directory where Codex discovers personal skills.

### macOS or Linux

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
git clone https://github.com/wjeasz4/master-landing-designer.git \
  "${CODEX_HOME:-$HOME/.codex}/skills/master-landing-designer"
```

### Windows PowerShell

```powershell
$skillsRoot = if ($env:CODEX_HOME) { Join-Path $env:CODEX_HOME 'skills' } else { Join-Path $env:USERPROFILE '.codex\skills' }
New-Item -ItemType Directory -Path $skillsRoot -Force | Out-Null
git clone https://github.com/wjeasz4/master-landing-designer.git (Join-Path $skillsRoot 'master-landing-designer')
```

Restart or reload Codex if the environment does not discover newly installed skills immediately.

To update an existing installation:

```bash
git -C "${CODEX_HOME:-$HOME/.codex}/skills/master-landing-designer" pull --ff-only
```

## Usage

Invoke the skill when designing, redesigning, planning, critiquing, or implementing a landing page.

Provide the strongest available product context:

- what the product is and the value it can credibly claim;
- who the page is for and what situation brings them there;
- the desired conversion outcome;
- brand attributes and existing constraints;
- content, research, analytics, or user evidence;
- technical, accessibility, legal, or performance constraints; and
- what is already decided versus still open.

An illustrative request can be concise:

```text
Use master-landing-designer to define and review the landing-page direction for this product. Do not generate code until the decision package and review gates pass.
```

Codex should then:

1. load the Constitution;
2. fill material evidence gaps;
3. complete the design decision pipeline;
4. present Decision Records and the coordinated direction;
5. run design and constitutional reviews;
6. expose unresolved risks; and
7. generate code only after the gates pass.

The output should explain why the direction fits the product. If it could be transferred unchanged to an unrelated product, it is not specific enough.

## Design Philosophy

Reasoning outlives recipes. Principles outlive trends.

The repository is inspired by the discipline of products such as Apple, Stripe, Linear, Vercel, Raycast, Framer, and Notion, but it does not reproduce them. It extracts transferable principles:

- focus and disciplined reduction;
- clarity for complex products;
- purposeful density and operational speed;
- coherent systems and precise hierarchy;
- efficiency and immediate feedback;
- expressive composition and intentional motion; and
- flexible structure with calm usability.

These principles are inputs to judgment, not a combined visual style. Brand resemblance is not evidence of quality.

Premium does not mean more animation, larger type, darker surfaces, softer gradients, or extra decoration. It means the experience makes deliberate promises and keeps them: perceptually, emotionally, technically, and ethically.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing changes. Contributions must comply with the [Repository Constitution](CONSTITUTION.md), satisfy the owning collection's contract, distinguish evidence from inference, and improve reusable Design Intelligence.

The repository values focused corrections and well-supported disagreement. Review the rationale, not just the output.

## License

Master Landing Designer is available under the [MIT License](LICENSE).
