# Enhancements — Standalone Edition Changelog

Upstream: https://github.com/trekhleb/javascript-algorithms
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)
- Added "About This Standalone Edition" section to README.md with upstream link, base version provenance, and credit.
- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates, plus npm for the root package.json).
- Added .markdownlint.json and .github/workflows/markdown-check.yml (markdown linting automation for the README and per-algorithm READMEs; upstream CI.yml — ESLint + Jest with coverage on Node 22 — kept as-is, so no additional code CI was needed).
- Set repository About: detailed description stating the enhancements and versions; homepage set to the main upstream repository.
- Upstream already ships a root .editorconfig — verified and kept exactly as-is.

## v1.0.0 — Baseline (2026-10-20)
- Clean standalone baseline of trekhleb/javascript-algorithms at upstream commit 85293e3e2b88f4d2ce330d956b139cf628aa1e82 (upstream HEAD dated 2026-07-25).
- Fork history severed; all files and the MIT licence (LICENSE) preserved as-is, including the 48 binary illustration images under src/**/images/ (largest 665297 bytes — none over 1 MB).
