---
title: "20 minutes to CAN-SPAM"
description: "What the CAN-SPAM Act asks of any business that sends marketing email, how it differs from what Gmail and Yahoo now require of bulk senders, and what the team needs to know."
domain: Marketing
rules: "CAN-SPAM Act (15 U.S.C. §§ 7701 to 7713) and the FTC's CAN-SPAM Rule (16 CFR Part 316)"
reviewed: 2026-11-19
---

**Read this if** your business sends newsletters, promotions, announcements, or sales emails, including one-to-one prospecting emails to other businesses. It also applies if you hire an agency or platform to send them for you.

## What CAN-SPAM is

The CAN-SPAM Act sets the rules for commercial email in the United States. It doesn't require permission before sending. It requires honesty, identification, and a working way to opt out. It covers business-to-business email too, and the FTC can hold both the business whose product is promoted and the business that sends the message responsible.

## Which messages it covers

**Commercial** messages promote a product or service, and all the requirements apply. **Transactional or relationship** messages, such as receipts, shipping notices, password resets, and account or safety notices, are exempt from most requirements but can't use false or misleading routing information. Mixed messages are judged by primary purpose, mostly from the subject line and what comes first in the body.

## The requirements

1. **No false or misleading header information.** The From name, From address, Reply-To, and routing must accurately identify the sender.
2. **No deceptive subject lines.** The subject must reflect the content.
3. **Identify the message as an ad**, clearly and conspicuously. Messages to people who gave prior affirmative consent don't need this.
4. **Include your valid physical postal address.** A street address, or a post office box or private mailbox registered under Postal Service rules.
5. **Tell people how to opt out**, clearly and conspicuously, with a reply address or a web link. You can offer a menu of choices, but one must stop all commercial email.
6. **Honor opt-outs within 10 business days.** The opt-out method must keep working for at least 30 days after you send. You can't charge a fee, ask for more than an email address and opt-out preferences, or make people do more than reply or visit a single page.
7. **Don't sell or transfer opted-out addresses**, except to a vendor helping you comply.
8. **Monitor what others send for you.** Hiring a marketing company doesn't move your responsibility to it.

The law also bans harvesting addresses from websites, guessing addresses by combining names and domains, and sending through others' computers or open relays.

## What mailbox providers require

Since February 2024, Gmail and Yahoo require bulk senders, roughly those sending more than 5,000 messages a day to their users, to:

- authenticate mail with SPF, DKIM, and DMARC,
- offer one-click unsubscribe in the headers of marketing mail and honor it within two days,
- and keep spam complaint rates low (Google sets 0.3 percent as the ceiling).

These aren't laws, but missing them sends your mail to spam or gets it rejected. Authentication also protects any sender's domain from phishing spoofs.

## Other laws that can apply

Texts fall under the [TCPA](20-minutes-to-tcpa.md). Email to people in Canada or the EU brings CASL and the GDPR, which generally require consent first. Marketing to children under 13 raises [COPPA](../education/20-minutes-to-coppa.md) issues.

## What the team needs to know

1. **Send marketing only from the approved email platform**, so opt-outs are tracked. Ask before adding tools that send for the company.
2. **Check the From name and subject line** before every send. No "Re:" or "Your order" on promotions.
3. **Every marketing email carries the postal address and an unsubscribe link** that doesn't require a login.
4. **Process opt-outs that arrive by reply, phone, or in person**, and sync them across every tool and the CRM.
5. **Never import purchased or scraped lists.**
6. **Prospecting emails count.** One-to-one sales emails to businesses still need an accurate identity, the address, and a way to opt out.

## What the business needs on paper

- A list of every tool and vendor that sends email for you, and templates with the postal address and opt-out built in.
- The suppression list, kept indefinitely and shared across tools.
- Records of how contacts joined each list.
- SPF, DKIM, and DMARC records for each sending domain.
- Training records. See the [training log](../../templates/training-log.csv).

## Penalties and enforcement

The FTC enforces CAN-SPAM, along with state attorneys general and internet access providers. Each separate email that violates the law can bring a civil penalty of up to $53,088, the amount the FTC applies in 2025 and 2026. Some violations, such as hijacking computers to send mail, are crimes. Recipients can't sue under CAN-SPAM, but state laws may let them sue over deceptive email.

Ask an attorney about email to recipients outside the United States, or if you get an inquiry from the FTC or a state.

## Check yourself

1. Does CAN-SPAM require consent before sending marketing email to U.S. recipients?
2. How long do you have to honor an opt-out?
3. Can you use a P.O. box as your postal address?
4. You hire an agency to send your promotions. Who's responsible for compliance?

<details>
<summary>Answers</summary>

1. No. It requires honest headers and subjects, identification, a postal address, and a working opt-out. Other countries' laws and mailbox provider rules may expect consent.
2. 10 business days, and the opt-out method must work for at least 30 days after the message is sent.
3. Yes, if it's registered with the U.S. Postal Service.
4. Both your business and the agency can be held responsible.

</details>

## Sources

- [15 U.S.C. §§ 7701 to 7713](https://www.law.cornell.edu/uscode/text/15/chapter-103), the CAN-SPAM Act. Requirements: [§ 7704](https://www.law.cornell.edu/uscode/text/15/7704).
- [16 CFR Part 316](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-C/part-316), the CAN-SPAM Rule, including primary purpose ([§ 316.3](https://www.ecfr.gov/current/title-16/section-316.3)) and opt-out limits ([§ 316.5](https://www.ecfr.gov/current/title-16/section-316.5)).
- FTC, [CAN-SPAM Act: A Compliance Guide for Business](https://www.ftc.gov/business-guidance/resources/can-spam-act-compliance-guide-business).
- FTC, [Adjustments to Civil Penalty Amounts](https://www.federalregister.gov/documents/2025/01/17/2025-01361/adjustments-to-civil-penalty-amounts), 90 FR 5580 (January 17, 2025), and [Civil Penalty Inflation Adjustments](https://www.federalregister.gov/documents/2026/09/15/2026-18853/civil-penalty-inflation-adjustments), 91 FR 58446 (September 15, 2026).
- Google, [Email sender guidelines](https://support.google.com/mail/answer/81126).
- Yahoo, [Sender best practices](https://senders.yahooinc.com/best-practices/).
