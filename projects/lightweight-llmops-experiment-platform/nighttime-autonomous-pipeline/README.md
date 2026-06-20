# Nighttime Autonomous Pipeline

The nighttime pipeline receives the best daytime prompt and runs without human intervention. It evaluates candidates, analyzes failures, searches prompt text and temperature, selects results, and produces a morning report.

It is designed for continuous, resource-aware experimentation during lower-traffic windows. The loop can run up to 50 iterations, subject to its stopping rules.

## Documentation

- [Workflow](workflow.md)
- [Optimization Engine](optimization-engine.md)
- [Parameter Search](parameter-search.md)
- [Knowledge Transfer](knowledge-transfer.md)
- [Artifact Tracking](artifact-tracking.md)
- [Early Stopping](early-stopping.md)
