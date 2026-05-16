# impeccable.design

Apply impeccable design principles to the current slideshow or presentation. Review every slide for visual consistency, hierarchy, spacing, and clarity — then fix what's off.

## What this skill does

1. **Audit** all slides for design issues: inconsistent fonts, misaligned elements, poor contrast, cluttered layouts, weak visual hierarchy
2. **Fix** each issue found — don't just report them
3. **Enforce** a coherent visual system across the deck: consistent spacing scale, a single type scale, a constrained color palette (3–4 colors max), and purposeful use of whitespace
4. **Verify** the result looks polished end-to-end before reporting done

## Design principles to enforce

- **Hierarchy first**: one dominant element per slide, supporting elements clearly subordinate
- **Whitespace is not waste**: generous margins, breathing room between elements
- **Alignment is law**: everything snaps to a grid or explicit alignment; no floating elements
- **Color restraint**: primary, secondary, accent — that's it; no decorative color noise
- **Typography discipline**: 2 typefaces max, consistent sizing scale (e.g. 48/32/20/14), no orphaned words in headlines
- **Contrast for legibility**: body text ≥ 4.5:1 contrast ratio against background
- **One idea per slide**: if a slide needs a scroll or bullet list longer than 4 items, split it

## How to run

When invoked, scan every slide file in the project (look for `.html`, `.md`, `.json`, `.pptx`-adjacent, or framework-specific slide files). Apply fixes directly. Summarize what changed and why.
