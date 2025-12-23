# Methodology

This document describes the general posture and constraints under which observations
in this repository are recorded.

It does not define a testing protocol intended to produce reproducible performance metrics.
Its role is to clarify how observations are collected and interpreted.

---

## Observation basis

Observations are derived from:

- public web content,
- publicly accessible AI interfaces,
- non-privileged interactions available to any user.

No internal model access, private APIs, or proprietary datasets are used.

---

## Query posture

- Queries are formulated in natural language.
- No prompt engineering intended to bias outcomes is applied.
- No system-level instructions or hidden constraints are injected.

The goal is to observe default interpretive behavior, not to elicit optimized responses.

---

## Model variability

AI models differ in:

- training data,
- retrieval mechanisms,
- summarization strategies,
- citation behavior.

As a result, divergence between models is expected and recorded as part of the observation.

---

## Temporal instability

AI systems evolve continuously.

An observation recorded at a given date:

- may not remain valid in the future,
- may change without notice,
- should not be treated as a permanent property.

Dates are therefore always included in observation files.

---

## Interpretive caution

Recorded outputs reflect how a system interpreted available information
at a specific point in time.

They do not represent factual truth,
only observed interpretive behavior.
