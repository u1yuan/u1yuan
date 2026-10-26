# Project icon rationale

Shared system: navy tile `#1F3A68` with a `#3A5A90` 2px border (rx 14). Greys: `#A9B6CC` (L) and `#6E82A6` (M). One white highlight per icon marks the "story" element. Live area is 12–52 and strokes are 3px. Source: `_tools/make_icons.py`.

## Philippine Earthquakes Analytics (`philippine-earthquakes-analytics.svg`)
- Thin axes with two ticks each (M): it is a scatter plot, which matches the project being data analysis.
- Grey dots (L): an even dot grid (2.5-unit pitch) clipped to the Natural Earth 10m PHL polygon. It fills the plot area, tall and centred, in its true aspect of about 1:1.5. Luzon, Palawan, the Visayas, Mindanao and Sulu are all included. The tiny far-north Batanes/Babuyan islets (north of 19.2°N) are cropped so the main archipelago can fill the height.
- White rings + centre dots: real USGS epicentres, with ring radius scaled by magnitude. They are the four M≥7.6 events inside lat 4.5–21.5 / lon 116–127.5 from 1996 to 2026:
  - M7.8, 2026-06-07, Mindanao
  - M7.6, 2023-12-02, east of Mindanao
  - M7.6, 2012-08-31, east of Samar
  - M7.6, 2010-07-23, Moro Gulf
- A thin navy halo around each ring keeps it distinct from the land dots underneath.
- The 1996–2026 window matches the README's record range.

## Instagram Usage & Well-Being (`instagram-usage-and-well-being-case-study.svg`)
- Rounded square and corner dot (L), lens ring (M): a simplified monochrome Instagram glyph. The lens is greyer so the data reads on top of it.
- Near-white fitted line at 37°, from lower left to upper right: the trend. It runs slightly past the lens but stops short of the frame, reading as "line through data" (the strong usage–stress link, ρ = 0.84). It goes the opposite way to a ban slash.
- Six grey points sitting just either side of the line: the observations, showing a positive correlation.

## ML team lab (`ml-ta3.svg`)
- Grey tree of nodes and edges (L/M): a decision tree, the base learner of the Random Forests.
- White path and leaf: one tuned decision path, standing for the grid and Bayesian hyperparameter tuning.

## Canvas-to-Notion Task Automation (`canvas-to-notion.svg`)
- Radial burst (L): a simplified monochrome Canvas LMS mark (the source).
- Rounded square with "N": a simplified monochrome Notion mark (the destination).
- M right-angle trace: the automated sync pipeline (GitHub Actions).
- White dot on the trace: an assignment in transit (the daily sync).

## Protektahanan (`protektahanan.svg`)
- Shield (L): protection against scams.
- Back speech bubble outline (M): the second language (Filipino by default, English switch).
- Front white bubble: a pasted message or described call.
- "!" inside it: the warning signs the checker surfaces.

## DevNet Reviewer (`revwi.svg`)
- Card (L): an exam question.
- Top line: the question stem.
- Three option rows: the answer choices (single/multiple choice).
- White checked option: a verified answer (122 verified questions).

## Remento (`remento.svg`)
- Front polaroid rotated −7°, with tape: the scene photo, in a scrapbook style.
- Person silhouette in the photo: the person you met.
- Caption line (M): the detail you kept about them.
- White washi tape: holding the moment in place.
- Back card rotated 9° with a dashed stitch: the "second page" recap (tagline: "A good conversation deserves a second page").

## Pastely (`pastely.svg`)
- Dashed frame (M): the photo whose background was removed.
- White die-cut star: the cut-out sticker lifting out of the frame.
- Three tiles at the right (L/L/M): the sticker library you can rearrange.

## CCSMA Scrollytelling (`site-ccsma.svg`)
- Browser window (L): it is a website (a static Next.js export).
- Three stacked section blocks: its three routes (programs, organizations, student activities/SADU).
- Scroll track with a white thumb: scrollytelling.
- White down chevron: the "descent" through the three routes.

## Trade-offs
- At 20px the PH dots merge into a silhouette and the quake rings become one bright spot over Mindanao.
- The Remento stitching and the Protektahanan second bubble are only readable at 32px and up.
- The Instagram, Canvas and Notion marks are simplified monochrome renditions, not official logo files.
