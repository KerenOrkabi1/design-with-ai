## Interview Synthesis Prompt

**Goal:** Turn messy, raw interview notes into structured themes, pain points, and a draft problem statement — fast.

**Tool:** ChatGPT / Claude

**Design Phase:** Discovery

---

### Prompt

> You are a senior UX researcher. I'm going to give you raw notes from [N] user interviews.
> 
> Please do the following:
> 1. Identify the top 5 pain points mentioned across the interviews.
> 2. Group them into themes (give each theme a short, memorable name).
> 3. Note any surprising or contradictory findings.
> 4. Draft one problem statement per theme in this format: "[User type] needs a way to [goal] because [insight]."
> 
> Raw interview notes:
> [paste your notes here]

---

### Example Output

**Theme: Onboarding Confusion**  
Pain points: users don't know where to start, tooltips are ignored, setup takes too long.  
Problem statement: *"New users need a way to get to their first success quickly because the current setup flow feels overwhelming and unclear."*

---

### Notes

- Works best with at least 3 interviews worth of notes. Less than that and the themes won't be reliable.
- If your notes are very long, split them across two messages and ask the AI to synthesize both at the end.
- Always validate AI-generated themes against your own memory of the interviews — AI can miss emotional tone and body language cues.
- **Variation:** Add *"What questions should I be asking that I haven't asked yet?"* at the end to identify research gaps.
