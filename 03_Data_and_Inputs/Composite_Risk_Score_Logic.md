# Composite Risk Score Logic

## Why a Composite Score Exists

Management must choose which cycles to intervene in under limited capacity.  
Comparing cycles across multiple KPIs without a unifying structure leads to inconsistent and subjective decisions.

The composite risk score exists to:
- Force explicit trade-offs
- Enable ranking under constraint
- Surface cycles with hidden execution risk

It does **not** represent true performance or profitability.

---

## What the Score Represents

The score represents **relative execution risk** at the cycle level, considering:
- Input efficiency deviations
- Irreversible losses
- Cost exposure
- Variance magnitude

It answers one question only:
> *“Which cycles are riskier candidates for management attention?”*

---

## What the Score Does NOT Represent

The score is **not**:
- A performance rating
- A prediction of future outcomes
- A financial return metric
- A measure of team quality
- A replacement for managerial judgment

Using it as such would be misuse.

---

## Weighting Philosophy

### Why Weighting Is Required
Not all risk signals are equally damaging.

For example:
- Irreversible loss is typically more severe than temporary inefficiency
- Persistent variance is more dangerous than one-off deviation
- Cost exposure matters only if linked to controllable behavior

Weighting reflects **risk severity**, not statistical correlation.

---

### How Weights Are Determined
Weights are:
- Judgment-based
- Informed by operational experience
- Transparent and adjustable

They are **not optimized for historical fit** to avoid overfitting and false confidence.

---

## Score Construction (Conceptual)

The composite score:
- Aggregates normalized risk signals
- Penalizes cycles with multiple aligned risk indicators
- Is stable under minor data fluctuations

Exact score values are less important than **relative ranking**.

---

## Safeguards Against Misuse

To prevent the score from becoming a black box:
- Component signals remain visible
- Confidence labels accompany rankings
- Large score jumps require explanation
- Score changes trigger review, not automatic action

---

## When the Score Is Revisited

The score logic is reviewed when:
- Repeated false positives occur
- High-risk cycles are missed
- Benchmarks materially change
- Intervention outcomes contradict expectations

Revisions are documented, not hidden.

---

## Summary

The composite risk score is a **decision aid**, not a truth engine.  
It exists to support prioritization under constraint while preserving transparency, judgment, and accountability.
