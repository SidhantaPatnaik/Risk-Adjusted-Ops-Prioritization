Placeholder
# Metric Construction Rules

## Purpose

This document defines how each KPI is constructed at a conceptual level to support intervention prioritization.  
The focus is on **decision reliability**, not mathematical precision.

Formulas may evolve; these rules must hold.

---

## General Construction Principles

All KPIs follow these rules:

- Metrics are constructed at the **cycle level**
- Directional accuracy is prioritized over exact precision
- One-off anomalies do not drive decisions
- No single KPI can trigger intervention in isolation
- Metrics must be explainable to a non-technical decision owner

---

## KPI-Specific Construction Rules

### 1. Feed / Input Efficiency

**Construction logic:**
- Aggregate total input usage over the cycle
- Normalize against expected usage based on benchmarks and cycle scale
- Express as deviation from expectation

**Allowed approximations:**
- Use benchmark ranges rather than exact targets
- Accept minor daily logging gaps if aggregate trend is stable

**Non-negotiable:**
- Must be comparable across cycles
- Must reflect execution behavior, not outcome alone

---

### 2. Mortality / Loss Rate

**Construction logic:**
- Aggregate irreversible losses over the cycle
- Normalize by cycle scale

**Allowed approximations:**
- Timing of loss events may be coarse

**Non-negotiable:**
- Missing loss data invalidates the cycle for prioritization
- Treated as a high-confidence signal

---

### 3. Yield per Cycle

**Construction logic:**
- Use realized output at cycle completion
- Normalize by initial cycle scale

**Allowed approximations:**
- Minor measurement timing differences

**Non-negotiable:**
- Yield is never interpreted without execution context

---

### 4. Cost per Unit Outcome

**Construction logic:**
- Aggregate variable and feed costs at cycle level
- Divide by realized output

**Allowed approximations:**
- Cost allocation may be coarse
- Timing mismatches are acceptable

**Non-negotiable:**
- Directional interpretation only
- Used to flag exposure, not to assign blame

---

### 5. Variance vs Benchmark

**Construction logic:**
- Measure deviation of execution KPIs from benchmark expectations
- Focus on magnitude and consistency, not sign alone

**Allowed approximations:**
- Benchmarks treated as reference bands

**Non-negotiable:**
- Large persistent variance elevates risk regardless of outcomes

---

### 6. Composite Risk-Adjusted Cycle Score

**Construction logic:**
- Combine execution efficiency, loss, cost exposure, and variance signals
- Weighting reflects relative risk contribution, not statistical optimization

**Allowed approximations:**
- Weighting may be judgment-based
- Exact score values are not meaningful outside ranking

**Non-negotiable:**
- Score is used only for prioritization
- Never interpreted as absolute performance

---

## Data Failure Handling

If any of the following occur:
- Missing cycle boundary
- Missing mortality data
- Untraceable output quantity

Then:
- Cycle is excluded from prioritization
- Logged for data quality follow-up
- No imputation used to “force” inclusion

---

## Summary

These construction rules ensure that KPIs:
- Are robust to noisy operational data
- Support defensible prioritization
- Remain aligned with decision constraints
- Avoid false precision and overconfidence
