---
title: "20 minutes to GxP"
description: "What the good practice rules (GMP, GLP, GCP, GDP, and Part 11) ask of drug, device, lab, and clinical research teams and the IT people who support them."
domain: Life sciences
rules: "FDA 21 CFR Parts 11, 58, 210, 211, 312, and 820, ICH E6(R3), and EU GMP and GDP guidelines"
reviewed: 2026-11-19
---

**Read this if** you work at or for a company that makes, tests, studies, or ships drugs, biologics, medical devices, or dietary supplements. That includes contract manufacturers and labs, clinical research sites and CROs, and the IT providers, software vendors, and consultants who run or validate their systems.

## What "GxP" means

GxP is shorthand for the "good practice" rules in regulated life sciences. The x stands for the area:

| Rule set | Area | Main U.S. rules |
|---|---|---|
| GMP (also CGMP, "current" good manufacturing practice) | Making and testing products | 21 CFR Parts 210 and 211 (drugs), 600 to 680 (biologics), 820 (devices), 111 (dietary supplements) |
| GLP | Nonclinical lab studies that support a product application | 21 CFR Part 58 |
| GCP | Clinical trials in people | 21 CFR Parts 50, 56, 312, and 812, and the ICH E6(R3) guideline |
| GDP | Storing and distributing products | EU GDP guidelines, and in the U.S. the Drug Supply Chain Security Act and state wholesale licensing |
| Part 11 | Electronic records and signatures in any of the above | 21 CFR Part 11 |

The rules share one idea. If it isn't written down correctly, at the time, by the person who did it, the regulator treats it as if it didn't happen. Each rule asks for trained people, written procedures, controlled changes, and records that prove the work was done as written.

## The shared core

**Written procedures.** Work follows approved standard operating procedures (SOPs). People use the current version, and changes go through controlled review before anyone works to the new one. A procedure that lives in someone's head, or in an uncontrolled copy on a desktop, fails an inspection.

**Trained and qualified people.** Each rule requires education, training, and experience for the task:

- **Drug GMP.** Training covers each person's operations and the GMP rules that apply, is given by qualified people, and is frequent enough that people stay familiar with the requirements.
- **GLP.** Each person on a study needs a current summary of training and experience and a job description.
- **Part 11.** People who build, maintain, or use electronic record systems must be trained for those tasks.
- **Clinical trials.** ICH E6(R3) expects trial staff to be qualified by education, training, and experience, documented.

**Records you can trust (data integrity).** Regulators describe them with the acronym ALCOA, often extended to ALCOA+:

- **Attributable**: you can tell who did it and when.
- **Legible**: it can be read for as long as it's kept.
- **Contemporaneous**: recorded when the work was done, not later from memory.
- **Original**: the first record, or a certified true copy.
- **Accurate**: correct and complete, with errors corrected openly.
- The "+" adds complete, consistent, enduring, and available.

On paper, that means single-line strikethrough with initials, date, and reason. No white-out, pencil, backdating, sticky notes, or shared logins.

**Controlled change.** Equipment, processes, documents, and computer systems change only through documented change control, which weighs the effect on product quality or data before the change is made.

**Deviations and CAPA.** When something goes wrong, people record a deviation, investigate the root cause, and fix it through corrective and preventive action (CAPA). An organization with no deviations isn't flawless. Inspectors read it as one that doesn't record them.

## Electronic records: Part 11 and Annex 11

21 CFR Part 11 sets the conditions under which FDA accepts electronic records and signatures in place of paper. For closed systems it requires, among other things:

- validation that the system works as intended and can detect invalid or altered records,
- secure, computer-generated, time-stamped audit trails that record who created, changed, or deleted a record, without hiding the earlier value,
- access limited to authorized people,
- written policies that hold people accountable for actions taken under their electronic signature,
- and training for the people who develop, maintain, or use the system.

Electronic signatures need at least two distinct parts, such as a user ID and password, and each belongs to one person only.

FDA enforces Part 11 with a risk-based approach, and its 2025 guidance on computer software assurance encourages testing effort proportional to risk.

