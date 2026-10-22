# uYouEnhanced

Theos tweak bundle for YouTube (uYouPlus). Sources: `Sources/`, `Tweaks/`, `Extensions/`, `Localizations/`. Build with `build.sh` / `make`.

## Working rules (token-saving)
- Read only the files you need; prefer Grep over reading whole files. `Tweaks/` are submodules: don't edit unless asked.
- Batch independent tool calls in one turn; avoid repeating the same edit.
- For multi-file changes, plan first, then implement.
- Do not connect/disconnect MCP servers or switch models mid-session; set them at the start.
- Run the build to self-check before reporting back.
- Run `/compact` before taking a break, not after; use `/clear` between unrelated tasks.
