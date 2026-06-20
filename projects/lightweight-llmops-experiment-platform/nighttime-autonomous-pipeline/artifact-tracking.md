# Artifact Tracking

## Iteration-level artifacts

Each iteration records an ID, timestamp, prompt version, parameter configuration, evaluation outputs, failure analysis, optimization decisions, and MSE. These records are stored in dedicated spreadsheets.

## Cycle-level artifacts

Each cycle records a timestamp, iteration ID, version summary, MSE, improvement flag, and cycle summary. These summaries are stored in CSV files.

This provides reproducibility, auditability, historical comparison, and cross-cycle knowledge transfer. It is conceptually similar to experiment tracking systems such as MLflow or Vertex AI Experiments, without claiming feature parity.
