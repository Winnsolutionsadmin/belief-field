---
name: active context — belief-field
description: Where the last session left off. Read at session start, update at session end.
type: project
---

# Active Context

> **Read this first.** Update at the END of every session via `/wrap-session` — this is the resume mechanism between sessions.

## Last session

- **Date:** 2026-06-02 (retrofitted via the canonical scaffold — no working session yet on the pattern)
- **What was done:** Retrofitted 2026-06-02 to the canonical scaffold; no working session yet on the pattern; existing state preserved. Added `CLAUDE.md` (cold-start ritual + accurate description) and `memory-bank/`. No artifact files were touched.

## Where I am now

Published belief-field artifact for Nathan McCauley (Co-Founder & CEO, Anchorage Digital) on GitHub remote `Winnsolutionsadmin/belief-field`, branch `main`. Last substantive commit (`3c50bfc`): "Canonical = 3D belief field on full 33-belief data (public-sanitized); drop 2D atlas" — the 2D atlas was removed and the 3D field is the canonical view. Current tree: `index.html`, `belief-map.html`, `belief-explorer.html`, and `data/{belief-db.js, beliefs-map-db.js, source-links.js}`. The `source/` build scripts referenced in the file headers are NOT present in this repo (only the generated public bundle is). One untracked `.DS_Store` is the only working-tree change.

## Immediate next step

(Define on next working session.)

## Open questions / blockers

- (none flagged at retrofit time)

## Open loops

<!-- Things in flight that aren't done but need to be remembered. -->
- The generated HTML + `beliefs-map-db.js` are build outputs; if the corpus changes, the build must be re-run from `source/` (not present here) rather than hand-editing the artifacts.