In the European Union, Annex 11 of EudraLex Volume 4 covers computerized systems in GMP. It closely matches Part 11 and adds supplier assessment, periodic review, and data backup. The European Commission consulted in 2025 on a revised Annex 11 and a new Annex 22 on AI in manufacturing, so check the current text.

For IT teams, a server patch, a database migration, a password reset, or a new cloud service that touches a GxP system is a regulated change. Admin accounts that can edit records or switch off audit trails are among the first things an inspector checks.

## Area by area

**GMP.** Drug GMP covers buildings, equipment, components, production and process controls, packaging and labeling, holding and distribution, lab controls, and records. A drug made without following CGMP is legally "adulterated" even if it turns out fine. Device makers follow the Quality Management System Regulation (QMSR), 21 CFR Part 820, which since February 2, 2026 incorporates ISO 13485:2016 by reference in place of FDA's older Quality System Regulation.

**GLP.** GLP covers lab studies, such as animal toxicology, that support an application to FDA. It requires a study director, an independent quality assurance unit, written protocols and SOPs, and archived raw data. FDA can disqualify a facility that fails GLP and reject its studies.

**GCP.** GCP protects trial participants and makes trial data credible. FDA's rules cover informed consent (Part 50), institutional review boards (Part 56), and the duties of sponsors and investigators (Parts 312 and 812). ICH E6(R3) was finalized in January 2025, took effect in the EU in July 2025, and was published by FDA as guidance in September 2025. It weighs quality by design and risk-proportionate management, and sets clearer expectations for computerized systems. Site staff need training on the protocol, their delegated tasks, and GCP, and the delegation log shows who may do what.

**GDP.** GDP keeps products safe between the factory and the patient: temperature control, secure storage, qualified suppliers, and traceability. In the EU, wholesale distributors follow the 2013 Guidelines on Good Distribution Practice. In the U.S., the Drug Supply Chain Security Act requires electronic tracing of prescription drugs.

## What every workforce member needs to know

Training for GxP roles is task specific, so a general session can't replace training on each person's own SOPs. Everyone in or supporting a GxP area should still know these points.

1. **Follow the current approved procedure.** If you can't follow it as written, stop, record a deviation, and raise it with your supervisor or quality. Don't improvise and fix the paperwork later.
2. **Record it when you do it**, in the approved place.
3. **Never share a login or sign for someone else.**
4. **Correct records openly.** One line through the error, the right value, your initials, the date, and the reason. In systems, use the correction function.
5. **Never delete, overwrite, or re-run to get a passing result.** Testing into compliance is one of the most serious findings FDA issues.
6. **Do only the tasks you're trained for**, once your training on the current version is recorded.
7. **Treat IT changes as regulated changes.** Patches, upgrades, and configuration changes on GxP systems go through change control.
8. **Keep records for the full retention period**, which can run years past the product's expiry or the study's end.
9. **Treat inspectors professionally.** Answer what's asked, truthfully.

## What the business needs on paper

- A quality manual or policy, and controlled SOPs with version history.
- Training records that tie each person to each SOP version they're trained on, with dates, and a training matrix by role. The [training log template](../../templates/training-log.csv) is a starting point.
- Change control, deviation, and CAPA records.
- For computer systems: an inventory of GxP systems, validation or assurance records, user access lists with periodic reviews, audit trail review records, and backup and restore tests.
- Supplier and vendor qualification records, including for software and cloud providers.

## Penalties and enforcement

FDA inspects regulated sites and lists problems on a Form FDA 483 at the end of an inspection. Serious or repeated problems lead to a warning letter, which FDA publishes. FDA can also refuse or delay product approvals, place import alerts that stop products at the border, seek seizures and injunctions, and enter consent decrees that put a company under court supervision. Clinical investigators and nonclinical labs can be disqualified, and some violations are crimes.

Inadequate training, incomplete records, missing audit trails, shared logins, and unvalidated systems are regular citations in warning letters.

This is training, not regulatory advice. Validation, inspection readiness, and submissions need qualified quality and regulatory professionals, and counsel for enforcement actions.

## Check yourself

