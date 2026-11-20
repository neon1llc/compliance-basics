---
title: "20 minutes to HIPAA"
description: "What HIPAA asks of medical practices, health plans, and their vendors, and what the workforce has to know."
domain: Healthcare
rules: "HIPAA Privacy, Security, and Breach Notification Rules (45 CFR Parts 160 and 164)"
reviewed: 2026-11-19
---

**Read this if** you work at a medical, dental, behavioral health, or therapy practice, a pharmacy, a lab, a health plan, or a billing company, or you sell a service to one that touches patient information: IT support, cloud hosting, answering services, shredding, or software.

## Who HIPAA covers

**Covered entities** are health plans, health care clearinghouses, and health care providers who send health information electronically in standard transactions, such as billing an insurer. A therapist who takes only cash and never bills insurance electronically may not be covered. Almost every practice that takes insurance is.

**Business associates** do work for a covered entity and create, receive, keep, or send protected health information while doing it: a managed IT provider with access to the practice's server, a cloud backup service, a transcription service, a consultant who reviews charts. Their subcontractors who touch the same information are business associates too.

A business associate needs a signed business associate agreement (BAA) with each covered entity it serves and each subcontractor it passes the information to. HHS publishes sample language. If it's unclear whether you're covered, use the CMS [covered entity decision tool](https://www.cms.gov/priorities/key-initiatives/burden-reduction/administrative-simplification/hipaa/covered-entities) or ask a health care attorney.

## What counts as protected health information

Protected health information (PHI) is health information that identifies a person, or could reasonably be used to, and that a covered entity or business associate holds or sends in any form: paper, electronic, or spoken. It includes diagnoses, test results, and prescriptions, and also the fact that someone is a patient, an appointment time, a billing record, and a photo taken in an exam room.

Not PHI: employment records a covered entity keeps as an employer, education records covered by FERPA, and properly de-identified information.

## The three rules

### The Privacy Rule

It says when PHI may be used and shared, and gives patients rights over their information.

- **Treatment, payment, and health care operations.** PHI can be used and shared for these without written authorization, such as sending records to a specialist or billing an insurer.
- **Minimum necessary.** For most other uses, people see and share only the PHI the task needs. The billing clerk doesn't need the full chart.
- **Authorization.** Marketing, most sales of PHI, and sharing psychotherapy notes need the patient's written authorization.
- **Notice of Privacy Practices.** Covered providers give patients a notice of how their information is used and what their rights are, and post it in the office and on the website.
- **Right of access.** Patients can see and get a copy of their records, including electronic copies in the form they ask for if the practice can produce it. The practice has 30 days to respond, with one 30-day extension if it tells the patient why in writing. Any fee must be reasonable and cost based.

### The Security Rule

It covers electronic PHI (ePHI) and requires administrative, physical, and technical safeguards that fit the organization's size and risk.

- **Risk analysis.** An accurate, thorough look at where ePHI lives and what could go wrong, kept current. A missing or stale risk analysis appears in a large share of HHS enforcement actions. The [HHS Security Risk Assessment Tool](https://www.healthit.gov/topic/privacy-security-and-hipaa/security-risk-assessment-tool) is built for small practices.
- **Access control.** A unique user ID for each person, automatic logoff, and access limited to what each role needs.
- **Audit controls.** Systems that record who looked at or changed ePHI, and someone who reviews the records.
- **Integrity and transmission security.** Protect ePHI from improper change, and encrypt it in transit where reasonable.
- **Contingency planning.** Backups, a disaster recovery plan, and a way to keep caring for patients when systems are down.
- **Training** for the whole workforce.

"Addressable" safeguards are not optional. The organization decides whether the safeguard is reasonable for it, and if not, documents why and what it does instead.

### The Breach Notification Rule

A breach is an impermissible use or disclosure of unsecured PHI. Any such incident is presumed a breach unless a documented risk assessment shows a low probability that the information was compromised. If it's a breach:

- **Patients** get written notice without unreasonable delay and no later than 60 calendar days after discovery.
- **HHS** gets notice at the same time if 500 or more people are affected. Smaller breaches go in a log and are reported to HHS within 60 days after the end of the calendar year.
- **The media** gets notice when more than 500 residents of one state or jurisdiction are affected.
- **Business associates** tell the covered entity, also within 60 days of discovery. Many BAAs set a shorter deadline, often 5 to 10 days.

Properly encrypted PHI, with the key kept safe, is "secured," and losing it is not a reportable breach. Full-disk encryption on laptops and phones is one of the best investments a small practice can make. State breach laws can add their own deadlines.

## What every workforce member needs to know

HIPAA requires training for all workforce members, including volunteers, trainees, and temps, on the privacy procedures their jobs need, plus a security awareness program for everyone. Privacy training is due within a reasonable time after a person starts and after a material policy change. The rule doesn't say "annually," but annual is the norm and the easiest to prove to an investigator.

1. **Look only at what your job needs.** Opening a neighbor's, coworker's, relative's, or celebrity's chart out of curiosity is a violation even if you tell no one. Record systems log every view.
2. **Verify before you share.** Confirm a caller's identity, and check the fax number, email address, and name on the envelope.
3. **Use the approved tools.** Don't text PHI from a personal phone, email it from a personal account, or paste it into an unapproved app, including AI chat tools, unless the practice has a BAA with that vendor.
4. **Keep it out of sight and earshot, and off social media**, even without names. Lock screens, shred paper, and hand old devices to IT for wiping.
5. **Report phishing and mistakes right away.** Most health care breaches start with a stolen password or a malicious attachment. A misdirected fax or lost phone is far easier to handle on day 1 than day 59. The 60-day clock starts when anyone in the workforce knows, not when the privacy officer hears.
6. **Know your privacy officer and security officer**, and send access requests to the right person promptly.

## What the business needs on paper

HIPAA requires you to keep required policies, procedures, and records of required actions, including training, for six years from creation or last effective date, whichever is later.

- A named privacy officer and security officer (one person can hold both in a small practice).
- Written privacy and security policies, and a sanctions policy.
- A current risk analysis and a plan that tracks the fixes.
- A posted Notice of Privacy Practices, and signed BAAs.
- Training records ([training log](../../templates/training-log.csv)).
- An incident and breach log, including risk assessments for incidents you decided were not breaches.
- Backup, disaster recovery, and emergency operations plans.

## Penalties and enforcement

The HHS Office for Civil Rights (OCR) enforces HIPAA, usually after a patient complaint or breach report, and cases end in corrective action, a settlement, or a civil money penalty. State attorneys general can also bring HIPAA cases.

Civil penalties come in four tiers based on culpability. After the January 2026 inflation adjustment, per-violation amounts run from $145 at the lowest tier up to $2,190,294 for willful neglect that isn't corrected, with a calendar-year cap of $2,190,294 for violations of the same requirement. Since 2019, OCR has applied lower annual caps to the first three tiers as a matter of enforcement discretion.

The Department of Justice prosecutes criminal violations: knowingly obtaining or disclosing PHI in violation of the law carries up to $50,000 and one year in prison, up to $100,000 and five years under false pretenses, and up to $250,000 and ten years with intent to sell or use the information for gain or harm.

## What's changing

- **Security Rule update.** HHS proposed a rewrite in January 2025 that would remove the addressable label from most safeguards, require encryption and multi-factor authentication with few exceptions, and require a written asset inventory and network map. As of this guide's review date it is still a proposal.
- **Substance use disorder records (42 CFR Part 2).** A 2024 rule brought Part 2 closer to HIPAA. Covered programs had to comply by February 16, 2026.
- **Reproductive health privacy rule.** A federal court in Texas vacated this 2024 rule in June 2025. Check with counsel before changing your forms.
- **Ad pixels.** Website pixels on appointment pages that send visitor information to advertisers are a known risk. OCR has warned about them, a federal court narrowed that guidance in 2024, and class actions continue.

Ask a health care attorney whether you're a covered entity, whether an incident is a reportable breach, and how to answer an OCR inquiry.

## Check yourself

1. A receptionist looks up a friend's appointment history but tells no one. Is that a HIPAA violation?
2. A laptop holding patient records is stolen from a car. Its disk was encrypted, and the password was not with it. Is it a reportable breach?
3. Your IT company can log in to the server that holds patient records. What do you need from them?

<details>
<summary>Answers</summary>

1. Yes. Looking at PHI without a job reason is an impermissible use, even without sharing it.
2. Generally no. Properly encrypted PHI is secured, and losing secured PHI is not a reportable breach. Document the incident and your reasoning anyway.
3. A signed business associate agreement, and assurance that they protect the information as the Security Rule requires.

</details>

## Sources

- [45 CFR Part 160](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-160) and [Part 164](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164), the HIPAA rules. Training: [§ 164.530(b)](https://www.ecfr.gov/current/title-45/section-164.530) and [§ 164.308(a)(5)](https://www.ecfr.gov/current/title-45/section-164.308). Records kept six years: § 164.530(j) and [§ 164.316(b)](https://www.ecfr.gov/current/title-45/section-164.316). Breach notice: [§§ 164.400 to 164.414](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D). Right of access: [§ 164.524](https://www.ecfr.gov/current/title-45/section-164.524).
- HHS, [Summary of the HIPAA Privacy Rule](https://www.hhs.gov/hipaa/for-professionals/privacy/laws-regulations/index.html), [Summary of the HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html), and [Breach Notification Rule](https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html).
- HHS, [Covered Entities and Business Associates](https://www.hhs.gov/hipaa/for-professionals/covered-entities/index.html) and [Sample Business Associate Agreement Provisions](https://www.hhs.gov/hipaa/for-professionals/covered-entities/sample-business-associate-agreement-provisions/index.html).
- HHS, [Individuals' Right to Access Their Health Information](https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/access/index.html).
- HHS, [Annual Civil Monetary Penalties Inflation Adjustment](https://www.federalregister.gov/documents/2026/01/28/2026-01688/annual-civil-monetary-penalties-inflation-adjustment), 91 FR 3665 (January 28, 2026). Penalty tiers: [45 CFR § 160.404](https://www.ecfr.gov/current/title-45/section-160.404). Lower annual caps: HHS, [Notification of Enforcement Discretion Regarding HIPAA Civil Money Penalties](https://www.federalregister.gov/documents/2019/04/30/2019-08530/notification-of-enforcement-discretion-regarding-hipaa-civil-money-penalties), 84 FR 18151 (April 30, 2019).
- U.S. District Court for the Northern District of Texas, *Purl v. HHS*, No. 2:24-cv-228 (June 18, 2025), vacating most of the [2024 reproductive health care privacy rule](https://www.federalregister.gov/documents/2024/04/26/2024-08503/hipaa-privacy-rule-to-support-reproductive-health-care-privacy), 89 FR 32976.
- [42 U.S.C. § 1320d-6](https://www.law.cornell.edu/uscode/text/42/1320d-6), criminal penalties.
- HHS, [HIPAA Security Rule To Strengthen the Cybersecurity of Electronic Protected Health Information](https://www.federalregister.gov/documents/2025/01/06/2024-30983/hipaa-security-rule-to-strengthen-the-cybersecurity-of-electronic-protected-health-information), proposed rule, 90 FR 898 (January 6, 2025).
- HHS, [Confidentiality of Substance Use Disorder (SUD) Patient Records](https://www.federalregister.gov/documents/2024/02/16/2024-02544/confidentiality-of-substance-use-disorder-sud-patient-records), final rule, 89 FR 12472 (February 16, 2024).
- ONC and OCR, [Security Risk Assessment Tool](https://healthit.gov/privacy-security/security-risk-assessment-tool/).
- HHS, [HHS Cyber Gateway](https://hhscyber.hhs.gov/), the home of the 405(d) Program and Health Industry Cybersecurity Practices (HICP): practical safeguards sized to small, medium, and large organizations.
- CMS, [Are You a Covered Entity?](https://www.cms.gov/priorities/key-initiatives/burden-reduction/administrative-simplification/hipaa/covered-entities).
