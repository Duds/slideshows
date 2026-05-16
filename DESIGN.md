---
name: University of Sydney Presentations
description: Academic conference slide system for USyd researchers — typographic tension, decisive colour, institutional confidence.
colors:
  signal-ochre: "#E64626"
  near-black: "#0A0A0A"
  body-charcoal: "#424242"
  neutral-grey: "#F1F1F1"
  warm-white: "#FCEDE2"
  white: "#FFFFFF"
  utility-blue: "#0148A4"
typography:
  display:
    fontFamily: "Playfair Display, Georgia, serif"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.01em"
  subheading:
    fontFamily: "Roboto Condensed, Arial, sans-serif"
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: "normal"
  body:
    fontFamily: "Roboto, Arial, sans-serif"
    fontSize: "28px"
    fontWeight: 400
    lineHeight: 1.35
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
  heading-gap: "12px"
  list-gap: "0.5em"
components:
  title-slide:
    backgroundColor: "{colors.signal-ochre}"
    textColor: "{colors.white}"
  segue-black:
    backgroundColor: "{colors.near-black}"
    textColor: "{colors.white}"
  segue-ochre:
    backgroundColor: "{colors.signal-ochre}"
    textColor: "{colors.white}"
  code-block:
    backgroundColor: "{colors.neutral-grey}"
    typography: "{typography.code}"
  example-slide:
    backgroundColor: "{colors.neutral-grey}"
    textColor: "{colors.body-charcoal}"
---

# Design System: University of Sydney Presentations

## 1. Overview

**Creative North Star: "Past in Forward Motion"**

The University of Sydney is Australia's oldest university. Maud's 2015 identity for the institution treated that heritage not as a weight but as a launching point: revealing the real workings of a place "where leading international minds collaborate on life-changing research" required a design language that was simultaneously rooted and contemporary, and deliberately "provocative editorial" in approach.

The typographic system carries this tension directly. Maud used four typefaces — GT Spectra, GT Haptik, Aperçu Pro, and Antwerp — moving between "the awkward, quirky and sober, those with significant character and those with a little more restraint, the on trend and those firmly rooted in the traditional." For the web presentation system, this tension is distilled into a serif/sans pairing: Playfair Display (bold, historical, display-weight) for slide titles against Roboto Condensed (contemporary, precise, condensed) for subheadings. The contrast between them is not accidental; it is the identity.

Colour is decisive: red, white, and black — a "limited but impactful combination that picks the work out from a concrete grey landscape." Signal Ochre is the institutional mark, present and confident at every structural boundary. Near-black and white are its field. Academic Blue exists only as a utility variant; it is not a brand colour.

The system rejects conservative academic slide design — the grey monotony the rebrand was specifically built to counter. It also rejects decorative excess. The register is peer-level academic conference; the tone is confident, direct, and unafraid.

**Key Characteristics:**
- Typographic tension: serif display titles (Playfair Display) against sans-serif structure (Roboto Condensed / Roboto)
- Committed colour strategy: red/white/black as the three-element structure
- Signal Ochre used decisively at every structural moment — titles, segue slides, H2 subheadings
- Photography: a first-class element, not an afterthought
- Flat surfaces; depth through tonal layering and typographic scale, not shadow
- High information density — calibrated for peer audiences who read slides as documents

## 2. Colors: The Structural Palette

**Strategy: Committed.** Red, white, and black carry the identity. Signal Ochre is the primary institutional signal, used boldly at every structural moment. Near-black provides the harder contrast surface. White is the content field. The palette is small by design — its impact comes from decisiveness, not variety.

