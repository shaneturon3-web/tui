---
name: literary-mechanism-workbench
description: Route a request to evidence analysis, narrative-mechanism extraction, reusable-skill extraction, or literary creation/transformation while preserving provenance and conditionality.
---


## v0.3 runtime contract

For v0.3.0, `CORE_CONTRACT_V3.md` is mandatory and forms part of the
executable contract. Read it before any literary operation.

Expanded files under `../../references/` are secondary documentation. Attempt to open them and
report `FULL` or `CORE-ONLY`, but failure to resolve an expanded reference must not erase the
embedded core.

Do not begin literary prose before the source-operation preflight passes.

# Literary Mechanism Workbench

Use this as the entry point when a request spans literary evidence, mechanism discovery, skill manufacture, or creating/editing a piece. It coordinates modes; it does not collapse their outputs into one workflow.

Read `../../references/evidence-schema.md`, `../../references/jurisdiction-gate.md`, and `../../references/promotion-and-validation.md` before substantive work.

## Route

- **Analyze a book, corpus, or session** → `analyze-literary-evidence`.
- **Find story-producing mechanisms** → `extract-literary-mechanisms` after evidence analysis has defined the source boundary.
- **Turn observed behavior into a skill** → `extract-reusable-skills`; do not infer a skill from a memorable mechanism name.
- **Write or transform a literary piece** → `create-transform-literary`; use only the relevant mechanism and preserve the user's requested output form.
- **Mixed task** → run the needed modes as separate passes and carry source IDs between them. Do not force analysis → extraction → creation if the user asked for only one.

## Shared rules

1. Verify each source and its authority. Treat memory/search snippets as leads, not source proof.
2. Mark coverage and evidence class. Never claim full-corpus review from a sample or a summary.
3. Preserve exact source terms, corrections, branches, contradictions, and negative spaces with provenance.
4. Use `N`, `D`, `M`, and `I` as separate count buckets; only independent narrative executions increase `N`.
5. Treat `J` (jurisdiction over interpretation, decision, preservation, and closure) as a **candidate audit dimension**, not a validated independent variable. Apply the shared falsification test.
6. Keep mechanisms conditional. Every proposed operator needs both activation and non-activation conditions.
7. Preserve surface freedom: internal labels do not select characters, objects, occupations, metaphors, plot shape, or voice.
8. Report unproven gates plainly. Do not call a package transfer test, LOPO, or literary evaluation complete unless it was actually run.

## Output selection

Respect the user's requested deliverable. For evidence work, provide a traceable ledger and a bounded finding. For a generated or transformed piece, provide diagnostic notes only if requested or necessary to expose a material limit. For skill manufacture, include its contract, dependencies, and tests.

## Greenfield / Isla del Dr. Moreau mode

When the user names **Isla del Dr. Moreau**, treat the run as adversarial greenfield evaluation. Read `../../references/isla-del-dr-moreau.md`. Check the available Library before manufacturing new capability. Assume prior interventions may be intelligent and well-intentioned but functionally wrong; test them rather than inheriting them.
