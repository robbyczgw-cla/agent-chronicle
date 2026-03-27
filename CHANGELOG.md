# Changelog

## [0.6.5] - 2026-03-27
### Fixed
- Replaced hardcoded temporary file examples with portable `$TMP_DIR` placeholders in `SKILL.md`

## [0.6.4] - 2026-03-26
### Changed
- README and CHANGELOG synchronized across ClawHub, GitHub, and local
- Version badges updated

## [0.6.3] - 2026-03-26
### Added
- `--month YYYY-MM` flag: export only entries from a specific month
- `--all` flag: explicit alias for default behavior
- Default output filename when `--month` is set: `Cami-Diary-YYYY-MM.pdf`
### Changed
- PDF export cron now generates monthly PDFs (smaller, faster)

## [0.6.2] - 2026-03-03
### Changed
- Synced changelog/docs and aligned package metadata

## [0.6.1] - 2026-02-11
### Added
- `.gitignore` to exclude cache, config, and export files
- Updated metadata to openclaw format
- Documentation consistency updates

## [0.6.0] - 2026-02-05
### Changed
- Removed raw HTTP calls to Gateway from scripts/generate.py
- Diary generation now uses sessions_spawn (OpenClaw-native)
- Added --emit-task CLI flag
