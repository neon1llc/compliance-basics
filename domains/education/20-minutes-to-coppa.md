---
title: "20 minutes to COPPA"
description: "What the Children's Online Privacy Protection Rule asks of websites, apps, and edtech tools used by children under 13, including the 2025 amendments, and what the team needs to know."
domain: Education
rules: "Children's Online Privacy Protection Act (15 U.S.C. §§ 6501 to 6506) and the COPPA Rule (16 CFR Part 312)"
reviewed: 2026-11-19
---

**Read this if** you build or run a website, app, game, connected toy, or learning tool that children under 13 use, or you work at a school choosing such tools. It also applies to general audience services that know they're collecting information from a child under 13, and to ad networks and plug-ins that know they're collecting from users of a child-directed service.

## What COPPA is

The Children's Online Privacy Protection Act (COPPA) and the FTC's rule under it control how online services collect, use, and share personal information from children under 13. The core requirement is notice to parents and verifiable parental consent before collecting a child's personal information, with a few narrow exceptions.

The FTC's 2025 amendments took effect June 23, 2025, and most had to be in place by April 22, 2026.

## Who's covered

You're an "operator" covered by COPPA if your website or online service:

- is **directed to children** under 13, judged by its subject matter, visual content, animated characters, music, ads, the age of models and celebrities, and evidence about who actually uses it, or
- is a general audience service with **actual knowledge** that it collects personal information from a particular child under 13.

A "mixed audience" service can age-screen users and apply COPPA only to those under 13, if it collects nothing before the screen.

## What counts as personal information

Name, address, email address or screen name, phone number, Social Security number, photos, videos, or audio of a child, precise geolocation, and persistent identifiers such as cookies, device IDs, and IP addresses that recognize a user over time and across services. The 2025 amendments added **biometric identifiers**, such as voiceprints and face templates, and **government-issued identifiers** such as passport and state ID numbers.

## What the rule requires

1. **A clear privacy notice** on the service, and a direct notice to parents before collecting information, saying what you collect, how you use it, and who you share it with.
2. **Verifiable parental consent** before collecting, using, or disclosing a child's personal information. Approved methods include a signed form, a card transaction with notice, a call or video call with trained staff, a government ID check (then delete it), knowledge-based questions, and, since 2025, a face match against a government photo ID. Email plus a follow-up step works only when you don't disclose the information to others.
3. **Separate consent for disclosure to third parties**, for example for targeted advertising, unless the disclosure is integral to the service. This is new in the 2025 amendments.
4. **Parent rights.** Parents can review their child's information, have it deleted, and refuse further collection. You can't require a child to give more than is reasonably necessary to take part in an activity.
5. **A written information security program.** New in 2025, with a designated coordinator, at least annual risk assessments, safeguards sized to the risk, regular testing, and at least annual review. Get written assurances from service providers and third parties that they can protect children's information.
6. **A written data retention policy.** Keep children's information only as long as reasonably necessary for the purpose it was collected for, then delete it securely. The policy must state the purposes, the business need, and the deletion timeframe, and appear in your privacy notice.

Exceptions to prior consent are narrow: collecting a parent's email address to ask for consent, or using a persistent identifier only to support the internal operations of the service, such as keeping a session working or preventing fraud, and not to build a profile or serve targeted ads.

## Schools and edtech

The FTC's guidance says a school can consent on parents' behalf when an edtech operator collects children's information only for the school's educational use and no other commercial purpose. The operator still gives the school the full notice, and the school can review and delete the information. If the operator wants the data for its own purposes, such as advertising or building products, parental consent is needed.

Schools have [FERPA](20-minutes-to-ferpa.md) obligations for the same data.

## What the team needs to know

COPPA sets no training requirement, but its security program expects people to know their part.

1. **Know whether the service is child-directed or mixed audience**, and where the age screen sits. Cartoon characters, kid-focused ads, and child celebrities in marketing count as evidence that it's child-directed.
2. **Collect nothing from a child before consent** except what an exception allows.
3. **Check every SDK, analytics tool, and ad library** before it ships in a child-directed product. Many collect persistent identifiers by default. No targeted advertising to children without the separate consent the rule requires.
4. **Route parent requests** to review or delete data to the right person, and act on them.
5. **Follow the retention schedule**, and report a security incident right away.

## What the business needs on paper

- An assessment, with reasons, of whether the service is child-directed, mixed audience, or general audience.
- The privacy notice, the direct notice to parents, and records of parental consent.
- A list of every third party and SDK that receives children's information, with written assurances.
- The written information security program with its annual risk assessments and reviews, and the written data retention policy.
- For edtech: school agreements covering school-authorized consent, deletion, and no commercial use.

## Penalties and enforcement

The FTC and state attorneys general enforce COPPA. Civil penalties can reach $53,088 per violation, and the FTC continues to apply that amount in 2026. Cases against app makers, toy companies, and video platforms have ended in penalties from thousands to hundreds of millions of dollars, plus deletion of data and algorithms built from it.

The usual mistakes are treating "users must be 13" in the terms of service as an age screen when the content plainly draws children, third-party SDKs in a kids' app collecting advertising IDs, and relying on school consent while also using the data for product marketing. Ask an attorney whether your service is child-directed and whether your consent method meets the rule.

## Check yourself

1. Your educational game uses cartoon characters and is marketed to elementary school students, but the terms say users must be 13. Is it covered?
2. Can a school consent on parents' behalf?
3. Do you need separate consent to share children's data with an ad network?
4. Is a device ID personal information under COPPA?

<details>
<summary>Answers</summary>

1. Very likely yes. Content, marketing, and audience decide whether a service is child-directed, not the terms of service.
2. Yes, when the operator collects the information only for the school's educational use and for no other commercial purpose.
3. Yes, unless the disclosure is integral to the service.
4. Yes, when it can recognize a user over time and across services. Using it only to support internal operations is an exception to prior consent.

</details>

## Sources

- [15 U.S.C. §§ 6501 to 6506](https://www.law.cornell.edu/uscode/text/15/chapter-91), the COPPA statute.
- [16 CFR Part 312](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-C/part-312), the COPPA Rule. Definitions: [§ 312.2](https://www.ecfr.gov/current/title-16/section-312.2). Consent: [§ 312.5](https://www.ecfr.gov/current/title-16/section-312.5). Security program: [§ 312.8](https://www.ecfr.gov/current/title-16/section-312.8). Retention: [§ 312.10](https://www.ecfr.gov/current/title-16/section-312.10).
- FTC, [Children's Online Privacy Protection Rule](https://www.federalregister.gov/documents/2025/04/22/2025-05904/childrens-online-privacy-protection-rule), final rule, 90 FR 16918 (April 22, 2025), effective June 23, 2025, compliance by April 22, 2026.
- FTC, [Complying with COPPA: Frequently Asked Questions](https://www.ftc.gov/business-guidance/resources/complying-coppa-frequently-asked-questions), including the section on schools.
- FTC, [Civil Penalty Inflation Adjustments](https://www.federalregister.gov/documents/2026/09/15/2026-18853/civil-penalty-inflation-adjustments), 91 FR 58446 (September 15, 2026), keeping 2025 amounts for 2026, and [Adjustments to Civil Penalty Amounts](https://www.federalregister.gov/documents/2025/01/17/2025-01361/adjustments-to-civil-penalty-amounts), 90 FR 5580 (January 17, 2025).
