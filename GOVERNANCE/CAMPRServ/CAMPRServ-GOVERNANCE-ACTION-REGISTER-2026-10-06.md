# CAMPRServ Governance Action Register — 2026-10-06

**Status:** OPEN GOVERNANCE ACTION  
**Source:** RG-003 Monkey Falls field proof  
**Authority state:** PENDING AUTHORIZED GECCO DECISION

## Purpose

Convert the completed RG-003 field-to-digital proof into a controlled governance action without manufacturing canonical competency, TCI, evaluator, or certification authority.

## Trigger

RG-003 has produced sufficient field evidence to support governance review:

**FIELD ACTION → OBSERVATION → EVIDENCE → HUMAN/GIS VALIDATION → COMPETENCY CANDIDATE → CAMPRServ PROVISIONAL OWNER → TCI CANDIDATE**

The remaining bottleneck is governance formalization, not field evidence or software capability.

## Action Register

| Action | Required decision | Current state |
|---|---|---|
| GA-001 | Confirm GeCCO-5 CAMPRServ ownership | PENDING |
| GA-002 | Approve/revise proposed competency statement | PENDING |
| GA-003 | Assign canonical competency ID | PENDING |
| GA-004 | Approve/revise proposed TCI | PENDING |
| GA-005 | Assign production TCI ID/version | PENDING |
| GA-006 | Define formal pass condition | PENDING |
| GA-007 | Define safety/compliance requirements | PENDING |
| GA-008 | Define authorized evaluator scope | PENDING |
| GA-009 | Define certification decision authority | PENDING |
| GA-010 | Define remediation/appeal process | PENDING |
| GA-011 | Establish minimum credible evidence standard | PENDING |
| GA-012 | Establish effective version and review cycle | PENDING |

## Evidence Package

The governance review should reference the existing RG-003 evidence and tests rather than reproduce them:

- FIELD-EVIDENCE-REGISTER.md
- TESTS/RG003-EVIDENCE-TO-VALIDATION-TEST-2026-10-06.md
- TESTS/RG003-FULL-EVIDENCE-LIFECYCLE-TEST-2026-10-06.md
- TESTS/RG003-EVIDENCE-TO-COMPETENCY-MAPPING-2026-10-06.md
- TESTS/RG003-COMPETENCY-AUTHORITY-MAPPING-2026-10-06.md
- TESTS/RG003-CAMPRServ-TCI-EVIDENCE-ASSESSMENT-2026-10-06.md
- TESTS/RG003-CAMPRServ-COMPETENCY-REGISTRY-GAP-2026-10-06.md
- GOVERNANCE/CAMPRServ/CAMPRServ-COMPETENCY-APPROVAL-RECORD-DRAFT-v0.1.md

## Decision Rule

No production competency, TCI, certification rule, or evaluator authority is created by this register.

A governance decision must be recorded before the proposed competency or TCI is treated as canonical.

## Required Approval Record

When authorized governance acts, the resulting record should contain:

1. decision authority;
2. date;
3. decision for each GA item;
4. competency ID and version, if approved;
5. TCI ID and version, if approved;
6. evaluator authority scope;
7. certification authority;
8. safety/compliance standard;
9. pass condition;
10. remediation/appeal rule;
11. effective date;
12. review date.

## Architectural Finding

The Monkey Falls proof has crossed the software validation threshold.

The correct next move is **governance adjudication**, not another RG-003 feature.

**CAPABILITY ≠ EVIDENCE ≠ AUTHORITY**

The repository preserves evidence.

The field record documents what occurred.

Human/GIS review validates the record.

GeCCO governance decides whether that evidence establishes a competency.

Authorized certification authority decides whether certification follows.

## Status

**GOVERNANCE ACTION OPEN**

**EVIDENCE SUFFICIENT FOR REVIEW: YES**

**CANONICAL COMPETENCY CREATED: NO**

**CANONICAL TCI CREATED: NO**

**CERTIFICATION AUTHORITY CREATED: NO**

**NEXT GATE: AUTHORIZED GECCO GOVERNANCE DECISION**
