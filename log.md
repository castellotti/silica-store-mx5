# Log

## 2026-11-14

* PR #1 merged. All 383 sourced facts verify against `main` (33 re-derived, 350 unchanged),
  including the 4 git-source canary facts; `silica check-store` reports 0 errors.
* Registered with `silica store add mx5`, pointing at the local checkout.
* Interim authoring tools (generator, pin helper) are kept, untracked, in `tools/`, which
  `.gitignore` excludes; they are expected to be obsolete once Silica ships Rounds 2–3.
* Created the store: model overview and glossary, 4 generations, 10 revisions, 37 model years
  (1990–2026), 4 engine concepts, 3 award concepts, 2 related concepts and the canary concept.
* Sources: permanent revisions of 11 English Wikipedia articles and the store's own canary files.
* Pins computed with Silica's own hashing and fingerprint code (Silica main at d23d43d).
* Silica round 1 (read path, CLI, registry) is merged. Configured: `.silica/config.yaml` with the
  default write policy (`mode: bot`, `gate: manual`). Not yet configured: `generate.yaml` (round 2),
  bot credentials and a PR check (round 3), an MCP deployment (round 4).
* Known follow-ups: model-year facts repeat revision-level facts (one copy per year), so a
  source change needs the same edit in several files; pinned `rev` values for Wikipedia pages
  drift as the rendered HTML changes, so those facts pass by region hash rather than the probe.
