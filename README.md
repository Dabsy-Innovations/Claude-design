# Block 90' — Brand & Design System

Street football. No filter.

This repository contains the complete brand identity, design system, and **live Post Studio** for **Block 90'**.

---

## 🚀 Live Studio

**[https://dabsy-innovations.github.io/Claude-design/](https://dabsy-innovations.github.io/Claude-design/)**

Open this URL on any device — desktop, tablet, or phone — to access the Post Studio. No install required.

> GitHub Pages deploys automatically every time you push to `main`. Changes are live within ~60 seconds.

---

## Repository Structure

```
/
├── index.html                  ← Block 90' Studio (GitHub Pages entry point — open this)
├── block90-studio.html         ← Studio (local copy)
├── BRAND-BRIEF.md              ← Master brand reference (colours, typography, rules, photo specs)
├── COMPONENT-SPECS.md          ← Exact layout specs per post type (pixel-level)
├── CLAUDE-DESIGN-PROMPT.md     ← Claude Design session prompt + usage examples
├── claude-design-prompts.md    ← Per-category prompts for generating posts in Claude chat
├── logo-variations.html        ← All logo versions with usage guide (open in browser)
├── template-photo.html         ← Universal photo background builder — all post types
├── template-match-reaction.html ← Live editable match reaction post
├── template-hot-take.html       ← Live editable hot take post
├── template-transfer.html       ← Live editable transfer news post
└── .github/
    └── workflows/
        └── deploy.yml          ← Auto-deploys to GitHub Pages on every push to main
```

---

## Quick Start

### Generating posts with Claude Design

1. Open [claude.ai](https://claude.ai)
2. Open `CLAUDE-DESIGN-PROMPT.md` → copy the master prompt block
3. Paste it as your **first message** in a new Claude Design session
4. Request any post — see `CLAUDE-DESIGN-PROMPT.md` for example requests

### Enabling GitHub Pages (one-time setup)

After pushing to GitHub:
1. Go to your repo → **Settings** → **Pages**
2. Under "Source" → select **GitHub Actions**
3. Save — the workflow runs automatically on every push
4. Your studio will be live at: `https://dabsy-innovations.github.io/Claude-design/`

### Pushing all files

```bash
git clone https://github.com/Dabsy-Innovations/Claude-design.git
cd Claude-design
# copy all files from this folder into the repo root
git add .
git commit -m "Block 90' brand system v1.0 — studio, templates, Pages config"
git push origin main
```



1. Download the template file you need
2. Open it in any browser (Chrome recommended)
3. **For photo posts:** Open `template-photo.html` → upload your photo → choose post type → fill fields
4. Fill in the text fields — the preview updates live
5. Screenshot the phone card: **Chrome → Inspect → right-click element → "Capture node screenshot"**
6. Upload to TikTok as an image post or cover frame

**Photo template supports:** Match Reaction · Hot Take · Transfer News · Headline/Statement — all with full-bleed photo background and dark overlay.

### Brand reference

- **Colours, typography, rules** → `BRAND-BRIEF.md`
- **Pixel-level layout specs** → `COMPONENT-SPECS.md`
- **Logo usage** → `logo-variations.html`

---

## Colour System

| Token | Hex | Use |
|---|---|---|
| Bloc Red | `#D62828` | Match reactions, breaking news, primary accent |
| Hot Red | `#FF3333` | Live moments, hot takes |
| Pitch Gold | `#F4A01C` | Transfers, eyebrows, labels |
| Pitch Green | `#1D9E75` | Tactical posts |
| Data Blue | `#378ADD` | Stats posts |
| Bronze | `#8B6914` | Culture/throwback posts |
| Terrace White | `#F0EDE8` | All text |
| Deep Black | `#0A0A0A` | Permanent background |

---

## Content Categories

| Category | Colour Signal | Template |
|---|---|---|
| Match Reaction | Red top bar | `template-match-reaction.html` |
| Hot Take | Red left bar | `template-hot-take.html` |
| Transfer News | Gold top bar | `template-transfer.html` |
| Tactical Breakdown | Green left bar | — |
| Stats & Data | Dark blue bg + blue bar | — |
| Football Culture | Bronze left bar | — |

---

## Brand Rules (Non-Negotiable)

- Background is always `#0A0A0A` — no exceptions
- Maximum 3 colours per post
- No gradients, no drop shadows, no glow effects
- No rounded corners on post cards
- Gold is for eyebrows and labels only — never body text
- Red bar on match/take posts; gold bar on transfer posts — never swap

---

*Block 90' Brand System v1.0 — built with Claude*
