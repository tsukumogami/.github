# Contributing to tsukumogami

Thanks for your interest in contributing. Here's how to get started.

## Finding work

- Look for issues labeled `good first issue` or `help wanted`
- Check the project's milestones for current priorities
- Open an issue before starting large changes

## Development setup

Each repository has its own development prerequisites documented in its README.
The general pattern:

1. Fork the repo
2. Clone your fork
3. Create a branch from `main`
4. Make your changes
5. Run tests (see the repo's README for test commands)
6. Open a PR

## Pull requests

- Keep PRs focused -- one concern per PR
- Write a clear description of what changed and why
- Link to the related issue if one exists
- All PRs are squash-merged, so the PR title becomes the commit message

## Code style

- Go: standard `gofmt`, no external linters beyond `go vet`
- Rust: standard `rustfmt` + `clippy`
- Shell: follow existing patterns in the repo

## Reporting bugs

Open an issue using the bug report template. Include:

- What you expected to happen
- What actually happened
- Steps to reproduce
- Version information

## License

By contributing, you agree that your contributions will be licensed under the
same license as the project (Apache 2.0).
