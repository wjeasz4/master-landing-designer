# Templates

## Purpose

`templates/` holds stable structures for reasoning artifacts. Templates make important decisions and reviews comparable without prescribing their content or visual outcome.

A template is useful when structure prevents omission. It is harmful when it turns judgment into form-filling.

## What Belongs Here

- Decision Record structures;
- design direction briefs;
- Design Review Framework reports;
- constitutional compliance reports;
- knowledge document structures;
- evidence and assumption registers; and
- review-to-learning records.

## What Does Not Belong Here

- finished landing pages;
- hero, feature, pricing, or testimonial layouts;
- copy decks intended for reuse across products;
- component boilerplate or framework scaffolding;
- templates that encode a visual trend;
- duplicate formats with superficial differences; or
- fields that collect information without affecting a decision.

## Canonical Decision Record

Every material decision record contains:

1. Context
2. Problem
3. Options Considered
4. Decision
5. Rationale
6. Trade-offs
7. Risks
8. Review Checklist

Templates may add metadata such as owner, date, status, related decisions, and evidence links, but may not remove the canonical fields.

## Template Design Standard

Every template must explain:

- the reasoning failure it prevents;
- when to use it and when not to;
- which fields are required and why;
- how tightly coupled decisions should be grouped;
- how independently changing decisions should be separated;
- what a complete artifact looks like without using filler content; and
- how the artifact enters review and future learning.

## How Codex Should Use This Collection

Select a template only after identifying the reasoning artifact needed. Complete it with product-specific evidence. Remove irrelevant optional fields instead of filling them with vague text.

Do not mistake completion of a template for completion of reasoning. Apply [checklists](../checklists/index.md) and review the underlying decision.

## Contribution Standard

A contribution must:

- comply with the [Repository Constitution](../CONSTITUTION.md);
- prevent a demonstrated omission or inconsistency;
- preserve canonical structures;
- avoid encoding implementation or aesthetic defaults;
- remain concise enough to use reliably; and
- define how it will be validated and retired if it becomes redundant.

## Relationship to the System

Templates structure outputs from the [skill pipeline](../SKILL.md). [Prompts](../prompts/index.md) may elicit missing inputs, and [checklists](../checklists/index.md) verify completed artifacts. Neither should be embedded into a monolithic template.
