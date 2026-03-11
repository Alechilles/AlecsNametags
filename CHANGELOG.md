# Changelog

## Unreleased

## 1.1.2 - Release Publish Hotfix - 2026-03-11
### Changed
- Updated `manifest.json` version to `1.1.2`.
- Updated release publish metadata config to stop submitting dependency relation payloads that are currently rejected by CurseForge.

## 1.1.1 - Release Tooling + Config Fixes - 2026-03-11
### Added
- Added release automation scaffolding (`publish.yml`, release scripts, and `.release/publish-config.json`).
- Added `LICENSE.txt` to the repository.

### Changed
- Updated `manifest.json` version to `1.1.1`.
- Updated dependency declaration to `Alechilles:Alec's Tamework! 2.1.x` (replacing the old pinned split dependency wording).
- Added explicit `ConfigId: "NameItem_Alecs_Nametag"` on `Alecs_Nametag` interaction wiring to ensure the intended naming rules config is used.
- Updated README content and refreshed project shields/badges.
- Hardened publish automation with dependency metadata support for CurseForge/Modtale and stricter upload failure handling.
- Updated Modtale release config to lowercase game version identifier format.
- Updated packaging config to exclude the empty `Common` folder from Nametags release artifacts.

## 1.1.0 - 2026-02-24
### Changed
- Updated dependencies to `Alec's Tamework!` and `Alec's Tamework! (Assets)` version `2.1.x`.
- Updated `ServerVersion` compatibility to `2026.02.19-1A311A592`.
- Added repository documentation (`README.md` and `CHANGELOG.md`).

## 1.0.0 - 2026-02-17
### Added
- Initial release of Alec's Nametags.
- Added craftable `Alecs_Nametag` item.
- Added Tamework naming config (`NameItem_Alecs_Nametag`) and English localization.


