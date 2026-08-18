# GeCCO KPI–TCI & Implementation Readiness Specification v0.4

**Status:** Phase 0 — Foundational Architecture Refinement

**Purpose:** Integrate the GeoCOMPASS Fulcrum Principle into the GeCCO KPI/TCI architecture while tightening measurement, competency, evidence, certification, and implementation rules without adding unnecessary bureaucracy.

## 1. Governing Architecture

**Canonical Descriptor → Target Competency → TCI → Assessment → Evidence → KPI → Certification → Recertification**

The canonical acronym and descriptor are the semantic foundation of every GeCCO certification.

> **No downstream competency, TCI, course, assessment, evidence requirement, KPI, or certification description may introduce a domain that cannot be reasonably traced to the canonical descriptor.**

### TCI — Target Competency Indicator

A TCI is an observable indicator demonstrating whether a learner has reached a defined target competency.

**TCI answers:** “Has the required competency been demonstrated?”

### KPI — Key Performance Indicator

A KPI is a measurable indicator of performance, effectiveness, quality, reliability, safety, compliance, or outcome over time.

**KPI answers:** “How well is the competency or resulting system performing?”

TCIs are not numerical performance targets. KPIs do not replace competency assessment.

## 2. The Fulcrum Principle

The **Fulcrum Principle** is a cross-cutting GeoCOMPASS design canon applied to GeCCO.

> **Find the fulcrums. Leverage the inputs. Maximize the return.**

The objective is the **highest return on inputs** through strategic leverage, minimum necessary effort, reuse of existing capability, and elimination of unnecessary complexity.

Applied to GeCCO:

- Enter data once.
- Reuse authoritative structured data.
- Leverage the canonical descriptor rather than repeatedly redefining meaning.
- Measure what matters.
- Automate repetition, not institutional authority.
- Build only what cannot be configured, reused, or leveraged.
- Eliminate duplicate records, duplicate measurements, duplicate workflows, and unnecessary approval layers.
- Preserve human energy for judgment, instruction, field work, evaluation, and consequential decisions.

**Financial expression:** highest return on investment (ROI).

**Broader expression:** highest return on inputs.

A proposed GeCCO feature, workflow, KPI, or administrative layer should be retained only when its expected value justifies its cost in money, time, energy, complexity, attention, or maintenance.

## 3. Descriptor Traceability Rule

For every unit:

**Acronym → Descriptor Terms → Certification Foundation → Target Competencies → TCIs → Coursework → Assessment → Evidence → KPIs**

The acronym is not merely a label. It establishes the foundation from which the certification is built.

Expanded descriptions and certification synopses may clarify the descriptor but may not arbitrarily redefine it.

Changing a canonical acronym or descriptor requires review of dependent coursework, competencies, TCIs, assessments, evidence requirements, KPIs, and certification rules.

## 4. Common Competency-to-Certification Model

Every unit should use the same minimum implementation sequence:

1. Preserve the canonical descriptor.
2. Derive target competencies from the descriptor.
3. Define observable TCIs.
4. Map coursework to the target competencies.
5. Map assessments to the TCIs.
6. Define required evidence and verification level.
7. Establish the certification threshold.
8. Define applicable KPI measurements.
9. Define recertification where required.
10. Record authoritative results in the Competency Record.
11. Allow GAIA-Zer0 to route, record, aggregate, notify, and report.

The structure is standardized; the content remains descriptor-specific.

## 5. KPI Architecture

KPIs should be created only where measurement produces useful operational or certification value.

### KPI Classes

**A — Competency Performance:** application of an achieved competency.

**B — Operational Performance:** effectiveness of unit operations.

**C — Quality:** quality, accuracy, reliability, or consistency of outputs.

**D — Safety & Compliance:** safety, legal, regulatory, policy, or institutional requirements.

**E — Outcome:** real-world environmental, educational, financial, health, infrastructure, or operational results.

