# NOV Lab — Design System

## Overview

**NOV Lab** is a Brazilian marketing and design agency whose tagline is *"Estética que impressiona"* ("Aesthetics that impress"). They position themselves at the intersection of technology and design, specializing in:

- Social media content (Reels, carousels, static posts)
- Landing pages / web design
- Brand identity & visual systems
- Video editing
- Performance marketing (Google Ads, Instagram/Facebook Ads, Tráfego Pago)

Their core promise: *"Toda transformação começa com uma faísca"* — every transformation starts with a spark.

**Language**: Brazilian Portuguese  
**Location**: Brazil

---

## Sources

- **Figma file**: `NOV Lab..fig` (mounted as virtual filesystem) — 4 pages: Sobre, Cores, Tipografia, Logo-Nome
- **Screenshots**: `uploads/Print1.png`, `uploads/Print2.png`, `uploads/Print3.png` — Behance portfolio showing social media work and landing page designs

---

## CONTENT FUNDAMENTALS

### Tone & Voice
- **Bold and confident** — declarative statements, no hedging
- **Poetic and punchy** — short, impactful phrases followed by elaboration
- **Tech-forward** — uses terms like "DNA tecnológico", "funil de vendas", "tráfego pago"
- **Inspirational** — transformation language ("toda transformação começa com uma faísca")

### Casing
- **Sentence case** for body text and headlines
- **ALL CAPS** used sparingly for labels/tags (e.g. "TRAMONTINAADS TRAFEGOPAGO")
- Brand name always written as **NOV Lab.** (NOV in italic/bold, Lab. in thin weight, with a period)

### Person
- Speaks **directly to the client** ("seu público", "suas vendas", "você") — "you"-forward
- Agency uses **"nós/nossa"** (we/our) positioning

### Emoji
- **Not used** in core brand materials. Clean and graphic.

### Copy examples
- *"Toda transformação começa com uma faísca..."*
- *"Quer impactar seu público? Comece criando conteúdo de valor."*
- *"Tenha páginas que convertem visitantes em clientes"*
- *"Estética que impressiona."*
- *"Cada entrega é pensada com intenção e executada com cuidado."*

---

## VISUAL FOUNDATIONS

### Colors
- **Background primary**: `#0F041A` — near-black deep purple; used as the main dark canvas
- **Background secondary**: `#2A0A4A` — deep violet; used for cards, panels, swatch elements
- **Accent / Brand**: `#FF1CF7` — electric magenta/hot pink; the signature color; used for strokes, accents, the logo dot, CTAs
- **White**: `#FDFDFD` / `#FFFFFF` — primary text and light surfaces
- **Black**: `#000000` — used on light-background logo variants

### Typography
- **Display / Brand**: Poppins Black Italic (hero text, "NOV" in logo) + Poppins Thin (contrast weight, "Lab." in logo)
- **Primary body**: Poppins (Medium, Light, Regular, ExtraBold) — versatile workhorse
- **Secondary / Labels**: Montserrat Regular — used for UI labels and design system headings
- **Mono / Accent**: Space Mono Regular — used as a label/accent font in type specimens

Scale seen in Figma: 128px (hero), 64px (section titles), 48px (subheads), 32px (body large)

### Backgrounds
- **Full-bleed dark**: `#0F041A` backgrounds dominate — almost always dark
- **Split layout**: half white / half dark used on logo reference sheet
- No photographic backgrounds in brand guidelines; product work shows 3D renders on dark BG

### Cards / Containers
- **Large border-radius**: `63px` on color swatches (pill-like rounded rectangles)
- **Border accent**: 2px solid `#FF1CF7` strokes on containers (seen in type page frames)
- No drop shadows seen in core brand; relies on color contrast

### Animation / Motion (inferred from product work)
- Bold, impactful transitions — no subtle fades
- Tech/futuristic feel — likely uses fast cuts, kinetic type

### Imagery
- **3D rendered icons/objects** on dark backgrounds (purple/indigo vibe) — seen in landing page work
- **High contrast**, cool-to-dark color palette in imagery
- No grain or texture in brand system itself; product work is polished and digital

### Borders & Strokes
- `2px solid #FF1CF7` — primary accent border
- Circular dot motif in `#FF1CF7` — signature brand mark detail in logo

### Corner Radii
- Large: `63px` (color swatches)
- `81px` (typography frames in Figma)
- Generally very rounded, almost pill-shaped containers

### Hover / Interaction States
- Not explicitly defined in brand system; inferred: opacity changes or magenta glow

### Layout
- Wide canvas: `1440px` wide references
- Generous margins (105–126px left padding)
- Bold vertical rhythm with large type leading at 100%

---

## ICONOGRAPHY

NOV Lab does not use a standard icon system or icon font in their brand guidelines. Visual interest is achieved through:

- **Bold typography** as the primary graphic element
- **The "N." logogram** — a custom geometric letterform with the `#FF1CF7` dot accent
- **3D rendered objects** in product/client work (not part of core brand)
- No SVG icon set, no emoji, no unicode icon chars in brand materials

Assets copied to `assets/`:
- `assets/logo-dark.svg` — NOV Lab. wordmark on dark background
- `assets/logo-light.svg` — NOV Lab. wordmark on light background
- `assets/color-palette.svg` — brand color reference

---

## VISUAL SYSTEM FILES

| File | Description |
|---|---|
| `colors_and_type.css` | CSS custom properties for colors, type scale, semantic tokens |
| `preview/` | Design system preview cards (registered in Design System tab) |
| `assets/` | Logos, brand SVGs |
| `ui_kits/novlab/` | UI Kit — agency landing page + social media content surfaces |

---

## UI KITS

- **`ui_kits/novlab/index.html`** — Agency landing page & component library
