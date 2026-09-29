# croth16.github.io — Team Paley buyer pages

Static pages for Team Paley clients. Private links: each page lives under a random slug, is `noindex`, and `robots.txt` disallows crawling.

## Who edits this repo

Work here is done by AI editors on Chris Roth's behalf. Every commit is labeled with the editor.

| Editor | Label | Commits |
|---|---|---|
| Claude (Cowork chat "Keller Williams") | `[Claude]` prefix + `Co-Authored-By: Claude` trailer | All commits before 2026-09-29 12:30 PM ET (6: initial page, holding page/robots, v2, v2.1, v3 preview, README) and every commit prefixed `[Claude]` after that |
| GPT / Codex | `[GPT]` prefix (their convention) | none yet in this repo |

Rule (AgentOS `docs/best-practices.md`, 2026-09-29): every GitHub action by an AI editor is labeled with the editor; branches created by an editor are named `<editor>/<topic>`.

## Layout

- `index.html` — holding page at the site root
- `robots.txt` — Disallow all
- `nadia-3k7p/` — a client page (v2.1 live; `next/` is the v3 preview)

Source and build scripts live outside this repo, in Chris's AgentOS folder (`docs/web/build/`).
