# Ashraellen Transcreation Protocol — Method Statement

## Definition

The Ashraellen Transcreation Protocol is a human-directed workflow for AI-assisted literary transcreation of long-form texts across languages while preserving controlled aspects of authorial identity that ordinary translation pipelines frequently flatten or drift away from.

The protocol treats literary transfer not as sentence-by-sentence substitution, but as constrained reconstruction under explicit authorial control.

## Problem

Long-form literary translation with AI tends to fail in recurring ways even when individual sentences appear fluent:

- authorial voice becomes more generic;
- recurring terminology drifts;
- dialogue loses character-specific temperature and function;
- local improvements damage global continuity;
- chapter structure or paragraph pressure changes unintentionally;
- metaphor is replaced by explanation;
- ambiguity is resolved when it should remain active;
- stylistic roughness is polished away despite being intentional;
- named concepts are translated inconsistently across a book or series;
- context is lost between sessions, tools, or production stages.

The protocol addresses these failures by making constraints, continuity, validation, and human approval first-class parts of the workflow.

## Core model

1. **Authorial source** — the literary work and its intentional structures.
2. **Constraint layer** — glossary, naming rules, voice rules, structural rules, prohibited simplifications, and project-specific decisions.
3. **AI-assisted transformation** — generation, comparison, or analysis performed under the constraint layer.
4. **Validation layer** — checks for semantic fidelity, voice, terminology, structure, dialogue function, continuity, and known failure modes.
5. **Human authority** — rejection, correction, interpretation, exception handling, and final approval remain with the author or designated human editor.

## Transcreation rather than generic translation

In this protocol, *transcreation* means transferring the functional literary effect of the source into another language while preserving explicit constraints and accepting that literal equivalence may be inferior to functional equivalence.

This does not authorize free rewriting. Any departure from literal wording must remain accountable to the source, the declared constraints, and the intended literary function.

## Human–AI boundary

AI is used as an assisted reasoning and production layer. It does not define the work's canon, authorial intent, or final accepted wording autonomously.

The human operator defines or approves source canon, naming and terminology decisions, interpretation of ambiguity, acceptable stylistic deviation, structural exceptions, and final literary text.

AI may assist with candidate transcreation, consistency checks, glossary-aware comparison, alternative phrasings, detection of drift or mismatch, and continuity reconstruction from authorized project state.

## Reproducibility principle

A literary result is not reproducible merely because the same model and prompt can be run twice. The protocol records the state required to understand why a result was accepted: governing constraints, terminology state, relevant continuity decisions, source segment identity, validation criteria, and final human decisions where choices are non-obvious.

Reproducibility means that another qualified operator can reconstruct the decision process and apply the same method coherently, not that stochastic model output must be byte-identical.

## Scope

The protocol is intended primarily for novels and literary series, philosophically dense prose, recurring fictional terminology, character-specific dialogue systems, multilingual editions requiring continuity across many chapters, and projects produced over multiple AI sessions or model contexts.

## Non-goals

The protocol is not autonomous AI authorship, a universal machine-translation benchmark, a guarantee that AI-generated language is correct without review, a prompt collection presented as methodology, a license to rewrite an author's work for fluency, or a substitute for copyright, editorial, or language expertise.

## Evidence model

The methodology was developed through sustained multilingual literary production rather than as a purely theoretical framework. MONOLITH may be referenced as an applied production environment while its manuscripts and private operational archive remain outside this public repository.
