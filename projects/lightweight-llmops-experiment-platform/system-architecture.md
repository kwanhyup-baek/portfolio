# System Architecture

```text
Daytime HITL loop
Prompt → Evaluation → Human review → Prompt revision → Best prompt
   │           │              │
   └─ Batch execution and resilience controls ────────┘
                                                    │
                                                    ▼
Nighttime autonomous loop
Evaluation → Failure analysis → Candidate generation → Cheap screening
    → Top-K selection → Full evaluation → Report and artifact storage
                                                    │
                                                    ▼
                                     Historical learning layer
```

The daytime loop prioritizes judgment and precision. The nighttime loop prioritizes unattended exploration and throughput, including parameter search and early stopping.

The best daytime prompt is the input to overnight experimentation. Iteration records, cycle summaries, reports, and decisions are retained for later cycles.
