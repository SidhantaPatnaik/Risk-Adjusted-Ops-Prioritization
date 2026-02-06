# Data to Decision Mapping

## Objective

This document defines how available data sources are translated into decision-relevant inputs for cycle-level prioritization.

The intent is not to maximize data usage, but to ensure that **only decision-relevant data influences intervention prioritization**.

---

## Unit of Decision

**Primary unit:** Production Cycle  
All analysis is aggregated to the cycle level.

Daily, farm-level, or event-level data is used only as supporting input and is not directly actionable.

---

## Data Sources and Their Role

### 1. Cycle / Batch Master
**Role:** Defines the unit of accountability.

Used to:
- Identify cycle boundaries
- Define scale and duration
- Anchor all aggregation logic

**Decision rule:**  
Cycles with missing or ambiguous boundaries are excluded from prioritization.

---

### 2. Daily Operations Data
**Role:** Supports aggregation into cycle-level execution metrics.

Used to:
- Aggregate feed usage
- Capture mortality events
- Track execution consistency

**Not used for:**
- Daily decision-making
- Micro-optimization
- Performance evaluation

**Decision stance:**  
Daily noise is collapsed into cycle-level signals.

---

### 3. Feed / Input Benchmarks
**Role:** Reference point for expected execution quality.

Used to:
- Calculate variance vs expectation
- Normalize across cycles of different scale

**Not used for:**
- Absolute performance judgment
- Blame attribution

Benchmarks are treated as directional anchors.

---

### 4. Harvest / Output Data
**Role:** Outcome realization.

Used to:
- Calculate yield per cycle
- Identify false positives and false negatives

**Decision stance:**  
Outcomes inform context, not priority by themselves.

---

### 5. Cost Data
**Role:** Economic translation of execution behavior.

Used to:
- Compute cost per unit outcome
- Flag cost leakage at the cycle level

**Constraints:**
- Allocation noise acknowledged
- Directional interpretation only

---

## Explicitly Ignored or De-emphasized Data

The following data is deliberately excluded from decision logic:

- Farm or site ranking
- Individual worker performance
- Daily volatility without persistence
- External shock indicators (weather, demand timing)
- One-off anomalies without recurrence

**Rationale:**  
These elements are either uncontrollable or introduce false precision.

---

## Mapping Summary (Decision View)

| Data Source | Feeds Which KPI | Decision Impact |
|------------|-----------------|----------------|
| Cycle Master | All | Defines decision unit |
| Daily Ops | Efficiency, Loss | Execution signal |
| Benchmarks | Variance | Risk normalization |
| Harvest Data | Yield | Outcome context |
| Cost Data | Cost per unit | Economic exposure |

---

## Summary

This mapping ensures that:
- Decisions are made at the correct level
- Noise is filtered before reaching management
- Analysis remains aligned with intervention capacity
- Data usage is defensible under scrutiny
