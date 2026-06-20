# Optimization Engine

The engine uses evaluation failures to guide candidate generation. Candidates are screened, ranked, and selected through repeated evaluation.

Beam-search-like exploration limits full evaluation to candidates that pass cheap screening. The engine is an experiment platform, not a prompt generator: its purpose is to compare changes under a repeatable selection process.
