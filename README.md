# Hugo Docs Theme

A reusable Hugo documentation theme maintained by Carsten Nichte.

This project is a fork of [Doks Core](https://github.com/thuliteio/doks-core).
It preserves the upstream Git history so fixes and improvements can continue to
be integrated while the theme evolves independently.

## Getting Started

The public package is `@glimpse-of-life/hugo-docs-theme`. During the initial
migration, the existing Doks configuration and extension contracts remain
compatible.

For the inherited functionality, see the Doks documentation:

- [Doks](https://getdoks.org/docs/start-here/getting-started/)

## Upstream Updates

The `upstream` remote points to the original Doks Core repository:

```bash
git fetch upstream
git merge upstream/main
```

Review and validate upstream changes before pushing the merge to `origin`.
