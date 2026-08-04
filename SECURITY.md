# Security Policy

*Deutsch-Syrische Forschungsstiftung e.V. (DSFG) — German-Syrian Research Foundation*

This policy applies to every repository in the [German-Syrian-Research-Foundation](https://github.com/German-Syrian-Research-Foundation) organisation unless a repository publishes its own `SECURITY.md`.

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Use one of these two channels:

1. **GitHub private vulnerability reporting** (preferred) — on the affected repository, go to **Security → Report a vulnerability**. This keeps the report private until a fix is published.
2. **Email** — [github@ds-fg.com](mailto:github@ds-fg.com), or [info@ds-fg.com](mailto:info@ds-fg.com) if the first address bounces. Write `SECURITY` in the subject line.

Please include, as far as you can:

- the repository, URL, or system affected
- what the issue is and what an attacker could achieve
- steps to reproduce, or a proof of concept
- any suggested fix
- whether you would like to be credited by name

### What to expect

| Stage | Target |
|:--|:--|
| Acknowledgement of your report | within **3 working days** |
| Initial assessment and severity rating | within **10 working days** |
| Fix or documented mitigation for critical issues | within **30 days** where feasible |
| Public disclosure | coordinated with you, normally after a fix ships |

We are a volunteer-supported non-profit, so please allow for holiday periods. We will keep you informed if something takes longer.

### Safe harbour

If you act in good faith, follow this policy, avoid privacy violations and service disruption, and give us reasonable time to respond before any public disclosure, we will not pursue legal action against you and will treat your research as authorised.

## Scope

**In scope**

- Any repository owned by this organisation
- GitHub Actions workflows, Pages sites, and packages published from this organisation
- Credentials or personal data accidentally committed to any of our repositories

**Out of scope** (report to [info@ds-fg.com](mailto:info@ds-fg.com) instead)

- `ds-fg.com` and other DSFG websites not hosted from this organisation
- Our email, membership, forms, and finance platforms operated by third-party vendors
- Findings from automated scanners with no demonstrated impact
- Social engineering of DSFG staff, board members, or volunteers
- Denial-of-service testing of any kind

## Exposed secrets and personal data

If you find a **credential** (API key, token, password, private key) or **personal data** in one of our repositories:

1. Do not use, download, or share it.
2. Report it immediately via one of the channels above, marking it **URGENT**.

Personal data exposure may trigger a reporting duty under Art. 33 GDPR within 72 hours, so speed matters more than completeness in your report.

## Our security commitments

Within this organisation we maintain:

- Two-factor authentication required for all members
- Secret scanning with push protection enabled on all repositories
- Dependabot alerts and security updates enabled on all repositories
- Code scanning (CodeQL) on repositories containing supported languages
- Protected default branches with mandatory pull-request review
- Least-privilege access: base permission `No permission`, access granted through teams
- Periodic review of members, outside collaborators, deploy keys, and installed GitHub Apps

## Supported versions

Unless a repository states otherwise, only the latest release on the default branch receives security fixes.

---

*Last reviewed: 2026-08. Owner: DSFG Board / IT.*
