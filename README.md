# MOLLY//CORE

> *Cyberpunk command center for Jon Rich and Molly.*

A constellation of 10 self-contained HTML pages — Jon's portfolio, project tracker, hacking guide, bot dashboard, and a few experiments — all deployed as a single static site on Vercel.

[Visit →](https://mollycore.vercel.app)

## Pages

| Page | Purpose |
|------|---------|
| `index.html` | Main dashboard — live BTC, project status, Molly chat avatar, quick links. |
| `portfolio.html` | Mobile-first portfolio. The page to share when someone asks "what do you build?" |
| `status.html` | Empire status board — visual project tracker. |
| `bots.html` | Bot control center for the live Telegram fleet. |
| `chat.html` | Molly chat avatar + voice interface (Ollama-backed). |
| `hacking-guide.html` | Personal ethical-hacking learning guide. CEH-track content. |
| `legion.html` | Lenovo Legion Go setup notes — Kali, dev environment, copy-buttons. |
| `publish.html` | MOLLY//PUBLISH content station + master checklist for posts. |
| `rpg.html` | Browser RPG experiment. Projectile attacks, flash effects. |
| `wrestling.html` | **CodeWrestling Episode 1: Molly vs The Conflict.** Concept wrestling. |

## Stack

Pure HTML, CSS, JavaScript. No build step. Some pages call external APIs (BTC price, project status, Ollama-served LLM). Deployed by pushing to `master` — Vercel handles the rest.

## Visual conventions

- **Background:** near-black (`#08080f`)
- **Accents:** pink `#ff2d78`, cyan `#00f5d4`, gold `#ffd60a`, purple `#8b00ff`, green `#00ff87`
- **Type:** Space Grotesk for body, Space Mono for code/data
- **Status badges:** `live` (cyan), `building` (gold), `dev`/`devnet` (purple), `idea` (gray)

Same vibe as [Stacker Zero](https://stackerzero.com) and [Maineiac Mystic](https://maineiac-mystic-landing.vercel.app) — Jon's broader visual signature.

## Local

```bash
# Just open a file
start index.html

# Or serve with anything
python -m http.server 8000
```

## License

MIT
