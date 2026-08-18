# GeCCO KPI Validity & Register Standard v0.1

## Purpose

Make KPI design measurable, decision-useful, resistant to gaming, and implementation-ready while avoiding unnecessary metrics.

## KPI Principle

**A KPI exists because someone needs to know something in order to make a meaningful decision or verify an important outcome.**

If a metric does not change a decision, improve an outcome, protect something important, or provide meaningful verification, it should not automatically become a KPI.

## KPI Record

Every production KPI should contain:

- KPI ID
- Unit
- Metric name
- Definition
- Formula/method
- Unit of measure
- Data source
- Collection method
- Measurement frequency
- Baseline
- Target
- Escalation threshold
- Responsible owner
- Accountable decision owner
- Required action
- Review frequency
- Version
- Status

## Baseline Rule

Never invent a baseline.

If no defensible baseline exists, record:

**Baseline: PENDING**

and define the method and period for establishing it.

## KPI Validity Test

Every KPI must pass:

### Relevance
Does it measure an outcome or condition that matters?

### Traceability
Can it be traced to the unit's canonical descriptor and competency model?

### Reliability
Can the data be collected consistently?

### Decision Utility
What decision or action changes when the KPI changes?

### Economy
Is the information worth the effort/cost/energy required to collect it?

### Anti-Gaming
Could someone improve the KPI while making the underlying outcome worse?

If yes, redesign it or add a necessary companion measure.

## KPI Anti-Gaming Examples

Completion rate may rise while competence remains poor.

Incident count may fall because reporting declines.

Production may rise while resource efficiency deteriorates.

Visitor satisfaction may rise while conservation outcomes decline.

Therefore, a KPI should be tested against foreseeable proxy failure before production use.

## KPI-to-TCI Rule

Not every TCI requires a KPI.

A KPI should be linked to a TCI only where ongoing performance measurement adds meaningful operational value beyond the certification decision itself.

## KPI Lifecycle

**Define → Validate → Baseline → Target → Measure → Review → Act → Retire/Revise**

## KPI Implementation Readiness

A KPI is implementation-ready when:

- [ ] Definition is unambiguous.
- [ ] Formula/method is defined.
- [ ] Data source exists or is explicitly planned.
- [ ] Collection method is defined.
- [ ] Frequency is defined.
- [ ] Baseline is defensible or marked pending.
- [ ] Target is justified or marked pending.
- [ ] Threshold is defined where escalation is needed.
- [ ] Owner is assigned.
- [ ] Decision/action is identified.
- [ ] Anti-gaming test has passed.
- [ ] Cost/effort of measurement is justified.
- [ ] Version is recorded.

## Example

**MOTO-KPI-01 — Fleet Readiness**

- Unit: GeCCO-9 — MOTO
- Metric: Percentage of assigned fleet assets meeting defined operational-readiness criteria
- Data source: fleet-maintenance/readiness record
- Frequency: monthly
- Target: ≥95% when formally established
- Escalation: below approved threshold
- Action: maintenance/readiness review

The target must not be treated as canonical until supported by the appropriate operational evidence and policy.

## Fulcrum Rule

**Measure what matters. Automate what repeats. Eliminate metrics that consume more resources than the decisions they enable.**
