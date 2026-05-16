---
name: University of Sydney Presentations
description: Academic conference slide system for USyd researchers — authoritative, typographic-first.
colors:
  signal-ochre: "#E64626"
  academic-blue: "#0148A4"
  accent-yellow: "#FFB800"
  body-charcoal: "#424242"
  near-black: "#0A0A0A"
  neutral-grey: "#F1F1F1"
  warm-white: "#FCEDE2"
  white: "#FFFFFF"
typography:
  headline:
    fontFamily: "Roboto Condensed, Arial, sans-serif"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "normal"
  body:
    fontFamily: "Roboto, Arial, sans-serif"
    fontSize: "28px"
    fontWeight: 400
    lineHeight: 1.3
  label:
    fontFamily: "Roboto, Arial, sans-serif"
    fontSize: "0.7em"
    fontWeight: 400
  code:
    fontFamily: "Source Code Pro, Lucida Console, Monaco, monospace"
    fontSize: "0.75em"
    fontWeight: 400
rounded:
  none: "0px"
spacing:
  slide-v: "25px"
  slide-h: "50px"
  heading-gap: "10px"
  list-gap: "0.5em"
components:
  title-slide:
    backgroundColor: "{colors.signal-ochre}"
    textColor: "{colors.white}"
  segue-blue:
    backgroundColor: "{colors.academic-blue}"
    textColor: "{colors.white}"
  segue-red:
    backgroundColor: "{colors.signal-ochre}"
    textColor: "{colors.white}"
  segue-yellow:
    backgroundColor: "{colors.accent-yellow}"
    textColor: "{colors.body-charcoal}"
  code-block:
    backgroundColor: "{colors.neutral-grey}"
    typography: "{typography.code}"
  example-slide:
    backgroundColor: "{colors.neutral-grey}"
    textColor: "{colors.body-charcoal}"
---

# Design System: University of Sydney Presentations

## 1. Overview

**Creative North Star: "The Forensic Brief"**

