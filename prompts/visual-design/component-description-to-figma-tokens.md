## Describe a Component → Generate Design Tokens

**Goal:** Turn a plain-English component description into a structured set of design tokens.
**Tool:** ChatGPT / Claude
**Design Phase:** Visual Design / Handoff

### Prompt

> I'm designing a [COMPONENT NAME, e.g. "primary button"] for a [BRAND STYLE, e.g. "modern SaaS product with a friendly tone"].
> Generate a set of design tokens in JSON format covering:
> - color (default, hover, disabled, focus)
> - typography (font-size, font-weight, line-height)
> - spacing (padding, gap)
> - border (radius, width, color)
> - shadow

### Example Output

See the `examples/` subfolder (coming soon).

### Notes

- Pipe the JSON output directly into a Tokens Studio or Style Dictionary workflow.
- Add your brand hex values to the prompt for more accurate color suggestions.
