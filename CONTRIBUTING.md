# Contributing to Synq

Thanks for wanting to help. This guide applies to every public Synq repository that doesn't have its own.

## Before you start

- For a bug, check the open issues first, then open one with the steps to reproduce it.
- For a new feature or a bigger change, open an issue that describes the problem before you write code, so we can agree on the approach.
- Security problems never go in a public issue. See [SECURITY.md](SECURITY.md).

## Pull requests

1. Fork the repository and branch from `main`.
2. Keep each pull request to one change, with tests that cover it.
3. Run the checks the repository's README lists before you push.
4. Title the pull request as a [Conventional Commit](https://www.conventionalcommits.org/), for example `fix(sdk): retry a failed token refresh`. Pull requests are squash-merged, so the title becomes the commit message.
5. If the repository uses Changesets, add one for any change to a published package (`pnpm exec changeset`).

A maintainer reviews every pull request. Workflows on a pull request from a fork run only after a maintainer approves them.

## Code of conduct

Everyone who takes part follows the [code of conduct](CODE_OF_CONDUCT.md).

## License

By contributing, you agree that your contribution is licensed under the license of the repository you contribute to.
