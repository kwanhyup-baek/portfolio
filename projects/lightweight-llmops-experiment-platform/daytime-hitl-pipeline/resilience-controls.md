# Resilience Controls

The pipeline exposes these controls:

- Worker count
- Retry count
- Sleep interval
- Retry strategy

They allow the workflow to adapt to traffic spikes and temporary service failures without hard-coding a single operating mode. The controls support recovery while keeping human review focused on failures that require judgment.
