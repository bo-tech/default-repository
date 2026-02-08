# Changelog

## Unreleased

- Forward watch app from sphinx-builder in docs flake

## 0.0.11 - 2026-02-08

- Add livehtml Makefile target for live-reloading docs preview

## 0.0.10 - 2026-02-03

- Add GitHub usage example to README
- Make sphinx-builder URL configurable with choice of internal GitLab or GitHub

## 0.0.9 - 2026-01-22

- Add .gitignore to docs folder to ignore _build directory

## 0.0.8 - 2026-01-13

- Add decisions README with ADR immutability guidance and cross-referencing docs
- Add MyST cross-reference labels to ADRs (`adr-NNNN` pattern)

## 0.0.7 - 2026-01-07

- Add pre-commit configuration with ruff and docformatter

## 0.0.6 - 2026-01-06

- Add complete Sphinx documentation setup (conf.py, index.rst, Makefile)
- Add GitLab CI pipeline for docs build and Pages publishing
- Add ADR (Architecture Decision Records) structure with template and initial 0000 ADR
- Add `nix run` support to docs flake (apps.make, apps.default)
- Add docs README with usage guidelines

## 0.0.5 - 2025-12-05

- Use pushd/popd in docs flake to restore the working directory during builds

## 0.0.4 - 2025-12-05

- Add Sphinx documentation flake template using the shared `sphinx-builder`

## 0.0.3 - 2025-11-22

- Use JSON5 for the renovate configuration

## 0.0.2 - 2025-11-22

- Incorporated bump-my-version
- Add changelog
