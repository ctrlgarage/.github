# `.github`

The garage's toolbox. This special repository holds **organization-wide defaults**
for [`@ctrlgarage`](https://github.com/ctrlgarage) — files that GitHub applies to
every repo in the org that doesn't ship its own.

> Looking for the public org landing page? That's [`profile/README.md`](profile/README.md),
> which renders at <https://github.com/ctrlgarage>. **This** file is just for people
> poking around the repo.

## What's in here

| Path | Applies to | Purpose |
|------|-----------|---------|
| [`profile/README.md`](profile/README.md) | the org page | Public landing page shown on `github.com/ctrlgarage` |
| [`SECURITY.md`](SECURITY.md) | every repo | Default security policy → `security@ctrlgarage.dev` |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | every repo | Contributor Covenant 2.1 |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | every repo | How to report issues and propose changes |
| [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) | every repo | Default PR checklist |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | every repo | Bug report + feature request forms, with security/contact links |

## How the defaults work

GitHub looks here when a repo lacks its own version of a community health file, so a
single file in this repo covers the whole org. A repo that ships its own copy
**overrides** the default here — this is a floor, not a ceiling.

## House rules

This repo is public — it's part of the org's front door. Keep it that way:

- **No secrets, ever.** Tokens and env live in our deploy platform, not in git.
- **Branch `main` is the default.** Keep changes small and reviewed.

---

<sub>Ctrl. Alt. Deliver. · [ctrlgarage.dev](https://ctrlgarage.dev)</sub>
