# AGENTS

- Add changelog entries under `## Unreleased` so bump-my-version can find and
  replace the header on the next version bump.
- Release process (see README): run `nix run nixpkgs#bump-my-version -- bump
  patch` from repo root, then commit, tag (with `v` prefix, e.g., `v0.0.8`), and push.
