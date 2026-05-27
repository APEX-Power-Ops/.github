# Security Policy

## Reporting security vulnerabilities

If you discover a security vulnerability in any APEX Power Operations repository, please report it via email to:

**jason.swenson@apexpowerops.com**

Please include:
- Repository affected
- Description of the vulnerability
- Steps to reproduce
- Potential impact assessment
- Suggested remediation (if known)

## Disclosure policy

APEX Power Operations is currently in pre-product stage. We do not operate a public bug bounty program. Reports are handled directly by the operator.

We commit to:
- Acknowledging receipt within 5 business days
- Providing initial assessment within 10 business days
- Coordinating disclosure timing with reporter
- Crediting reporters (with permission) in any subsequent advisory

## Out-of-scope

- Issues with third-party dependencies (report directly to the upstream project)
- Issues requiring physical access to operator workstation
- Vulnerabilities in unreleased / pre-production code paths

## Credentials and secrets discipline

- NEVER paste secrets / API keys / PATs into issues, PRs, comments, or commit history
- Secret scanning + push protection are enabled org-wide; the protection layer will block obvious secret commits at push time
- If you accidentally commit a secret: notify operator immediately via the email above; do NOT attempt rotation/cleanup unilaterally
