## [0.6.3] - 2026-03-26

### Added
- `--month YYYY-MM` flag: export only entries from a specific month (e.g. `--month 2026-03`)
- `--all` flag: explicit alias for default behavior (export all entries)
- Default output filename when `--month` is set: `Cami-Diary-YYYY-MM.pdf`

### Changed
- Cron switched to monthly PDFs — smaller files, faster export, cleaner history

# Changelog

## [0.6.2] - 2026-03-03

### Changed
- Synced changelog/docs and aligned package metadata with current release state.


## v0.6.1 — 2026-02-11

- Added `.gitignore` to exclude cache, config, and export files
- Updated metadata to openclaw format
- Documentation consistency updates

## v0.6.0 — 2026-02-05

- **Architecture:** removed raw HTTP calls to the Gateway from `scripts/generate.py`.
- **OpenClaw-native generation:** diary generation is now intended to run via **sub-agents** using the `sessions_spawn` tool (model selection is handled by OpenClaw defaults; no hardcoded model name).
- **CLI ergonomics:** added `--emit-task` to print a portable JSON payload that agents can pass into `sessions_spawn`.

