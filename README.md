# DIKWP-CREDENCE²

**Open Claims, Independent Replication, Adversarial Challenge, Interoperability and Public Evidence Network**

中文：**开放主张、独立复现、反证悬赏、互操作与公共可信扩散系统**。

## Why

The system distinguishes:

- open source from open evidence;
- author-side reproduction from independent replication;
- provenance from truth;
- conformance from real-world effectiveness;
- popularity from credibility;
- a repository from the individual claims it contains.

## Quick start

```bash
cd DIKWP_CREDENCE2_MVP
PYTHONPATH=src python -m credence2.cli --trials 20000 --seed 17072026
PYTHONPATH=src pytest -q
```

Then open `outputs/dashboard.html`.

## Evidence states

- E0 Narrative claim
- E1 Inspectable artifact
- E2 Author-computational reproduction
- E3 Independent replication
- E4 Adversarial robustness
- E5 Two independent interoperable implementations
- E6 Field validation
- E7 Public infrastructure

Status is assigned **per claim**, never as a blanket badge for an entire project.

## Safety and scope

This MVP is offline-first and advisory-only. The GitHub snapshot is manually curated from public pages on 2026-07-17. Probabilities and simulations are synthetic mechanism tests, not empirical ratings or official certifications.
