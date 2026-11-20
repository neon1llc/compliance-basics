---
title: "20 minutes to PCI DSS"
description: "What the card industry's security standard asks of any business that takes card payments, and what staff need to know."
domain: Payments
rules: "PCI Data Security Standard (PCI DSS) v4.0.1"
reviewed: 2026-11-19
---

**Read this if** your business takes credit or debit cards in any way: a counter terminal, a phone order, an online checkout, or an invoice with a pay link. It also applies to service providers that handle card data or can affect its security, such as processors, hosts, and IT firms that manage a merchant's network.

## What PCI DSS is

The Payment Card Industry Data Security Standard (PCI DSS) is published by the PCI Security Standards Council, founded by the major card brands. It isn't a law. It reaches you through your agreement with your payment processor or bank (your "acquirer"), which requires PCI DSS and the card brands' rules and decides how you prove it and what happens if you don't.

The current version is v4.0.1, published in June 2024. Its "future-dated" requirements became mandatory on March 31, 2025. In June 2026 the Council opened a request for comments on the next version.

**Cardholder data** is the primary account number (PAN, the long number on the card), plus the cardholder name, expiration date, and service code when stored with the PAN. The PAN is what puts data in scope.

**Sensitive authentication data** is the full magnetic stripe or chip data, the three- or four-digit security code (CVV2, CVC2, CID), and PINs. You may not keep it after authorization, even encrypted. Writing down the security code from a phone order "for later" breaks this rule.

The cardholder data environment (CDE) is the people, processes, and technology that store, process, or send card data, plus anything connected to them. The smaller your CDE, the less of the standard applies.

## How small businesses comply

Most small merchants prove compliance yearly with a **Self-Assessment Questionnaire (SAQ)** and, depending on the SAQ, quarterly external vulnerability scans by an Approved Scanning Vendor (ASV). Larger merchants and service providers may need an on-site assessment by a Qualified Security Assessor (QSA).

| How you take cards | Usual SAQ |
|---|---|
| Online only, and a third-party processor hosts the whole payment page (redirect or embedded iframe) | SAQ A, which since 2025 also asks you to confirm your site isn't open to malicious scripts |
| Online, and your own site controls how the payment page is delivered | SAQ A-EP |
| Standalone terminals, not connected to other systems | SAQ B or SAQ B-IP |
| A validated point-to-point encryption (P2PE) terminal | SAQ P2PE |
| Typing card numbers into a processor's virtual terminal in a browser | SAQ C-VT |
| Anything else, including storing card numbers | SAQ D |

Your acquirer tells you which one to file. A wrong SAQ, such as SAQ A for a site that hosts its own payment form, is a common way to be out of compliance without knowing it.

The biggest lever is to **keep card data out of your systems**: a hosted payment page online, P2PE or tokenizing terminals in the store, and no stored card numbers. Each moves you to a shorter SAQ. Outsourcing doesn't remove responsibility, so get each provider's Attestation of Compliance and know which requirements they handle and which you do.

## The twelve requirements

1. **Network security controls** between the CDE and everything else, including guest Wi-Fi.
2. **Secure configuration.** Change vendor default passwords and settings, and turn off what you don't use.
3. **Protect stored account data.** Keep as little as possible for as short a time as possible. Mask the PAN on screen and make it unreadable where stored.
4. **Encrypt card data over open networks.** Never send card numbers by email, text, or chat.
5. **Protect against malware**, including phishing.
6. **Secure systems.** Patch promptly. For online stores, control and monitor payment page scripts to stop skimming code.
7. **Restrict access** to card data to people whose job needs it.
8. **Identify and authenticate users.** Unique IDs, strong passwords, and multi-factor authentication into the CDE.
9. **Restrict physical access.** Lock up paper with card data and inspect terminals for tampering and skimmers.
10. **Log and monitor** access to systems and card data.
11. **Test regularly.** Scans, penetration tests where required, and checks for changes to payment pages.
12. **Support security with policies and programs**: risk assessment, training, incident response, and service provider management.

## What staff need to know

Requirement 12.6 requires:

