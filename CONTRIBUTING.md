# Contributing to DSFG

Thank you for helping the German-Syrian Research Foundation. This guide applies to every repository in this organisation unless a repository overrides it.

By participating you agree to our [Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to contribute

You do not need to be a programmer:

- **Report a problem** — a broken link, a wrong translation, an outdated scholarship deadline
- **Improve documents** — clarity, structure, or translation into German or Arabic
- **Design** — visual assets, slides, social media templates
- **Code** — websites, automation, data tools
- **Review** — read someone else's pull request and comment

## Before you start

1. **Search existing issues** so you do not duplicate work.
2. **Open an issue first** for anything larger than a typo. Describe the problem before proposing a solution — it saves everyone effort.
3. **Ask to be assigned** before starting substantial work, so two people do not build the same thing.

## Workflow

```
1.  Fork the repository (external contributors) or create a branch (members)
2.  Create a branch:  <type>/<short-description>
3.  Make your change, in small focused commits
4.  Open a pull request against `main`
5.  Fill in the PR template and link the issue ("Closes #12")
6.  Respond to review comments; a maintainer merges when approved
```

### Branch naming

| Prefix | Use for |
|:--|:--|
| `feat/` | new functionality or content |
| `fix/` | corrections and bug fixes |
| `docs/` | documentation and translation only |
| `chore/` | dependencies, tooling, housekeeping |
| `design/` | visual assets |

Example: `fix/broken-scholarship-links`

### Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
docs(readme): add Arabic summary
fix(forms): correct required-field validation on membership form
feat(datacamp): add cohort reporting script
```

Write in **English**, in the imperative mood, and keep the first line under 72 characters.

### Pull requests

- Keep them small — one logical change per PR. A 60-file PR will sit unreviewed.
- Every PR needs at least **one approving review** from a maintainer before merge.
- All required checks must pass.
- Mark work in progress as a **draft** PR.
- Be responsive; PRs with no activity for 30 days may be closed (you can always reopen).

## Data protection — read this before committing anything

DSFG is subject to the **GDPR / DSGVO**. This is the most important rule in this guide.

> ### ❌ Never commit personal data to any DSFG repository — public **or** private.

That includes, and is not limited to:

- Applicant, member, scholar, mentee, or mentor names, emails, phone numbers, or addresses
- CVs, motivation letters, transcripts, certificates, passport or ID scans
- Immigration, asylum, visa, or residence status
- Health information
- Financial details, IBANs, donor records
- Exports, screenshots, or backups from WISO MeinVerein, OpnForm, Formbricks, or any CRM
- Real data in test fixtures — **use synthetic data**

Personal data belongs in our contracted systems with a data processing agreement (AVV) in place. Git history is effectively permanent: even a deleted file remains in the history and in every clone.

**If you commit personal data by accident:** do not just delete it in a new commit. Report it immediately to [github@ds-fg.com](mailto:github@ds-fg.com) so the history can be purged and the incident assessed under Art. 33 GDPR.

### Also never commit

- Passwords, API keys, tokens, private keys, `.env` files, service-account JSON
- Anything under a licence we do not hold — stock photos, fonts, paid templates
- Unpublished internal governance documents, or content that could put a person in the region at risk

Secret scanning with push protection is enabled and will block many of these automatically, but it is not a substitute for care.

## Licensing

Unless a repository says otherwise, by contributing you agree that:

- **Code** is licensed under the [MIT Licence](https://opensource.org/licenses/MIT)
- **Documentation and content** is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **DSFG names, logos, and brand marks** are excluded — see [brand usage](https://github.com/German-Syrian-Research-Foundation/assets/blob/main/BRAND-USAGE.md)

You confirm you have the right to contribute the material.

## Language

- Code, commit messages, branch names, issues, and pull requests: **English**
- Public-facing content may be English, German, or Arabic. Keep translations in parallel files (`README.md`, `README.de.md`, `README.ar.md`), not mixed in one document.

## Getting help

Open a [discussion or issue](SUPPORT.md), or email [info@ds-fg.com](mailto:info@ds-fg.com). We would rather answer a question than review a wrong-direction PR.

---

*Last reviewed: 2026-08.*
