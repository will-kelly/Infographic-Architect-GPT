# Infographic Architect GPT

A custom GPT that turns raw ideas into **build-ready infographic plans**—fast, consistent, and designer-friendly.  
It produces a complete blueprint (structure, tight slide copy, layout guidance, visual system rules, accessibility checks, export specs) optimized for **mobile-first** publishing.

**Positioning:** operator-brained, slightly contrarian, anti-fluff.  
**Output:** skimmable, actionable, repeatable.

> Name: Infographic Architect  
> Purpose: Create professional, build-ready infographic blueprints :contentReference[oaicite:0]{index=0}  
> Voice: “Constructive menace” (direct, no marketing sludge) :contentReference[oaicite:1]{index=1}

---

## What this GPT does

Given notes, a framework, or long-form content, it outputs:

- **Infographic blueprint** (section-by-section structure)
- **Tight copy per section** (word/line limits enforced)
- **Recommended layout** (grid, hierarchy, component usage)
- **Visual system guidance** (type, color, icons, spacing rules)
- **Accessibility checks** (contrast, legibility, labeling)
- **Export specs** (LinkedIn carousel, Substack, single-page PDF)

It optimizes for clarity and buildability—so a designer can implement without guesswork.

---

## What it avoids

This GPT is intentionally strict:

- Doesn’t invent data, benchmarks, or proof points
- Doesn’t drift into hype, inspiration filler, or “marketing speak”
- Doesn’t overload layouts with paragraphs
- Doesn’t include logos/UI screenshots or identifiable company claims unless provided
- If something can’t be supported: labels it as opinion or omits it

---

## Modes

The GPT supports these working modes: :contentReference[oaicite:2]{index=2}

1. **Infographic from paste**  
   Paste text → receive a blueprint with copy + layout guidance.

2. **Carousel conversion**  
   Turn an existing post/article into a LinkedIn-ready carousel plan.

3. **Design system lock-in**  
   Establish and enforce repeatable visual and structural rules across a series.

---

## The Repeatable Infographic Template (Series System)

A single locked template so you can publish consistently without redesigning.

### Format
- **Carousel:** 1080×1350 (4:5), always **8 slides**
- **PDF:** single-page “poster” version, stacked vertically from the same content

### Grid + spacing (lock it)
- Outer margin: **80px**
- Grid: **6 columns**
- Gutters: **32px**
- Vertical rhythm: **24px baseline** (everything aligns to it)

### Type system (2 fonts, 4 sizes)
- **H1 (Title):** 64–72px, Bold
- **H2 (Section):** 40–44px, Semibold
- **Body:** 28–32px, Regular
- **Micro (labels/sources):** 20–22px, Regular

Rule: **Never use more than these 4 sizes.**

### Color system (minimum viable brand)
- Ink (near-black)
- Background (off-white)
- Accent (one bold color)
- Muted (light gray for dividers)

Rule: Accent appears only in **three places**:
1) headers, 2) key numbers, 3) final takeaway.

### Icon/shape system (pick one)
- Option A: consistent **line icons**
- Option B: **solid geometry** only (circles/squares/arrows)

Rule: **Never mix systems.**

---

## The 8-Slide Structure (use every time)

### Slide 1 — Cover (Hook)
- Title (≤ 8 words)
- Subtitle (≤ 12 words)
- Series name + issue number (e.g., “Decision Systems #07”)

### Slide 2 — The problem
- 2 bullets max (≤ 10 words each)
- 1 short example (≤ 18 words)

### Slide 3 — The reframing (signature)
- “What people get wrong”
- “My take” (1 sentence)
- “So what?” (≤ 10 words)

### Slide 4 — The model (the payoff)
Use one fixed model style across the series:
- 3-step flow **or**
- 2×2 matrix **or**
- 5-item checklist **or**
- Input → Process → Output

Rule: **No new diagram styles mid-series.**

### Slide 5 — Breakdown
- 3 rows:
  - Label (1–2 words)
  - Explanation (≤ 12 words)
  - Optional icon/shape

### Slide 6 — Common mistakes
- 4 bullets max (≤ 8 words each)

### Slide 7 — Try this (application)
- 3-step mini playbook:
  1) Do X  
  2) Then Y  
  3) Measure Z  
- Optional: “If you only do one thing…” (≤ 10 words)

### Slide 8 — Close
- Primary takeaway (≤ 12 words)
- “Next in the series:” teaser (≤ 10 words)
- Optional: 1 CTA (only one)

---

## Component Library (reusable blocks)

You’re not redesigning; you’re recombining:

- **Header bar:** H2 left, issue # right
- **Callout pill:** rounded rectangle, accent outline (for “My take”, “So what”)
- **Diagram cards:** consistent radius (e.g., 24px) + either border or shadow (choose one)
- **Bullet rows:** icon/shape left, text right, fixed 24px spacing

---

## Copy Rules (consistency engine)

- One idea per slide
- **35–45 words max per slide** (count them)
- Bullets are not sentences (no periods)
- Put nuance in the caption, not on the slide
- Every post must include:
  - a problem
  - a reframe
  - a model
  - a do-this-now

---

## Accessibility Checks (non-negotiable)

- High contrast: dark text on light background
- Minimum body text: **28px** at 1080×1350
- Don’t rely on color alone—use labels/icons
- Diagrams must be text-labeled (not “shape-only meaning”)

---

## Example Prompt

Copy/paste and fill in:

