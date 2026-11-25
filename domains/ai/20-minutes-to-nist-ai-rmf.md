---
title: "20 minutes to the NIST AI Risk Management Framework"
description: "How a small business can use AI tools responsibly at work, using the NIST AI Risk Management Framework, the EU AI Act's AI literacy duty, and the U.S. rules that already apply, and what staff need to know."
domain: AI use
rules: "NIST AI Risk Management Framework 1.0 and Generative AI Profile (NIST AI 600-1), EU AI Act Article 4, and existing U.S. consumer protection, privacy, and anti-discrimination law"
reviewed: 2026-11-19
---

**Read this if** people at your business use AI chat assistants, writing or coding tools, meeting transcribers, or AI features inside software you pay for, or you build products that use AI.

## The rules that already apply

There's no single U.S. AI law, but existing laws apply when AI is involved:

- **Confidentiality and privacy.** Pasting patient records, tax returns, student data, or card numbers into an AI tool is a disclosure. HIPAA, the FTC Safeguards Rule, FERPA, PCI DSS, and state privacy laws apply as they do to any vendor. Use only approved tools under a contract, and check whether the vendor trains on your inputs.
- **Consumer protection.** The FTC has said there's no AI exemption. Claims about what your AI product does must be true and backed by evidence. AI-generated fake reviews are banned under the FTC's 2024 consumer reviews rule.
- **Discrimination.** Employment, lending, housing, and insurance decisions are covered whether a person or software makes them.
- **Contracts and copyright.** Customer contracts may limit where their data can go.

Some places add AI-specific rules. New York City requires bias audits and notices for automated hiring tools (see [20 minutes to NYC Local Law 144](20-minutes-to-nyc-local-law-144.md)). In May 2026, Colorado repealed and reenacted its 2024 AI law with new requirements for AI used in consequential decisions, effective January 1, 2027.

## The EU AI Act

It applies to businesses that provide or use AI systems in the EU, including U.S. businesses whose output is used there. Its **AI literacy** duty took effect February 2, 2025. Article 4 requires providers and deployers to support AI literacy among staff and others who operate or use AI on their behalf, considering their skills and the context. It does not require a guaranteed literacy level for each person. A 2026 amendment softened the wording and delayed many high-risk requirements until December 2, 2027, or August 2, 2028. A practical step is to train staff who use AI tools and keep records.

## The NIST AI Risk Management Framework

NIST released AI RMF 1.0 in January 2023 and a Generative AI Profile (NIST AI 600-1) in July 2024. Both are voluntary and recognized by regulators.

| Function | What it means for a small business |
|---|---|
| Govern | An AI use policy, a named owner, and rules for approving tools |
| Map | A list of where AI is used, for what, with what data, and who's affected |
| Measure | Checking outputs for accuracy, bias, and leaks where they matter most |
| Manage | Limiting uses, adding human review, switching tools, or stopping |

The Generative AI Profile names the risks of generative tools: confident made-up facts ("confabulation"), leaks of personal or confidential data, harmful or biased content, intellectual property problems, and prompt injection.

## A one-page AI use policy

1. **Approved tools.** Business accounts with data protection terms beat free personal accounts.
2. **Data rules.** Never enter regulated personal data, credentials, or client confidential material unless the tool is approved for it.
3. **Human review.** A person checks output before it goes to a customer or regulator, changes production code, or informs a decision about a person.
4. **Disclosure.** Say when customers are dealing with AI, such as chatbots or generated images.
5. **High-impact uses.** Hiring, lending, pricing, medical, and legal uses need the owner's approval and a check against the laws above.
6. **Reporting.** Say how to report a leak, a harmful output, or a tool behaving oddly.

## What staff need to know

1. **Use approved tools** with your work account, and keep regulated or confidential data out of the rest.
2. **Check the output.** AI states wrong facts with confidence. Verify names, numbers, citations, and code. You own what you send.
3. **Watch for prompt injection.** Documents, web pages, and emails can hide instructions aimed at AI tools. Don't let an AI agent act on untrusted content unreviewed.
4. **Don't use AI to decide** hiring, firing, credit, or similar matters without approval.
5. **Get consent** where required before using meeting recorders, and skip them on privileged or sensitive calls.
6. **Report problems**, including suspected leaks.

## What the business needs on paper

- The AI use policy with staff acknowledgments ([acknowledgment form](../../templates/acknowledgment-form.md)).
- An inventory of AI tools and AI features in existing software, with the data each touches and the vendor's training and retention terms.
- Review records for high-impact uses.
- Training records ([training log](../../templates/training-log.csv)).

Ask an attorney before using AI for decisions about people, or if you sell AI products in the EU.

## Check yourself

1. Is it a HIPAA issue to paste a patient's chart into a free AI chat tool?
2. An AI tool drafts a client letter citing a regulation. What do you do before sending?

<details>
<summary>Answers</summary>

1. Yes. Without a business associate agreement and approval, it's an impermissible disclosure of PHI.
2. Check the citation and facts yourself. AI tools can invent or misstate sources.

</details>

## Sources

- NIST, [AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework), [AI RMF 1.0 (NIST AI 100-1)](https://doi.org/10.6028/NIST.AI.100-1) (January 2023), and [Generative AI Profile (NIST AI 600-1)](https://doi.org/10.6028/NIST.AI.600-1) (July 2024).
- [Regulation (EU) 2024/1689, consolidated through July 27, 2026](https://eur-lex.europa.eu/eli/reg/2024/1689/2026-07-27), the EU Artificial Intelligence Act, Article 4 and Article 113.
- [Regulation (EU) 2026/1744](https://eur-lex.europa.eu/eli/reg/2026/1744/oj), the Digital Omnibus on AI, which amends Regulation (EU) 2024/1689.
- FTC, [FTC Announces Crackdown on Deceptive AI Claims and Schemes](https://www.ftc.gov/news-events/news/press-releases/2024/09/ftc-announces-crackdown-deceptive-ai-claims-schemes) (September 2024), and [Trade Regulation Rule on the Use of Consumer Reviews and Testimonials](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-D/part-465) (16 CFR Part 465).
- Colorado General Assembly, [SB 26-189](https://leg.colorado.gov/bills/sb26-189) (2026), replacing SB 24-205.
- NYC Department of Consumer and Worker Protection, [Automated Employment Decision Tools](https://www.nyc.gov/site/dca/about/automated-employment-decision-tools.page).
