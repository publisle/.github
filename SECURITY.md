# Security policy

## Supported versions

Publisle is in beta. Security fixes land on `main` and ship in the next patch
release of the affected packages/crates. Only the latest published version of
each `@publisle/*` npm package and `publisle*` crate is supported.

## Reporting a vulnerability

**Please do not open public issues for security problems.**

1. Preferred: use GitHub's private reporting — open the affected repository's
   **Security → Report a vulnerability** form
   ([publisle](https://github.com/publisle/publisle/security/advisories/new),
   [publisle-rs](https://github.com/publisle/publisle-rs/security/advisories/new)).
2. Or email [the maintainers](mailto:coder64bit@gmail.com) with “SECURITY” in the subject.

Include affected package/crate and version, a minimal reproduction or proof of
concept, and the impact you observed. We aim to acknowledge within 3 days and to
agree on a fix and disclosure timeline within 14 days. We credit reporters in
the advisory unless you ask us not to.

## Scope

In scope: the npm packages, crates, the CLI, the hosted PDF service at
`api.publisle.xyz`, and the publisle.xyz site. Out of scope: denial of service
through volume, findings that need a compromised machine, and third-party
dependencies already tracked upstream (report those upstream; we will bump).
