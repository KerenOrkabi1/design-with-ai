# Prompts

This folder contains reusable AI prompts organized by design task.

## Structure

```
prompts/
├── ux-research/       # Prompts for user research, interviews, synthesis
├── visual-design/     # Prompts for mood boards, style guides, components
├── content/           # Prompts for UX writing, microcopy, accessibility text
└── feedback/          # Prompts for critique, design reviews, iterations
```

## Prompt Index

### 🔬 UX Research

| File | Goal | Phase |
|------|------|-------|
| [interview-synthesis.md](ux-research/interview-synthesis.md) | Turn raw interview notes into themes, pain points, and a problem statement | Discovery |

### 🎨 Visual Design

| File | Goal | Phase |
|------|------|-------|
| [component-description-to-figma-tokens.md](visual-design/component-description-to-figma-tokens.md) | Turn a plain-English component description into design tokens (JSON) | Visual Design / Handoff |
| [visual-direction-brief.md](visual-design/visual-direction-brief.md) | Turn a vague brief or mood reference into a concrete, opinionated visual direction | Visual Design / Concept |

---

## How to Contribute

Each prompt file should follow the template below.

```markdown
## Prompt Title

**Goal:** What this prompt helps you achieve.
**Tool:** ChatGPT / Claude / Gemini / Midjourney / etc.
**Design Phase:** Discovery / Ideation / Validation / Handoff

### Prompt

> Paste the prompt here

### Example Output

Optional: share a sample output or screenshot.

### Notes

Tips, variations, or known limitations.
```

> ⚠️ **Maintainer note:** Update this README's Prompt Index every time a new prompt file is added or renamed.

See [CONTRIBUTING.md](../CONTRIBUTING.md) for full guidelines.
