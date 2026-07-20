# Copilot instructions for vscode-angular-essentials

This repository is a **VS Code extension pack**. Treat it as a metadata/release repo, not an Angular runtime app.

## Project intent

- Keep the extension pack minimal, stable, and broadly useful for Angular developers.
- Prefer well-maintained, mainstream extensions over niche additions.
- Avoid deprecated tooling and references.

## Core files and responsibilities

- `package.json`
  - Source of truth for extension metadata, version, and `extensionPack`.
- `README.md`
  - Public-facing docs and included extension Marketplace links.
- `CHANGELOG.md`
  - Release history and rationale.
- `CONTRIBUTING.md`
  - Contributor flow expectations.

## Conventions mined from prior maintenance

- Extension list changes should include docs + changelog updates in the same PR.
- Remove outdated/deprecated integrations when surfaced in issues/PRs.
- Keep release changes explicit and small; avoid unrelated churn.
- Prefer direct Marketplace links over retired badge providers.

## Code change conventions

- Make targeted edits only; do not reformat large files unnecessarily.
- Keep naming consistent with existing extension IDs (exact case where required by Marketplace IDs).
- Do not add runtime/framework assumptions (no Angular package upgrades in this repo unless explicitly requested).

## Testing and validation conventions

- Run packaging validation after meaningful manifest/docs release changes:
  - `npm run package`
- For release actions, ensure version and changelog are aligned before publish:
  - `package.json` version
  - top changelog entry in `CHANGELOG.md`

## Asset/content rules

- `README.md` should match the current `extensionPack` entries.
- Changelog entries should be chronological, newest first.
- Keep icon/image references stable unless intentionally updating branding.

## Maintenance matrix

| If you change | Also review/update | Why |
| --- | --- | --- |
| `package.json` `extensionPack` | `README.md` Included table, `CHANGELOG.md` | Keep public docs and release notes synchronized with manifest |
| `package.json` `version` | `CHANGELOG.md`, release/publish workflow steps | Prevent marketplace version/changelog drift |
| Included extension IDs | Case-sensitive Marketplace links in `README.md` | Broken IDs/links cause install confusion |
| Contribution process or review expectations | `CONTRIBUTING.md`, PR template(s) | Keep contributor guidance and review rubric aligned |
| Legacy templates at repo root | `ISSUE_TEMPLATE.md`, `PULL_REQUEST_TEMPLATE.md` | Keep existing community templates usable and consistent with docs |

## What not to do

- Don’t add speculative dependencies or framework tooling.
- Don’t overwrite existing contributor docs wholesale; patch specific sections.
- Don’t delete legacy templates unless asked; prefer additive migration.
