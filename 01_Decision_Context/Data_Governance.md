# Data Governance & Decision Safety

## Data Trust Philosophy
Data is imperfect but usable. The goal is decision safety, not analytical perfection.

---

## Key Data Risks
- Missing or delayed daily logs
- Inconsistent cycle boundaries
- Benchmark drift
- Cost allocation noise

Daily data is used only for cycle-level aggregation.

---

## Directional vs Precise Metrics

| Metric | Reliability |
|------|------------|
| Feed Efficiency | Directional |
| Mortality / Loss | High |
| Yield | High |
| Cost per Unit | Medium |
| Variance vs Benchmark | Directional |
| Composite Score | Decision construct |

---

## Metric Ownership & Challenges

| KPI | Owner | Likely Challenger |
|----|------|------------------|
| Feed Efficiency | Operations | Site Leads |
| Mortality | Operations | Site Leads |
| Yield | Production | Commercial |
| Cost per Unit | Finance | Operations |
| Variance | Ops / Analytics | Finance |
| Composite Score | Business Analysis | All |

Disputes downgrade confidence, not decisions.

---

## Decision Confidence Labels
All insights are classified as:
- High confidence
- Medium confidence
- Hypothesis

No unlabeled insight proceeds to recommendation.

---

## Incentive & Ethics Safeguards
- Rankings visible only to leadership
- No direct penalties tied to prioritization
- Clear messaging: prioritization = attention, not blame
