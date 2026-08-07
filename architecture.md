# Architecture Model

ATP is a closed human-directed control loop rather than a one-pass translation pipeline.

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

## 1. Authorial source

The source layer identifies the literary authority from which a target-language unit may be derived. It requires explicit source language and version, stable unit identity, clear canonical status, and no silent use of an intermediate translation unless explicitly authorized.

A fluent target derived from the wrong source is still a protocol failure.

## 2. Constraint state

Constraint state externalizes decisions that must survive beyond one prompt, session, model, or operator: terminology and naming decisions, character voice rules, structural rules, prohibited transformations, approved headings, semantic invariants, accepted exceptions, workflow status, and identifiers for prior approved units.

Constraint state is not canon by itself. It is a durable representation of previously authorized human decisions.

## 3. AI-assisted transformation

AI operates only after source and constraints are known. Permitted functions may include candidate transcreation, alternative formulation, contrastive comparison, terminology-aware generation, continuity analysis, and detection of likely semantic or stylistic drift.

AI output is provisional until it crosses the human decision gate.

## 4. Validation

Validation compares a candidate not merely with local grammar but with the full control state: semantic fidelity, literary function, authorial voice, terminology consistency, dialogue, structure, ambiguity, continuity, prohibited smoothing or explanation, and source/target version integrity.

No automated score overrides an authorial rejection.

## 5. Human decision gate

The human authority layer may accept, reject, revise, request alternatives, authorize an exception, change a governing rule, or defer the unit. Only an accepted decision may update canonical project state.

## 6. Updated authorized state

After approval, future work inherits relevant decisions. An accepted unit can update glossary entries, character rules, structural decisions, continuity notes, unit status, validation history, and exception records.

## State separation

ATP distinguishes source state, decision state, workflow state, and publication state. Conflating them creates false finality and accidental publication.

## Atomic unit principle

Large works should be processed in stable addressable units small enough to validate and large enough to preserve literary function. Each unit should have source identity, target identity, status, applicable constraints, validation outcome, and human acceptance state.

## Long-range audits

Local PASS does not imply corpus PASS. ATP supports chapter, block/part, inter-block, whole-work, and where relevant series-level audits.

## Failure containment

If source authority, constraint state, or continuity cannot be reconstructed reliably, production should stop rather than improvise missing canon.

**Complexity may be delegated. Canonical authority may not.**
