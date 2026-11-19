# Changelog

Compliance Basics releases use `v0.MINOR.PATCH` until the first complete release, v1.0.0, following neon1's [versioning standard](https://neon1.tech/knowledge/standards/versioning/). Each version below has an annotated tag on the commit it names. The release workflow adds missing tags and never moves one.

## v0.1.4 - 2026-11-19

### Fixed
- TCPA page: the opt-out paragraph now follows the FCC's September 30, 2026 order (FCC 26-67) and its source list. The page says to confirm the effective date.
- PCI DSS page: the SAQ A row notes the condition about attacks from malicious scripts.
- GxP page: notes the 2025 consultation on EU GMP Annex 11 and the new Annex 22.
- SOC 2 page: removed the unsupported "40 to 80 controls" and "most common exception" claims, and added when a platform or an auditor's readiness assessment fits better.
- Each primer says it is training and names who to hire when it matters, such as an attorney, a Qualified Security Assessor, or an auditor.
- The `reviewed` date is 2026-11-19 on every page checked.

## v0.1.3 - 2026-11-15

### Changed
- Shorter, plainer wording in the README, walkthroughs, plans, and training guide.

## v0.1.2 - 2026-11-13

### Changed
- The project is now called Compliance Basics, in the README, LICENSE, NOTICE, TRADEMARK.md, attributions, and pages that mention it. The credit line in LICENSE and NOTICE uses the new name. Links to the other neon1 education projects use their new names and addresses.
- Each domain's plan is now a 20-day learning plan. The plans, the domain pages, and the README say the 20 days are a learning pace, not a deadline, and that finishing a plan doesn't make a business compliant.
- The README and each domain page open with a note that the material is training, not legal advice or a compliance determination.
- The README says the scope is stable: the repository gets accuracy and source updates, and no new modules for now. The contributing guide no longer asks for new walkthroughs or domains.

## v0.1.1 - 2026-11-12

### Fixed
- Sources that moved now link their current pages: New York DFS's cybersecurity resource center, the European Accessibility Act, the Security Risk Assessment Tool, Google's email sender guidelines, and the AICPA's SOC suite of services.
- The HHS 405(d) site became the HHS Cyber Gateway, and the HIPAA pages link and name it.

## v0.1.0 - 2026-11-12

### Added
- Ten domains, each with a README, 20-minute walkthroughs, and a 20-day plan: healthcare (HIPAA), life sciences (GxP), payments (PCI DSS), financial services (FTC Safeguards Rule), education (FERPA and COPPA), privacy (state laws and New York's SHIELD Act), security (NIST CSF, CIS Controls, and SOC 2), accessibility (ADA and WCAG), marketing (CAN-SPAM and the TCPA), and AI use (NIST AI RMF and NYC Local Law 144).
- A training kit: a facilitator guide, an acknowledgment form, and a training log.
- A check that every page has front matter, a review date, and a Sources section, and that every relative link works.
