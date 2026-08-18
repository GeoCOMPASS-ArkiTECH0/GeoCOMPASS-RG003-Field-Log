# GeCCO 14-Unit Competency Ownership Matrix v0.1

## Purpose

Establish one authoritative competency owner for every certification competency while allowing other GeCCO units to support or consume that competency.

## Canonical Unit Register

| Unit | Canonical Acronym | Canonical Descriptor | Primary competency domain |
|---|---|---|---|
| GeCCO-0 | OPSEC | Operational Security | Operational security |
| GeCCO-1 | TECCOMM | Training & Education COMMand | Training, education, command |
| GeCCO-2 | MEDServ | MEDical SERVices | Medical services |
| GeCCO-3 | SEEDS | Sustainability Engineering & Eco-integrative Deployment Systems | Environmental engineering and eco-integrative deployment |
| GeCCO-4 | SMARTCOMM | Science, Metrics, Analytics, Reconnaissance, Technology & Communications | Science, metrics, analytics, reconnaissance, technology, communications |
| GeCCO-5 | CAMPRServ | Conservation Area Management & Public Relations Services | Conservation-area management and public relations services |
| GeCCO-6 | JAGPAW | Justice Advocacy, Governance, People And Wildlife | Justice advocacy, governance, people, wildlife |
| GeCCO-7 | SURPLUS | Supply, Utilities, Resources, Provisions, Logistics, Upcycling & Sustainability | Supply, utilities, resources, provisions, logistics, upcycling, sustainability |
| GeCCO-8 | BUILD | Built Utility & Infrastructure Logistics Development | Built utility and infrastructure logistics development |
| GeCCO-9 | MOTO | Mobility Operations, Technology & Outfitting | Mobility operations, technology, outfitting |
| GeCCO-10 | FINSEC | Financial Security | Financial security |
| GeCCO-11 | WASH | Water Accessibility, Sanitation & Hygiene | Water accessibility, sanitation, hygiene |
| GeCCO-12 | AGRO-Farm | Applied Growth & Regenerative Operations – Farm | Farm growth and regenerative operations |
| GeCCO-13 | FOOD | Fresh Organics & Optimized Dietetics | Fresh organics and optimized dietetics |

## Ownership Rule

**One competency has one authoritative owner.**

A supporting unit may teach, use, or depend upon a competency without becoming its certification owner.

## Ownership Tests

Before assigning a competency to a unit:

1. Does it directly derive from the unit's exact acronym/descriptor?
2. Would a reasonable evaluator place the competency primarily within that descriptor?
3. Is another unit already the authoritative owner?
4. If multiple units legitimately require the competency, which unit is the source authority?
5. Can supporting relationships be recorded without duplicate certification authority?

## High-Overlap Areas Requiring Explicit Mapping

### SEEDS / SMARTCOMM / BUILD / WASH / AGRO-Farm

Environmental systems, monitoring, engineering, water, and productive systems may intersect. Ownership must follow the descriptor, not convenience.

### SURPLUS / MOTO / BUILD

Logistics, equipment, infrastructure, and resource movement may overlap. SURPLUS owns supply/resource/logistics systems; MOTO owns mobility/technology/outfitting; BUILD owns built utility/infrastructure development.

### AGRO-Farm / FOOD / WASH

Food production, food systems, and water may interact. AGRO-Farm owns farm production; FOOD owns fresh organics/dietetics; WASH owns water/sanitation/hygiene systems.

### TECCOMM / All Units

TECCOMM may deliver or administer training across units but does not automatically become the owner of the underlying operational competency.

### SMARTCOMM / All Units

SMARTCOMM may provide scientific, metric, analytics, technology, reconnaissance, or communications capabilities to other units while retaining ownership of its descriptor-derived competencies.

## Matrix Fields for Implementation

Each competency record should eventually contain:

- Competency ID
- Canonical unit owner
- Exact descriptor element(s) supporting the competency
- Supporting units
- TCI IDs
- CERTWORX pathway
- Assessment method
- Evidence requirement
- KPI relationship, if any
- Applicable external authority/standard
- Version
- Approval status

## Acceptance Rule

No competency should enter production certification unless its authoritative owner is unambiguous.

**Fulcrum objective:** eliminate duplicated standards, duplicated assessment logic, and competing sources of truth.
