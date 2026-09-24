# ISO/IEC 27001:2022 Gap Assessment

A full Annex A gap assessment: all 93 controls of ISO/IEC 27001:2022, assessed against a fictional mid-size company transitioning from ISO 27001:2013 certification to the 2022 revision.

This is a non-technical GRC deliverable — no code, no infrastructure — modelling the actual documents a GRC analyst or ISO 27001 consultant produces during a real gap assessment engagement.

## Scenario

**Meridian Analytics Ltd**, a fictional SaaS analytics company, already holds ISO/IEC 27001:2013 certification. This assessment was performed ahead of their Stage 2 transition audit to the 2022 revision, which restructured Annex A from 114 controls across 14 domains into 93 controls across 4 themes and introduced several new control requirements.

## Deliverables

- **`deliverables/ISO27001_2022_Gap_Assessment.xlsx`** — the working assessment file:
  - **Cover** — scope, methodology, maturity and priority rating legends
  - **Dashboard** — live summary statistics, a stacked bar chart (controls by theme and maturity), and a pie chart (findings by priority) — all formula-driven
  - **Gap Assessment Matrix** — all 93 Annex A controls rated, with evidence notes, gap descriptions, priority, target remediation date (calculated by formula), and owner
  - **Remediation Roadmap** — the 17 findings requiring action, sorted by priority, with a status tracker
  - **Reference Data** — lookup tables backing the formulas (maturity scores, priority-to-SLA mapping)

- **`deliverables/ISO27001_2022_Gap_Assessment_Executive_Summary.docx`** — the management-facing report: purpose, methodology, summary statistics, the full findings table, prioritised recommendations, and next steps.

## Findings summary

- 93 controls assessed; 17 (18%) rated below an acceptable maturity threshold
- 8 High priority (Not Implemented), 9 Medium priority (Partially Implemented)
- 81.7% of controls already operating at an acceptable maturity level
- Gaps concentrate in two areas: controls new to the 2022 revision (threat intelligence, configuration management, data leakage prevention, monitoring activities) not yet built out under the legacy 2013-based ISMS, and a handful of existing controls where policy exists but isn't yet technically enforced

## Methodology

Each control was rated on a 5-point maturity scale (Not Implemented → Implemented - Reviewed & Effective), assigned an owner, and — where a gap exists — a priority and target remediation date calculated from the assessment date via a priority-to-SLA lookup table (High: 60 days, Medium: 120 days, Low: 180 days).

## Note

This is a self-directed portfolio project modelling a real ISO/IEC 27001:2022 gap assessment methodology against a fictional company. All findings, ratings, and dates are illustrative.

## Author

Sanika Mahamulkar - MSc Cybersecurity, University of Bristol
