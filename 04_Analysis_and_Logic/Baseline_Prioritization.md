# Baseline Cycle Prioritization

## Objective

This analysis applies the decision framework to baseline operational data to identify which production cycles warrant management attention under normal operating conditions.

The focus is on **risk-adjusted execution quality**, not headline profitability.

---

## Data Scope

- Dataset: Internal baseline operational data
- Unit of analysis: Production cycle
- Aggregation: Daily and transactional data rolled up to cycle level
- Exclusions: Cycles with incomplete boundaries or missing critical inputs

Simulated stress data is intentionally excluded at this stage.

---

## Method Overview

The following approach was applied:

1. Aggregate execution, cost, and outcome data to the cycle level
2. Construct decision-relevant KPIs per defined construction rules
3. Compare cycles using aligned execution, loss, cost, and variance signals
4. Group cycles by **intervention priority**, not by profit ranking

No single KPI was interpreted in isolation.

---

## Key Baseline Observations

### Variance Is Concentrated, Not Evenly Distributed
A small subset of cycles accounts for a disproportionate share of:
- High mortality
- Elevated cost per unit outcome
- Execution inefficiency

This confirms that operational risk is concentrated in the tail rather than spread uniformly.

---

### Outcome vs Execution Mismatch Is Material
Several cycles show **acceptable or strong financial outcomes** despite:
- High mortality rates
- Poor feed efficiency
- Elevated cost per bird

Conversely, some low-outcome cycles exhibit relatively stable execution once uncontrollable factors are considered.

This demonstrates that **headline profit is an unreliable prioritization signal**.

---

## Baseline Priority Grouping

### High Priority — Immediate Attention
Characteristics:
- Persistently high mortality or irreversible losses
- Elevated cost per unit driven by execution behavior
- Poor efficiency relative to benchmarks
- Multiple aligned risk signals

These cycles represent **hidden or compounding risk**, even when outcomes appear tolerable.

---

### Medium Priority — Monitor Closely
Characteristics:
- Mixed execution signals
- Moderate variance
- Partial alignment between cost, loss, and efficiency metrics

These cycles warrant visibility and monitoring before intervention.

---

### Low Priority — No Action Required
Characteristics:
- Stable execution signals
- Acceptable efficiency
- Deviations largely explained by external or temporary factors

Intervening here is unlikely to yield meaningful benefit.

---

## Core Insight

Baseline analysis shows that prioritization decisions change materially when execution risk is separated from outcomes.

Cycles that appear “fine” under profit-based review often surface as high-risk once variance, loss, and efficiency are considered together.

---

## What This Analysis Does Not Claim

- It does not predict future performance
- It does not assign blame to teams or sites
- It does not imply intervention guarantees improvement
- It does not replace managerial judgment

---

## Next Step

These baseline priorities will be stress-tested using simulated operational shocks to assess whether intervention logic remains robust under adverse conditions.
