# Diagnostic Inquiry Protocols

## Purpose

`prompts/` contains a deliberately small set of inquiry and review protocols that help Codex obtain missing evidence or examine a completed decision. The directory name reflects the repository structure; the collection is not a prompt library and has no growth target.

The value of a protocol is the quality of the decision it enables, not how reusable its wording appears.

## What Belongs Here

- focused product-understanding inquiries;
- audience-evidence inquiries;
- protocols for exposing assumptions or conflicting constraints;
- structured Decision Record review questions;
- Design Review Framework protocols; and
- constitutional compliance inquiries.

## What Does Not Belong Here

- “ultimate” or one-shot prompts;
- prompts that generate complete landing pages without reasoning;
- style prompts that imitate brands or trends;
- large role-playing preambles;
- minor wording variants;
- prompts whose output cannot change a material decision; or
- prompt-engineering tricks unrelated to Design Intelligence.

## Protocol Standard

Every protocol must state:

1. the decision or evidence gap it addresses;
2. when to use it;
3. when not to use it;
4. required inputs;
5. the expected reasoning artifact;
6. how the output affects a decision or review;
7. failure modes and leading-question risks; and
8. retirement or consolidation criteria.

Use the fewest questions needed to surface information that could materially change the direction. Do not burden users with questions whose answers will not affect a decision.

## How Codex Should Use This Collection

Load a protocol only after identifying a specific evidence gap or review need. Adapt wording to the user's context without changing the protocol's purpose. Ask one focused question at a time when possible.

Never use a protocol to bypass the [decision pipeline](../SKILL.md), manufacture certainty, or convert weak inputs into premature code.

## Contribution Standard

A contribution must:

- comply with the [Repository Constitution](../CONSTITUTION.md);
- solve a recurring diagnostic or review problem;
- demonstrate that its output changes decision quality;
- avoid overlap with an existing protocol;
- document bias, burden, and failure risks; and
- remain shorter than the reasoning it enables.

## Relationship to the System

Protocols obtain or test evidence. [Knowledge](../knowledge/index.md) explains principles, [patterns](../patterns/index.md) frame options, and [templates](../templates/index.md) structure outputs. Protocols do not replace any of them.
