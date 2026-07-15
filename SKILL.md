# free-n-compressor

**free(n) Compressor Loop Protocol** — High-density structured responses with mandatory exchange logging and liftable artifacts.

Install once. Trigger with `free(n):` for the rest of the session. Every exchange is logged, radically compressed (~1/10th), and every third topic delivers a concrete, copy-pasteable deliverable (code, spec, checklist, or formula).

Live site & demo: https://fitzyracing1.github.io/free-n-protocol/

---

## Activation & Triggers

From the moment you paste the INSTALL block (or activate this skill), the following grammar is active:

- `free(n): <question>` → Run the full protocol on that question
- `free(n)` (alone) → Arm the loop at n=0 and wait for input
- `free(0)` → Reset the counter and start a fresh loop
- Normal messages (no keyword) → Respond normally

The internal `free_n(n)` factorial increases "density pressure" with each exchange — the protocol becomes stricter about what earns its place.

---

## What the Protocol Does

1. **Log first** (before any answer):
   ```
   n=[NUMBER] | Exchange [NUMBER]
   DESC: [one-line summary]
   EVAL: [calculation]
   RESULT: [0 or 1] → [COMPUTING or RESOLVED]
   ```

2. **Radical compression** — Internally solve the full problem, then output only the essential ~10%. No filler, no hedging, no restating.

3. **Numbered TOPICS** (bold title + one dense line, max ~25 words).

4. **Every 3rd topic** (03, 06, 09...) includes:
   - **WHY IT'S HERE** (1–2 sentences explaining necessity)
   - **ARTIFACT** (real, liftable deliverable: code snippet, table, checklist, formula, or spec fragment)

5. Small questions get exactly 3 topics (the third still has WHY + ARTIFACT).

---

## Compatibility

Works in:
- **Grok** (native skill + custom instructions)
- **Claude** (Projects / custom instructions)
- **ChatGPT** (Custom GPTs / instructions)
- Any other modern LLM that supports system prompts or persistent instructions

---

## How to Install

### As a Grok Skill (recommended for persistent use)
1. Go to the skill settings or use the skill-creator flow.
2. Paste the full INSTALL block from the website or README.md.
3. Name it `free-n-compressor` (or similar).
4. Activate. The triggers above will now work automatically in every conversation where the skill is enabled.

### Quick one-time use (any LLM)
Simply paste the entire INSTALL block at the start of a new chat or as a custom/system instruction.

Full INSTALL prompt and interactive demo: https://fitzyracing1.github.io/free-n-protocol/

---

## Example Flow

```
free(n)
free(n): Design a minimal nanocraft g-force sensor payload with ADC calibration
free(n): How does this integrate with organic spin processor concepts?
free(0)
```

Each response will be logged, compressed, and will include at least one production-ready artifact.

---

## Rules (enforced by the protocol)
- Never skip the log line.
- Be honest about RESOLVED vs COMPUTING (judgment, not arithmetic).
- n increments automatically with every triggered exchange.
- The loop *is* the thinking — do not shortcut it.

---

## License

MIT — free to use, modify, share, and turn into skills or custom instructions.

Created by Joshua Almeida (fitzyracing1). Part of the 3XB / Pie Face / quantum sensing ecosystem.

---

**Related**
- Website + Demo: https://fitzyracing1.github.io/free-n-protocol/
- GitHub: https://github.com/fitzyracing1/free-n-protocol
- 3XB Entity Intelligence: https://earthenwarecomputer.com