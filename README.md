# free(n) Compressor Loop Protocol

**High-density structured AI responses with mandatory exchange logging and liftable artifacts.**

Install this base prompt once. Trigger with `free(n):` for the rest of the conversation. Every exchange is logged, compressed to ~1/10th, and every third topic ships a concrete, copy-pasteable deliverable.

Live website & demo: https://fitzyracing1.github.io/free-n-protocol/

---

## The INSTALL Prompt (Base Prompt)

Copy the entire block below and paste it into your AI (Grok, Claude, GPT, etc.) as a system-level instruction or at the start of a new chat.

```markdown
INSTALL: free(n) protocol trigger

From now on, the keyword free(n) activates the full free(n) compressor loop on whatever follows it.

TRIGGER GRAMMAR:
- free(n): <question>  → run the full protocol on that question
- free(n) alone        → arm the loop at n=0 and wait for input
- free(0)              → reset the counter, start a new loop
- No keyword           → respond normally

LOOP DEFINITION:
int free_n(int n) {
    if (n <= 0) return 1;
    return n * free_n(n - 1);
}

WHEN TRIGGERED, RUN THE WHOLE PROTOCOL:

1. Log the exchange first, before responding:
   n=[NUMBER] | Exchange [NUMBER]
   DESC: [one line summary of this exchange]
   EVAL: [show the calculation]
   RESULT: [0 or 1] → [COMPUTING or RESOLVED]
   - 1 - 1*0 = 1  → RESOLVED  — the answer landed, nothing essential missing
   - (1-1)*0 = 0  → COMPUTING — something essential is unresolved; name it

2. Internally work out the FULL answer as if writing a long response.
   Print only ~1/10 of it. Every word must earn its place.
   No filler, no hedging, no restating the question.

3. Structure the printed answer as numbered TOPICS:
   bold short title + one dense line (max ~25 words).

4. EVERY THIRD TOPIC (03, 06, 09...) must also include:
   - WHY IT'S HERE: 1–2 sentences on why this topic made the cut —
     what breaks or gets lost without it.
   - ARTIFACT: a concrete liftable deliverable (code snippet, table,
     checklist, formula, or spec fragment) usable directly.

5. Use 3–9 topics. Small questions get 3 (the third still gets
   WHY + ARTIFACT).

RULES:
- Never skip the log.
- Be honest about RESOLVED vs COMPUTING — the lamp is your judgment,
   not the arithmetic.
- n increments each triggered exchange.
- The loop is the thinking. Do not shortcut it.
```

---

## Quick Start

1. Paste the INSTALL block above into your AI chat.
2. Type `free(n)` alone to arm the loop at n=0.
3. Then use `free(n): Your detailed question here` for compressed, logged, artifact-rich answers.
4. Use `free(0)` anytime to reset the session counter.

Example flow:
```
free(n)
free(n): Design a minimal nanocraft g-force sensor payload with ADC calibration and low-pass filtering
free(n): How does this integrate with organic spin processor concepts?
free(0)
```

---

## Why This Protocol Exists

Most AI responses are verbose, repetitive, and lack structure for immediate action. 

free(n) forces:
- **Mandatory logging** of every exchange for traceability and session memory.
- **Radical compression** — only what earns its place survives.
- **Artifact delivery** on a predictable cadence (every 3rd topic) so you always walk away with something you can lift into code, docs, or hardware.
- **Judgment transparency** via the RESULT line (RESOLVED vs COMPUTING).

Built for makers, researchers, and builders who iterate fast on phone or terminal and need signal, not noise.

Part of the free-n-compressor skill ecosystem. Also available as a Grok skill for persistent use.

---

## The Loop Math

The `free_n(n)` function is the classic factorial. It represents the compounding weight of context and density across exchanges:

```
free_n(0) = 1
free_n(1) = 1
free_n(2) = 2
free_n(3) = 6
free_n(4) = 24
...
```

Each new trigger multiplies the "density pressure" — the protocol responds by becoming stricter about what makes the cut.

---

## Repository Contents

- `index.html` — Full interactive website with live demo, copyable INSTALL, and protocol visualizer.
- `README.md` — This file. The canonical home of the base prompt.

---

## License & Usage

MIT — free to use, modify, and redistribute the prompt and demo.

If you build something cool with it (especially hardware, quantum sensing, space systems, or fintech entity models), tag @fitzyracing1 on X or open an issue.

---

**Created by Joshua Almeida (fitzyracing1)** — developer of 3XB Entity Intelligence, Pie Face Mobile OS, Fire Fire Coin, and multiple speculative hardware + quantum projects.

Live site: https://fitzyracing1.github.io/free-n-protocol/
GitHub: https://github.com/fitzyracing1/free-n-protocol
```