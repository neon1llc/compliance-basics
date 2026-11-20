---
title: "20 minutes to SOC 2"
description: "What a SOC 2 report is, who asks for one, what it takes to get one, and what staff need to know, with a pointer to the full SOC 2 Readiness course."
domain: Security
rules: "AICPA SOC 2 examinations and the 2017 Trust Services Criteria"
reviewed: 2026-11-19
---

**Read this if** a customer has asked for your SOC 2 report, a deal is stuck on a security questionnaire, or you sell software or services that hold other companies' data. For the full hands-on course, with a controls map, evidence checklists, and templates, see [SOC 2 Readiness](https://github.com/neon1llc/soc-2-readiness).

## What SOC 2 is

SOC 2 is a report, not a certification and not a law. An independent CPA firm examines your controls and issues an opinion under American Institute of Certified Public Accountants (AICPA) standards. Larger and regulated customers often require it in contracts.

Controls are judged against the AICPA's **Trust Services Criteria**. Security (the "common criteria") is in every report. You can add Availability, Confidentiality, Processing Integrity, and Privacy if customers need them.

- **Type 1** covers whether controls are designed properly as of a single date.
- **Type 2** also covers whether they worked over a period, usually 3 to 12 months. Customers generally want Type 2.

## What it takes

1. **Decide why and for whom.** Confirm a customer needs SOC 2 and not something lighter, such as a completed questionnaire.
2. **Draw the boundary.** Pick the system, the criteria, and how vendors such as your cloud provider are treated.
3. **Assess risk,** then **put controls in place and write policies.** Most companies end up with dozens.
4. **Collect evidence as you go.** Auditors test samples, so controls must leave records: tickets, logs, review sign-offs, and training records.
5. **Choose an audit firm** and run a readiness review. A compliance platform (Vanta, Drata, and Secureframe are examples, not endorsements) can collect evidence once your controls exist, but it doesn't choose your scope or do the work.
6. **Get through the observation period** for a Type 2, then the audit.

## Training and staff habits

Auditors look for security awareness training at hire and at least yearly, a signed acknowledgment of the code of conduct and security policies at hire and yearly, role-specific training for engineers, support staff, and admins, and records for everyone in scope, including contractors. Missing records for sampled people produce exceptions in the report. The [acknowledgment form](../../templates/acknowledgment-form.md) and [training log](../../templates/training-log.csv) here work as evidence.

Staff follow the habits in [20 minutes to the NIST Cybersecurity Framework](20-minutes-to-nist-csf.md), plus a few an auditor will test:

1. **Follow the process even when it's slow.** Changes need a ticket and a review. Access needs an approved request.
2. **Leave a record.** An unrecorded control counts as not done.
3. **Complete training and acknowledgments on time.**
4. **Report incidents and near misses**, so the incident process has real entries.
5. **Tell IT when someone leaves or changes roles**, so access is removed on time.

Only a licensed CPA firm can issue a SOC 2 report, and nothing here promises an auditor will accept your evidence.

## Check yourself

1. Is SOC 2 a certification?
2. What's the difference between Type 1 and Type 2?
3. Why do training records matter so much in a SOC 2 audit?

<details>
<summary>Answers</summary>

1. No. It's an attestation report with a CPA firm's opinion on your controls.
2. Type 1 covers design at a point in time. Type 2 also covers whether controls operated effectively over a period.
3. Auditors test samples of people, and a missing record counts as an exception in the report.

</details>

## Sources

- AICPA and CIMA, [System and Organization Controls: SOC suite of services](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services).
- AICPA, [2017 Trust Services Criteria for Security, Availability, Processing Integrity, Confidentiality, and Privacy (with revised points of focus, 2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022). Training and competence: CC1.4 and CC2.2.
- neon1, [SOC 2 Readiness](https://github.com/neon1llc/soc-2-readiness), SOC 2 readiness course, controls map, and templates.
- neon1, [Ready, Secure, Go](https://github.com/neon1llc/ready-secure-go), plain-language SOC 2 track.
