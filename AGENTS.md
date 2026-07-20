# AGENTS.md

## Project Overview

This repository publishes the **Angular Essentials** VS Code extension pack (`johnpapa.angular-essentials`).
It is a metadata-first project: the main source of truth is `package.json` (`extensionPack`, metadata, version), with supporting release notes in `CHANGELOG.md` and user-facing docs in `README.md`.

## Repository Structure

- `package.json` — extension manifest, extension pack entries, version, publish scripts
- `README.md` — marketplace-facing docs and included extension links
- `CHANGELOG.md` — release history
- `CONTRIBUTING.md` — contribution process
- `ISSUE_TEMPLATE.md` / `PULL_REQUEST_TEMPLATE.md` — legacy root templates
- `.devcontainer/` — development container config
- `images/` — extension icon assets

## Tech Stack

- Node.js tooling via npm scripts
- VS Code extension packaging/publishing via `vsce`
- No runtime application code; this repo manages extension-pack metadata

## Build & Run

- Package extension:
  - `npm run package`
- Publish extension (maintainers):
  - `npm run publish`
- Local extension-pack test:
  - Open VS Code in this repo and press `F5` (see `vsc-extension-quickstart.md`)

## Testing

There is no unit/integration test suite in this repo.
Validation is packaging-oriented:

- Ensure manifest is valid and pack still builds: `npm run package`
- Verify docs and manifest stay in sync (`README.md`, `CHANGELOG.md`, `package.json`)

## Key Patterns and Conventions

- Keep the extension pack curated and broadly useful; avoid niche or deprecated extensions.
- When changing included extensions, update all linked surfaces in one PR:
  - `package.json` (`extensionPack`)
  - `README.md` (Included table links)
  - `CHANGELOG.md`
- Use direct VS Marketplace links in README; avoid retired badge providers.
- Versioning follows release intent:
  - major for Angular-major branding updates
  - patch for documentation/maintenance updates

## CI/CD

- CI validation workflow: `.github/workflows/ci.yml`
- Release is marketplace publish via `npm run publish` (maintainer-driven)

## Adding or Removing an Extension from the Pack

1. Edit `package.json` and update `extensionPack`.
2. Update `README.md` Included table so docs match manifest.
3. Add a `CHANGELOG.md` entry in the current release section.
4. Run `npm run package` to validate packaging.
5. Open a PR with clear rationale (value, maintenance burden, deprecation risk).

## Common Pitfalls

- Updating only one of README/manifest/changelog and leaving the others stale.
- Reintroducing deprecated tooling/extensions.
- Publishing without bumping `package.json` version and changelog.
- Assuming this is an Angular runtime repo; it is a VS Code extension-pack repo.

## Documentation Status

This repo intentionally has lightweight docs:

- Primary docs: `README.md`, `CONTRIBUTING.md`, `CHANGELOG.md`
- No separate docs site is currently needed for this project size/scope.
