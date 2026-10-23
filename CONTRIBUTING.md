# Contributing to Publisle

Thanks for helping build a publishing toolkit that treats articles as portable,
validatable data. This is the organization-wide default; a repository's own
`CONTRIBUTING.md` takes precedence and has the exact setup and test gates.

- **TypeScript core, adapters, site:** [publisle/publisle — CONTRIBUTING](https://github.com/publisle/publisle/blob/main/CONTRIBUTING.md)
- **Rust engine and crates:** [publisle/publisle-rs](https://github.com/publisle/publisle-rs)

## Getting help and proposing ideas

- Ask questions and share ideas in
  [GitHub Discussions](https://github.com/publisle/publisle/discussions).
- Bug reports start best as a Discussion unless you can already reproduce them
  against `main` — then open an issue with the reproduction template.
- Look for issues tagged
  [`good first issue`](https://github.com/search?q=org%3Apublisle+label%3A%22good+first+issue%22+is%3Aopen&type=issues)
  for scoped entry points.

## Pull requests

- Keep each PR focused; run the repository's standard gate
  (`pnpm check` in publisle, `cargo fmt && cargo clippy && cargo test --workspace` in publisle-rs).
- Conventional Commits (`feat:`, `fix:`, `perf:`, `chore:` …), subject only.
- Wire contracts and block schemas are versioned deliberately — read the
  [contracts](https://github.com/publisle/publisle/blob/main/docs/contracts.md) and
  [beta standards](https://github.com/publisle/publisle/blob/main/docs/standards/README.md)
  before proposing changes.
- Every documented behavior deserves a test that fails without it.
- User-facing changes in publisle need a changeset (`pnpm changeset`).

## Licensing

By contributing you agree that your contributions are licensed under the
MIT License of the repository you contribute to (Copyright (c) 2026 Publisle).
