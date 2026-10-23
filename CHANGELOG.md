# Changelog

All notable changes to this standalone edition of javascript-algorithms are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus npm updates for the root `package.json`.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow) for the README and per-algorithm READMEs; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's `CI.yml` (ESLint + Jest with coverage on Node 22) was kept as-is, so no additional code CI was needed.
- Set the repository About description and homepage (the main upstream repository).
- Upstream already ships a root `.editorconfig` — verified and kept exactly as-is.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) at upstream commit `85293e3e2b88f4d2ce330d956b139cf628aa1e82` (upstream HEAD dated 2026-07-25).
- Fork history severed; all files and the MIT licence (`LICENSE`) preserved as-is, including the 48 binary illustration images under `src/**/images/`.
