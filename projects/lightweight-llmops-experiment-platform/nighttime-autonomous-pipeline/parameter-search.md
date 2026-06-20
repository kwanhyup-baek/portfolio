# Parameter Search

The search space includes prompt text and temperature. The design can extend to other model parameters.

The system uses beam-search-like exploration:

```text
Generate candidates → Cheap screening → Top-K selection → Full evaluation
```

This limits expensive evaluation to candidates that pass an initial comparison. It supports higher experiment throughput without exhaustively testing every candidate.
