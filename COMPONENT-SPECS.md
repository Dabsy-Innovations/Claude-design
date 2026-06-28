# Block 90' — Claude Design Component Specs
**Reference this alongside BRAND-BRIEF.md for exact layout instructions per post type.**

---

## Component 1 — Match Reaction Post

```
Canvas: 1080 × 1920px
Background: #0A0A0A

LAYER ORDER (bottom to top):
1. Background fill: #0A0A0A
2. Ghost "90" text: Bebas Neue, ~400px, rgba(214,40,40,0.06), anchored bottom-right, overflow allowed
3. Top accent bar: full width, 6px height, #D62828, y=0
4. Eyebrow text: Barlow Condensed 600, 28px, #F4A01C, letter-spacing 8px, uppercase, y=80px, x=48px
5. Home team name: Barlow Condensed 800, 72px, #F0EDE8, uppercase, x=48px
6. Home score: Bebas Neue, 120px, #F0EDE8, right-aligned
7. Away team name: Barlow Condensed 800, 72px, #F0EDE8, uppercase, x=48px
8. Score dash: Bebas Neue, 100px, #D62828, between scores
9. Away score: Bebas Neue, 120px, #F0EDE8, right-aligned
10. Divider: 1px, #2E2E2E, full width, y=~900px
11. Reaction headline: Barlow Condensed 700, 72px, #F0EDE8, uppercase, x=48px, max-width 980px
    — Key word override: #D62828
12. Footer divider: 1px, #2E2E2E, full width, y=~1780px
13. Wordmark "BLOCK 90'": Bebas Neue, 52px, x=48px, y=1830px — "BLOCK" #F0EDE8, "90'" #D62828
14. Status badge: Barlow Condensed 600, 28px, right side footer — colour per status

SPACING:
- Content starts at y=100px (below top bar)
- Score block: teams left, scores right, vertically centered per row
- Reaction headline: below score block with 60px gap
- Footer: y=1820px fixed
```

---

## Component 2 — Hot Take Post

```
Canvas: 1080 × 1920px
Background: #0A0A0A

LAYER ORDER (bottom to top):
1. Background fill: #0A0A0A
2. Left accent bar: 8px wide, full height, #FF3333, x=0
3. "HOT TAKE" badge: Barlow Condensed 600, 28px, letter-spacing 6px, #F0EDE8 on #D62828 pill, x=80px, y=120px, padding 10px 24px, border-radius 2px
4. Quote mark: Bebas Neue, 220px, #D62828, line-height 0.75, x=72px, y=260px
5. Statement text: Barlow Condensed 700, 88px, #F0EDE8, uppercase, x=80px, y=420px, max-width 940px, line-height 1.15
   — Highlight word: #F4A01C
6. Divider: 1px, #2E2E2E, full width, y=~1720px
7. Wordmark: Bebas Neue, 52px, x=80px, y=1790px
8. CTA text: Barlow Condensed 600, 36px, #5A5A5A, right side footer y=1790px

SPACING:
- All content indented 80px from left (to clear the left bar)
- Statement fills the middle third of the canvas
- Generous white space above and below statement
```

---

## Component 3 — Transfer News Post

```
Canvas: 1080 × 1920px
Background: #0A0A0A

LAYER ORDER (bottom to top):
1. Background fill: #0A0A0A
2. Gold accent bar: 580px wide, 8px height, #F4A01C, x=48px, y=60px
3. "TRANSFER UPDATE" eyebrow: Barlow Condensed 600, 28px, #F4A01C, letter-spacing 8px, x=48px, y=120px
4. Club FROM: Barlow Condensed 700, 52px, #5A5A5A, uppercase, x=48px, y=200px
5. Arrow →: Bebas Neue, 52px, #D62828, inline with clubs
6. Club TO: Barlow Condensed 700, 52px, #F0EDE8, uppercase
7. Player first name: Bebas Neue, 140px, #F0EDE8, x=48px, y=320px
8. Player last name: Bebas Neue, 200px, #F4A01C, x=48px (larger than first name)
9. Fee card: rect 984px wide, 120px tall, fill #141414, border 1px #2E2E2E, x=48px, y=~1100px
   — "REPORTED FEE" label: Barlow Condensed 600, 24px, #5A5A5A, left-padded 32px
   — Fee value: Bebas Neue, 80px, #F4A01C, right-padded 32px
10. Status pill: Barlow Condensed 600, 28px, border-radius 2px
    — Rumour: border 1px #2E2E2E, #5A5A5A text
    — Breaking: fill #D62828, #F0EDE8 text
    — Official: fill #F4A01C, #0A0A0A text
11. Divider: 1px, #2E2E2E, y=~1780px
12. Wordmark: left footer
13. Source tag: Barlow Condensed 600, 28px, #3A3A3A, right footer
```

