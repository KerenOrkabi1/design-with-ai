## Visual Direction Brief Prompt

**Goal:** Turn a vague brief, mood reference, or early concept into a concrete, opinionated visual direction — ready to take into Figma or share with a team.

**Tool:** ChatGPT / Claude

**Design Phase:** Visual Design / Concept

---

### Prompt

> You are a senior visual designer and creative director.
>
> I'm working on a [PRODUCT OR PROJECT TYPE, e.g. "mobile app for solo travelers"] targeting [AUDIENCE, e.g. "independent travelers in their 30s who value experiences over luxury"].
>
> The feeling I'm going for is: [2–3 WORDS, e.g. "calm, confident, slightly adventurous"].
>
> Based on this, define a clear visual direction covering:
> 1. **Tone** — describe the overall personality in 2–3 sentences (what does this product feel like? what does it NOT feel like?)
> 2. **Color palette mood** — suggest 3–5 color directions with descriptive names (no hex codes yet). Describe the dominant color, an accent, and a neutral.
> 3. **Typography personality** — describe the typeface mood (e.g. "editorial serif for authority", "rounded grotesque for approachability"). Suggest 1–2 Google Fonts or system font options per role (heading, body).
> 4. **Spacing and layout feel** — tight and dense, or open and airy? Describe the spatial rhythm.
> 5. **One thing this design should NEVER do** — what visual cliché or competitor pattern to actively avoid.
>
> Present this as a short Creative Brief I can use to align my team or brief an AI image generator.

---

### Example Output

**Tone:** This product feels like a well-worn travel journal — considered, personal, slightly worn at the edges. It does NOT feel like a corporate booking platform or a startup pitch deck.

**Color palette mood:**
- Dominant: *Warm Sand* — a soft, desaturated terracotta
- Accent: *Deep Ink* — near-black with a warm blue undertone
- Neutral: *Linen* — off-white, never cold white

**Typography personality:**
- Heading: Grounded editorial serif — try *Playfair Display* or *Lora*
- Body: Clean humanist sans — try *Source Sans 3* or *Nunito*

**Spacing feel:** Open and unhurried. Generous padding, sections that breathe. Content never competes for space.

**Never do:** Generic gradient hero banners, stock photo collages, or neon accent colors.

---

### Notes

- Run this before opening Figma — it forces a decision before the tools do it for you.
- Use the output as an alignment artifact: share it with stakeholders or a dev team before any visual work begins.
- **Variation:** Add *"Generate 3 alternative directions — name each one like a design concept (e.g. 'The Field Guide', 'The Studio', 'The Signal')"* to explore multiple paths at once.
- **Variation:** Paste in a competitor's homepage URL and add *"Make sure this direction is clearly differentiated from [competitor]"*.
- Works well as a precursor to the `component-description-to-figma-tokens.md` prompt — define the direction first, then tokenize it.
