# Required Deliverables

Every team repository must contain evidence for all deliverables below.

## D1 — Discovery & Data Quality Assessment

**Due:** End of Week 1  
**Location in team repo:** `docs/01-discovery/`

Required:

- source-table inventory;
- row counts and grain;
- key relationships;
- uniqueness checks;
- missing-data assessment;
- date/time coverage;
- identified anomalies;
- assumptions;
- initial analytical risks.

**Acceptance:** another analyst can understand the source data and its main limitations.

## D2 — Data Model & Transformation Layer

**Due:** Initial version by end of Week 3  
**Location:** `src/`, `sql/`, and `docs/02-data-model/`

Required:

- preserved raw-data approach;
- reproducible transformations;
- documented join logic;
- student/module/presentation analytical structures;
- time-based engagement structures where used;
- handling of missing and exceptional records;
- model/relationship diagram.

**Acceptance:** analytical datasets can be regenerated without undocumented manual manipulation.

## D3 — KPI & Metric Catalogue

**Due:** End of Week 3  
**Location:** `docs/03-kpi-catalogue/`

Each KPI must include:

- name;
- business purpose;
- definition;
- calculation logic;
- grain;
- source fields;
- exclusions;
- refresh/measurement frequency where relevant;
- limitations.

Expected metric areas include registration, engagement, assessment behaviour, withdrawal, completion and attainment.

## D4 — Analytical Investigation

**Due:** End of Week 4  
**Location:** `analysis/` or `notebooks/`

Required analysis should address the agreed business questions and distinguish:

- observation;
- interpretation;
- uncertainty;
- recommendation.

**Acceptance:** major findings can be reproduced from source data and code.

## D5 — Student Success Dashboard / Decision-Support Product

**Due:** Draft Week 5; final Week 6  
**Location:** `dashboard/`

Include either:

- the dashboard/project file where practical; or
- a secure accessible link plus screenshots/export and usage notes.

The product should support management decisions rather than simply display charts.

## D6 — Responsible Analytics / Early-Warning Assessment

**Due:** Week 5  
**Location:** `docs/04-responsible-analytics/`

Required:

- proposed early-warning indicators, if any;
- evidence supporting them;
- false-positive/false-negative considerations;
- risks of demographic bias;
- limitations;
- recommended safeguards;
- explanation of what the analysis cannot establish.

If a predictive model is developed, include model evaluation and responsible-use limitations.

## D7 — Technical Handover

**Due:** Week 6  
**Location:** `docs/05-technical-handover/`

Must explain:

- repository structure;
- environment/setup;
- source data;
- transformation process;
- data model;
- metric definitions;
- how to reproduce outputs;
- known limitations;
- recommended next steps.

## D8 — Executive Briefing

**Due:** Week 6  
**Location:** `deliverables/executive-briefing/`

Maximum two pages or equivalent concise briefing covering:

- major findings;
- business implications;
- recommended actions;
- significant limitations;
- recommended next phase.

## D9 — Final Presentation

**Due:** Mettelo Demo Day  
**Location:** `deliverables/presentation/`

15–20 minute team presentation plus Q&A.

All team members should be able to explain their contribution.

## D10 — Contribution Record

**Due:** Final submission  
**Location:** `CONTRIBUTIONS.md`

For every team member:

- project role;
- responsibilities;
- major deliverables;
- links to commits/PRs/issues where practical;
- presentation contribution.

Commit count alone is not sufficient evidence.
