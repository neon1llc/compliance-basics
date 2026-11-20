---
title: "20 minutes to the NIST AI Risk Management Framework"
description: "How a small business can use AI tools responsibly at work, using the NIST AI Risk Management Framework, the EU AI Act's AI literacy duty, and the U.S. rules that already apply, and what staff need to know."
domain: AI use
rules: "NIST AI Risk Management Framework 1.0 and Generative AI Profile (NIST AI 600-1), EU AI Act Article 4, and existing U.S. consumer protection, privacy, and anti-discrimination law"
reviewed: 2026-11-19
---

**Read this if** people at your business use AI chat assistants, writing or coding tools, meeting transcribers, or AI features built into software you already pay for, or if you build products that use AI. That's most businesses now.

## The rules that already apply

There's no single U.S. AI law, but the laws you already follow apply when AI is involved:

- **Confidentiality and privacy.** Pasting patient records, client tax returns, student data, or card numbers into an AI tool is a disclosure. HIPAA, the FTC Safeguards Rule, FERPA, PCI DSS, and state privacy laws apply as they do to email or any other vendor. Use only tools your business has approved and has a contract with, and check whether the vendor trains its models on your inputs.
- **Consumer protection.** The FTC has said there's no AI exemption from the laws on its books. Claims about what your AI product can do must be true and backed by evidence, and AI-generated fake reviews are banned under the FTC's 2024 rule on consumer reviews and testimonials.
- **Discrimination.** Employment, lending, housing, and insurance decisions are covered by anti-discrimination law whether a person or software makes them.
- **Intellectual property and contracts.** Customer contracts may limit where their data can go. AI output can raise copyright and accuracy questions.

Some places have AI-specific rules. New York City requires bias audits and notices for automated hiring tools (see [20 minutes to NYC Local Law 144](20-minutes-to-nyc-local-law-144.md)). Colorado replaced its 2024 AI law in May 2026 with a disclosure-focused law for automated consumer decisions, set to take effect January 1, 2027. Other states have narrower laws on chatbots, deepfakes, and AI in hiring.

## The EU AI Act and AI literacy

The EU AI Act applies to businesses that provide or use AI systems in the EU, including U.S. businesses whose AI output is used there. Its **AI literacy** duty took effect February 2, 2025. Article 4 requires providers and deployers to take measures for the AI literacy of staff and others using AI on their behalf, given their knowledge, experience, and context of use. A 2026 amendment (the "AI Omnibus") softened the wording to measures that support AI literacy and moved most high-risk system rules to December 2027 and August 2028.

For a U.S. small business with EU customers, the step is the same: train the people who use AI tools, and keep a record.

## The NIST AI Risk Management Framework

NIST released the AI Risk Management Framework (AI RMF 1.0) in January 2023, and a Generative AI Profile (NIST AI 600-1) in July 2024. It's voluntary and free, and regulators recognize it.

| Function | What it means for a small business |
|---|---|
| Govern | An AI use policy, a named owner, and rules for approving new tools |
| Map | A list of where AI is used, for what, with what data, and who's affected |
| Measure | Checking outputs for accuracy, bias, and leaks, especially where they matter most |
| Manage | Acting on what you find: limiting uses, adding human review, switching tools, or stopping |

The Generative AI Profile names risks specific to generative tools: made-up facts presented confidently ("confabulation"), leaks of personal or confidential data, harmful or biased content, intellectual property problems, and prompt injection.

## A simple AI use policy

One or two pages cover most small businesses.

1. **Approved tools.** Business accounts with data protection terms beat free personal accounts.
2. **Data rules.** What can never go into an AI tool, such as regulated personal data, credentials, and client confidential material unless the tool is approved for it.
3. **Human review.** A person checks AI output before it goes to a customer, gets filed with a regulator, changes code in production, or informs a decision about a person.
4. **Disclosure.** When to tell customers AI was used, for example in chatbots or AI-generated images.
5. **High-impact uses.** Hiring, lending, pricing, medical, or legal uses need the owner's approval and a check against the laws above.
6. **Reporting.** How to report a data leak, a harmful output, or a tool behaving oddly.

## What staff need to know

1. **Use only approved AI tools**, signed in with your work account, and **don't paste regulated or confidential data** into a tool that isn't approved for it.
2. **Check the output.** AI tools state wrong facts with confidence. Verify names, numbers, citations, and code. You own what you send.
3. **Watch for prompt injection.** Documents, web pages, and emails can hide instructions aimed at AI tools. Don't let an AI agent act on untrusted content without review.
4. **Don't use AI to make or decide hiring, firing, credit, or similar decisions** without approval.
5. **Be careful with meeting recorders.** Get consent where required, and don't record privileged or sensitive calls.
6. **Report problems**, including suspected leaks.

## What the business needs on paper

- The AI use policy, acknowledged by staff. See the [acknowledgment form](../../templates/acknowledgment-form.md).
- An inventory of AI tools and AI features in existing software, with the data each touches and vendor terms on training and retention.
- Records of reviews for high-impact uses, and AI literacy training records. See the [training log](../../templates/training-log.csv).

Ask an attorney before you use AI for hiring, lending, or other decisions about people, or if you sell AI products in the EU.

## Check yourself

1. Is it a HIPAA issue to paste a patient's chart into a free AI chat tool?
2. What are the four functions of the NIST AI RMF?
3. An AI tool drafts a client letter citing a regulation. What should you do before sending?

<details>
<summary>Answers</summary>

1. Yes. Without a business associate agreement and approval, it's an impermissible disclosure of PHI.
2. Govern, Map, Measure, and Manage.
3. Check the citation and the facts yourself. AI tools can invent or misstate sources.

</details>

## Sources

- NIST, [AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework), [AI RMF 1.0 (NIST AI 100-1)](https://doi.org/10.6028/NIST.AI.100-1) (January 2023), and [Generative AI Profile (NIST AI 600-1)](https://doi.org/10.6028/NIST.AI.600-1) (July 2024).
- [Regulation (EU) 2024/1689](https://eur-lex.europa.eu/eli/reg/2024/1689/oj), the EU Artificial Intelligence Act, Article 4 (AI literacy).
- Future of Privacy Forum, [The AI Act Implementation Timeline: What Changes Under the AI Omnibus?](https://fpf.org/blog/the-ai-act-implementation-timeline-what-changes-under-the-ai-omnibus) (2026).
- FTC, [FTC Announces Crackdown on Deceptive AI Claims and Schemes](https://www.ftc.gov/news-events/news/press-releases/2024/09/ftc-announces-crackdown-deceptive-ai-claims-schemes) (September 2024), and [Trade Regulation Rule on the Use of Consumer Reviews and Testimonials](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-D/part-465) (16 CFR Part 465).
- Colorado General Assembly, [SB 26-189](https://leg.colorado.gov/bills/sb26-189) (2026), replacing SB 24-205.
- NYC Department of Consumer and Worker Protection, [Automated Employment Decision Tools](https://www.nyc.gov/site/dca/about/automated-employment-decision-tools.page).
