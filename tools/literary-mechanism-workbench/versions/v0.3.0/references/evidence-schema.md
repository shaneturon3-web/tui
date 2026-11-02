# Evidence and mechanism record

Use one record per distinct source observation. Never merge source evidence, user correction, inference, or implementation into one untraceable claim.

```yaml
id: LMW-YYYYMMDD-###
source:
  title: exact title
  uri_or_path: verified source pointer
  location: section/page/turn/line range
  version_or_date: exact known version or date
  speaker: author/user/assistant/other/unknown
  coverage: full | partial | excerpt | summary | inaccessible
evidence_class: OBSERVED_TRANSFORMATION | OBSERVED_PRODUCT | OBSERVED_MONTAGE | OBSERVED_SESSION
kind: artifact | occurrence | skill-candidate | contradiction | hypothesis | negative-space
label_exact: exact source wording, if any
description: neutral account of what is observable
mechanism:
  function_under_pressure: what work is performed
  trigger: condition that activates it
  operation: causal relation or decision change
  result: observable consequence
  non_activation: condition under which it should not be used
jurisdiction:
  status: candidate | observed | unknown | contradicted
  holder: who/what may interpret, decide, preserve, or close
  scope: the question, scene, or position governed
  evidence: source pointer or explicit missing evidence
relations:
  - type: supports | contradicts | mutates-to | observed-in | derived-from | requires
    target: record id or exact label
    basis: direct | inferred
count_bucket: N | D | M | I
independence_group: stable story/event ID; summaries inherit the underlying source group
delta: decision changed by this observation
counterexample_or_limit: observed limit, or "not yet tested"
open_questions: []
```

## Evidence classes

- `OBSERVED_TRANSFORMATION`: directly available source and target pair; supports claims about what changed.
- `OBSERVED_PRODUCT`: directly inspected finished work without a paired source; supports claims about the product only.
- `OBSERVED_MONTAGE`: relation created by sequence, separation, callback, recontextualization, or omission among pieces.
- `OBSERVED_SESSION`: words, corrections, choices, or hypotheses actually present in the inspected session.
- `INFERRED`, `CANDIDATE`, `UNKNOWN`, and `CONTRADICTED` are statuses, not evidence classes. Keep them explicit.

## Count buckets

- `N`: independent narrative situation executing a mechanism.
- `D`: a design, specification, report, or discussion that describes/proposes it.
- `M`: a montage relation across pieces.
- `I`: an inferred or proposed inversion, not yet observed.

Only distinct independent executions add to `N`. A mention, a summary, or a repeated report does not.
