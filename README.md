# Dialysis ESRD Bundle Reimbursement Recovery

Recalculate ESRD bundled payments, training adjustments, comorbid factors, and outlier reimbursement at treatment level.

**Primary buyer:** Dialysis organizations and renal practices. **Evidence:** patient eligibility, ESRD PPS rates, treatments, labs, drugs, comorbidities, onset adjustments, training, outliers, claims, and remittances.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Patient eligibility registry
- Treatment ingestion
- ESRD base rate library
- Wage index adjustment
- Low-volume adjustment
- Rural adjustment
- Onset adjustment
- Comorbidity adjustment
- Training add-on calculation
- TDAPA treatment
- Outlier service calculation
- Missing treatment detection
- Claim reconciliation
- Appeal package generation
- Facility modality analytics

Run `./start.sh`, then open <http://127.0.0.1:4651>. API: `5651`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
