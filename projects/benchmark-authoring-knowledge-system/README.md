# Benchmark Authoring Knowledge System

## Summary

A lightweight knowledge system for multilingual AI benchmark task authoring. It converts CI expectations, reviewer feedback, and successful task patterns into reusable guidance.

## Problem

Task quality expectations were distributed across examples, validation behavior, and reviews. Feedback was often used only for the current submission, which led to repeated review cycles.

## System

The system has five parts:

1. Best-practice notes from successful patterns.
2. Compact notes on CI validation expectations.
3. A library of generalized reviewer feedback.
4. A pre-submission design checklist.
5. A focused context pack for LLM-assisted authoring.

## Workflow

1. Draft a task.
2. Validate it against the checklist.
3. Submit it for CI and review.
4. Convert generalizable feedback into a rule or pattern.
5. Update the knowledge system for the next task.

## Outcome

Early-stage immediate approval was about 1 out of 5 submissions. Later, 5 of 7 consecutive submissions received immediate LGTM and merged without revision requests.

## Documentation

- [Architecture](architecture.md)
- [Design Decisions](design-decisions.md)
- [Metrics](metrics.md)
- [Lessons Learned](lessons-learned.md)
- [Privacy and Redaction](privacy-and-redaction.md)
- [Workflow Diagram](diagrams/workflow.md)
- [Knowledge Loop](diagrams/knowledge-loop.md)

## Disclosure

This case study excludes proprietary tasks, prompts, scripts, review logs, datasets, and submission artifacts.
