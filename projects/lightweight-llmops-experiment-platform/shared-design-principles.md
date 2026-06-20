# Shared Design Principles

## Separate judgment from repetition

Humans handle direction changes and ambiguous failures. Automation handles repeated evaluation and comparison.

## Make resource use configurable

Worker count, retries, sleep intervals, and retry strategy are explicit controls. This allows the workflow to adapt to shared infrastructure and changing traffic.

## Preserve experiment history

Iteration and cycle artifacts record prompt versions, parameter settings, analysis, decisions, and metrics. This supports comparison and later work.

## Stop unproductive work

Stopping rules protect compute capacity and improve throughput.

## Use automation for exploration, not judgment

The nighttime loop explores and ranks candidates. The daytime loop retains human control of prompt direction and ambiguous failure interpretation.