- a formal security awareness program, reviewed at least every 12 months,
- training at hire and at least every 12 months, in more than one way, such as a session plus written reminders,
- coverage of phishing and related attacks, and acceptable use of laptops, phones, and remote access,
- each person's acknowledgment, at least every 12 months, that they've read and understood the security policy,
- for staff who handle terminals, spotting tampering and device substitution (9.5.1.3).

Front-line staff should:

1. **Never write down card numbers or security codes**, or accept or send them by email, text, or chat. If a customer sends one, don't reply with it, tell your manager, and delete it as your procedure says. Never ask for a PIN.
2. **Check the terminal** for loose parts, extra layers over the keypad or card slot, broken seals, or a serial number that doesn't match the one on file.
3. **Verify repair visits.** Don't let anyone service, swap, or take a terminal without confirming with your manager or the provider. Criminals pose as technicians.
4. **Use your own login**, and watch for fake "processor" emails asking you to log in or update payment settings.
5. **Shred paperwork** with card data, and **report problems right away**: a suspected skimmer, a lost device, or a customer reporting fraud after shopping with you.

## What the business needs on paper

- A list of every way you accept cards, with the systems and providers involved and a simple diagram of how card data flows.
- Your SAQ (or Report on Compliance) and Attestation of Compliance for the year, plus ASV scan reports if required.
- An information security policy, reviewed at least every 12 months.
- A terminal list with make, model, serial number, and location, and tamper inspection records.
- A list of service providers and their PCI status.
- Training records and annual acknowledgments ([training log](../../templates/training-log.csv), [acknowledgment form](../../templates/acknowledgment-form.md)).
- An incident response plan saying who to call, including your acquirer.

## Penalties and enforcement

The PCI Council doesn't fine anyone. Card brands can assess fees and penalties against an acquirer, and acquirer agreements commonly let the acquirer pass them on to the merchant. The amounts aren't published.

After a breach, costs usually include a forensic investigation by a PCI Forensic Investigator, card brand assessments for fraud and reissuance, higher processing fees, stricter validation, and in serious cases losing the ability to accept cards. State breach notification laws can apply, and the FTC has brought cases against companies whose weak security exposed card data. After a suspected compromise, hire a PCI Forensic Investigator and an attorney.

## Check yourself

1. A customer reads their security code over the phone, and you write it down to process the order later. Is that allowed?
2. Your online store redirects to the processor's hosted payment page. Which SAQ is likely?
3. A technician arrives unannounced to replace your card terminal. What do you do?

<details>
<summary>Answers</summary>

1. No. Security codes can't be stored after authorization, including on paper. Process the payment directly while on the call.
2. SAQ A, if the processor serves the entire payment page and your site handles no card data. Confirm with your acquirer.
3. Don't hand over the device. Confirm the visit with your manager or the provider using a phone number you already have.

</details>

## Sources

- PCI Security Standards Council, [Document Library](https://www.pcisecuritystandards.org/document_library/): PCI DSS v4.0.1, the Self-Assessment Questionnaires and their instructions, and the glossary. Training: requirements 12.6.1 to 12.6.3.2 and 9.5.1.3. Sensitive authentication data: requirement 3.3.1.
- PCI Security Standards Council, [Just Published: PCI DSS v4.0.1](https://blog.pcisecuritystandards.org/just-published-pci-dss-v4-0-1) (June 2024).
- PCI Security Standards Council, [Now is the Time for Organizations to Adopt the Future-Dated Requirements of PCI DSS v4.x](https://blog.pcisecuritystandards.org/now-is-the-time-for-organizations-to-adopt-the-future-dated-requirements-of-pci-dss-v4-x) (effective March 31, 2025).
- PCI Security Standards Council, [Request for Comments: PCI DSS v4.0.1](https://blog.pcisecuritystandards.org/request-for-comments-pci-data-security-standard-pci-dss-v4.0.1) (June 2026).
- PCI Security Standards Council, [Merchant resources](https://www.pcisecuritystandards.org/merchants/), including the Guide to Safe Payments and the Data Security Essentials Evaluation Tool for small merchants.
- PCI Security Standards Council, [New Information Supplement: Payment Page Security and Preventing E-Skimming](https://blog.pcisecuritystandards.org/new-information-supplement-payment-page-security-and-preventing-e-skimming).
- Federal Trade Commission, [Data Security](https://www.ftc.gov/business-guidance/privacy-security/data-security) business guidance.
