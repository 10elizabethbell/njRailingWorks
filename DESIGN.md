---
name: New Jersey Railing Works
description: A powder-coat line on a New Jersey stoop; siding-gray grounds, coat-black metal, logo gold as trim.
colors:
  siding: "#d3dce3"
  siding-deep: "#c3ced7"
  light: "#eef1f3"
  slate: "#1f2a35"
  slate-deep: "#17202a"
  ink: "#141a21"
  ink-soft: "#3c4855"
  on-dark: "#eef2f5"
  on-dark-soft: "#b7c3ce"
  coat: "#16191d"
  coat-hover: "#2a3038"
  gold: "#c9a24b"
  gold-bright: "#e0bd6a"
  focus: "#7cc0f0"
  focus-deep: "#1f6fb0"
  rule-light: "#cdd5dc"
  field-fill: "#283440"
  field-stroke: "#6b7a89"
  mill-aluminum: "#a3abb2"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.55rem, min(12.4vw, 14svh), 5.6rem)"
    fontWeight: 850
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem, 8vw, 3.4rem)"
    fontWeight: 850
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "0.005em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.45
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 700
    lineHeight: 1.1
  fine:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  photo: "8px"
  control: "10px"
  pill: "999px"
  round: "50%"
spacing:
  gutter: "16px"
  gutter-wide: "32px"
  tile-gap: "8px"
  tile-gap-wide: "12px"
  stack: "22px"
  band: "56px"
  band-wide: "80px"
  column-gap-wide: "56px"
components:
  button-coat:
    backgroundColor: "{colors.coat}"
    textColor: "{colors.gold-bright}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "56px"
  button-coat-hover:
    backgroundColor: "{colors.coat-hover}"
    textColor: "{colors.gold-bright}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.coat}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "56px"
  button-gold-panel:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.coat}"
    rounded: "{rounded.control}"
    padding: "12px 18px"
    height: "64px"
  button-gold-panel-hover:
    backgroundColor: "{colors.gold-bright}"
  chip:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.coat}"
  input-text:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.control}"
    padding: "14px"
    height: "54px"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    padding: "8px 0"
    height: "64px"
  service-row-arrow:
    backgroundColor: "#dfe5ea"
    textColor: "{colors.coat}"
    rounded: "{rounded.round}"
    size: "44px"
  service-row-arrow-hover:
    backgroundColor: "{colors.coat}"
    textColor: "{colors.gold-bright}"
  step-number:
    backgroundColor: "{colors.coat}"
    textColor: "{colors.gold-bright}"
    rounded: "{rounded.round}"
    size: "44px"
---

# Design System: New Jersey Railing Works

## Overview

**Creative North Star: "The Powder-Coat Line"**

The site is the crew's finishing booth. A bare mill-aluminum railing stands on a New Jersey stoop against blue-gray vinyl siding, and the visitor sprays it semi-gloss black with a finger; further down, railing runs drawn as section dividers take their coat as they scroll into view. Everything else is built from the same three materials: siding-gray grounds, coat-black metal, and the gold of the company's logo badge, used as trim the way a nameplate sits on a finished job.

Density is phone-first and plain-spoken. Heavy uppercase headings in the device's own system sans carry the voice; body copy is large (17px) and short. The crew's own photos are the evidence and get the darkest, quietest band on the page. Light siding bands and dark slate bands alternate, and the page never goes black: black is reserved for the metal itself.

Confirmed rejections, from the direction contract: no stock-photo hero, no stat row, no icon-card grid. No sticky bars of any kind.

**Key Characteristics:**
- Three materials: siding gray (ground), coat black (metal, buttons, numbers), logo gold (trim).
- Alternating light siding/light bands and dark slate bands; never a black page ground.
- Heavy (850) uppercase system sans for every heading; no webfont.
- Large touch targets: 56px buttons, 64px rows, 48px chips, 44px minimum links.
- Signature motion is the coating itself: the hero spray canvas and the self-coating railing dividers.

## Colors

A cool, low-chroma gray world (siding, slate) with one warm metal accent (logo gold) and a separate cool blue reserved for form interaction.

### Primary
- **Logo Gold** (gold): the badge's gold. Text color on coat-black buttons (in its brighter step), fill of selected chips and of the single Instagram panel on the dark work band, underline on the header phone hover, footer icon color. Never a band or page ground.
- **Bright Gold** (gold-bright): gold as it reads on black; label color on every coat-black button, step number, and active service arrow; hover state of gold fills.

### Secondary
- **Coat Black** (coat): semi-gloss black powder coat. Primary button fill, outlined-button stroke and text, step numbers, active service arrows, coated divider bars. It is the metal, not a surface.
- **Coat Hover** (coat-hover): lifted coat for hover on black buttons.

### Tertiary
- **Booth Blue** (focus): outline accent for form controls on dark bands; borders of inputs, chips and the send button turn this color on hover and focus, and it is the focus ring on dark surfaces.
- **Booth Blue Deep** (focus-deep): the focus ring on light surfaces.

