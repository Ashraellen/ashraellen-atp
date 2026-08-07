# Validation Model

Validation exists to detect literary drift that fluent target-language prose can conceal. A candidate is not successful merely because it is grammatical, elegant, or semantically approximate; it must remain accountable to source, constraints, continuity, and human authorial intent.

## Validation layers

### V1 — Source integrity
Confirm correct source version and unit boundary, no unauthorized intermediate source, and no omission or duplication.

### V2 — Semantic fidelity
Check omitted meaning, added explanation, changed agency, altered causality or chronology, resolved ambiguity that should remain active, and metaphor replaced by summary.

### V3 — Terminology control
Check locked terms, meaningful capitalization, recurring names and institutional vocabulary, prohibited synonyms, and consistency with prior approved decisions.

### V4 — Voice preservation
Check sentence pressure, rhythm, deliberate roughness, irony, emotional temperature, philosophical density, register, and functional repetition. Fluency is not permission to normalize the text.

### V5 — Dialogue function
Check social position, aggression or restraint, irony, distance, characteristic vocabulary, and whether speakers remain distinguishable.

### V6 — Structural fidelity
Check paragraph boundaries, headings, ordering, intentional white space, fragmentation, and repeated structural devices.

### V7 — Continuity
Check names, terminology, character behavior, motifs, conceptual vocabulary, and previously authorized exceptions against prior state.

### V8 — Authorship continuity
Ask: **Does the target text still appear governed by the same authorial intelligence as the source?**

## Outcome states

- `PASS`
- `PASS_WITH_RECORDED_EXCEPTION`
- `REVISE`
- `REVIEW_REQUIRED`
- `BLOCKED`
- `REJECTED`

## Practical order

Source integrity → semantic fidelity → terminology → voice/dialogue → structure → continuity → authorship continuity → human decision.

## Local and corpus validation

Validation should occur at unit, chapter, part/block, whole-work, and where relevant series scale.

## Human veto

No checklist, automated metric, model confidence, or majority of AI-generated alternatives can overrule the human authority layer.
