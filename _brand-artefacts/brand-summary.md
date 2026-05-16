# University of Sydney — Brand Artefacts

Collected from publicly available sources. The University's full brand hub requires intranet/staff access at `intranet.sydney.edu.au/services/marketing-communications.html`.

---

## Colour Palette

### Masterbrand (Primary)
| Name | Hex | RGB |
|---|---|---|
| Masterbrand Ochre | `#E64626` | 230, 70, 38 |
| Masterbrand Black | `#0A0A0A` | 10, 10, 10 |
| Masterbrand Charcoal | `#424242` | 66, 66, 66 |
| Masterbrand White | `#FFFFFF` | 255, 255, 255 |

### Accent / Supporting
| Name | Hex | RGB |
|---|---|---|
| Accent Blue | `#0148A4` | 1, 72, 164 |
| Accent Yellow | `#FFB800` | 255, 184, 0 |
| Accent Light Grey | `#F1F1F1` | 241, 241, 241 |
| Sandstone | `#FCEDE2` | 252, 237, 226 |

### Extended Palette (named colours)
Navy `#1B355E` · Eucalypt `#71A499` · Jacaranda `#8F9EC8` · Heritage Rose · Secondary Blue `#4E98D3`

Source: [Sydney-Informatics-Hub/usydColours](https://github.com/Sydney-Informatics-Hub/usydColours) (derived from Brand Document V2.0)

---

## Typography

The official typeface is **Apertura** (licensed; not publicly available). Public/web presentations use:
- **Body**: Roboto (Google Fonts)
- **Headings**: Roboto Condensed (Google Fonts)
- **Code**: Source Code Pro
- **Display/Quote**: Patrick Hand

See `css/sydney-fonts.css` for web import declarations.

---

## Logo Files

| File | Description |
|---|---|
| `logos/USydLogo.svg` | Full colour lockup (shield + wordmark) |
| `logos/USydLogo-black.svg` | Black/dark version |
| `logos/USydLogo-white.svg` | White/reversed version |

Logo usage requires written approval from the University. See the [Logo Requests page](https://www.sydney.edu.au/about-us/working-with-the-university/logo-requests.html).

The logo comprises two elements: the **stylised shield** (based on the coat of arms) and the **University of Sydney wordmark** in a serif typeface.

---

## Brand Principles

- **Colour strategy**: Restrained palette — Ochre as the dominant brand signal, black/white for structure
- **Absolute bans**: gradient text, glassmorphism, excessive colour variation
- **Layout**: Left-aligned, structured grid; title slides use full Ochre background with white text
- **Contrast**: White text on Ochre; Charcoal text on white/light-grey/Sandstone

---

## Files in this Directory

```
_brand-artefacts/
├── brand-summary.md          ← this file
├── logos/
│   ├── USydLogo.svg          ← full colour SVG lockup
│   ├── USydLogo-black.svg    ← black version
│   └── USydLogo-white.svg    ← white/reversed version
├── css/
│   ├── sydney.css            ← full RevealJS/Quarto presentation stylesheet
│   ├── sydney-fonts.css      ← font imports and typography rules
│   └── sydney.scss           ← SCSS source with brand variables
├── beamer-theme/
│   ├── beamercolorthemeusyd.sty   ← LaTeX colour definitions
│   ├── beamerfontthemeusyd.sty    ← LaTeX font definitions
│   ├── beamerthemeusyd.sty        ← main Beamer theme
│   ├── beamerinnerthemeusyd.sty   ← inner theme
│   ├── beamerouterthemeusyd.sty   ← outer theme
│   └── README.md
└── colour-palette/
    ├── usydColours-README.md ← full palette documentation (23 palettes)
    └── define_palettes.R     ← R source defining all palette combinations
```

---

## Sources

- Official brand policy: https://www.sydney.edu.au/policies/showdoc.aspx?recnum=PDOC2011/160
- Brand hub (staff): https://intranet.sydney.edu.au/services/marketing-communications.html
- Logo requests: https://www.sydney.edu.au/about-us/working-with-the-university/logo-requests.html
- Colour palettes: https://github.com/Sydney-Informatics-Hub/usydColours
- CSS presentation theme: https://github.com/fraba/presentation
- Beamer theme: https://github.com/malramsay64/usyd-beamer-theme
- Brand identity by Maud: https://www.maud.com.au/projects/university-of-sydney/