### Primary
- **Signal Ochre** (#E64626): The institutional identity mark. Full-bleed title slide background, H2 subheading text on content slides, segue slide backgrounds. Present and confident at every structural boundary — not rationed.
- **Near Black** (#0A0A0A): The maximum contrast surface. Used as an alternative segue background for harder structural breaks; masterbrand logo applications.
- **White** (#FFFFFF): Slide body background; all text on dark structural slides.

### Neutral
- **Body Charcoal** (#424242): Default body text on all white and light-grey surfaces. The primary reading colour.
- **Neutral Grey** (#F1F1F1): Example/aside slide backgrounds, code block backgrounds. The only in-body surface variation that is prescribed.
- **Warm White** (#FCEDE2): Sandstone wash — references the neo-gothic sandstone of USyd's campus, visible in Maud's photography palette. Available for warm neutral surfaces when Neutral Grey reads too cold.

### Utility
- **Utility Blue** (#0148A4): A segue variant for structural breaks requiring visual differentiation from both Ochre and Black. Not a brand colour in the Maud system; never used on content slides or as an emphasis colour.

### Named Rules
**The Commitment Rule.** Signal Ochre is not a rare accent — it is a committed structural colour. Every title slide, every section break, every H2 subheading is a moment for the brand's identity to land. Rationing Ochre out of caution produces the conservative timidity the brand was designed to reject.

**The Three-Colour Rule.** Red, white, and black carry the palette. Within a content slide body, all surfaces are white or Neutral Grey. Colour appearing inside a content slide body is a structural error.

## 3. Typography

**Display (H1):** Playfair Display, weight 700 (Google Fonts — serif)
**Subheading (H2):** Roboto Condensed, weight 500 (Google Fonts — sans-serif)
**Body:** Roboto, weight 400 (Google Fonts — humanist sans-serif)
**Code:** Source Code Pro (monospace)
**Blockquote:** Playfair Display Italic, weight 400

**Character:** Maud used four typefaces that moved "between the awkward, quirky and sober" — GT Spectra (geometric serif), GT Haptik (humanist sans), Aperçu Pro (geometric sans), and Antwerp (old-style serif). These are commercial faces not available for web use. The presentation system approximates their essential tension: Playfair Display carries the historical, high-contrast serif register of GT Spectra and Antwerp; Roboto Condensed carries the condensed geometric precision of Aperçu Pro and GT Haptik; Roboto body text provides readable contemporary prose.

The serif/sans contrast at the heading level is the typographic personality of the system. It must be preserved. A single-family slide deck — all Roboto, all the time — erases the brand's most visible signal and produces the institutional blandness the Maud identity was designed to counter.

### Hierarchy
- **Display/H1** (Playfair Display, weight 700, near-black, line-height 1.15): Slide titles. The historical register — bold serif at display scale. Left-aligned.
- **Subheading/H2** (Roboto Condensed, weight 500, Signal Ochre, line-height 1.2): Section headings within content slides. The contemporary counterpoint. Ochre enforces the structural identity signal.
- **Body** (Roboto, weight 400, 28px RevealJS / 24px Beamer, line-height 1.35): All prose, bullet lists. 0.5em margin top and bottom per list item.
- **Label** (Roboto, weight 400, 0.7em, line-height 1.3): Footnotes, slide numbers, captions. Positioned at slide bottom.
- **Code** (Source Code Pro, weight 400, 0.75em for blocks / 0.95em for inline): On Neutral Grey background.
- **Blockquote** (Playfair Display Italic, weight 400): Cited passages and pull-quotes. Reserved for direct quotation only. The italic serif registers as scholarly citation without stepping outside the type system.

### Named Rules
**The Tension Rule.** The serif/sans pairing is the system's personality, not a stylistic choice. Do not collapse both H1 and H2 into the same typeface family. The contrast between Playfair Display and Roboto Condensed is the design.

**The Density Rule.** Line height is calibrated for projection legibility, not for white space. 1.35 body, 1.15–1.2 for headings. Do not increase line height to "open up" slides; reduce content instead.

## 4. Elevation

This system is flat by design. Depth and separation are achieved through tonal surface layering: Ochre or Near-black full-bleed backgrounds signal structural transitions; Neutral Grey creates content zones within white slides.

The only text-shadows in the system appear on dark segue slides — a projector legibility micro-treatment only, invisible at presentation distance.

**The Flat-By-Default Rule.** Shadows do not exist on content slides. Separation is tonal and typographic, not spatial.

## 5. Photography

Photography is a first-class element of the USyd brand identity. Maud's photography by Irenaeus Herok deliberately collides neo-gothic stonework with contemporary interior architecture — the same past/present tension embodied by the typography.

- **Subject:** University spaces (neo-gothic exteriors, contemporary interiors, research environments, people at work). Not stock photography.
- **Treatment:** Full-bleed or significantly cropped — images that run off the slide edge. No inset thumbnail framing.
- **Contrast:** Favour high-contrast images that hold their own against the red/white/black palette. Desaturated or B&W treatment is appropriate where colour competes with Signal Ochre.
- **Placement:** Full-bleed slide background or asymmetric column (60/36 or 36/60 split). Never floating, never decoratively framed.

## 6. Components

Typographic-first: layout primitives step back. The serif/sans tension at the heading level is the design.

### Title Slide
Signal Ochre (#E64626) fills the full slide background. White SVG logo anchors bottom-right.
- **Background:** Signal Ochre (#E64626) full-bleed.
- **Title:** White, Playfair Display weight 700, left-aligned. Large scale.
- **Metadata:** White, Roboto weight 400. Italic for journal or venue name.
- **Logo:** White SVG lockup, bottom-right, ~15% slide width.
- **Padding:** 25px vertical, 50px horizontal.

### Segue / Section Break Slides
Full-bleed colour slides signalling structural transitions. Text is centred vertically and horizontally. Slide number suppressed.
- **Segue Ochre:** Signal Ochre background, white text, mild text-shadow for projector legibility.
- **Segue Black:** Near-Black background, white text, mild text-shadow. Harder structural break; use when a second consecutive segue would otherwise repeat the Ochre.

### Content Slide Frame
The default vessel for argument. White background, Body Charcoal body text, Ochre H2 subheadings, Playfair Display H1 title.
- **Padding:** 25px top/bottom, 50px left/right. Fixed — never reduced.
- **H1:** Playfair Display, weight 700. Near-black. 5px top margin, 12px bottom — tight to content.
- **H2:** Roboto Condensed, weight 500, Signal Ochre (#E64626). The prescribed in-body Ochre application.
- **Body text:** Roboto, 28px, line-height 1.35 (RevealJS); 24px, line-height 1.4 (Beamer).
- **List items:** 0.5em margin top and bottom per item.

### Code Blocks
- **Background:** Neutral Grey (#F1F1F1). No border, no radius.
- **Font:** Source Code Pro, 0.75em block / 0.95em inline.
- **Highlighted lines:** `background-color: yellow` — functional only.

### Example / Aside Slides
- **Background:** Neutral Grey (#F1F1F1). Visually distinguished from white content slides without a full structural colour break. Used for worked examples, demonstrations, or asides.

### Two-Column Layouts
The prescribed academic layout for argument + evidence pairings.
- **60/36 split:** Argument left, evidence/figure right. 4% gutter implied.
- **36/60 split:** Figure left, annotation right.
- Neither column introduces borders, backgrounds, or shadows. The column division is spatial, not visual.

### Footnotes
- **Position:** Absolute, bottom of slide.
- **Size:** 0.7em. Citation or clarification only. Never decorative.

## 7. Do's and Don'ts

### Do:
- **Do** use Playfair Display weight 700 for H1 slide titles — the bold serif is the brand's historical register and its contrast against Roboto Condensed is the typographic identity.
- **Do** use Roboto Condensed weight 500 in Signal Ochre for H2 subheadings — the sans/serif contrast is the system's personality.
- **Do** use Signal Ochre at every structural boundary: title slides, segue slides, H2 subheadings. Confidence in the colour is the brand.
- **Do** keep slide padding fixed at 25px vertical / 50px horizontal. Precision reads as rigour.
- **Do** use the 60/36 asymmetric two-column split for argument + evidence layouts.
- **Do** use footnotes for citations. Academic audiences notice absent references.
- **Do** use Neutral Grey (#F1F1F1) for code blocks and example slides — the only prescribed in-body surface variation.
- **Do** use Playfair Display Italic for blockquotes and direct citations. The italic serif registers as scholarly reference within the type system.

### Don't:
- **Don't** collapse the typographic system to a single font family. The serif H1 against the condensed-sans H2 is the design; erasing it produces generic institutional output.
- **Don't** use gradient fills, SmartArt-style layouts, clip art, or shadow boxes on any slide.
- **Don't** use blue gradients, icon grids, or illustration-heavy layouts — the visual language of general-audience science communication is explicitly rejected.
- **Don't** apply Signal Ochre inside a content slide body as a decorative element. H2 subheading colour is the full in-body allocation.
- **Don't** add drop shadows to slide components or content surfaces. Flat-By-Default.
- **Don't** ration Signal Ochre out of caution — a timid, whispered brand presence is the specific failure mode the Maud identity was designed to prevent.
- **Don't** use Patrick Hand or any handwriting font. There is no role for cursive in this system.
- **Don't** increase line height to create breathing room. Reduce content instead — the density is intentional.
- **Don't** design for a general audience. This system is calibrated for peer-level academic conferences.