1. A result fails, and an analyst re-runs the sample until it passes, keeping only the passing run. What's wrong?
2. What does the A in ALCOA stand for, and how does a shared login break it?
3. Is applying an operating system patch to a lab instrument's computer a GxP matter?
4. What changed for U.S. device makers on February 2, 2026?

<details>
<summary>Answers</summary>

1. It's testing into compliance. The failing result is part of the record and must be investigated, not discarded.
2. Attributable. With a shared login you can't tell who did the work.
3. Yes. It's a change to a GxP system and goes through change control, with an assessment of whether re-testing is needed.
4. The Quality Management System Regulation took effect, replacing the old Quality System Regulation and incorporating ISO 13485:2016 by reference.

</details>

## Sources

- [21 CFR Part 11](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-A/part-11), electronic records and signatures. Training: [§ 11.10(i)](https://www.ecfr.gov/current/title-21/section-11.10). Signature parts: [§ 11.200](https://www.ecfr.gov/current/title-21/section-11.200).
- [21 CFR Parts 210](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-C/part-210) and [211](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-C/part-211), drug CGMP. Training: [§ 211.25](https://www.ecfr.gov/current/title-21/section-211.25).
- [21 CFR Part 58](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-A/part-58), good laboratory practice. Personnel and training records: [§ 58.29](https://www.ecfr.gov/current/title-21/section-58.29).
- [21 CFR Part 820](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-H/part-820), Quality Management System Regulation, and FDA, [Medical Devices; Quality System Regulation Amendments](https://www.federalregister.gov/documents/2024/02/02/2024-01709/medical-devices-quality-system-regulation-amendments), final rule, 89 FR 7496 (February 2, 2024), effective February 2, 2026.
- [21 CFR Part 312](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-D/part-312), investigational new drugs, and [Part 50](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-A/part-50), informed consent.
- [21 U.S.C. § 351(a)(2)(B)](https://www.law.cornell.edu/uscode/text/21/351), drugs not made under CGMP are adulterated.
- FDA, [Part 11, Electronic Records; Electronic Signatures: Scope and Application](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/part-11-electronic-records-electronic-signatures-scope-and-application) (2003).
- FDA, [Data Integrity and Compliance With Drug CGMP: Questions and Answers](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/data-integrity-and-compliance-drug-cgmp-questions-and-answers) (2018).
- FDA, [Computer Software Assurance for Production and Quality System Software](https://www.federalregister.gov/documents/2025/09/24/2025-18468/computer-software-assurance-for-production-and-quality-system-software-guidance-for-industry-and), guidance, 90 FR 45945 (September 24, 2025).
- FDA, [E6(R3) Good Clinical Practice](https://www.federalregister.gov/documents/2025/09/09/2025-17311/e6r3-good-clinical-practice-international-council-for-harmonisation-guidance-for-industry), guidance, 90 FR 43460 (September 9, 2025), and ICH, [Efficacy guidelines](https://www.ich.org/page/efficacy-guidelines) (E6).
- European Commission, [EudraLex Volume 4](https://health.ec.europa.eu/medicinal-products/eudralex/eudralex-volume-4_en), EU GMP guidelines including Annex 11 (computerised systems).
- European Commission, [Stakeholder consultation on EudraLex Volume 4 Chapter 4, Annex 11, and new Annex 22](https://health.ec.europa.eu/consultations/stakeholders-consultation-eudralex-volume-4-good-manufacturing-practice-guidelines-chapter-4-annex_en) (7 July to 7 October 2025).
- European Commission, [Guidelines of 5 November 2013 on Good Distribution Practice of medicinal products for human use](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A52013XC1123%2801%29), 2013/C 343/01.
- FDA, [Drug Supply Chain Security Act](https://www.fda.gov/drugs/drug-supply-chain-integrity/drug-supply-chain-security-act-dscsa).
- FDA, [Warning letters](https://www.fda.gov/inspections-compliance-enforcement-and-criminal-investigations/compliance-actions-and-activities/warning-letters), searchable database.
- Further reading: GxPReady, [GxP Compliance Guide: GMP, GLP, GCP and GDP](https://gxpready.com/gxp-compliance-guide/) (2026), a vendor's overview of the same areas.
