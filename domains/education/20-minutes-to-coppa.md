---
title: "20 minutes to COPPA"
description: "What the Children's Online Privacy Protection Rule asks of websites, apps, and edtech tools used by children under 13, including the 2025 amendments, and what the team needs to know."
domain: Education
rules: "Children's Online Privacy Protection Act (15 U.S.C. §§ 6501 to 6506) and the COPPA Rule (16 CFR Part 312)"
reviewed: 2026-11-19
---

**Read this if** you build or run a website, app, game, connected toy, or learning tool that children under 13 use, or you work at a school choosing such tools.

## Who's covered

COPPA and the FTC's rule control how online services collect, use, and share personal information from children under 13. The FTC's 2025 amendments took effect June 23, 2025, and most had to be in place by April 22, 2026.

You're an "operator" if your service:

- is **directed to children**, judged by subject matter, visuals, animated characters, music, ads, the age of models and celebrities, and who actually uses it, or
- is a general audience service with **actual knowledge** that it collects from a particular child under 13.

Ad networks and plug-ins that know they collect from a child-directed service are covered too. A "mixed audience" service can age-screen users and apply COPPA only to those under 13, if it collects nothing before the screen.

**Personal information** includes name, address, email or screen name, phone number, photos, video or audio of a child, precise geolocation, and persistent identifiers such as cookies, device IDs, and IP addresses that recognize a user over time. The 2025 amendments added **biometric identifiers**, such as voiceprints and face templates, and **government-issued identifiers**.

## What the rule requires

1. **Notices.** A clear privacy notice on the service, and a direct notice to parents before collecting, saying what you collect, how you use it, and who gets it.
2. **Verifiable parental consent** before collecting, using, or disclosing a child's information. Approved methods include a signed form, a card transaction with notice, a call or video call with trained staff, a government ID check (then delete it), knowledge-based questions, and, since 2025, a face match against a government photo ID. Email plus a follow-up step works only when you don't disclose the information to others.
3. **Separate consent for disclosure to third parties**, such as for targeted advertising, unless integral to the service. New in 2025.
4. **Parent rights.** Parents can review the information, have it deleted, and refuse further collection. You can't require a child to give more than reasonably necessary to take part in an activity.
5. **A written security program.** New in 2025: a designated coordinator, at least annual risk assessments and reviews, safeguards sized to the risk, and regular testing. Get written assurances from service providers and third parties.
6. **A written retention policy.** Keep information only as long as reasonably necessary, then delete it securely. State the purposes, the business need, and the deletion timeframe in your privacy notice.

Exceptions to prior consent are narrow: collecting a parent's email address to ask for consent, or using a persistent identifier only for internal operations such as keeping a session working or preventing fraud, not to build a profile or serve targeted ads.

## Schools and edtech

A school can consent for parents when an edtech operator collects information only for the school's educational use and no other commercial purpose. If the operator wants the data for advertising or building products, parental consent is needed. Schools also have [FERPA](20-minutes-to-ferpa.md) obligations for the same data.

## What the team needs to know

COPPA sets no training requirement, but the security program expects people to know their part.

1. **Know whether the service is child-directed or mixed audience**, and where the age screen sits.
2. **Collect nothing from a child before consent** except what an exception allows.
3. **Check every SDK, analytics tool, and ad library** before it ships in a child-directed product. Many collect persistent identifiers by default.
4. **Route parent requests** to review or delete data, and act on them.
5. **Follow the retention schedule**, and report a security incident right away.

## What the business needs on paper

- A reasoned assessment of whether the service is child-directed, mixed audience, or general audience.
- The privacy notice, parent notice, and consent records.
- A list of third parties and SDKs that receive children's information, with written assurances.
- The written security program and retention policy.
- For edtech: school agreements covering school-authorized consent, deletion, and no commercial use.

## Penalties and enforcement

The FTC and state attorneys general enforce COPPA. Civil penalties can reach $53,088 per violation, and the FTC continues to apply that amount in 2026. Cases against app makers, toy companies, and video platforms have ended in penalties from thousands to hundreds of millions of dollars, plus deletion of data and algorithms built from it.

The usual mistakes are treating "users must be 13" in the terms as an age screen when the content plainly draws children, kids' apps with third-party SDKs collecting advertising IDs, and relying on school consent while also using the data for marketing. Ask an attorney whether your service is child-directed and your consent method meets the rule.

## Check yourself

1. Your educational game uses cartoon characters and is marketed to elementary school students, but the terms say users must be 13. Is it covered?
2. Can a school consent on parents' behalf?
3. Do you need separate consent to share children's data with an ad network?

<details>
<summary>Answers</summary>

1. Very likely yes. Content, marketing, and audience decide whether a service is child-directed, not the terms of service.
2. Yes, when the operator collects the information only for the school's educational use and for no other commercial purpose.
3. Yes, unless the disclosure is integral to the service.

</details>

## Sources

- [15 U.S.C. §§ 6501 to 6506](https://www.law.cornell.edu/uscode/text/15/chapter-91), the COPPA statute.
- [16 CFR Part 312](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-C/part-312), the COPPA Rule. Definitions: [§ 312.2](https://www.ecfr.gov/current/title-16/section-312.2). Consent: [§ 312.5](https://www.ecfr.gov/current/title-16/section-312.5). Security program: [§ 312.8](https://www.ecfr.gov/current/title-16/section-312.8). Retention: [§ 312.10](https://www.ecfr.gov/current/title-16/section-312.10).
- FTC, [Children's Online Privacy Protection Rule](https://www.federalregister.gov/documents/2025/04/22/2025-05904/childrens-online-privacy-protection-rule), final rule, 90 FR 16918 (April 22, 2025), effective June 23, 2025, compliance by April 22, 2026.
- FTC, [Complying with COPPA: Frequently Asked Questions](https://www.ftc.gov/business-guidance/resources/complying-coppa-frequently-asked-questions), including the section on schools.
- FTC, [Civil Penalty Inflation Adjustments](https://www.federalregister.gov/documents/2026/09/15/2026-18853/civil-penalty-inflation-adjustments), 91 FR 58446 (September 15, 2026), keeping 2025 amounts for 2026, and [Adjustments to Civil Penalty Amounts](https://www.federalregister.gov/documents/2025/01/17/2025-01361/adjustments-to-civil-penalty-amounts), 90 FR 5580 (January 17, 2025).
