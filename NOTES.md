# 📓 Session Notes — design-with-ai

This file tracks progress, decisions, and what to pick up next across sessions.
Update this file whenever something is completed or a new decision is made.

---

## ✅ Completed

- [x] Repository structure created (`prompts/`, `workflows/`, `case-studies/`, `resources/`)
- [x] `README.md` written with purpose, topics, audience, and contributing info
- [x] `CONTRIBUTING.md` written with full contributor guide
- [x] `LICENSE` added (MIT)
- [x] `prompts/README.md` — structure + contribution template
- [x] `prompts/ux-research/` folder created
- [x] `prompts/visual-design/` folder created
- [x] `case-studies/README.md` — structure + case study template
- [x] `workflows/README.md` — structure + workflow file format
- [x] `workflows/discovery/` folder created
- [x] `resources/README.md` — curated tools, articles, courses, communities
- [x] **Challenge 1** — `workflows/discovery/ai-discovery-sprint.md` added (first real workflow)
- [x] **Challenge 2** — `resources/README.md` was already complete ✅
- [x] **Challenge 3** — `README.md` updated with folder map + section links
- [x] **Challenge 4** — `prompts/ux-research/interview-synthesis.md` added (first real prompt)
- [x] Fixed broken image tag in `README.md`
- [x] `NOTES.md` created (this file)
- [x] `prompts/visual-design/visual-direction-brief.md` added (second real prompt — concept-to-brief, inspired by `@thedesignproject/agent-skills` `frontend-design` skill)
- [x] `prompts/README.md` updated with Prompt Index table + maintainer note about keeping it current

---

## 🔜 Up Next

- [ ] Add first real case study under `case-studies/`
- [ ] Add workflows for `ideation/`, `validation/`, `handoff/`
- [ ] Add `prompts/content/` and `prompts/feedback/` folders with real prompts
- [ ] Add `## Customize This` section to each existing prompt (list placeholders for local override)
- [ ] Consider adding GitHub Issue templates for contributions
- [ ] Consider adding a GitHub Discussions section for community Q&A

---

## 💡 Decisions Made

- Dual license: MIT for code/scripts, CC-BY-4.0 for content and prompts
- Folder slugs use kebab-case (`ux-research`, `visual-design`)
- Each folder has its own `README.md` as a guide for contributors
- Workflow files follow a fixed 6-section format (Overview, Tools, Time, Steps, Tips, Output)
- Prompt files follow a fixed format (Goal, Tool, Phase, Prompt, Example Output, Notes)
- **README rule:** Every time a new file is added or renamed, the nearest `README.md` (and its Prompt/Workflow Index) must be updated in the same commit
- **Public repo stays generic:** `design-with-ai` uses `[PLACEHOLDERS]` throughout — local copies override with real product/brand/audience details
- **Local override strategy:** Each prompt will include a `## Customize This` section listing exactly which placeholders to replace locally, so the public file is self-documenting about its own genericness

### ⚠️ Public/Private Repo Challenges to Watch

This repo is intentionally generic so it can be used as a public template. When working with it locally (or on client projects), keep these risks in mind:

1. **Placeholder drift** — generic prompts use `[BRAND STYLE]`, `[AUDIENCE]` etc. If local overrides aren't maintained, you silently lose specificity and nobody notices
2. **Two sources of truth** — if you improve a prompt locally, it's easy to forget to generalize it back to the public repo
3. **No enforcement layer** — nothing stops someone from using the generic version locally by mistake. Add a README note like *"check your local overrides before using any prompt directly"*
4. **Versioning mismatch** — local customizations can fall out of sync when the public repo updates the base prompt structure
5. **Solution pattern:** Each prompt should include a `## Customize This` section at the bottom listing which placeholders to override — makes the public file self-documenting

---

## 🗓️ Session Log

| Date | What happened |
|---|---|
| 2026-07-20 | Resumed after lost session. Completed all 4 challenges. Created NOTES.md. |
| 2026-07-20 | Added `prompts/visual-design/visual-direction-brief.md`. Discussed public/private repo strategy and challenges. Updated `prompts/README.md` with Prompt Index. Established README update rule. |

---

*Update this file at the start and end of every working session.*
