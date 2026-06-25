# GitHub account cleanup plan

This document tracks the cleanup work needed to turn this GitHub account into a professional AI engineering and product portfolio.

## Goal

Position the account as:

> AI application engineer / agentic product engineer / frontend full-stack developer.

The account should highlight AI workflows, agent tooling, creator tools, content automation, personal publishing, and selected frontend architecture work.

## Profile positioning

- [x] Rewrite profile README with a clear professional narrative.
- [x] Link to personal site, featured projects, and public channels.
- [x] Prioritize public projects in the profile README.
- [x] Avoid linking private repositories directly from the public profile.
- [x] Remove forked / reference-based projects from flagship positioning.
- [ ] Pin only the most relevant repositories.
- [ ] Remove low-signal repositories from the first impression.

## Priority repositories

### Tier A: polish and showcase

| Repository | Action | Status |
| --- | --- | --- |
| `agent-workstation` | Polish README, clean metadata, add examples, prepare for public showcase. | README and package metadata updated. Public case study added to `maoxunxing.com`. Needs examples / screenshots before public release. |
| `xiaohongshushipfast` | Reposition as Xiaohongshu AI Operator; replace starter-template residue. | README rewritten. Needs real MVP implementation and demo. |
| `maoxunxing.com` | Use as the central project and writing hub. Add `/projects/` page. | Projects page added / updated in English and Chinese. |
| `ebook-maker` | Keep private if it contains real book material; extract a clean public template later. | Public case study added to `maoxunxing.com`. Template extraction still pending. |
| `a-simple-mcp` | Polish as a small MCP browser-tooling experiment. | README rewritten. Needs screenshots / sample output. |

### Tier B: keep but do not over-promote

| Repository | Action | Status |
| --- | --- | --- |
| `frontend-map` | Keep as historical frontend knowledge asset. | README repositioned as legacy frontend knowledge archive. |
| `rag-search` | Keep only as forked / reference-based RAG learning experiment. | README rewritten, moved out of flagship positioning. Do not pin. |
| `crawler_ai_info` | Review and decide whether it supports creator-operation positioning. | README added. Likely merge with crawler extension later. |
| `crawler_ai_chrome` | Review and decide whether it supports creator-operation positioning. | README rewritten as Twitter / X crawler extension experiment. |
| `Convert-to-HD-Video` | Add README or archive depending on usefulness. | README added. Still needs implementation details. |
| `capcut_audio_subtitle_align` | Add README or archive depending on usefulness. | README added. Still needs implementation details. |
| `front-end-architecture` | Remove CRA template residue; mark as low-priority historical experiment. | README replaced with archive note. |
| `schema-render` | Remove CRA template residue; mark as low-priority schema-rendering experiment. | README replaced with archive note. |

### Tier C: archive or make private

Algorithm and learning repositories:

- [ ] `algorithm`
- [ ] `algo`
- [ ] `leetcode-c`
- [ ] `leetcode-js`
- [ ] `codewars`
- [ ] `daily-c-exercises`
- [ ] `freecodecamp`

Empty, tiny, or low-signal demos:

- [ ] `renderProps-demo`
- [ ] `ultron-render`
- [ ] `edge-server-render`
- [ ] `render-html-benchmark`
- [ ] `plugin-event-demo`
- [ ] `how-to-implement-plugins`

Template residue or unclear frontend demos:

- [x] `front-end-architecture` README marked as archived / low-priority.
- [x] `schema-render` README marked as archived / low-priority.
- [ ] `xstate-demo`
- [ ] `xstate-demo2`
- [ ] `TableDemo`
- [ ] `TestReactValuePass`
- [ ] `Formily-Demo`
- [ ] `downshift-demo`
- [ ] `jsonpath-plus-demo`
- [ ] `grid-layout`
- [ ] `tree-shaking`
- [ ] `web-component`
- [ ] `simpleRedux`
- [ ] `simple-redux-thunk`
- [ ] `simple-rx`
- [ ] `simple-reactivity`
- [ ] `shared-state-management`

Private-only / sensitive repositories:

- [ ] `all-in-one-promotion` should stay private because it contains business and internal development context.
- [ ] `english-simple` should stay private until internal GitLab and local-path details are removed.
- [ ] `ebook-maker` should stay private until real book contents are separated from a clean template.
- [ ] `agent-workstation` should stay private until examples and sensitive residue are fully cleaned.

## Repository README standard

Every showcased repository should have:

- [ ] One-sentence positioning at the top.
- [ ] Clear problem statement.
- [ ] Architecture or workflow diagram.
- [ ] Quick start.
- [ ] Tech stack.
- [ ] Project status.
- [ ] Roadmap.
- [ ] Screenshots, demo GIF, or example output.
- [ ] Link back to `maoxunxing.com` when there is a deeper write-up.

## Suggested pinned repositories

Current public-only pin suggestion:

1. `xiaohongshushipfast`
2. `a-simple-mcp`
3. `crawler_ai_chrome`
4. `frontend-map`
5. `maoxunxing.com`

Keep the sixth pin empty for now rather than pinning a weak or forked project.

Do not pin:

- `rag-search` because it is forked / reference-based.
- `agent-workstation` until it is public-ready.
- `ebook-maker` until a clean public template is extracted.

After cleanup, replace weaker pins with:

- `agent-workstation` once public-ready
- `ebook-factory-template` after extraction from `ebook-maker`

## Completed changes

- [x] Updated profile README.
- [x] Reworked profile README to prioritize public repositories.
- [x] Removed `rag-search` from profile featured projects.
- [x] Moved `rag-search` into reference / learning positioning.
- [x] Rewrote `xiaohongshushipfast` README.
- [x] Rewrote `agent-workstation` README.
- [x] Cleaned `agent-workstation/package.json` metadata.
- [x] Rewrote `a-simple-mcp` README.
- [x] Rewrote `rag-search` README.
- [x] Rewrote `crawler_ai_chrome` README.
- [x] Added `crawler_ai_info` README.
- [x] Added `Convert-to-HD-Video` README.
- [x] Added `capcut_audio_subtitle_align` README.
- [x] Repositioned `frontend-map` README.
- [x] Replaced CRA README in `front-end-architecture`.
- [x] Replaced CRA README in `schema-render`.
- [x] Added English and Chinese `/projects/` pages to `maoxunxing.com`.
- [x] Added English and Chinese Agent Workstation case-study pages.
- [x] Added English and Chinese Ebook Factory case-study pages.
- [x] Updated project pages to avoid direct links to private repos.

## Next actions

1. Review GitHub pinned repositories manually.
2. Archive or privatize Tier C repositories.
3. Add demo screenshots to Tier A projects.
4. Write a Xiaohongshu AI Operator case study.
5. Add example traces / screenshots for Agent Workstation.
6. Extract a clean public `ebook-factory-template` from `ebook-maker` after separating real book content.