### Neutral
- **Vinyl Siding** (siding): header and hero ground, the browser theme color, the hero scene backdrop.
- **Siding Shade** (siding-deep): lower stop of the hero scene fallback gradient.
- **Morning Light** (light): light content bands (services, how it works, area) and the ground behind railing dividers.
- **Slate** (slate): dark content bands (work, estimate).
- **Deep Slate** (slate-deep): footer, and the body color under the page.
- **Ink** (ink) / **Ink Soft** (ink-soft): primary and secondary text on light grounds.
- **On Dark** (on-dark) / **On Dark Soft** (on-dark-soft): primary and secondary text on slate.
- **Light Rule** (rule-light): 1px row and table dividers on light bands.
- **Field Slate** (field-fill) / **Field Stroke** (field-stroke): fill and 2px rest stroke of chips and text fields on slate.
- **Mill Aluminum** (mill-aluminum): uncoated metal in the railing dividers (the hero canvas paints its own close variant).
- Error text on dark is a pale coral (#ffb4a8), bold, at body size.

### Named Rules
**The Never-Black Ground Rule.** No page, band or section ground is black. Grounds are siding (#d3dce3), light (#eef1f3) or slate (#1f2a35 / #17202a). Black (coat) is a material: buttons, numbers, metal.

**The Gold Is Trim Rule.** Gold appears on black (as label color) or as a small fill on a slate band (selected chip, the Instagram panel). It never fills a band, a heading, or a large area on a light ground.

**The Two Accents, Two Jobs Rule.** Gold means "the brand / selected". Booth blue means "you are touching a form control". Never swap them: gold is not a focus color and blue is not a fill.

## Typography

**Display Font:** System UI sans (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same stack

**Character:** One family at very different weights. Headings are 850 uppercase with slightly tight tracking, blunt like stamped metal; body is regular weight at a generous 17px. The system stack is a mandated house rule of the site's maker (pitch-site style), not a placeholder awaiting a webfont.

### Hierarchy
- **Display** (850, clamp(2.55rem, min(12.4vw, 14svh), 5.6rem), 1.02, uppercase, max 11ch): the hero headline only. Height-clamped so the first phone screen still holds the buttons.
- **Headline** (850, clamp(2rem, 8vw, 3.4rem), 1.02, uppercase, balanced wrap): one per section.
- **Title** (700-850, 1.25rem, uppercase): service rows, step titles.
- **Lead** (400, 1.0625-1.25rem, 1.45, max 34-36ch, ink-soft): the hero promise and the area statement.
- **Body** (400, 1.0625rem, 1.55, max 44-46ch): all running text.
- **Label** (700-800, 1.0625rem): button text, form legends and labels, phone number, footer links.
- **Fine** (0.875rem): helper notes, the scene hint, footer fine print, the Instagram handle under the panel.

### Named Rules
**The Stamped Heading Rule.** Every h1-h3 is uppercase at weight 850 (titles may drop to 700). No sentence-case headings, no light display weights.

**The Three-Step Text Rule.** Text below headings uses only three sizes: 14px, 17px, 20px. Hierarchy under the headlines comes from weight and color, not more sizes; nothing smaller than 14px.

## Layout

A single centered column (max 1200px) with 16px side gutters on phones and 32px from 960px. Full-width color bands stack vertically; each band carries its own vertical padding (about 52-56px top and 56-64px bottom on phones, 72-88px on desktop). Breakpoints are 700px (photo grid goes from 2 to 3 columns, steps go 3-across, area and footer split into columns) and 960px (hero splits copy left / scene filling the right; services and estimate become two-column with a sticky companion photo). Small-phone tweaks at 380px and 419px shrink the wordmark and drop button icons so the two hero buttons fit side by side.

The photo grid is a masonry of CSS columns with 8px gaps (12px wide); on phones the first photo spans both columns. The hero scene is full-bleed: on phones it sits under the copy and runs edge to edge; on desktop it fills the hero behind the copy. Railing dividers sit between bands on the light ground.

The phone number lives top-right in the header and scrolls away with the first screen; the email address appears only in the footer. Nothing is fixed or sticky to the viewport except the companion photos inside their own sections on desktop.

## Elevation & Depth

Mostly flat bands with soft, negative-spread drop shadows reserved for objects: the coat-black buttons, the photos, the gold panel, and the logo badge. Shadows fall straight down and stay tight to the object, like a fitting set on a step. Bands and text never carry shadows.

### Shadow Vocabulary
- **Coat button** (`box-shadow: 0 6px 16px -6px rgba(20,26,33,.55)`): primary black buttons on light grounds.
- **Send button** (`box-shadow: 0 8px 18px -8px rgba(0,0,0,.7)`): black button on slate.
- **Photo tile** (`box-shadow: 0 10px 24px -14px rgba(0,0,0,.7)`): work grid photos; the gold panel uses the near-identical `0 10px 22px -12px rgba(0,0,0,.7)`.
- **Companion photo** (`box-shadow: 0 14px 30px -18px rgba(20,26,33,.6)` on light, `0 18px 36px -20px rgba(0,0,0,.8)` on slate): the single sticky photo beside services and the estimate form on desktop.
- **Badge** (`box-shadow: 0 3px 8px -3px rgba(0,0,0,.45)`): the round logo.

### Named Rules
**The Objects Cast, Bands Don't Rule.** Shadows belong to things you could pick up (buttons, photos, the badge). Grounds are separated by color change and railing dividers, never by shadow or border.

## Shapes

Softly rounded rectangles for everything you press or type into (10px), slightly tighter for photos (8px), full pills for chips, and true circles for the logo badge, service arrows and step numbers. Borders are 2px when they mean "this is a control" (outlined button, inputs, chips) and 1px when they divide rows of content. The railing dividers and hero canvas draw literal railing geometry: posts with caps, top and bottom rails, pickets about three times taller than their gaps, a deck line.

## Components

### Buttons
Heavy, square-shouldered and big enough for a thumb.
- **Shape:** gently rounded (10px), 56px minimum height, 2px coat stroke on all variants.
- **Primary (coat):** coat-black fill, bright-gold label, weight 800, optional 20px stroked SVG icon leading. Hover lifts to coat hover; press nudges down 1px.
- **Outlined (line):** transparent, coat-black stroke and label; hover tints with 8% coat.
- **Send (on slate):** coat-black full-width with a lighter stroke (#5b6672); hover and focus turn the stroke booth blue, focus adds a 3px blue ring.
- **Gold panel:** one per page, on the dark work band: gold fill, coat text at 1.25rem/850 with a 14px sub-line, Instagram glyph right, hover to bright gold.

### Chips
- **Style:** pill (999px), 48px tall, field-slate fill, 2px field-stroke border, bold label; the native checkbox or radio is visually hidden underneath.
- **State:** hover turns the border booth blue; selected fills gold with coat text (blue border still on hover); keyboard focus draws a 3px booth-blue outline.

### Inputs / Fields
- **Style:** field-slate fill, 2px field-stroke border, 10px radius, 14px padding, 54px minimum (textarea 110px), on-dark text, placeholder #8e9cab.
- **Focus:** border turns booth blue on hover and on focus; no glow.
- **Error:** bold pale-coral message under the field, announced politely; the field gets aria-invalid.

### Navigation
There is no nav menu. The header is the badge plus a two-line uppercase wordmark at left and the phone number (850 weight, gold-brown handset icon) at right; hover underlines the number in 3px gold. The footer repeats the badge and lists phone, email and Instagram as 44px-tall icon links (gold icons, hover to bright gold).

### Service Rows
Full-width uppercase links (64px, 1px light-rule dividers) that each open a pre-filled text. Hover and focus change only the arrow: its 44px circle goes from pale gray to coat black with a bright-gold arrow, and keyboard focus rings the arrow, not the row.

### Process Steps
A counter-numbered list: 44px coat-black circles with bright-gold numerals, uppercase title, short ink-soft line. Stacked on phones, three across from 700px.

### Hero Powder-Coat Scene (signature)
A canvas drawing of a stoop with a bare aluminum stair railing on siding. Dragging sprays powder that is electrostatically pulled onto the metal, builds a matte coat, and cures to semi-gloss black once coverage passes 92%. An autopilot spray gun sweeps until the visitor touches, and resumes 3.5s after the last touch. Tunables (particle rate, attraction radius, deposit radius, autopilot speed, cure time, overspray share) live as named constants at the top of its script. A single fine-size hint ("Drag across the railing to coat it") fades out on first use. Reduced motion hands scrolling back to the page.

### Railing Divider (signature)
An SVG railing run drawn to the container width, placed between bands. It renders bare in mill aluminum, then, when 80% visible, each bar fades to coat black over 0.45s with a left-to-right delay (1.4s pass), as if an unseen gun passes along it. Reduced motion shows it already coated.

## Do's and Don'ts

### Do:
- **Do** alternate siding/light bands with slate bands, and keep every ground one of siding, light, slate or deep slate.
- **Do** put gold on black: coat-black buttons and circles carry bright-gold labels.
- **Do** outline form controls in booth blue (#7cc0f0) on hover and focus, and use the deep blue (#1f6fb0) focus ring on light grounds.
- **Do** set every heading uppercase at weight 850 in the system sans stack.
- **Do** keep touch targets at 44px or more (56px buttons, 64px rows, 48px chips).
- **Do** use the coating as the motion language: things go from bare aluminum to coat black; respect reduced motion by showing the finished state.
- **Do** let the crew's photos carry the dark work band, 8px corners, soft drop shadow.

### Don't:
- **Don't** use black (#000 or coat) as a page or band ground.
- **Don't** fill large areas or light-ground elements with gold, and don't use gold as a focus or hover-outline color.
- **Don't** add a webfont; the system stack is the house rule.
- **Don't** add sticky or fixed bars (call bars, nav bars, cookie bars).
- **Don't** repeat the phone number in a fixed position; it sits top-right on the first screen and in body/footer contact lines only. Keep the email in the footer.
- **Don't** add hover backgrounds, shadows or outlines to whole service rows; only the arrow changes.
- **Don't** use stock imagery, stat rows or icon-card grids.
