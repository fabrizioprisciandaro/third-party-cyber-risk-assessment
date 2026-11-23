# Assessment Registers

**Third-Party Cyber Risk Assessment | Operational Workbooks**

This folder contains the operational Excel workbooks developed for the fictional Third-Party Cyber Risk Assessment case study.

The enhanced workbook introduces automated risk calculations, evidence traceability and structured remediation tracking.

## 1. Available Workbooks

| Workbook | Description |
|---|---|
| [Enhanced Risk Register](Third_Party_Cyber_Risk_Assessment_Register_Enhanced.xlsx) | Enhanced version with automated scoring, evidence traceability and additional assessment fields |
| [Original Risk Register](Third_Party_Cyber_Risk_Assessment_Register.xlsx) | Original baseline version retained for reference and comparison |

**Recommended version:** Enhanced Risk Register.

## 2. Enhanced Workbook Structure

The enhanced workbook contains five worksheets.

### 2.1 Third-Party Register

Supplier inventory and classification, including:

- Supplier identification and service scope.
- Business ownership and data processing.
- System access and supplier criticality.
- Due diligence status.
- Expected and observed security controls.
- Evidence references and identified gaps.
- Linked cybersecurity risks.
- Review cadence and next review dates.

### 2.2 Cyber Risk Register

Structured assessment of third-party cybersecurity risks, including:

- Risk scenarios and affected assets.
- Inherent Likelihood and Impact.
- Inherent Risk Score and Rating.
- Existing and planned security controls.
- Control effectiveness assessment.
- Residual Likelihood and Impact.
- Residual Risk Score and Rating.
- Risk treatment strategy and ownership.
- ISO/IEC 27001:2022 and NIST CSF 2.0 mapping.
- Treatment threshold decisions.

Risk scores and ratings are calculated using spreadsheet formulas.

### 2.3 Treatment Plan

Tracks remediation activities and accountability:

- Action and risk identification.
- Remediation deliverables.
- Acceptance evidence.
- Assigned action owners.
- Due dates and priorities.
- Treatment status and dependencies.
- Days between assessment reference date and target date.
- Due-date position relative to the assessment snapshot.

### 2.4 Scoring & Mapping

Documents the assessment methodology, including:

- Likelihood and Impact scales.
- Risk scoring thresholds.
- Assessment reference date.
- Risk evaluation guidance.
- Framework mapping references.

### 2.5 Evidence Log

Provides traceability between suppliers, risks and supporting documentation.

Each evidence reference includes:

- Evidence ID.
- Related supplier and risk IDs.
- Evidence description and type.
- Availability and review status.
- Evidence date or period.
- Scope and coverage.
- Review outcome and limitations.
- Reviewer or responsible owner.
- Verification notes.

Evidence references are simulated. Items marked as required for validation represent expected documentation, not independently verified evidence.

## 3. Risk Scoring Model

**Risk Score = Likelihood × Impact**

Both Likelihood and Impact are assessed on a 1–5 scale.

| Score | Risk Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–15 | High |
| 16–25 | Critical |

The workbook distinguishes inherent risk from residual risk after considering the effectiveness of security controls.

Residual risk decisions remain subject to risk-owner review and organisational risk appetite.

## 4. Assessment Reference Date

**18 October 2026**

All supplier review dates, remediation deadlines and treatment statuses must be interpreted relative to this fictional assessment snapshot.

The assessment is a point-in-time simulation, not a representation of current supplier security status.

## 5. Framework References

The assessment uses:

- ISO/IEC 27001:2022, including relevant Annex A controls.
- NIST Cybersecurity Framework (CSF) 2.0.

Framework mappings are indicative and based on control intent and cybersecurity outcomes. They do not represent one-to-one equivalences or certification claims.

## 6. Important Limitations

This is an educational portfolio case study.

All supplier names, evidence references, risk scenarios, assessment results and treatment activities are fictional.

Evidence references must not be interpreted as proof that actual supplier documentation was obtained, reviewed or independently validated.

The workbook does not constitute an independent security audit, formal assurance report or certification assessment.
