# Contributing to Kollaudo

Thanks for your interest! Kollaudo is at an early stage, so the most valuable contributions right
now are use cases, feedback on the design and recipes for the tools you use.

## Before you start

- **Ideas and bugs**: open an [issue](https://github.com/kollaudo/kollaudo/issues) first, so we can
  agree on the approach before you write code.
- **Design**: read the [architecture decisions](https://github.com/kollaudo/kollaudo/tree/main/docs/adr).
  A change that goes against an accepted ADR needs a new ADR that supersedes it.
- **Tool-specific support** belongs in a recipe, not in the core
  (see [ADR 0002](https://github.com/kollaudo/kollaudo/blob/main/docs/adr/0002-tool-agnostic-core.md)).

## Pull requests

- Keep each pull request focused on one change.
- Add or update tests for the behavior you change.
- Update the documentation when behavior visible to users changes.
- Use [Conventional Commits](https://www.conventionalcommits.org) for commit messages and pull
  request titles, for example `feat(cli): add push command` or `docs: explain versions`.

## Licensing

Kollaudo is licensed under [Apache-2.0](https://github.com/kollaudo/kollaudo/blob/main/LICENSE).
By contributing, you agree that your contribution is licensed under the same terms.

Only contribute code that you wrote yourself, or that you have the right to contribute under
Apache-2.0. Don't copy code from proprietary projects or from projects with incompatible licenses.

## Security issues

Don't open public issues for vulnerabilities. See [SECURITY.md](SECURITY.md).
