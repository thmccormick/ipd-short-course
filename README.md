# IPD Short Course

This repository is maintained as a simple Quarto website plus Docker image.

## Publishing

- GitHub Pages publishes from the `main` branch and the `docs/` directory.
- The live site is <https://thmccormick.github.io/ipd-short-course/>.
- Docker images publish to `ghcr.io/thmccormick/ipd-short-course`.

## Maintainer Workflow

1. Edit the source files (`.qmd`, assets, styles, and supporting content).
2. Run `quarto render` locally from the repository root.
3. Commit both the source changes and the regenerated `docs/` output.
4. Push to `main`.

## GitHub Actions

- No `GH_PAT` repository secret is required.
- The only repo-managed workflow kept here is Docker publishing.
- GitHub Pages deployment is handled by GitHub Pages using the committed `docs/` output.
