# Contributing to NOBAD

Thanks for helping. This is the default guide for every repository in the
[`nobad-studio`](https://github.com/nobad-studio) organization; a repository's own `CONTRIBUTING.md` adds its build
and test steps and wins where they differ.

## How changes are made
1. **Fork** the repository and create a branch for your change.
2. Keep the change focused, add or update tests, and run the repository's tests and lint (see its README).
3. Open a **pull request** against `main` and explain *why* in the description. Say if AI helped; a person submits,
   understands and is responsible for every PR.
4. On your first pull request a bot asks you to sign the [Contributor License Agreement](CLA.md) with one comment.
   You keep the copyright to your work.
5. A maintainer reviews it. `main` is protected: no direct pushes, required checks must pass, and official releases
   are built only by the release workflows.

## House rules
- **Security first.** NOBAD apps handle networks, files and credentials, and some run as administrator. Untrusted
  input never reaches shell strings or HTML unescaped. No tracking. New outbound connections need a setting and
  documentation.
- **Honest text.** UI and docs never claim more than the code actually measures or does.
- **The NOBAD name.** Forks are welcome; a fork you publish yourself uses its own name and logo. See
  [TRADEMARKS.md](TRADEMARKS.md).

## Where to start
- [`good first issue`](https://github.com/search?q=org%3Anobad-studio+label%3A%22good+first+issue%22+state%3Aopen&type=issues)
  across all repositories.
- Questions and ideas: the Discussions tab of the repository.
- Be kind: [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
