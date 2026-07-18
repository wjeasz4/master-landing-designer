# Contributing to Master Landing Designer

Thank you for helping build a rigorous design operating system for Codex. Contributions should strengthen judgment, not increase document count.

## Before You Contribute

Read these documents in order:

1. [Repository Constitution](CONSTITUTION.md)
2. [Skill operating protocol](SKILL.md)
3. [Global agent instructions](AGENTS.md)
4. the `index.md` for the collection you plan to change

The Constitution is the highest authority. A contribution that conflicts with it cannot be merged through an exception in a lower-level document.

## Suitable Contributions

Good contributions may:

- clarify a durable design principle;
- add evidence-backed decision guidance;
- document a contextual pattern and its trade-offs;
- contribute an annotated reasoning example;
- improve a Decision Record or review instrument;
- add a reliable reference with clear provenance;
- correct contradictory, stale, inaccessible, or unsupported guidance; or
- turn repeated review findings into reusable knowledge.

The repository is not seeking generic prompt collections, copied interfaces, trend summaries without analysis, finished landing-page templates, or unsupported taste advice.

## Knowledge Quality Standard

Every durable knowledge document must answer:

1. Why does this principle exist?
2. When should it be used?
3. When should it not be used?
4. What are the trade-offs?
5. What psychological effect is expected, and how strong is the evidence?
6. What mistakes do beginners commonly make?
7. What do experienced practitioners notice?
8. Which conditional heuristics support a decision?

Label research, standards, observed behavior, expert practice, inference, and hypothesis accurately. Cite primary or authoritative sources where possible. Avoid universal claims unless the evidence justifies them.

## Proposing a Change

Open an issue before substantial or governance-changing work. Explain:

- the problem and who it affects;
- the relevant constitutional principles;
- the evidence or repeated review finding motivating the change;
- the collection that owns the knowledge;
- alternatives considered;
- expected trade-offs and risks; and
- how success will be reviewed.

Small corrections with no change in meaning may proceed directly to a pull request.

## Branches and Commits

- Create a focused branch from the current default branch.
- Keep unrelated changes separate.
- Use imperative, descriptive commit messages.
- Do not rewrite published history shared by other contributors.

Example commit messages:

```text
docs: clarify evidence levels for design principles
feat: add decision record review template
fix: resolve conflicting motion guidance
```

## Pull Requests

A pull request should include:

- a concise statement of the change and why it matters;
- links to supporting issues, research, standards, or review findings;
- affected constitutional principles and collection contracts;
- trade-offs, risks, and known limitations;
- validation performed; and
- screenshots or artifacts only when they help reviewers evaluate meaning.

Keep the change reviewable. Large knowledge additions should be separated by independently assessable responsibility rather than arbitrary file count.

## Review Criteria

Reviewers assess whether the contribution:

- complies with the Constitution;
- improves reusable Design Intelligence;
- explains why instead of prescribing a recipe;
- distinguishes evidence from opinion;
- documents context, contraindications, and trade-offs;
- avoids imitation and generic AI design language;
- preserves accessibility and performance requirements;
- fits one clear repository location without duplication;
- remains concise enough for progressive disclosure; and
- provides observable checks for its claims.

A constitutional violation blocks approval. Ordinary weaknesses may be marked `Refine` or `Reconsider` with the underlying decision identified.

## Validation

Before requesting review:

1. Read every changed file in full.
2. Confirm required headings and repository contracts are present.
3. Check internal links and cited sources.
4. Scan for unfinished text, filler, unsupported absolutes, and contradictory guidance.
5. Run the Codex skill validator when `SKILL.md` changes.
6. Run `git diff --check`.
7. Confirm no secrets, generated output, dependency folders, or local workspace artifacts are included.

Document the checks and their results in the pull request.

## Constitutional Amendments

Do not change constitutional principles through an ordinary documentation pull request. Follow the amendment process in [CONSTITUTION.md](CONSTITUTION.md), including a dedicated Decision Record, impact analysis, maintainer approval, changelog entry, and migration plan.

## Conduct

Critique decisions and evidence, not people. Be specific, charitable, and open to correction. Good review makes both the current artifact and the future decision system stronger.
