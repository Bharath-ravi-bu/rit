# RitSetu Brand Guide

## Brand foundation

**Brand:** RitSetu  
**Pronunciation:** Rit-Say-Too  
**Domain:** `ritsetu.com`  
**Short tagline:** **Modernize. Build. Advance.**  
**Capability line:** **Modernize · Refactor · Productize**

RitSetu is inspired by *Ṛta*—truth, order, and dependable foundations—and *Setu*—a bridge or connection. RitSetu connects valuable existing systems to future-ready technology.

> Preserve what matters. Transform what limits progress. Engineer what comes next.

The identity is Indian in meaning and global in presentation: intelligent, dependable, precise, crafted, and forward-looking.

## Final logo — Refactor Path

The mark describes RitSetu’s actual work rather than drawing a literal bridge:

- **Fragmented Sindoor blocks:** undocumented legacy systems and fragile AI-generated code.
- **Converging Palm paths:** discovery, reverse engineering, and human-reviewed refactoring.
- **Kesar transformation signal:** AI used at a controlled engineering decision point.
- **Ordered Kesar modules:** secure, maintainable software and reusable products.
- **Forest Ink container:** dependable foundations, governance, and engineering depth.

Together, the motion reads **legacy → intelligence + engineering → product**. It supports both RitSetu Engineering and RitSetu Labs.

### Logo files

- `ritsetu-logo-primary.svg` — horizontal lockup on light backgrounds
- `ritsetu-logo-dark.svg` — horizontal lockup on Forest Ink backgrounds
- `ritsetu-icon.svg` — favicon, avatar, app icon, and compact mark
- `ritsetu-logo-monochrome.svg` — single-color print and documents
- `ritsetu-brand-board.svg` — complete identity reference

### Usage

- Keep clear space equal to one quarter of the icon width around the mark.
- Use the horizontal lockup at 240 px or wider.
- Below 240 px, omit the capability line if necessary.
- Below 128 px, use the icon only.
- Do not stretch, rotate, redraw, recolor, outline, or add glow/shadow effects.
- Do not place the primary lockup on a busy image.
- Do not reintroduce the rejected literal bridge symbol.

## Vedic Earth color system

| Token | Hex | Role |
|---|---:|---|
| Forest Ink | `#1C211D` | Primary dark, headings, navigation, primary CTA |
| Deep Leaf | `#2A332C` | Elevated dark surfaces and hover states |
| Kesar | `#E07A13` | Transformation signal, emphasis, diagrams, selected controls |
| Sindoor | `#B9362B` | Legacy/problem signal, important highlights, wordmark accent |
| Palm | `#EFE3CC` | Warm panel background and text on dark surfaces |
| Warm Canvas | `#F7F2E8` | Main page background |
| Pure Cream | `#FFF8EC` | Cards and high-contrast text |
| Muted Olive | `#5B655B` | Secondary text on light surfaces |
| Sand Border | `#D8C9AF` | Borders, dividers, and muted controls |

This palette draws from earth, forest, kesar, and mineral red without becoming ceremonial or decorative. Its restrained warmth distinguishes RitSetu from common blue, cyan, purple, and neon AI brands.

### Accessible color roles

- Use Forest Ink on Warm Canvas, Palm, Pure Cream, or Kesar.
- Use Pure Cream or Palm on Forest Ink and Deep Leaf.
- Primary button: Forest Ink background with Pure Cream text.
- Highlight button: Kesar background with Forest Ink text.
- Sindoor button: Sindoor background with Pure Cream text.
- Kesar must not be used for small text on light backgrounds.
- Muted Olive is for secondary text at normal or larger sizes; verify final implementation.
- Never communicate status by color alone. Validate every final combination against WCAG 2.2 AA.

### Restricted gradient

The brand is primarily flat-color. If a transformation path genuinely benefits from a gradient, use only:

```css
linear-gradient(120deg, #B9362B 0%, #E07A13 100%)
```

Never use gradient body text, rainbow gradients, purple-neon treatments, glowing AI effects, or generic blue/teal technology palettes.

## Typography

**Headings:** Manrope 600–800. Use confident, compact headlines with slightly tight letter spacing.  
**Body and UI:** Inter 400–700. Use for paragraphs, navigation, forms, captions, and technical content.

```css
--font-display: "Manrope", "Inter", system-ui, -apple-system, sans-serif;
--font-body: "Inter", system-ui, -apple-system, sans-serif;
```

## Voice

RitSetu speaks with calm engineering confidence:

- Specific, not exaggerated
- Outcome-oriented, not tool-obsessed
- Technically credible, not unnecessarily complex
- Honest about product status and limitations
- Human-reviewed and accountable when describing AI

Prefer “AI-generated software productionization,” “client-authorized system discovery,” “modernization roadmap,” and “measurable outcomes.” Avoid unsupported superlatives and unrestricted “reverse engineering” language.

## Division architecture

### RitSetu Engineering

Legacy modernization, AI-generated software productionization, authorized system discovery, enterprise AI integration, product engineering, architecture, security, performance, cloud, and managed engineering.

### RitSetu Labs

Reusable accelerators, product experiments, applied AI research, and independent SaaS products.

Product endorsement pattern:

> **LegacyLens**  
> A RitSetu product

## UI and imagery

- Use a light-first Warm Canvas interface with Forest Ink sections for contrast.
- Let Forest Ink dominate. Kesar attracts attention; Sindoor identifies friction or transformation origins.
- Use modular system maps, refactoring paths, architecture diagrams, authentic interface details, and engineering environments.
- Use structured grids, generous whitespace, moderate radii, fine Sand borders, and restrained shadows.
- Avoid robots, glowing brains, stock handshakes, hooded hackers, random code walls, glassmorphism, floating particles, and ornamental Vedic motifs.

## CSS design tokens

```css
:root {
  --color-forest-ink: #1C211D;
  --color-deep-leaf: #2A332C;
  --color-kesar: #E07A13;
  --color-sindoor: #B9362B;
  --color-palm: #EFE3CC;
  --color-canvas: #F7F2E8;
  --color-surface: #FFF8EC;
  --color-text: #1C211D;
  --color-text-muted: #5B655B;
  --color-border: #D8C9AF;
  --font-display: "Manrope", "Inter", system-ui, sans-serif;
  --font-body: "Inter", system-ui, sans-serif;
  --radius-sm: 0.5rem;
  --radius-md: 0.875rem;
  --radius-lg: 1.25rem;
}
```

## Release checklist

- Use only the approved Refactor Path logo assets.
- Confirm clear space and minimum size.
- Confirm color tokens and WCAG contrast.
- Use Manrope and Inter consistently.
- Do not fabricate clients, numbers, certifications, partnerships, or results.
- Present AI with human review, security, and accountability.
- Make the result feel like a serious product-engineering company, not a generic AI template.