**F — System:** BioSPHERE/GeCCO-wide performance.

Not every unit requires every KPI class.

### Leading and Lagging Indicators

Where useful, KPIs should be identified as:

- **Leading:** signals likely future performance.
- **Process:** measures execution.
- **Lagging:** measures achieved results.
- **Outcome:** measures real-world effect.

This prevents dashboards from becoming collections of statistics without decision value.

### KPI Measurement Grammar

Every approved KPI should ultimately contain:

**KPI ID → Unit/Class → Metric → Formula → Unit of Measure → Definition → Data Source → Collection Method → Frequency → Baseline → Target → Threshold → Owner → Accountable Owner → Review Action → Version → Approval Status → Effective Date**

The formula and unit of measure are required before a KPI is considered implementation-ready.

## 6. KPI Baseline and Target Rule

A target should not be established without an identified baseline where a baseline is reasonably available.

The performance chain is:

**Baseline → Target → Actual → Variance → Trend → Action**

Where no baseline exists, the system should explicitly identify the metric as **baseline pending** rather than inventing a value.

## 7. TCI-to-KPI Rule

**Not every TCI requires a KPI.**

Some TCIs demonstrate one-time qualification and require no continuing operational metric.

Some KPIs measure system performance involving multiple TCIs or multiple GeCCO units.

Therefore:

- **TCI = competency attainment.**
- **KPI = continuing performance measurement.**

This distinction prevents unnecessary KPI proliferation.

## 8. Evidence and Assessment Integrity

Evidence should be classified by verification strength:

1. Self-reported.
2. Instructor-observed.
3. Evaluator-verified.
4. Instrument/data-verified.
5. Independent or authorized third-party evidence.

Each assessment should identify the minimum acceptable evidence class.

Evaluator integrity should include, where applicable:

- evaluator qualification;
- evaluator authorization;
- assessment-rubric version control;
- evaluator calibration;
- conflict-of-interest controls; and
- reassessment rules.

The goal is reliable certification without unnecessary administrative burden.

## 9. Certification Threshold

Certification is not triggered by a single KPI.

A certification decision evaluates, as applicable:

**Prerequisites + Required Knowledge + Practical Skills + TCI Attainment + Required Evidence + Assessment Result + Applicable Compliance Requirements**

KPIs may support continuing performance, recertification, quality assurance, or operational authorization.

Consequential certification decisions remain subject to authorized human governance.

## 10. Remediation Logic

Two different remediation loops must remain distinct.

### Competency Remediation

**TCI Not Met → Remediation → Reassessment → Evidence Update → Certification Decision**

### Operational Remediation

**KPI Below Threshold → Operational Review → Corrective Action → Follow-up Measurement**

GAIA-Zer0 may automate notifications, routing, tracking, and reporting for these loops but does not invent the underlying standards.

## 11. KPI Data Quality

KPI data should be evaluated for:

- completeness;
- accuracy;
- timeliness;
- consistency;
- provenance; and
- validation status.

Where data quality is insufficient, the KPI should be flagged rather than treated as authoritative.

## 12. Ownership and Authority

Separate, where applicable:

**Data Owner ≠ KPI Owner ≠ Operational Accountable Owner ≠ Certification Authority**

This preserves institutional separation of duties.

## 13. Cross-Unit KPIs

Distinguish:

- **Unit KPI:** owned by one GeCCO unit.
- **Cross-unit KPI:** depends on multiple units but has one accountable owner.
- **BioSPHERE System KPI:** measures whole-system performance.

A system KPI should not be duplicated as multiple artificial unit KPIs merely to populate dashboards.

## 14. Competency Record

The authoritative record connects:

**Candidate → Unit → Competency → TCI → Assessment → Evidence → Result → KPI Relationship → Credential**

The same structured information should populate curriculum, assessment, certification, KPI reporting, credential verification, and administrative reporting.

**One competency model. One authoritative record. Multiple interfaces.**

## 15. GAIA-Zer0 Boundary

