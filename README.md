# Ashraellen Transcreation Protocol (ATP)

**A human-directed protocol for AI-assisted literary transcreation.**

The Ashraellen Transcreation Protocol is a reproducible workflow for moving long-form literary works across languages while preserving authorial voice, terminology, structure, dialogue function, continuity, ambiguity, and semantic pressure.

> **Success is measured by how well the system prevents the human from losing themselves.**

The protocol does not treat removal of the author as progress. It uses AI to absorb coordination burden, comparison work, continuity checking, and linguistic search while keeping canonical authority with the human author or designated editor.

## Why this exists

Fluent AI translation can still fail literary work through voice flattening, terminology drift, dialogue convergence, unwanted explanation, polishing away intentional roughness, local improvements that damage long-range continuity, and context loss between sessions or tools.

ATP treats these not as edge cases but as system-design problems.

## Core architecture

```text
AUTHORIAL SOURCE
      ↓
CONSTRAINT STATE
      ↓
AI-ASSISTED TRANSFORMATION
      ↓
VALIDATION
      ↓
HUMAN DECISION
      ↓
UPDATED AUTHORIZED STATE
      ↺
```

**Complexity may be delegated. Canonical authority may not.**

## Human–AI boundary

AI may assist with candidate generation, alternatives, comparison, continuity reconstruction, terminology checks, and detection of semantic or stylistic drift.

The human authority layer remains responsible for canon, meaning, ambiguity, voice, terminology, exceptions, and final publication approval.

**Human-authored. Human-directed. AI-assisted. State-controlled. Canonically approved.**

## Reproducibility

Reproducibility does not mean forcing a stochastic model to produce identical wording twice. It means preserving enough authorized state that another qualified operator can reconstruct the decision environment and continue the work coherently.

**The durable object is not the prompt. The durable object is the authorized decision system around the work.**

## Repository map

- [`docs/methodology.md`](docs/methodology.md) — definition, scope, and core method
- [`docs/human-ai-boundary.md`](docs/human-ai-boundary.md) — responsibility and authority model
- [`docs/architecture.md`](docs/architecture.md) — end-to-end control loop
- [`docs/validation.md`](docs/validation.md) — validation layers and outcome states
- [`docs/reproducibility.md`](docs/reproducibility.md) — durable state and decision provenance
- [`protocol/`](protocol/) — reusable public templates
- [`examples/synthetic-demonstrator.md`](examples/synthetic-demonstrator.md) — rights-safe worked example
- [`examples/monolith-case-study-framework.md`](examples/monolith-case-study-framework.md) — framework for a future bounded literary case study
- [`research/limitations.md`](research/limitations.md) — known limitations and failure modes

## Applied evidence

The methodology was developed through sustained multilingual literary production in **MONOLITH**, a long-form literary trilogy by Ashraellen. MONOLITH is referenced as an applied production environment, not released as open-source literary content.

The first public release deliberately uses a synthetic demonstrator. A real literary excerpt may be added later only after a separate explicit publication decision.

## What this is not

This is not autonomous AI authorship, one-click book translation, a style-cloning toolkit, a generic prompt collection, a claim that AI output is correct without human review, or permission to rewrite an author's work merely for fluency.

## Who this may be useful for

Authors producing multilingual editions, literary translators using AI assistance, editors managing long-form continuity, digital-humanities researchers, multilingual publishing teams, and researchers studying human–AI creative collaboration.

## Citation

Citation metadata is provided in [`CITATION.cff`](CITATION.cff). GitHub should expose a **Cite this repository** action after the file is published.

Repository: https://github.com/Ashraellen/ashraellen-atp

## Rights

Unless otherwise stated, methodology, documentation, and public templates are licensed under **CC BY 4.0**. MONOLITH and all literary works by Ashraellen remain separately copyrighted and are not covered by this license.

See [`LICENSE`](LICENSE).

## Version

**v1.0.0 — 2026-08-07.**
