---
title: "20 minutes to the NIST Cybersecurity Framework"
description: "How a small business can use the NIST Cybersecurity Framework 2.0 and the CIS Controls to build a security program that regulators, insurers, and customers recognize, and what staff need to know."
domain: Security
rules: "NIST Cybersecurity Framework 2.0, CIS Critical Security Controls v8.1, and NIST SP 800-50 Rev. 1"
reviewed: 2026-11-12
---

**Read this if** you own or run IT for a small or midsize business and want one sensible way to organize security. It's also for anyone asked by a customer, insurer, or regulator "what framework do you follow?"

## Why a framework

Many laws in this repository say "reasonable safeguards" without spelling them out, including the New York SHIELD Act, the FTC's reading of Section 5, and state privacy laws. Insurers, customers, and contracts ask the same question. A recognized framework gives you a checklist and evidence that your safeguards are reasonable. New York requires schools to align their student data policies with the NIST Cybersecurity Framework.

Two free frameworks suit small businesses. The **NIST Cybersecurity Framework (CSF)** describes what a security program should achieve. The **CIS Critical Security Controls** list specific safeguards in priority order. Use CSF for the shape of the program and CIS for the first concrete steps.

## The NIST Cybersecurity Framework 2.0

NIST published CSF 2.0 on February 26, 2024, for organizations of any size, with a quick-start guide for small businesses. It organizes outcomes into six functions.

| Function | The question it answers | Small business examples |
|---|---|---|
| Govern | Who decides, and what's the plan? | A named owner for security, a written policy, a risk budget, rules for suppliers |
| Identify | What do we have, and what could go wrong? | An inventory of devices, accounts, data, and vendors, and a simple risk list |
| Protect | How do we prevent harm? | MFA, updates, backups, encryption, least privilege, training |
| Detect | How would we know? | Alerts from email, endpoint, and cloud tools that someone actually reads |
| Respond | What do we do when it happens? | An incident plan with phone numbers, roles, and notice deadlines |
| Recover | How do we get back to normal? | Tested restores, a plan for working without systems, lessons learned |

Govern is new in version 2.0. It puts security decisions, supply chain risk, and accountability with leadership.

You don't have to do every subcategory. Describe your **current profile**, choose a **target profile**, and work the gap in priority order.

## The CIS Critical Security Controls

The Center for Internet Security publishes 18 controls broken into specific safeguards. Version 8.1 (June 2024) aligns them with CSF 2.0. **Implementation Group 1 (IG1)** is essential cyber hygiene, the minimum every organization should have, and the right starting point for most small businesses. It covers:

- an inventory of devices and software, and a data inventory,
- secure configurations and changed default passwords,
- account management, including MFA for remote and admin access and external apps,
- patching, email and browser protections, and anti-malware,
- automated backups, with one copy isolated,
- security awareness training and managing service providers,
- and an incident response process.

## How this connects to other frameworks

- **SOC 2** is a report a CPA firm issues on your controls, often asked for by business customers. A CSF or CIS program covers much of what it tests. See [20 minutes to SOC 2](20-minutes-to-soc-2.md) and the full course in [SOC 2 Readiness](https://github.com/neon1llc/soc-2-readiness).
- **ISO/IEC 27001** is an international certifiable standard. NIST publishes mappings to CSF.
- **HIPAA, the FTC Safeguards Rule, and PCI DSS** each have their own walkthrough here. A CSF program makes each easier to meet but doesn't replace their requirements.
- **New York DFS-regulated companies** (banks, insurers, and other financial firms licensed in New York) follow 23 NYCRR Part 500, which requires annual cybersecurity awareness training that includes social engineering.

## What security training should cover

NIST's SP 800-50 Rev. 1 (2024) recommends tying training to the organization's actual risks and roles and measuring whether it changes behavior. For general staff:

1. **Use MFA, and never approve a prompt you didn't start.** Deny it and report it. It usually means someone has your password.
2. **Use a password manager** and a different password for each account.
3. **Spot phishing, smishing, and phone scams**, and report them.
4. **Verify money and data requests out of band**, by calling a known number.
5. **Keep devices updated and locked.** Let IT install patches.
6. **Store work data only in approved places**, and use approved tools, including for AI.
7. **Report incidents fast**, including your own mistakes, and know who to call day and night.

Admins, finance staff, and executives need extra training on the risks aimed at them: admin account protection, payment fraud, and impersonation.

For a ready-made session, see [Phishing Awareness Kit](https://github.com/neon1llc/phishing-awareness-kit). For home security, see [Household Tech Handbook](https://github.com/neon1llc/household-tech-handbook).

## What the business needs on paper

- A named security owner and a short security policy approved by leadership.
- An asset inventory and a risk list with owners and next steps.
- A current and target profile, even a one-page table.
- Records of MFA coverage, patching, backup tests, and training. See the [training log](../../templates/training-log.csv).
- A vendor list with reviews for the important ones.
- An incident response plan and records of incidents and exercises.

Buying tools before knowing what you have, MFA on email but not on remote access or finance systems, and backups that have never been restored are the common mistakes.

## Check yourself

1. Which CSF 2.0 function is new, and what does it cover?
2. Which CIS implementation group should a small business start with?
3. Does following NIST CSF make you HIPAA compliant?
4. What should staff do when an MFA prompt appears that they didn't start?

<details>
<summary>Answers</summary>

1. Govern. It covers strategy, roles, policy, risk management, and supply chain risk, and places them with leadership.
2. Implementation Group 1, the essential cyber hygiene safeguards.
3. No. It helps a lot, but HIPAA has specific requirements, such as BAAs and breach notice rules, that a general framework doesn't cover.
4. Deny it and report it. It usually means someone has their password.

</details>

## Sources

- NIST, [The NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework), NIST CSWP 29 (February 26, 2024), with its quick-start guides, and NIST's [Small Business Cybersecurity Corner](https://www.nist.gov/itl/smallbusinesscyber).
- Center for Internet Security, [CIS Critical Security Controls v8.1](https://www.cisecurity.org/controls) and [Implementation Group 1](https://www.cisecurity.org/controls/implementation-groups/ig1).
- NIST, [SP 800-50 Rev. 1, Building a Cybersecurity and Privacy Learning Program](https://csrc.nist.gov/pubs/sp/800/50/r1/final) (September 2024).
- CISA, [Cyber Essentials](https://www.cisa.gov/resources-tools/resources/cyber-essentials) for small businesses and local governments.
- New York State Department of Financial Services, [Cybersecurity Resource Center, 23 NYCRR Part 500](https://www.dfs.ny.gov/cybersecurity). Training: § 500.14(a)(3).
- New York General Business Law [§ 899-bb](https://www.nysenate.gov/legislation/laws/GBS/899-BB), reasonable safeguards.
- FTC, [Cybersecurity for Small Business](https://www.ftc.gov/business-guidance/small-businesses/cybersecurity).