University of Sydney presentations operate like well-prepared scholarly briefs. Every slide is a statement of fact or argument, stripped of decoration. Signal Ochre (#E64626) functions as an institutional stamp — it appears in frame title text, section breaks, and the full-bleed title slide background — but it does not embroider. The typographic system (Roboto Condensed for headings, Roboto for body) carries the cognitive load without visual noise.

The system rejects the language of the conference-circuit PowerPoint: no gradient fills, no SmartArt, no icon grids, no shadow boxes. It also rejects the visual clichés of science communication — illustration-heavy slides, vivid multi-colour palettes, Kurzgesagt-style layouts. The audience is peer-level academics contributing to venues like *Critical Perspectives on Accounting*; the design signals that the researcher knows this.

The governing logic is restraint with purpose. Colour backgrounds (Ochre, Academic Blue, Accent Yellow) mark structural boundaries — title slides, section transitions, segue slides — not decoration within content slides. Content slides are typographic: left-aligned, grid-locked, high information density.

**Key Characteristics:**
- Flat surfaces, zero decorative elements on content slides
- Signal Ochre as structural marker only — never used as a decorative accent within content slide bodies
- All layout is left-aligned and grid-anchored
- Typography (Roboto Condensed / Roboto) carries hierarchy without weight or ornament
- High information density — calibrated for peer audiences who read slides as documents

## 2. Colors: The Structural Palette

A restrained three-accent palette over a neutral ground. Signal Ochre signals the institution, Academic Blue signals structural transitions, Accent Yellow provides a secondary break. All content lives in charcoal on white.

### Primary
- **Signal Ochre** (#E64626): The institutional identity mark. Used as title slide background, H2 heading text color on content slides, and block title backgrounds. Never used as a decorative accent within content bodies. Its rarity on content slides is the point.

### Secondary
- **Academic Blue** (#0148A4): Section transition slides (segue, inverse classes), block body tint backgrounds. Indicates a structural break in the argument, not inline emphasis.

### Tertiary
- **Accent Yellow** (#FFB800): Segue slides requiring a warmer register break. Reserved for one segue variant only. Never used for body text.

### Neutral
- **Body Charcoal** (#424242): Default body text on all white and light-grey surfaces. The primary reading colour.
- **Near Black** (#0A0A0A): Maximum contrast contexts — masterbrand logo applications, critical emphasis moments.
- **Neutral Grey** (#F1F1F1): Example/aside slide backgrounds, code block backgrounds. The only in-body surface variation that is prescribed.
- **Warm White** (#FCEDE2): Sandstone wash — available for warm neutral surfaces when Neutral Grey reads too cold.
- **White** (#FFFFFF): Slide body background; all text on dark-background structural slides.

### Named Rules
**The Structural Signal Rule.** Ochre, Blue, and Yellow appear only at structural boundaries: title slides, segue slides, H2 heading text, block titles. Within a content slide body, all surfaces are white or Neutral Grey. Colour appearing inside a content slide body is evidence of a design error.

**The Rarity Rule.** Signal Ochre covers the full title slide background and frame H2 text. That is its full budget. An Ochre accent added anywhere else is a violation, not a bonus.

## 3. Typography

**Headline Font:** Roboto Condensed (Arial, sans-serif fallback)
**Body Font:** Roboto (Arial, sans-serif fallback)
**Code Font:** Source Code Pro (Lucida Console, Monaco, monospace fallback)
**Blockquote Font:** Patrick Hand (cursive)

**Character:** A utilitarian condensed-sans pairing chosen for information density and projector legibility. Roboto Condensed at normal weight achieves scale hierarchy without weight contrast — functional, not expressive. Roboto body text at 28px (RevealJS) or 24px (xaringan) is calibrated for reading at presentation distance. The system does not use decorative type; every font choice is a legibility decision.

### Hierarchy
- **Headline** (Roboto Condensed, weight 400, line-height 1.2): Slide title (H1). Condensed form provides visual scale; never bold.
- **Title** (Roboto Condensed, weight 400, body size, line-height 1.2, Signal Ochre): H2 subheadings on content slides. The one prescribed in-body Ochre application.
- **Body** (Roboto, weight 400, 28px RevealJS / 24px xaringan, line-height 1.3–1.4): All prose, bullet lists. 0.5em margin top and bottom per list item.
- **Label** (Roboto, weight 400, 0.7em, line-height 1.3): Footnotes, slide numbers, aside text. Positioned at slide bottom.
- **Code** (Source Code Pro, weight 400, 0.75em for blocks / 0.95em for inline): Code on Neutral Grey (#F1F1F1) background.
- **Blockquote** (Patrick Hand, cursive): Cited passages and pull-quotes. Reserved for direct quotation only.

### Named Rules
**The Weight-Free Rule.** Heading hierarchy is achieved through condensed form and size, not weight. Do not bold slide headings at any level. Bold within body text is for factual emphasis only — a key term, a datum — never for stylistic effect.

**The Density Rule.** Line height is tight by design (1.3–1.4). Academic slides carry argument, not white space. Do not increase line height to "open up" slides; reduce content instead.

## 4. Elevation

This system is flat by design. No drop shadows appear on slide components or content surfaces. Depth and separation are achieved entirely through tonal surface layering: Ochre, Academic Blue, or Yellow full-bleed background slides signal structural transitions; Neutral Grey creates content zones; white is the default content surface.

The only text-shadows in the system appear on dark segue slides (`text-shadow: 0 0 20px #333` on Blue and Ochre segue backgrounds) — a projector legibility micro-treatment, not an aesthetic choice. They are functional and invisible at presentation distance.

### Named Rules
**The Flat-By-Default Rule.** Shadows do not exist on content slides. If a design element needs to "pop" or appear lifted, the answer is typographic scale or tonal background layering — not shadow. A drop shadow on a content slide is always wrong.

## 5. Components

Typographic-first: layout primitives step back. The type is the design.

### Title Slide
The only slide type composed entirely of colour. Signal Ochre (#E64626) fills the full slide background. University of Sydney logo (white SVG lockup) anchors bottom-right.
- **Shape:** No border radius; full-bleed rectangular surfaces only throughout the system.
- **Background:** Signal Ochre (#E64626) full-bleed.
- **Text:** White, left-aligned. Title in Roboto Condensed, all other fields in Roboto.
- **Logo:** White SVG lockup at `background-position: 95% 95%; background-size: 15%`.
- **Padding:** 25px vertical, 50px horizontal — consistent with all slide types.

### Segue / Section Break Slides
Full-bleed colour slides that signal structural transitions between sections. Text is centered vertically and horizontally. Slide number suppressed.
- **Segue Blue:** Academic Blue (#0148A4) background, white text, mild text-shadow.
- **Segue Red:** Signal Ochre (#E64626) background, white text, mild text-shadow.
- **Segue Yellow:** Accent Yellow (#FFB800) background, Body Charcoal (#424242) text, lighter text-shadow.

### Content Slide Frame
The default vessel for argument. White background, Body Charcoal body text, Ochre H2 headings.
- **Padding:** 25px top/bottom, 50px left/right. Fixed — never reduced.
- **H1 margin:** 5px top, 10px bottom — tight to content.
- **H2 color:** Signal Ochre (#E64626). The prescribed in-body Ochre application.
- **Body text:** 28px / line-height 1.3 (RevealJS); 24px / line-height 1.4 (xaringan).
- **List items:** 0.5em margin top and bottom per item.

### Code Blocks
- **Background:** Neutral Grey (#F1F1F1). No border, no radius.
- **Font:** Source Code Pro, 0.75em block / 0.95em inline.
- **Highlighted lines:** `background-color: yellow` — functional only.

### Example / Aside Slides
- **Background:** Neutral Grey (#F1F1F1). Visually distinguished from white content slides without a full structural colour break. Used for worked examples, demonstrations, or asides.

### Two-Column Layouts
The prescribed academic layout for argument + evidence pairings.
- **60/36 split** (`.pull-left-2` / `.pull-right-1`): Argument left, evidence/figure right. 4% gutter implied.
- **36/60 split** (`.pull-left-1` / `.pull-right-2`): Figure left, annotation right.
- Neither column introduces borders, backgrounds, or shadows. The column division is spatial, not visual.

### Footnotes
- **Position:** Absolute, bottom of slide.
- **Size:** 0.7em. Citation or clarification only. Never decorative.

## 6. Do's and Don'ts

### Do:
- **Do** use Signal Ochre only at structural boundaries: title slides, segue-red slides, H2 heading colour, block title backgrounds. Nowhere else.
- **Do** use Roboto Condensed at normal weight (400) for all headings. Size provides hierarchy; weight does not.
- **Do** keep slide padding fixed at 25px vertical / 50px horizontal. Tighter padding signals unpreparedness.
- **Do** use the 60/36 asymmetric two-column split for argument + evidence layouts.
- **Do** use footnotes for citations. Academic audiences notice absent references.
- **Do** use Neutral Grey (#F1F1F1) for code blocks and example slides — the only prescribed in-body surface variation.
- **Do** trust the type. Roboto Condensed headings and Roboto body text at the specified sizes carry all necessary hierarchy without additional visual intervention.

### Don't:
- **Don't** use gradient fills, SmartArt-style layouts, clip art, or shadow boxes on any slide.
- **Don't** use blue gradients, icon grids, or illustration-heavy layouts — the visual language of general-audience science communication is explicitly rejected.
- **Don't** apply Signal Ochre inside a content slide body as a decorative element. H2 heading colour is the full allocation.
- **Don't** bold headings at any level. The Weight-Free Rule applies throughout.
- **Don't** add drop shadows to slide components or content surfaces. Flat-By-Default.
- **Don't** use Patrick Hand (the blockquote font) for anything other than a directly cited quotation.
- **Don't** increase line height to create breathing room. Reduce content instead — the density is intentional.
- **Don't** design for a general audience. This system is calibrated for peer-level academic conferences.
