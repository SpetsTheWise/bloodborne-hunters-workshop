# Changelog

## 0.2.0 — 2026-10-20

- Standalone public Windows build with embedded catalogs and an original app icon.
- Rebuilt gothic interface: item browser, six-slot gem studio, persistent favorites and recipes, session status, and backup tools.
- Supports byte-verified official visy 0.6.7 and 0.6.8 executables with Bloodborne 1.09.
- Detects the running game's actual save directory, including isolated or custom `--user` locations.
- Verified snapshots cover solo and party saves, recheck the complete file set and hashes, and publish only completed backups.
- Background operations keep the interface responsive; duplicate grants and disconnects during a grant are blocked.
- Requests the game's own autosave after every successful grant so later grants persist reliably.
- Fixes gem reference cleanup on failed instance resolution, and ensures diagnostic write failures cannot interrupt successful grants.
- Adds portable development scripts, catalog/storage tests, exact-byte bridge tests, real CPU AVX checks, UI checks and copied-save integration tests.

## 0.1.0 — private prototype

Initial native-port item and gem grant proof of concept.
