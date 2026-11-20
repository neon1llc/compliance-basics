---
title: "20-day learning plan: Payments"
description: "A 20-day learning plan that walks a small merchant through the work to shrink its card data footprint, train staff, and file an honest PCI DSS self-assessment."
domain: Payments
reviewed: 2026-11-12
---

Read [20 minutes to PCI DSS](20-minutes-to-pci-dss.md) first. Each day is one to two hours for the person leading the effort. The pace is for learning, not a deadline, and finishing the plan doesn't make a business compliant. Skip steps already done, and keep the order.

## The plan

| Day | Do this |
|---|---|
| 1 | Name one person responsible for PCI compliance. |
| 2 | List every way you take cards: counter, phone, online, invoices, events, and mobile readers. |
| 3 | Draw a simple diagram of how card data moves for each channel. Note every place it could be written, stored, or recorded. |
| 4 | Search for stored card data: order forms, spreadsheets, email, shared drives, and call recordings. |
| 5 | Securely delete any card data you don't need, and all stored security codes. |
| 6 | Ask your acquirer which SAQ applies and whether you need ASV scans. Get the login for their compliance portal. |
| 7 | List your payment service providers and download each one's Attestation of Compliance. |
| 8 | Consider a hosted payment page or P2PE terminals to shrink your scope. Get quotes if needed. |
| 9 | Change every default password on terminals, routers, and the point-of-sale system. |
| 10 | Separate the payment network from guest Wi-Fi and personal devices. |
| 11 | Turn on multi-factor authentication for the payment portal, virtual terminal, and remote access. |
| 12 | List payment terminals with serial numbers and locations. Photograph each one for comparison. |
| 13 | Inspect each terminal for tampering. Set a schedule for repeat checks. |
| 14 | Write or update the security policy, acceptable use policy, and incident response plan. |
| 15 | Schedule training for all staff. Use the [facilitator guide](../../training/facilitator-guide.md). |
| 16 | Run the training. Collect each person's signed acknowledgment of the security policy. |
| 17 | Schedule ASV scans if required and fix what they find. |
| 18 | Complete the SAQ with honest answers. Note anything that isn't in place yet. |
| 19 | Fix the gaps, or agree a plan and dates with your acquirer. |
| 20 | Submit the SAQ and Attestation of Compliance. Set the calendar for scans, terminal checks, training, and next year's SAQ. |

## After day 20

Quarterly: ASV scans, if your SAQ requires them. On a set schedule: terminal tamper inspections. Each year: training, policy acknowledgments, a policy review, a check of each provider's Attestation of Compliance, and a new SAQ. A new payment channel, provider, or terminal means a fresh look at your SAQ type.

## Sources

- [20 minutes to PCI DSS](20-minutes-to-pci-dss.md), with references to PCI DSS v4.0.1.
- PCI Security Standards Council, [Document Library](https://www.pcisecuritystandards.org/document_library/), for the standard and the SAQs.
- PCI Security Standards Council, [Merchant resources](https://www.pcisecuritystandards.org/merchants/).