GAIA-Zer0 may:

- maintain records;
- route workflows;
- organize evidence;
- calculate approved KPIs;
- issue notifications and reminders;
- aggregate reports;
- track credential status;
- preserve audit trails; and
- recommend administrative actions.

GAIA-Zer0 may not independently:

- redefine competencies;
- redefine TCIs;
- change certification thresholds;
- create institutional policy;
- override evaluator authority; or
- make consequential certification decisions outside authorized policy.

**GeCCO defines the standard. GAIA-Zer0 executes and records the authorized workflow.**

## 16. Implementation Readiness Gate

A unit is implementation-ready when:

- [ ] Canonical acronym and descriptor are approved and preserved exactly.
- [ ] Descriptor traceability is demonstrated.
- [ ] Target competencies are defined.
- [ ] TCIs are observable and measurable.
- [ ] Coursework maps to competencies.
- [ ] Assessments map to TCIs.
- [ ] Evidence requirements are defined.
- [ ] Evidence verification level is defined.
- [ ] Certification threshold is defined.
- [ ] Recertification requirement is defined where applicable.
- [ ] KPI classes are identified where useful.
- [ ] Individual KPI definitions exist where required.
- [ ] KPI formulas and units of measure exist.
- [ ] KPI data sources are authoritative.
- [ ] Collection method and frequency are defined.
- [ ] Baseline is established or explicitly marked pending.
- [ ] Target is authorized.
- [ ] Threshold is authorized.
- [ ] KPI ownership is explicit.
- [ ] Review action is authorized.
- [ ] Competency Record fields are mapped.
- [ ] GAIA-Zer0 workflow is mapped.
- [ ] Human decision points are defined.
- [ ] Role separation is defined.
- [ ] Evidence/data provenance is preserved.
- [ ] A representative end-to-end acceptance test passes.
- [ ] The implementation satisfies the Fulcrum Principle by avoiding unnecessary duplication and complexity.

## 17. Minimum-Complexity Implementation Sequence

### Phase 1 — Canonical Data Model

Candidate; Unit; Competency; TCI; Assessment; Evidence; KPI; Credential.

### Phase 2 — Descriptor-to-Competency Mapping

**Descriptor → Competencies → TCIs → Coursework → Assessment → Evidence**

### Phase 3 — Certification Rules

Prerequisites, thresholds, evaluator authority, exceptions, and recertification.

### Phase 4 — KPI Specification

Convert only useful KPI domains into measurable records with formulas, sources, frequency, baseline, target, threshold, owner, and action.

### Phase 5 — Administrative Workflow

**Enrollment → Training → Assessment → Certification → Review/Recertification**

### Phase 6 — GAIA-Zer0 Integration

Connect authoritative records and workflows without duplicate data entry or duplicate institutional logic.

### Phase 7 — Verification

Implement controlled digital credential verification before physical credential integration.

### Phase 8 — Physical Credential Integration

Add physical credentials only when they produce sufficient operational value.

### Phase 9 — Agentic Automation

Automate repetitive work only where measurable savings or improved return justify the complexity.

## 18. Final Design Canon

**Acronyms establish meaning.**

**Meaning establishes function.**

**Function establishes competency.**

**Competency establishes TCIs.**

**TCIs establish assessment.**

**Assessment establishes evidence.**

**KPIs measure performance.**

**Credentials represent authorized achievement.**

**GAIA-Zer0 administers the workflow.**

**The Fulcrum Principle governs how the whole system is built:**

> **Find the fulcrums. Leverage the inputs. Maximize the return.**

> **Highest return on inputs with the minimum necessary complexity.**

No unnecessary layer should exist merely because it can be built.

No duplicate data should exist merely because it is convenient for one interface.

No acronym should be expanded into a meaning it does not contain.

No KPI should exist merely to populate a dashboard.

No automation should replace institutional authority.

**The objective is not maximum complexity. The objective is maximum potential.**
