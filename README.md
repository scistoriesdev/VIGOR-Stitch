---
name: Clinical Genomic Research
colors:
  surface: '#faf8ff'
  surface-dim: '#ced9ff'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2ff'
  on-surface: '#0a1a3c'
  on-surface-variant: '#434652'
  inverse-surface: '#212f52'
  inverse-on-surface: '#eef0ff'
  outline: '#747683'
  outline-variant: '#c4c6d4'
  surface-tint: '#325ab5'
  primary: '#002668'
  on-primary: '#ffffff'
  primary-container: '#003a96'
  on-primary-container: '#8caaff'
  inverse-primary: '#b2c5ff'
  secondary: '#006970'
  on-secondary: '#ffffff'
  secondary-container: '#81f4fe'
  on-secondary-container: '#006f77'
  tertiary: '#511700'
  on-tertiary: '#ffffff'
  tertiary-container: '#762600'
  on-tertiary-container: '#ff8e63'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b2c5ff'
  on-primary-fixed: '#001848'
  on-primary-fixed-variant: '#0f419c'
  secondary-fixed: '#81f4fe'
  secondary-fixed-dim: '#63d7e1'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59a'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#802a00'
  background: '#faf8ff'
  on-background: '#0a1a3c'
  surface-variant: '#dae2ff'
typography:
  display-lg:
    fontFamily: Source Serif 4
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Source Serif 4
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  body-lead:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  caption:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 2rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

The design system establishes an institutional research identity that is authoritative, scientifically rigorous, and deeply human. Built for clinical and academic partnership between major medical schools, it avoids cold, sterile laboratory tropes as well as commercial healthcare SaaS aesthetics. 

The interface evokes quiet permanence, peer-reviewed credibility, and respectful clarity for participants and clinical researchers. Visual communication relies on structural order, editorial typographic hierarchy, crisp hairline partitions, and deliberate negative space. Decorative fluff, trendy pill-shaped containers, and startup design idioms are discarded in favor of archival elegance and clinical legibility.

## Colors

The palette is anchored in deep academic institutionals and warmed clinical neutrals:

- **Primary (`#003A96`)**: Anchor Blue. Applied to institutional banners, primary navigation chrome, structural dividing rules, and active secondary actions.
- **Secondary (`#009CA6`)**: Clinical Teal. Reserved strictly for large display typography (24px and larger), biological diagrams, pedigree connectors, and visual motifs. Never used for small body copy or low-contrast text.
- **Tertiary (`#E65100`)**: Deep Persimmon Amber. Reserved solely and exclusively for primary study recruitment actions ("Join the Study", "Check Eligibility"). It must never appear as a background wash or generic accent.
- **Ink Primary (`#0B1B3D`)**: Deep Navy Blue-Black. Serves as the universal reading color across all text and structural framing lines. Pure black (`#000000`) is prohibited.
- **Surfaces**: Canvas is set to `#F9F8F5` (warm alabaster) to eliminate monitor glare during long research reading sessions. Container cards utilize pure clinical white (`#FFFFFF`) to delineate actionable information panels against the alabaster ground.
- **Rules & Dividers**: Expressed as `#0B1B3D` at 12% opacity or `#003A96` at 15% opacity to maintain disciplined boundary articulation without heavy visual weight.

## Typography

Typography pairs institutional academic gravitas with pristine clinical legibility:

- **Headlines & Display**: Set in `Source Serif 4`. Expresses historical integrity, medical scholarship, and dignified humanity. Use optical weights carefully—semi-bold (`600`) balances editorial warmth with presence.
- **Body & Controls**: Set in `Inter`. Designed for extreme optical clarity at text sizes. Standard long-form reading copy is strictly 18px (`body-md`), scaling to 20px (`body-lead`) in introductory abstracts. Body copy must never drop below 16px to protect readability for aging or visually impaired study participants.
- **Styling Rules**: Tracked-out, all-caps uppercase labels are forbidden. Section markers and meta-information use sentence case or title case in regular-to-medium weight with tabular numerals.

## Layout & Spacing

Layouts follow a disciplined 12-column grid constrained to a 1440px desktop frame, anchored by generous margins and wide section pauses:

- **Desktop (1440px max)**: 12 columns, 32px (`2rem`) gutters, 48px (`3rem`) page margins.
- **Tablet (768px – 1024px)**: 8 columns, 24px (`1.5rem`) gutters, 32px (`2rem`) page margins.
- **Mobile (< 768px)**: 4 columns, 16px (`1rem`) gutters, 20px (`1.25rem`) page margins.
- **Vertical Rhythm**: Section separation utilizes `space-2xl` (64px) or `space-3xl` (96px) to emulate the measured pacing of a scientific monograph. Component interiors rely on structured multiples of 8px.

## Elevation & Depth

Visual hierarchy rejects blurry drop shadows, heavy layered neomorphism, and floating cards. Elevation is established through crisp surface stratification and precise architectural borders:

- **Base Layer**: Canvas surface (`#F9F8F5`).
- **Surface Elevation**: White cards (`#FFFFFF`) sitting directly on `#F9F8F5`, framed by a clean 1px hairline border in `#0B1B3D` with an opacity of 12%.
- **Depth Cueing**: In place of diffuse shadows, interactive states and active containers employ an engineered technical offset: a single subtle border shift (`#003A96`) combined with a razor-thin 1px keyline shadow (`0 1px 2px rgba(11, 27, 61, 0.05)`).
- **Modals & Overlays**: Framed in crisp 1px borders with a high-contrast structural scrim (`#0B1B3D` at 40% opacity), avoiding diffuse radial blurs.

## Shapes

The design system employs a soft, precise corner geometry (`roundedness: 1`):

- **Standard Elements (inputs, buttons, badges)**: `4px` (`0.25rem`) corner radius.
- **Cards and Data Containers**: `4px` (`0.25rem`) to `8px` (`0.5rem`) maximum.
- **Form Controls & Checks**: Precision `2px` to `4px` chamfers.
- **Disallowed**: Fully rounded pill buttons (`9999px`) and soft bubbly cards are strictly prohibited, preserving institutional authority and precision.

## Components

### Action Buttons
- **Primary Study Action ("Join the Study")**: Solid `#E65100` background with pure `#FFFFFF` text. Height is 48px with 4px border radius. Font weight 600, 16px label. Hover state darkens cleanly to `#D34600`. Never append arrow icons (`→`, `>`) to button labels.
- **Institutional Secondary**: Transparent background with a 1.5px solid `#003A96` border and `#003A96` text. Hover applies a 6% tint of `#003A96`.
- **Text Actions**: `#003A96` with an underline positioned 4px beneath the baseline; never rely on standalone naked colored text.

### Cards & Data Panels
- Rendered in pure `#FFFFFF` over `#F9F8F5` with a 1px border (`rgba(11, 27, 61, 0.12)`) and 4px border radius.
- Internal padding is strictly 32px (`space-xl`) on desktop, reducing to 20px on mobile.
- Section headers within cards utilize `headline-sm` with a thin horizontal rule separating metadata from narrative analysis.

### Form Inputs & Checks
- **Text Inputs**: Height 48px, `#FFFFFF` background, 1px border (`rgba(11, 27, 61, 0.2)`), text set in 16px `Inter`. Focus state applies a 1.5px solid `#003A96` stroke with zero ambient glow.
- **Checkboxes & Radios**: 20px square/circular bounds with 2px borders. Selected states fill with `#003A96` featuring a sharp white checkmark. Labels sit at 16px body copy with an 8px offset.

### Chips & Metadata Badges
- Sentence-case text set in 14px `Inter` medium.
- Minimal border styling: 1px outline in `#003A96` at 20% opacity with an institutional `#003A96` text color. Never style chips as pill tags.

### Scientific & Research Modules
- **Pedigree & Genetic Lineage Trees**: Rendered with secondary `#009CA6` vector lines at 1.5px thickness. Nodes use sharp geometric forms (rectangles and circles) without decorative gradients.
- **Data Tables**: Plain, horizontal rule-delimited rows with 16px vertical padding. Headers set in `label-sm` with text aligned strictly to data type (left for narrative, right for numerical study metrics).