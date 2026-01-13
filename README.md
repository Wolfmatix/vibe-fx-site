# 🚨 VIBE FX: COLLAGE SPECIFICATION (NON-NEGOTIABLE)

This repository is for the high-fidelity graffiti dashboard. It must NOT use standard web rows or "clean" grids.

## 🎨 Visual Identity
* **VIBEX Logo**: Must use the hand-drawn font with 15px red offset shadow and 4-color liquid drips (Red, Blue, Yellow, Teal).
* **Layering**: Elements must use `z-index` and `absolute` positioning to overlap like physical stickers slapped on a wall.
* **Drip Logic**: Boxes must have irregular "running paint" bottoms using SVG gooey filters—NOT straight borders.
* **Bounty Sticker**: The "BOUNTY" tag must be a physical-looking sticker rotated at -12 degrees and placed ON TOP of the center card.

## 📉 Data Integrity
* **STRICT RULE**: Do NOT use the placeholder values ($0.084, $9,750, 120,300) in production.
* **Live Data**: Fetch real price from `vibe.market` and real balance via the `0x30...17c1` contract.

## 🛠️ Deployment
* Only one `index.html` is required.
* Inline CSS is preferred to ensure "clean" external stylesheets don't override the collage aesthetic.
