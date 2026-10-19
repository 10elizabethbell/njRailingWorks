# New Jersey Railing Works — handoff at ~60%

**Live:** https://10elizabethbell.github.io/njRailingWorks/ · **Repo:** https://github.com/10elizabethbell/njRailingWorks · **Built:** 2026-10-19 from Muse brief (run 2026-10-19, North Jersey Contractors group post)

## What's built
- One page, phone first: header (logo, name, 973-281-3208 top right), hero, Our work (9 photos), What we build (6 rows), How it works (3 steps), estimate form, All of New Jersey + hours, footer.
- **World:** a powder-coat line on a New Jersey stoop. Blue-gray vinyl siding ground, stone stair, logo gold as trim on black buttons and dark slate bands. Their captions mention a "semi-gloss black powder-coated finish" on nearly every job.
- **Signature:** the hero is a bare aluminum stair railing.
  - A powder gun sprays it on its own until you touch it. Then your finger or mouse sprays, the grains wrap onto the bars, and the metal turns matte charcoal.
  - At full coat it cures to semi-gloss black and the loop stops to save battery.
  - Drag works up, down and sideways on phones.
  - Reduced motion shows a still frame, half coated, and the page scrolls normally over it.
- **Dividers:** two railing runs that take their coat bar by bar when scrolled into view.
- **Contact:**
  - "Text us a photo" (pre-filled SMS) and "Get an estimate" (jumps to the form).
  - Each service row opens an SMS naming that service.
  - The form composes a text, with a copy fallback.
  - Email is in the footer only. The Instagram button sits right under the photos, and Instagram is in the footer too.

## Assumptions I made
- **Texting:** the brief said "accepts texts: unknown", but their Instagram captions say "📞 Call or text: 973-281-3208", so texting is the main channel.
- **Email:** njrailingworks@gmail.com comes from those same captions (the brief found none). It is in the footer only.
- **Instagram instead of Facebook:** "more of our work" links to @newjerseyrailings. The only Facebook link in the brief is Tony's personal profile, and Instagram is their whole web presence (416 posts).
- **Voice:** "we/our", since the captions speak as a crew. The hero promise "We treat your home like our own…" is my wording in that spirit.
- **Services:** taken from the captions: interior & exterior railings, stair renovations, fences, custom gates, metalwork. The materials (aluminum, iron, wood, vinyl) come from the captions too. "Repairs" comes from the Facebook post.
- **How it works, step 2** ("We plan it with you: style, material and finish") is inferred; I cut a price-before-work claim I couldn't source.
- **Area:** "Serving all of New Jersey" (captions). I show "Based in Pompton Lakes" but not the street address (131 Dawes Hwy), because I can't tell whether that's a shop or a home.
- **Hours:** Mon–Fri 9–6, Sat 10–3, from the business listing Muse found. Sunday isn't listed, so I left it off.
- **Colors:** black and gold from the logo. The page ground is siding blue-gray and dark slate, never black (house rule).
- **Audience:** treated as general North Jersey homeowners, not 40+, because Muse didn't flag it. If Tony's customers skew older, apply `older-audience.md`: draw the hero as a still frame and drop the dividers' motion.

## Placeholders and gaps
- **Logo:** I only have the 100px Instagram profile picture, which looks soft in the header and footer. The favicon is a redrawn SVG of the mark (gold railing + NJRW on black).
- **Photos:** 10 of their 28 Instagram photos are used (9 in the gallery, 1 in the desktop services column).
  - work-01 had house number "31" painted out.
  - IG photos 01, 06, 07 and 08 were skipped because they show house numbers.
  - None show fences or gates on their own, even though both are listed services.
- No reviews, prices, years in business, insurance or licence numbers anywhere, so none are on the page.

## Questions for the owner
- Original logo file (vector or large PNG)?
- Is 131 Dawes Hwy a shop customers can visit, or should it stay off the page?
- Photos of fences, gates and repairs, plus any before/after pairs of the same stoop?
- Do you give free estimates, and do you come out to measure? (Both would strengthen the hero and step 2.)
- A few customer reviews we can quote word for word, with first names?
- Is there a business Facebook page to link next to Instagram?
- Towns you most want work in (for the area section and search)?

## Ideas not built (yours to pick)
- **Runner-up world:** a contractor's shop drawing. The railing as an elevation with dimension lines (2" posts, 3/4" balusters, 36" rail height) that draw themselves in. It's calmer, and suits an older audience.
- **Other candidates:** red oak treads and stain; welding sparks on iron gates; wrought-iron scrollwork.
- **Hero:** let the visitor pick the finish color (black, bronze, white) before spraying. After the cure, a gentle "next railing" swap so late arrivals can spray again; I chose to let it rest instead, because a coat that dissolves doesn't read as real.
- **Before/after slider** once Tony sends same-spot pairs.
- **"Railing style" picker** in the form (horizontal, vertical Colonial, wood + iron) using his own photos as the choices.
- **Gallery:** tap to open a full-screen photo; currently the photos are static.
- **Type:** the detector wants a sourced display face; house rule keeps the system stack. A condensed industrial face would suit the world if you ever relax that.

## Not verified
- Real-device touch, and the SMS handoff on iOS and Android, especially inside Facebook's and Instagram's in-app browsers.
- Frame rate on old Android phones (particles are capped and phones get 60% of the spray rate).
- iOS Safari rendering of the canvas shadows (switched from `ctx.filter` to `shadowBlur` for WebKit; not seen on a device).
- WebKit / Playwright audit (only headless Chrome was run).
