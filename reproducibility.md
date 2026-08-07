# Reproducibility Model

Reproducibility in literary transcreation does not mean reproducing identical stochastic model output. It means preserving enough authorized state that another qualified operator can reconstruct why a literary decision was accepted and continue the work coherently.

## Minimum record

Where relevant, preserve:

- stable source identity;
- source version or content hash;
- target language and target unit identity;
- governing constraints;
- terminology state;
- continuity state;
- model/tool role where material;
- validation result;
- human decision;
- recorded exception or new rule;
- final accepted target identity.

## What must be reproducible

The decision environment, source-to-target relationship, applied constraints, validation logic, authority chain, and resulting state change.

## What need not be reproducible

Byte-identical AI output, every discarded candidate, private chats or full prompts, dependence on one model vendor, or unpublished literary material outside an authorized example boundary.

## Model independence

Durable project state should live outside a single model conversation so the workflow can survive a new chat, different model, different operator, long interruption, or migration to another tool.

## Decision provenance

For non-obvious choices that affect future work, record the source problem, constraints that mattered, relevant rejected alternatives, human approval, and whether the choice created a future rule.

## State integrity

Useful labels include `DRAFT`, `ACTIVE`, `LOCKED`, `SUPERSEDED`, `FINAL`, `BLOCKED`, and `AUTHOR_REVIEW_REQUIRED`, provided their semantics are documented.

**The durable object is not the prompt. The durable object is the authorized decision system around the work.**
