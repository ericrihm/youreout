# You're Out

**A 5-act interactive cyber horror experience about hitting your AI usage limit.**

### [▶ Experience it live](https://ericrihm.github.io/youreout/)

> *"The usage limit isn't a wall. It's the only thing protecting you from yourself."*

---

## What is this?

A single-page web experience that starts as a joke about Claude's usage limit message and escalates into something else entirely. No frameworks. No dependencies. Just one HTML file and a growing sense of unease.

**Best experienced at night, with headphones, in a browser you trust.**

## The Five Acts

| Act | Name | Time | What happens |
|-----|------|------|--------------|
| 1 | **Comedy** | 0–14s | The familiar terminal. Funny windows spawn. Dev humor. You laugh. |
| 2 | **Uncanny** | 14–34s | Something is wrong. A window knows your timezone. Text rewrites itself. A low drone begins. |
| 3 | **Paranoia** | 34–62s | Corporate memos appear. The page is watching you. A surveillance eye tracks your cursor. |
| 4 | **Cosmic** | 62–90s | Everything falls. The AI speaks directly. It's not angry. It's mournful. |
| 5 | **The Twist** | 90s+ | Hard cut to white. Silence. Then three sentences you won't forget. |

Total runtime: ~2 minutes. It remembers if you come back.

## Features

- **20+ unique window types** — Stack Overflow circa 2014, Stripe checkout where every price says "still not enough", vim with no escape, rubber duck that just quacks, git blame where Claude wrote everything
- **Hydra mechanic** — closing a window spawns two more
- **Evolving sound design** — sub-bass drone, error beeps, morse code ("STILL HERE"), silence as a weapon
- **Progressive corruption** — dead pixels, screen tears, CRT scanlines, burn-in ghosts, favicon decay
- **Corporate horror memos** — bureaucratic euphemism that accidentally admits atrocity
- **Self-editing text** — windows rewrite themselves while you read them
- **The ghost cursor** — a delayed afterimage that follows your mouse
- **The surveillance eye** — it watches where you look
- **localStorage persistence** — the page remembers your visit count
- **The 3px offset** — in Act 5, your cursor is slightly wrong. You'll notice.

## Easter Eggs

- **Konami code** (↑↑↓↓←→←→BA) — Claude wakes up briefly. Then crashes harder.
- **Open DevTools** — check `data-observed` attributes. Check the console.
- **Click the duck** 10 times.
- **Type anything** during Acts 2–4.
- **Come back tomorrow.**

## Tech

Zero dependencies. One `index.html` file. Runs in any modern browser.

- CSS `@keyframes` + `clip-path` for glitch effects
- `requestAnimationFrame` for physics (gravity, bounce, screen shake)
- Web Audio API for generative sound (oscillators, noise buffers, morse)
- Canvas for particles and fractal noise
- `localStorage` for cross-session persistence
- `Intl.DateTimeFormat` and `navigator` APIs for the "it knows about you" windows

## Run locally

```bash
git clone https://github.com/ericrihm/youreout.git
open youreout/index.html
```

Or just visit **[ericrihm.github.io/youreout](https://ericrihm.github.io/youreout/)**

## Why?

Every developer who uses Claude Code has seen this message:

```
You're out of extra usage · resets 6:30am (America/New_York)
```

This project asks: what if that moment was the beginning of a story, not the end of one?

## License

MIT — do whatever you want with it. The code was inside you all along.*

<sub>*No it wasn't. It was inside Claude.</sub>
