# RG-003 Full Evidence Lifecycle Test — 2026-10-06

## Objective

Exercise the complete field-record lifecycle against the deployed RG-003 v1.0.5 architecture:

**Observation → Evidence → Human/GIS Review → Reviewed Lock → Export → Reconstruction**

## Static verification

### 1. Observation capture — PASS
The application requires Date, Subject, and Direct observations. It also captures conditions, evidence, interpretation, confidence, alternative explanation, and recommended next action.

### 2. Evidence attachment — PASS
The application has a dedicated Evidence field, and the repository now contains registered primary field photographs.

### 3. Provenance — PASS
New records receive immutable record identity, creation timestamp, and application version provenance. Draft editing updates content without replacing original creation time or provenance.

### 4. Human review — PASS
A Draft can be explicitly marked Reviewed by a named human reviewer. Reviewer identity and review timestamp are recorded.

### 5. Reviewed lock — PASS
Reviewed records are excluded from ordinary editing. Edit is only exposed for non-Reviewed records.

### 6. Reconstruction — PASS BY DESIGN
The report and JSON record preserve record ID, status, review information, creation information, field observations, evidence, interpretation, confidence, alternatives, next action, and application version.

### 7. Backup / export / restore — PASS BY DESIGN
The application provides portable JSON backup, JSON restore with duplicate protection, complete JSON export, and text report export.

### 8. Offline persistence — PASS BY DESIGN
The application implements localStorage and IndexedDB, plus a service worker and diagnostic panel.

## Boundary

A live browser execution is required to certify runtime behavior of the full lifecycle. Static inspection establishes the implemented controls but does not substitute for a runtime test.

## Runtime acceptance procedure

1. Create a Draft field record using the current field evidence.
2. Save it and reload the application.
3. Confirm the record survives reload.
4. View the generated report.
5. Mark the record Reviewed with the authorized human/GIS reviewer identity.
6. Confirm Edit is no longer available.
7. Export the JSON record.
8. Clear local records only after the export is secured.
9. Restore the exported JSON.
10. Confirm the same record ID, creation timestamp, evidence, review identity, review timestamp, and status are reconstructed.
11. Confirm the restored record remains Reviewed and cannot be ordinarily edited.

## Acceptance rule

The lifecycle passes only when **identity + provenance + evidence + human review + reviewed lock + export + restoration** survive the complete cycle without silent mutation.

## Current verdict

**ARCHITECTURE: PASS**

**RUNTIME EXECUTION: PENDING**

This is the correct remaining gate. No architectural redesign is indicated by the current inspection.
