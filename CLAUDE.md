# belief-field

## COLD-START RITUAL (read on the first message of every session)

1. Read this entire file.
2. Read `memory-bank/activeContext.md` for the live state — what the last session did, where artifacts live, what open questions are blocking, what's next.
3. If working on a deliverable, also read `memory-bank/lessons.md` for any folder-specific dos/don'ts.
4. If `memory-bank/activeContext.md` and this file conflict, trust `activeContext.md` for state and trust this file for rules / standing instructions.
5. At session end, run `/wrap-session` to refresh `memory-bank/activeContext.md` and audit in-flow captures.

## What this is

A published, self-contained **belief field** artifact for **Nathan McCauley** (Co-Founder & CEO, Anchorage Digital) — the output of the `/belief-field` skill. It is a static, dependency-light web bundle: an interactive **3D belief map** (`index.html` / `belief-map.html`, Three.js from the unpkg CDN, no build step at view time) plus a tabulated **belief database / explorer** (`belief-explorer.html`). The data lives in `data/*.js` as `window.*` globals: 32 scored beliefs across 7 sectors, ~883–1017 verbatim quotes from 56–69 sources, plus `source-links.js` for provenance.

This is the **public-sanitized** build: private 1:1 material has been excluded (see the header note in `data/belief-db.js`). The HTML and `data/beliefs-map-db.js` are generated artifacts (by `source/build*.py` / `source/build.mjs`, which are NOT vendored into this repo) — do not hand-edit the inline engine or the map DB; the editable corpus is the belief database that feeds the build. Status: **published** (git remote `Winnsolutionsadmin/belief-field`), canonical view is the 3D field on the full 33/32-belief data; the older 2D atlas was dropped.

## Memory

Project-local state and history live in [`memory-bank/`](memory-bank/). Start with [`memory-bank/activeContext.md`](memory-bank/activeContext.md). Behavior rules come from the macro fileset (auto-loaded every session) — this file holds project-local context only.
