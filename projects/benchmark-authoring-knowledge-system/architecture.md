# Architecture

## Overview

```text
Successful patterns ─┐
CI behavior ─────────┼─> Knowledge layer ─> Authoring workflow
Reviewer feedback ───┘        │
                                ├─> Design checklist
                                ├─> Failure-mode library
                                └─> LLM context pack
```

## Layers

### Input layer

Sources include successful patterns, CI behavior, review feedback, and failed submissions.

### Knowledge layer

The layer stores best-practice notes, CI notes, feedback rules, and a checklist.

### Authoring layer

The author uses the guidance to prepare a draft, validate it, revise it, and submit it.

### Feedback loop

Generalizable CI failures and review comments become new guidance.
