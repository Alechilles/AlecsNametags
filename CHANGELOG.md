# Changelog

## Unreleased

## 1.2.0 - Random Name System Support - 2026-04-02
### Added
- Added `RandomNamesId: "TwNamesDefault"` to `NameItem_Alecs_Nametag`, enabling compatibility with Tamework's random-name system for naming flows.

### Changed
- Updated `manifest.json` version to `1.2.0`.
- Expanded `.gitignore` to ignore local IntelliJ project files under `.idea/`.

## 1.1.4 - Release Metadata Cleanup + Compatibility Refresh - 2026-03-26
### Changed
- Updated `manifest.json` version to `1.1.4`.
- Updated release compatibility metadata to `ServerVersion`/`gameVersions` `2026.03.26-89796e57b`.
- Updated README badge link for Animal Husbandry to the current CurseForge URL.

### Fixed
- Removed unsupported Modtale dependency relation payload from `.release/publish-config.json` so release submissions do not include rejected dependency metadata.

## 1.1.3 - Release Alignment (Tamework 2.4) - 2026-03-15
### Added
- Added UpdateChecker support in `manifest.json`.

### Changed
- Updated `manifest.json` version to `1.1.3`.
- Updated dependency declaration to `Alechilles:Alec's Tamework! 2.4.x`.
- Normalized `manifest.json` `ServerVersion` to lowercase (`2026.02.19-1a311a592`) for consistency with the current release set.
- Updated README requirements to reflect Tamework `2.4.x`.

## 1.1.2 - Release Publish Hotfix - 2026-03-11
### Changed
- Updated `manifest.json` version to `1.1.2`.
- Updated release publish metadata config to stop submitting dependency relation payloads that are currently rejected by CurseForge.
- Restored release dependency metadata for publishing (`requiredProjects` with CurseForge slugs and `requiredModIds` for Modtale).
- Synced `publish-curseforge.ps1` with the shared dependency-aware release script used by the other Alec mods.

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