---

## Component 4 — Tactical Breakdown Post

```
Canvas: 1080 × 1920px
Background: #0A0A0A

LAYER ORDER (bottom to top):
1. Background fill: #0A0A0A
2. Left accent bar: 8px wide, full height, #1D9E75
3. "TACTICAL BREAKDOWN" eyebrow: Barlow Condensed 600, 28px, #F4A01C, letter-spacing 8px, x=80px, y=80px
4. Headline: Barlow Condensed 800, 80px, #F0EDE8, uppercase, x=80px, y=140px, max-width 940px
   — Formation number (e.g. "4-3-3"): #D62828
5. Pitch diagram rect: 984px wide, ~700px tall, fill #0D1A0F, border 1px #1A3020, x=48px, y=~480px
   — Centre line: 1px #1A3020, horizontal midpoint
   — Centre circle: ~200px diameter, 1px #1A3020, no fill
   — Our team dots (red): 32px circles, #D62828 fill; position label below in Barlow Condensed 600, 20px, #5A5A5A
   — Opposition dots (grey): 32px circles, transparent fill, 1px #5A5A5A border
6. Key point rows (below pitch):
   — Number: Bebas Neue, 52px, #D62828
   — Text: Barlow 400, 36px, #C0BBBA, max-width 880px
7. Divider + footer standard

PITCH LAYOUT (4-3-3 example):
- Opposition top row: 4 dots evenly spaced
- Opposition mid row: 3 dots
- Gap = centre line
- Our mid row: 3 dots (CM, DM, CM)
- Our front row: 3 dots (LW, ST, RW) with labels
```

---

## Component 5 — Stats & Data Post

```
Canvas: 1080 × 1920px
Background: #04193A (dark blue — only category)

LAYER ORDER (bottom to top):
1. Background fill: #04193A
2. Left accent bar: 8px wide, full height, #378ADD
3. Eyebrow: Barlow Condensed 600, 28px, #378ADD, letter-spacing 8px, x=80px, y=80px
4. Headline: Barlow Condensed 800, 80px, #F0EDE8, uppercase, x=80px, y=140px
5. Data rows (top 5):
   — Rank number: Bebas Neue, 60px, #378ADD, x=80px
   — Name: Barlow Condensed 700, 52px; #1 = #F0EDE8, others = #5A5A5A
   — Bar: rect height 12px, fill #378ADD, track fill #0C2E5A, full width 760px starting x=280px
   — Value: Bebas Neue, 52px, #F0EDE8, right-aligned
   — #1 bar slightly wider/brighter than others
6. Context note: Barlow 400, 32px, #5A5A5A, x=80px, below data rows
7. Footer: wordmark left, hashtag/source right
```

---

## Component 6 — Football Culture Post

```
Canvas: 1080 × 1920px
Background: #0A0A0A with rgba(139,105,20,0.06) warm tint overlay

LAYER ORDER (bottom to top):
1. Background fill: #0A0A0A
2. Warm tint overlay: full canvas, rgba(139,105,20,0.06)
3. Left accent bar: 8px wide, full height, #8B6914
4. "FOOTBALL CULTURE" eyebrow: Barlow Condensed 600, 28px, #8B6914, letter-spacing 8px, x=80px, y=80px
5. Year/era ghost: Bebas Neue, ~300px, rgba(139,105,20,0.12), bottom-right corner
6. Headline: Barlow Condensed 800, 80px, #F0EDE8, uppercase, x=80px, y=140px
   — Key word: #8B6914 (bronze — NOT red or gold)
7. Body text: Barlow 400, 40px, #C0BBBA, x=80px, max-width 940px, line-height 1.5
8. Divider: 1px #2E2E2E
9. Footer: wordmark left, "#Throwback" in #3A3A3A right
```

---

## Shared Footer Spec (All Posts)

```
Footer zone: y=1820px to y=1920px
Left: "BLOCK 90'" — Bebas Neue, 52px — "BLOCK" #F0EDE8, "90'" #D62828
Right: category tag / status — Barlow Condensed 600, 28px, #3A3A3A or #5A5A5A
Divider above footer: 1px #2E2E2E, full width, y=1810px
```

---

*Block 90' Component Specs v1.0*
