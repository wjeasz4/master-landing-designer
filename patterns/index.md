# Patterns

## Purpose

`patterns/` holds reusable decision models for recurring landing-page problems. A pattern describes a tension, the forces that shape it, viable responses, and how context changes the choice.

Patterns are not components, layouts, recipes, or guarantees. They help Codex compare options without erasing product specificity.

## What Belongs Here

- recurring design problems with recognizable contextual forces;
- multiple valid approaches and their selection criteria;
- interactions between hierarchy, content, composition, conversion, accessibility, and performance;
- failure modes and contraindications;
- conditional decision heuristics; and
- review signals that reveal whether a chosen pattern is working.

## What Does Not Belong Here

- copy-ready sections or page templates;
- prescriptions such as “always use” or “never use” without constitutional cause;
- framework-specific component code;
- visual trends treated as reusable solutions;
- a single product's distinctive composition;
- patterns without trade-offs; or
- names that disguise a vague aesthetic preference as a system.

## Required Pattern Structure

Every pattern should include:

1. **Problem:** the recurring decision and why it matters.
2. **Context:** audience, journey, content, brand, device, and constraint conditions.
3. **Forces:** competing needs that make the decision non-trivial.
4. **Options:** credible approaches and the contexts that support each.
5. **Decision heuristics:** conditional guidance for selecting among options.
6. **Trade-offs:** gains, costs, and second-order effects.
7. **Contraindications:** when the pattern should not be used.
8. **Failure modes:** superficial or harmful applications.
9. **Accessibility and performance impact:** requirements and risks.
10. **Review signals:** observable evidence that should produce `Pass`, `Refine`, `Reconsider`, or `Blocked`.

The underlying principles must satisfy the [Knowledge Document Contract](../knowledge/index.md), either within the pattern or through direct links.

## How Codex Should Use This Collection

Load a pattern after product and audience understanding identifies a recurring problem. Compare its forces with the current context. Use its options to improve a Decision Record, not to skip one.

If a pattern's assumptions do not match the current product, do not adapt it through cosmetic changes. Choose another approach or reason from principles.

## Contribution Standard

A contribution must:

- comply with the [Repository Constitution](../CONSTITUTION.md);
- demonstrate recurrence across more than one product context;
- explain why the pattern exists;
- document trade-offs, contraindications, and failure modes;
- include accessibility, performance, and system-level consequences;
- avoid resembling a copied product signature; and
- link to supporting [knowledge](../knowledge/index.md) and [references](../references/index.md).

## Relationship to the System

Patterns translate durable knowledge into contextual option sets. [Examples](../examples/index.md) can show a pattern being chosen or rejected. [Templates](../templates/index.md) structure the resulting decision. [Checklists](../checklists/index.md) verify the outcome after reasoning.
