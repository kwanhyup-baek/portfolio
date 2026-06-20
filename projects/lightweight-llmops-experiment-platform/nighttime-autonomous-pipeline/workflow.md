# Workflow

```text
Best daytime prompt
  → Evaluation
  → Failure analysis
  → Candidate generation
  → Parameter search
  → Cheap screening
  → Top-K selection
  → Full evaluation
  → Selection
  → Report and knowledge storage
```

The loop ends when it reaches the target MSE or detects five consecutive worsening MSE results.
