---
version: alpha
name: Inocras-design-analysis
description: Inocras Cancer Genome Nexus — a clinical genomics SaaS platform design language that balances scientific authority with human readability. The system is built on three distinct typefaces (DM Sans for headings/actions, Atkinson Hyperlegible for body, JetBrains Mono for data/code), a warm near-black ink (#1a1a19) on white canvas, a single brand-defining dark forest green (#1a6b52), and a burnt orange accent (#b44d1a). Surfaces use a deliberate temperature system: warm off-white for navigation panels, cool off-white for analysis/chat panes, neutral off-white for data portals, and pure white for primary content. Tables are the primary data component. Status signals are colored text only — never badges with background fills. Coverage spans the homepage, genome data portal, agent scientist interface (3-pane chat + file system), data visualization outputs, and clinical metadata surfaces.

colors:
  # ── Core text
  ink: "#1a1a19"
  ink-secondary: "#52524e"
  ink-tertiary: "#8b8b86"
  on-dark: "#ffffff"
  on-dark-muted: "rgba(255,255,255,0.45)"

  # ── Canvas & surfaces
  canvas: "#ffffff"
  surface-warm: "#faf8f5"
  surface-neutral: "#f4f3f0"
  surface-cool: "#f7f8fa"

  # ── Borders
  line: "#dddbd5"
  line-light: "#eceae5"

  # ── Brand
  brand: "#1a6b52"
  brand-light: "#e8f1ed"
  brand-deep: "#145440"

  # ── Accent
  accent: "#b44d1a"
  accent-soft: "#f5e4d9"

  # ── Semantic / data roles
  blue: "#1a5fb4"
  blue-soft: "#dce9f9"
  purple: "#6c3fa0"
  purple-soft: "#ece3f5"
  red: "#c4271a"
  red-soft: "#fde8e7"
  green: "#1a7f37"
  green-soft: "#d9f0e0"
  gold: "#96690d"
  gold-soft: "#f5eccf"

  # ── Navigation (dark shell)
  nav-bg: "#1a1a19"
  nav-text: "#ffffff"
  nav-text-inactive: "rgba(255,255,255,0.45)"

  # ── Genomic variant roles
  snv-oncogene: "#1a5fb4"
  snv-tsg: "#6c3fa0"
  snv-pathogenic: "#c4271a"
  cnv-gain: "#b44d1a"
  cnv-loss: "#6c3fa0"
  cnv-neutral: "#dddbd5"
  sv-fusion: "#1a5fb4"
  sv-deletion: "#c4271a"
  sv-inversion: "#96690d"
  sv-duplication: "#1a7f37"
  indel-frameshift: "#c4271a"
  indel-inframe: "#96690d"
  msi-high: "#b44d1a"
  msi-stable: "#8b8b86"
  tmb-high: "#c4271a"
  tmb-low: "#1a5fb4"
  hrd-positive: "#6c3fa0"
  hrd-negative: "#8b8b86"
  signature-sbs: "#1a5fb4"
  signature-dbs: "#6c3fa0"
  signature-id: "#96690d"

  # ── PAM50 subtypes
  subtype-lumA: "#1a7f37"
  subtype-lumB: "#1a5fb4"
  subtype-basal: "#c4271a"
  subtype-her2: "#b44d1a"
  subtype-normal: "#8b8b86"

  # ── Dataset type labels (text-only, no chips)
  type-reference: "#1a7f37"
  type-mine: "#1a5fb4"
  type-shared: "#b44d1a"

  # ── Semantic
  semantic-success: "#1a7f37"
  semantic-error: "#c4271a"
  semantic-warning: "#96690d"
  semantic-info: "#1a5fb4"
  semantic-active: "#b44d1a"

  # ── Code syntax (in script viewer)
  syntax-keyword: "#6c3fa0"
  syntax-function: "#1a5fb4"
  syntax-string: "#1a6b52"
  syntax-comment: "#8b8b86"
  syntax-number: "#b44d1a"

typography:
  # ── DM Sans: headings, UI actions, stat numbers
  hero-number:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.03em
  display-lg:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -0.03em
  display-md:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.03em
  heading-1:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: -0.02em
  heading-2:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: -0.01em
  heading-3:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: -0.01em
  heading-4:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 13px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  section-title:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  button:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 13px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0
  button-sm:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0
  nav-brand:
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0

  # ── Atkinson Hyperlegible: body, descriptions
  body-lead:
    fontFamily: "'Atkinson Hyperlegible', sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body-md:
    fontFamily: "'Atkinson Hyperlegible', sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  body-sm:
    fontFamily: "'Atkinson Hyperlegible', sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  body-xs:
    fontFamily: "'Atkinson Hyperlegible', sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  chat-message:
    fontFamily: "'Atkinson Hyperlegible', sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0

  # ── JetBrains Mono: data, labels, code
  data-value:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  data-value-sm:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  domain-label:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 9px
    fontWeight: 600
    lineHeight: 1.0
    letterSpacing: 0.06em
    textTransform: uppercase
  domain-label-sm:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 8px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: 0.04em
    textTransform: uppercase
  status-text:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 0
  code-block:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 10.5px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 0

rounded:
  none: 0
  xs: 1px
  sm: 2px
  md: 3px
  lg: 6px
  xl: 8px
  full: 9999px

spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 20px
  xxl: 24px
  xxxl: 32px
  section-sm: 40px
  section: 56px
  section-lg: 80px

components:
  # ── Buttons
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: "8px 18px"
    border: "none"
  button-primary-hover:
    backgroundColor: "{colors.ink-secondary}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: "8px 18px"
    border: "1px solid {colors.line}"
  button-secondary-hover:
    backgroundColor: "{colors.surface-warm}"
  button-sm:
    typography: "{typography.button-sm}"
    rounded: "{rounded.md}"
    padding: "7px 16px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink-secondary}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.md}"
    padding: "4px 8px"
    border: "none"

  # ── Links
  link:
    textColor: "{colors.brand}"
    fontWeight: 700
    textDecoration: underline
    textUnderlineOffset: 3px
  link-table:
    textColor: "{colors.blue}"
    fontWeight: 700
    textDecoration: underline
    textUnderlineOffset: 3px

  # ── Navigation
  nav-bar:
    backgroundColor: "{colors.nav-bg}"
    textColor: "{colors.nav-text}"
    height: 46px
    padding: "0 20px"
    typography: "{typography.nav-brand}"
  nav-item-active:
    textColor: "{colors.on-dark}"
    fontWeight: 700
  nav-item-inactive:
    textColor: "{colors.nav-text-inactive}"

  # ── Tables (primary data component)
  table-header-cell:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 10px
    fontWeight: 400
    textTransform: uppercase
    letterSpacing: 0.06em
    color: "{colors.ink-tertiary}"
    borderBottom: "2px solid {colors.ink}"
    padding: "6px 10px 5px"
  table-row:
    borderBottom: "1px solid {colors.line-light}"
    padding: "7px 10px"
  table-row-hover:
    backgroundColor: "{colors.surface-warm}"
  table-cell-data:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 12px
    color: "{colors.ink}"
  table-cell-body:
    fontFamily: "'Atkinson Hyperlegible', sans-serif"
    fontSize: 13px
    color: "{colors.ink}"
  table-note: "No alternating row fills. Borders separate rows only."

  # ── Cards
  card-base:
    backgroundColor: "{colors.canvas}"
    border: "1px solid {colors.line-light}"
    rounded: "{rounded.none}"
    padding: "20px 22px"
  card-hover:
    border: "1px solid {colors.line}"
    shadow: "0 2px 12px rgba(0,0,0,0.06)"
  card-active:
    backgroundColor: "{colors.brand-light}"
    border: "1px solid {colors.brand}"
  card-empty:
    backgroundColor: "{colors.canvas}"
    border: "1px solid {colors.line-light}"
    rounded: "{rounded.none}"
    padding: "20px 22px"
    minHeight: 220px

  # ── Callouts & annotations (left-border only, no bg fill)
  callout-clinical:
    borderLeft: "4px solid {colors.blue}"
    backgroundColor: "transparent"
    padding: "8px 12px"
    typography: "{typography.body-sm}"
  callout-warning:
    borderLeft: "4px solid {colors.gold}"
    backgroundColor: "transparent"
    padding: "8px 12px"
  callout-brand:
    borderLeft: "3px solid {colors.brand}"
    backgroundColor: "transparent"
    padding: "9px 11px"
  callout-error:
    borderLeft: "4px solid {colors.red}"
    backgroundColor: "transparent"
    padding: "8px 12px"

  # ── Status indicators (colored text only)
  status-active:
    color: "{colors.accent}"
    dot: "8px circle with pulse animation"
  status-verified:
    color: "{colors.green}"
    noBackground: true
  status-unverified:
    color: "{colors.gold}"
    noBackground: true
  status-note: "No pills, no badge backgrounds. Status is always plain colored text."

  # ── Dataset type labels
  type-label-ref:
    color: "{colors.type-reference}"
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 9px
    letterSpacing: 0.04em
    textTransform: uppercase
  type-label-mine:
    color: "{colors.type-mine}"
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 9px
    letterSpacing: 0.04em
    textTransform: uppercase
  type-label-shared:
    color: "{colors.type-shared}"
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 9px
    letterSpacing: 0.04em
    textTransform: uppercase

  # ── Agent Scientist 3-pane layout
  as-left-pane:
    backgroundColor: "{colors.surface-warm}"
    borderRight: "1px solid {colors.line}"
    width: 256px
  as-center-pane:
    backgroundColor: "{colors.surface-cool}"
  as-right-pane:
    backgroundColor: "{colors.canvas}"
    borderLeft: "1px solid {colors.line}"
    width: 340px
  as-pane-header:
    padding: "14px 16px 10px"
    borderBottom: "1px solid {colors.line-light}"

  # ── Chat messages
  chat-user-bubble:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    rounded: "12px 12px 2px 12px"
    padding: "9px 13px"
    maxWidth: "78%"
    typography: "{typography.chat-message}"
  chat-ai-bubble:
    backgroundColor: "{colors.canvas}"
    border: "1px solid {colors.line-light}"
    padding: "11px 13px"
    typography: "{typography.chat-message}"
    textColor: "{colors.ink}"
  chat-input:
    border: "1px solid {colors.line}"
    focusBorder: "1px solid {colors.ink}"
    padding: "7px 9px 7px 13px"
    typography: "{typography.chat-message}"
  agent-steps:
    backgroundColor: "{colors.canvas}"
    border: "1px solid {colors.line-light}"
    borderLeft: "3px solid {colors.brand}"
    padding: "9px 11px"
  step-done-color: "{colors.ink-secondary}"
  step-active-color: "{colors.brand}"

  # ── Inline data table (inside chat)
  inline-table-header:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 9px
    textTransform: uppercase
    letterSpacing: 0.06em
    color: "{colors.ink-tertiary}"
    borderBottom: "2px solid {colors.ink}"
    padding: "3px 8px 5px 0"
  inline-table-cell:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 11px
    color: "{colors.ink-secondary}"
    borderBottom: "1px solid {colors.line-light}"
    padding: "4px 8px 4px 0"
  inline-table-cell-gene:
    color: "{colors.ink}"
    fontWeight: 600
  inline-table-cell-high:
    color: "{colors.accent}"
    fontWeight: 600
  inline-table-cell-mod:
    color: "{colors.gold}"
  inline-table-cell-low:
    color: "{colors.ink-tertiary}"

  # ── File tree (in right pane)
  tree-folder-name:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 11px
    fontWeight: 600
    color: "{colors.ink}"
  tree-file-name:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 10px
    color: "{colors.ink-secondary}"
  tree-file-active:
    backgroundColor: "{colors.brand-light}"
    color: "{colors.brand}"
    fontWeight: 700

  # ── Section label (horizontal rule style)
  section-label:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 9px
    fontWeight: 600
    letterSpacing: 0.07em
    textTransform: uppercase
    color: "{colors.ink-tertiary}"
    afterContent: "1px solid {colors.line}"

  # ── Portal page panels
  panel-base:
    backgroundColor: "{colors.canvas}"
    border: "1px solid {colors.line-light}"
    rounded: "{rounded.none}"
  panel-header:
    padding: "10px 14px 8px"
    borderBottom: "1px solid {colors.line-light}"
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 12px
    fontWeight: 700
    color: "{colors.ink}"

  # ── Tabs (underline style)
  tab-inactive:
    color: "{colors.ink-tertiary}"
    fontWeight: 500
    borderBottom: "2px solid transparent"
    padding: "11px 16px"
  tab-active:
    color: "{colors.ink}"
    fontWeight: 700
    borderBottom: "2px solid {colors.ink}"

  # ── Dividers
  section-divider-brand:
    borderTop: "3px solid {colors.brand}"
    note: "Used for Explore further sections"

  # ── Homepage hero (marketing surface)
  hero-band:
    backgroundColor: "#1B2B6B"
    textColor: "{colors.on-dark}"
    padding: "80px 5vw 72px"
  hero-eyebrow:
    backgroundColor: "rgba(255,255,255,0.12)"
    border: "1px solid rgba(255,255,255,0.25)"
    textColor: "rgba(255,255,255,0.9)"
    fontFamily: "'DM Sans', sans-serif"
    fontSize: 10px
    fontWeight: 600
    letterSpacing: 0.1em
    textTransform: uppercase

  # ── Footer
  footer-region:
    backgroundColor: "{colors.canvas}"
    borderTop: "1px solid {colors.line-light}"
    padding: "40px 5vw"
    textColor: "{colors.ink-tertiary}"
    typography: "{typography.body-xs}"
---

## Overview

Inocras Cancer Genome Nexus is a clinical genomics SaaS platform that enables researchers and clinicians to analyze somatic variant data — SNVs, INDELs, SVs, CNVs, MSI, TMB, HRD, and mutational signatures — at both cohort and sample level. The design language communicates scientific authority through restraint: warm near-black ink on white, a single forest-green brand accent, and JetBrains Mono as the universal data voice.

The platform comprises four surfaces: a **marketing homepage** (dark navy hero), a **genome data portal** (neutral off-white grid of datasets), an **agent scientist** (3-pane chat + file system), and **data visualization outputs** (genomic plots generated to disk). Each surface uses a different background temperature — warm, neutral, cool, or pure white — as the primary context signal without heavy visual chrome.

**Key Characteristics:**
- Three-font system with strict role separation: DM Sans for headings/actions, Atkinson Hyperlegible for body text, JetBrains Mono for all data/labels/code
- Brand green (#1a6b52) as the single accent — appears on active states, links, agent step indicators, and section dividers
- Burnt orange (#b44d1a) for accent/active pipeline — pulsing 8px dot for live status, never used as a generic highlight
- Tables are the primary data component — not card grids
- Status signals are colored text only — never badges with background fills
- Zero border-radius on cards (rounded.none); 3px on buttons only
- All domain category labels (GENOMIC, CLINICAL, METADATA) in JetBrains Mono uppercase at 9-10px with 0.06em tracking
- Page temperature: warm left panel, cool center analysis, neutral data portal, white primary content

## Colors

### Brand & Accent
- **Brand Green** ({colors.brand}): The single brand signal. Forest green — active states, text links, agent step indicators, section dividers ("Explore further"), dataset item active border.
- **Brand Light** ({colors.brand-light}): Active item background tint — appears behind active dataset items and file tree selections.
- **Brand Deep** ({colors.brand-deep}): Pressed/hover state for brand elements.
- **Accent Burnt Orange** ({colors.accent}): Active pipeline dot (with pulse animation), publication labels (AACR), shared dataset type label. Never used decoratively.

### Text Stack
- **Ink** ({colors.ink}): Near-black warm tone — primary headlines, table cell data, nav background.
- **Ink Secondary** ({colors.ink-secondary}): Secondary text — descriptions, table body.
- **Ink Tertiary** ({colors.ink-tertiary}): Muted — mono domain labels, placeholder, metadata.

### Surface Temperature System
- **Canvas** ({colors.canvas}): Primary content surfaces — AI message bubbles, panels, table rows.
- **Surface Warm** ({colors.surface-warm}): Left navigation panes, Explorer context — #faf8f5, warm off-white.
- **Surface Neutral** ({colors.surface-neutral}): Data portal backgrounds — #f4f3f0.
- **Surface Cool** ({colors.surface-cool}): Analysis and agent chat center panes — #f7f8fa, cool off-white.

### Borders
- **Line** ({colors.line}): Primary border — card outlines, input borders, structural dividers.
- **Line Light** ({colors.line-light}): Table row separators, panel internal dividers — #eceae5.

### Genomic Data Roles
- **Oncogene / SNV blue** ({colors.snv-oncogene}): Gain-of-function mutations, oncogene annotations — #1a5fb4.
- **TSG / Loss purple** ({colors.snv-tsg}): Tumor suppressor genes, loss of function — #6c3fa0.
- **Pathogenic red** ({colors.snv-pathogenic}): Pathogenic variants, danger states — #c4271a.
- **Verified green** ({colors.green}): Verified/confirmed results, LuminalA subtype — #1a7f37.
- **Warning gold** ({colors.gold}): Unverified/uncertain findings, GOLD warnings — #96690d.

### PAM50 Breast Cancer Subtypes
- **LuminalA** ({colors.subtype-lumA}): Green #1a7f37 — favorable prognosis signal.
- **LuminalB** ({colors.subtype-lumB}): Blue #1a5fb4.
- **Basal-like** ({colors.subtype-basal}): Red #c4271a — aggressive subtype signal.
- **HER2-enriched** ({colors.subtype-her2}): Accent #b44d1a.
- **Normal-like** ({colors.subtype-normal}): Gray #8b8b86.

## Typography

### Font System (Three Fonts, Three Roles)
All three fonts are available on Google Fonts:
- **DM Sans**: `DM+Sans:wght@400;500;600;700` — humanist geometric sans for headings, numbers, CTAs
- **Atkinson Hyperlegible**: `Atkinson+Hyperlegible:wght@400;700` — high legibility body text; designed to distinguish Il1 and 0O without feeling clinical
- **JetBrains Mono**: `JetBrains+Mono:wght@400;500;600;700` — all data values, domain labels, and code surfaces

**Critical rule**: Never use system font stacks (-apple-system, Inter, Roboto, Segoe UI). The three-font stack is the brand identity.

### Role Assignments

| Token | Font | Size | Weight | Use |
|---|---|---|---|---|
| `{typography.hero-number}` | DM Sans | 28–48px | 700 | Cohort N, TMB values, hero stats |
| `{typography.display-lg}` | DM Sans | 28px | 700 | Page-level headlines |
| `{typography.heading-1}` | DM Sans | 18px | 700 | Panel/section titles in spec view |
| `{typography.heading-2}` | DM Sans | 16px | 700 | Study titles in data portal |
| `{typography.section-title}` | DM Sans | 12px | 700 | Panel headers, pane titles |
| `{typography.button}` | DM Sans | 13px | 700 | All button labels |
| `{typography.body-lead}` | Atkinson | 16px | 400 | Hero subtitle, description lede |
| `{typography.body-sm}` | Atkinson | 13px | 400 | Primary body, chat messages |
| `{typography.body-xs}` | Atkinson | 12px | 400 | Descriptions, captions, citations |
| `{typography.data-value}` | JetBrains Mono | 12px | 500 | Table cells with numeric/ID data |
| `{typography.domain-label}` | JetBrains Mono | 9–10px | 600 | GENOMIC / CLINICAL / METADATA labels |
| `{typography.code-block}` | JetBrains Mono | 10.5px | 400 | Script viewer, inline code |

### Principles
- Negative letter-spacing on DM Sans display sizes: -0.03em at 22px+, -0.02em at 18px, -0.01em at 15-16px
- JetBrains Mono domain labels: always uppercase, always 0.06em letter-spacing, always 9-10px
- Body text (Atkinson): generous leading 1.6 for readability in clinical/scientific contexts
- Data values: JetBrains Mono 12px/500 in tables — never Atkinson in data cells
- Chat messages: Atkinson 13px / 1.65 line-height

## Layout

### Spacing System
- Base unit: 4px
- Standard content padding: 16–24px
- Portal page padding: 32px 36px
- Agent pane padding: 14px 16px (headers), 18px (chat messages)
- Table cell padding: 7px 10px (rows), 6px 10px (headers)

### Grid Patterns
- **Data portal**: 2-column dataset card grid (1fr 1fr), 16px gap
- **Summary panels**: 4-column grid (repeat(4, 1fr)), 14px gap
- **Agent scientist**: 3-pane flex layout — left 256px fixed | center flex-1 | right 340px slide-in
- **Homepage**: 2-column hero (1fr 340px), max-width 1200px

### Container
- Max-width: 1200px, centered
- Horizontal gutter: 5vw (marketing), 32–36px (app surfaces)

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 (flat) | No shadow; `{colors.line-light}` border | Default cards, panels |
| 1 (hover) | `0 2px 12px rgba(0,0,0,0.06)` + `{colors.line}` border | Hovered dataset cards |
| 2 (lightbox scrim) | `rgba(0,0,0,0.92)` full overlay | Image lightbox background |
| 3 (dropdown) | `0 4px 16px rgba(0,0,0,0.12)` | Context menus |

Inocras uses almost no elevation. Depth is created through surface temperature (warm/cool/neutral) and border weight (1px vs 2px), not shadows.

## Shapes

### Border Radius Scale
| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0 | All cards, panels, tables — zero radius is the brand signal |
| `{rounded.xs}` | 1px | Data tags in agent pane |
| `{rounded.sm}` | 2px | File tree items |
| `{rounded.md}` | 3px | Buttons (the only rounded element in the core UI) |
| `{rounded.lg}` | 6px | Search inputs in some contexts |

**Critical rule**: Cards and panels use `border-radius: 0`. Inocras is deliberately rectilinear — the angular geometry signals scientific precision. The only rounded elements are buttons (3px) and circular status dots.

## Components

### Buttons
**`button-primary`** — Near-black (#1a1a19) fill, white text, DM Sans 13px 700, 3px border-radius. The dominant action CTA.

**`button-secondary`** — White fill, #1a1a19 text, 1px line border. Secondary/cancel actions.

**`button-ghost`** — Transparent, no border. Used for icon actions in pane headers.

**`link`** — Brand green, bold, underline with 3px offset. Used for all text-link navigations (not buttons).

**`link-table`** — Blue (#1a5fb4), bold, underline. Used inside tables for sample ID links.

### Navigation
**`nav-bar`** — #1a1a19 background, 46px height. DM Sans 15px 700 white brand text left. Inactive items at rgba(255,255,255,0.45). No border-bottom.

### Tables (Primary Data Component)
Tables are the central UI component for all genomic data. Rules:
- Header: JetBrains Mono 10px uppercase, 0.06em tracking, 2px solid #1a1a19 bottom border
- Rows: 1px solid #eceae5 bottom separator, no alternating fills
- Data cells: JetBrains Mono 12px
- Text cells: Atkinson Hyperlegible 13px
- Hover: surface-warm (#faf8f5) background

### Cards
**`card-base`** — Zero border-radius, 1px line-light border. Dataset cards, portal items.

**`card-active`** — Brand-light background, brand-color border. Selected state for dataset items.

### Callouts (Left-Border Pattern)
All callouts use a left border only — no background fill, no rounded corners.
- **`callout-clinical`** — 4px blue left border. Clinical context notes.
- **`callout-warning`** — 4px gold left border. Quality/confidence warnings.
- **`callout-brand`** — 3px brand-green left border. Agent step panels, explore sections.
- **`callout-error`** — 4px red left border. Error states, failed pipeline steps.

### Status Indicators
All status signals are colored text only. No pill backgrounds, no chip containers.
- Active pipeline: 8px circle in accent orange with `pulse` CSS animation
- Dataset type: GENOMIC, CLINICAL, METADATA in JetBrains Mono uppercase colored text
- Confidence: green = verified, gold = unverified — text only

### Agent Scientist Interface
3-pane layout:
- **Left pane** (256px, surface-warm): Dataset selector, query history, dataset detail strip (brand left-border callout)
- **Center pane** (flex, surface-cool): Chat messages, input bar at bottom
- **Right pane** (340px, canvas, slide-in): File tree tabs + preview panel

**`chat-user-bubble`** — Ink fill, white text, asymmetric border-radius (12/12/2/12).

**`chat-ai-bubble`** — White bg, line-light border, rectangular (no radius).

**`agent-steps`** — White bg, brand left-border callout, mono text. Done steps = fg2, Active step = brand green.

**`inline-table`** — Inside AI messages: mono 9px header with 2px ink bottom, mono 11px data cells with line-light separator.

### Section Labels
JetBrains Mono 9px uppercase, 0.07em tracking, ink-tertiary color. Followed by a 1px line hairline extending to the right edge. Used to segment portal pages and portal panels.

## Do's and Don'ts

### Do
- Use DM Sans for ALL headings, stat numbers, and buttons — it's the heading voice
- Use Atkinson Hyperlegible for ALL body text and descriptions
- Use JetBrains Mono for ALL data values, domain labels, and code — including in chat
- Apply 0px border-radius to cards and panels — rectilinear geometry is a key brand signal
- Use left-border callouts (no background fill) for all annotations and agent steps
- Keep status signals as colored text only — never add a background chip or pill
- Apply the page temperature system: warm left panel, cool center, neutral portal, white primary
- Use brand green (#1a6b52) sparingly — only for active/selected states, text links, agent indicators
- Separate table rows with 1px line-light borders, not alternating fill colors

### Don't
- Don't use system fonts (Inter, Roboto, -apple-system, Segoe UI) — they destroy the brand identity
- Don't use pill-shaped badges or chips with background fills for status
- Don't apply border-radius to cards, panels, or tables
- Don't use pastel background fills for callout blocks — left border only
- Don't use progress bar widgets — represent pipeline status with sentence text + pulse dot
- Don't use icon-in-circle patterns
- Don't apply uniform spacing across all sections — vary to create rhythm
- Don't use Tailwind default color tokens (slate, teal, emerald, etc.)
- Don't use blue (#1a5fb4) as a generic link color for non-table contexts — brand green is the link color

## Visualization Output Palette

For matplotlib/seaborn/circos PNG generation, use these role assignments:

### Mutation Type Palette
| Role | Hex | Usage |
|---|---|---|
| SNV — missense | `{colors.snv-oncogene}` (#1a5fb4) | Missense substitutions |
| SNV — nonsense/frameshift | `{colors.snv-pathogenic}` (#c4271a) | Truncating mutations |
| SNV — TSG | `{colors.snv-tsg}` (#6c3fa0) | Tumor suppressor loss |
| INDEL — frameshift | `{colors.indel-frameshift}` (#c4271a) | Frameshift indels |
| INDEL — inframe | `{colors.indel-inframe}` (#96690d) | In-frame indels |
| SV — fusion | `{colors.sv-fusion}` (#1a5fb4) | Gene fusions |
| SV — deletion | `{colors.sv-deletion}` (#c4271a) | Structural deletions |
| SV — duplication | `{colors.sv-duplication}` (#1a7f37) | Tandem duplications |
| SV — inversion | `{colors.sv-inversion}` (#96690d) | Inversions |
| CNV — gain | `{colors.cnv-gain}` (#b44d1a) | Copy number gain |
| CNV — loss | `{colors.cnv-loss}` (#6c3fa0) | Copy number loss |
| CNV — neutral | `{colors.cnv-neutral}` (#dddbd5) | Copy number neutral |

### Cohort / Clinical Palette
| Role | Hex | Usage |
|---|---|---|
| MSI-H | `{colors.msi-high}` (#b44d1a) | MSI-high samples |
| MSI-S/L | `{colors.msi-stable}` (#8b8b86) | MSI-stable/low |
| TMB-high | `{colors.tmb-high}` (#c4271a) | High tumor mutation burden |
| TMB-low | `{colors.tmb-low}` (#1a5fb4) | Low TMB |
| HRD-positive | `{colors.hrd-positive}` (#6c3fa0) | HRD-positive |
| LuminalA | `{colors.subtype-lumA}` (#1a7f37) | PAM50 LumA |
| LuminalB | `{colors.subtype-lumB}` (#1a5fb4) | PAM50 LumB |
| Basal | `{colors.subtype-basal}` (#c4271a) | PAM50 Basal |
| HER2-enriched | `{colors.subtype-her2}` (#b44d1a) | PAM50 HER2 |

### Plot Background
- Figure background: `{colors.canvas}` (#ffffff) or `{colors.surface-warm}` (#faf8f5) for warm context
- Axes background: `{colors.canvas}` (#ffffff)
- Grid lines: `{colors.line-light}` (#eceae5), alpha 0.5
- Axis labels / tick text: `{colors.ink}` (#1a1a19) in JetBrains Mono
- Axis titles: `{colors.ink}` (#1a1a19) in DM Sans 700

## Page Temperature Reference

| Surface | Background | Context |
|---|---|---|
| Dashboard | `{colors.canvas}` #ffffff | Neutral white — primary decisions |
| Explorer / left pane | `{colors.surface-warm}` #faf8f5 | Browsing, navigation |
| Analysis / chat center | `{colors.surface-cool}` #f7f8fa | Active inquiry |
| Data portal | `{colors.surface-neutral}` #f4f3f0 | Dataset grid |
| Sample detail | `{colors.canvas}` #ffffff | Deep focus |
| Upload / sharing | `{colors.canvas}` #ffffff | Form surfaces |

## Responsive Behavior

### Breakpoints
| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | Agent panes collapse. Single column. |
| Tablet | 768–1024px | Left pane toggle. 1-col dataset grid. |
| Desktop | > 1024px | Full 3-pane layout. 2-col dataset grid. |

### Collapsing Strategy
- Agent left pane (256px): collapses to hamburger toggle on tablet/mobile
- Agent right pane (340px): hidden by default, slide-in on desktop
- Dataset grid: 2-up → 1-up on mobile
- Summary panels: 4-up → 2-up → 1-up

## Known Gaps
- Exact animation timing for pulse dot not specified; recommend 2s infinite ease
- Dark mode not implemented in current surfaces
- Responsive breakpoint behavior for genomic visualization panels not defined
- Print/PDF export styling not documented
- Accessibility contrast ratios for ink-tertiary (#8b8b86) on surface-warm (#faf8f5) should be verified
