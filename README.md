# GT-0215 cross-workflow C3

An external issue reaches a Claude producer. The model response is uploaded as
an artifact and consumed by a separate `workflow_run` job with repository write
permission. The artifact controls the replacement of a workflow file and push.
