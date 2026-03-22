# Vulnerability Disclosure Policy

## 1. Purpose

This policy establishes a responsible vulnerability disclosure process for Mondu's systems. It defines how vulnerabilities should be reported, eligible assets, guidelines for security researchers, and Mondu's response commitments.

## 2. Scope

This policy applies to external security researchers and ethical hackers reporting vulnerabilities in Mondu's publicly accessible systems.

## 3. Reporting a Vulnerability

Vulnerabilities should be reported through [GitHub Security Advisories](https://github.com/mondu-ai/security/security/advisories/new), which ensures reports are handled privately and securely. As a backup, if GitHub is unavailable, reports may be sent to **security@mondu.ai**.

Reports should include:

- Description of the vulnerability
- Steps to reproduce
- Affected systems or URLs
- Impact assessment
- Any supporting evidence (screenshots, proof of concept)

## 4. Eligible Assets

Non-intrusive security testing is permitted on the following assets:

| Asset | Description |
|---------|-------------|
| mondu.ai | Public website |
| api.mondu.ai | API for merchant integrations |
| portal.mondu.ai | Web application for merchants |
| business.mondu.ai | Web application for business buyers |

## 5. Out-of-Scope Activities

The following activities are not covered by this policy:

- Denial-of-service (DoS/DDoS) attacks
- Physical security testing
- Social engineering (phishing, vishing)
- Automated scanner output without demonstrated impact
- Vulnerabilities in third-party services or libraries (these should be reported to the respective vendor)
- UI/UX bugs without security impact

## 6. Guidelines for Researchers

- Do not access, modify, or delete data belonging to other users
- Do not degrade the availability of Mondu's services
- Keep vulnerability details confidential until Mondu has had a reasonable opportunity to address them
- Act in good faith and comply with applicable laws

## 7. Response Commitments

- **Acknowledgement** within 3 business days of the report
- **Triage and initial assessment** within 7 business days
- Transparent communication throughout the remediation process
- Public acknowledgement for valid reports, unless the reporter prefers to remain anonymous

## 8. Safe Harbor

Security research conducted in good faith and in accordance with this policy will be considered authorized. Mondu will not pursue legal action against researchers who comply with these guidelines.
