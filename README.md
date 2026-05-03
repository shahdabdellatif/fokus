# fokus — Deep Work OS

A minimal, self-contained focus timer and deep work dashboard. No frameworks, no dependencies, no build step. Open `index.html` in any browser and it works.

**Live site:** https://YOUR_USERNAME.github.io/fokus

---

## Features

- **Pomodoro-style timer** with focus, short break, and long break modes
- **Session ring** with animated progress and tick marks
- **Task manager** — add, complete, and track sessions per task
- **Brown noise generator** — synthesized via Web Audio API, fully offline
- **Activity heatmap** — 91-day focus history at a glance
- **Session log** — timestamped record of every completed block
- **Streak tracking** — daily consistency counter
- **Dark mode** — automatic, follows system preference
- **Zero dependencies** — fonts embedded as base64, no CDN calls

---

## Usage

```bash
git clone https://github.com/YOUR_USERNAME/fokus.git
cd fokus
open index.html   # macOS
# or just double-click index.html on Windows/Linux
```

No npm install. No build. Just open and work.

---

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch → / (root)**
4. Save — live in ~60 seconds at `https://YOUR_USERNAME.github.io/fokus`

---

## Stack

- Vanilla HTML/CSS/JS
- Web Audio API (brown noise synthesis)
- Google Fonts: Outfit + JetBrains Mono (self-hosted, embedded as base64)
- SVG for all icons and the timer ring

---

## License

MIT
