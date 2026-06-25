# Contributing

Thanks for popping the hood. These guidelines apply across all
[`@ctrlgarage`](https://github.com/ctrlgarage) repositories unless a repo ships its own
`CONTRIBUTING.md`, which takes precedence.

By participating, you agree to our [Code of Conduct](CODE_OF_CONDUCT.md).

## Reporting bugs & requesting features

- Search existing issues first — yours may already be filed.
- Open a new issue using the templates (Bug report / Feature request).
- For **security vulnerabilities, do not open an issue** — follow the
  [Security Policy](SECURITY.md) (`security@ctrlgarage.dev`).

## Proposing changes

1. **Open an issue first** for anything non-trivial, so we can agree on the approach
   before code is written.
2. **Fork** the repo and create a branch off the default branch:
   `git checkout -b fix/short-description`.
3. Keep changes **focused** — one logical change per pull request.
4. Match the surrounding code's style; don't reformat unrelated lines.
5. **Never commit secrets.** Tokens, keys, and env values stay out of git (see each
   repo's `.gitignore`).

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>: <short summary>

<optional body explaining what and why>
```

Types: `feat`, `fix`, `refactor`, `docs`, `test`, `chore`, `perf`, `ci`.

## Pull requests

- Fill in the pull request template.
- Reference the issue it closes (`Closes #123`).
- Make sure any checks pass and the branch is up to date with the default branch.
- Be ready for review — we keep a high bar, kindly.

## Questions

Not sure where something fits? Email
[aleksandar@ctrlgarage.dev](mailto:aleksandar@ctrlgarage.dev) or open a discussion.

> Ctrl. Alt. Deliver.
