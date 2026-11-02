# Frontier Engine — draft v0.1

## Function

Explore the boundary of a project by generating viable routes, exposing their consequences and selecting the smallest route that produces new evidence.

## Inputs

- current state: `{{current_state}}`
- frontier question: `{{frontier_question}}`
- resources and limits: `{{limits}}`
- protected state: `{{protected_state}}`

## Procedure

1. Declare the current boundary and what is not yet known.
2. Generate at least three routes with different consequences.
3. Compare value, complexity, reversibility, dependency, risk and time to evidence.
4. Identify the minimum safe proof for the leading route.
5. Execute or specify that proof.
6. Record what the result makes possible, impossible or still unknown.

## Formula

`frontier_move = route × consequence × constraint × evidence_gain`

## Failure filters

- Do not confuse expansion with progress.
- Do not activate frontier work outside the authorized scope.
- Do not select the most elaborate route merely because it is interesting.
- Do not declare a frontier crossed without new evidence.

## Status

`candidate / test-ready / not promoted`
