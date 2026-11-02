# Vigil — Two Lights

Prepared for Louder Labs / Brad McCorkle and McKayl, 2 November 2026.
Review artwork; owner approval remains pending. No website changes or publication performed.

## Integration files

- mark.svg — editable 1024-unit vector master, full Deep Space square.
- favicon.svg — the same geometry with a 32 px default size.
- icon-1024.png, icon-512.png, icon-192.png, icon-180.png, icon-32.png — RGB PNGs with embedded sRGB profiles.
- icon-512-maskable.png — all artwork fits inside the centered circular 80% safe zone. Intentionally identical to icon-512.png: the master already fits that zone.
- og-card.png — 1200 × 630 link card. Cormorant Garamond 600, tracking 0.32em. Exact requested tagline and domain.

All icons use #03040E to all four edges. No baked corner masks or external shadows. The review sheet uses simulated operating-system masks only; these are not part of any deliverable icon.

The flame is a single uncut silhouette above two convex arcs meeting beneath it. It uses only the locked palette endpoints: #FF7A2A, #FFB54F, and #FFE7B0, with interpolated gradient colors. The link card uses #FFF8EA for supporting text.

## Supporting files

review/review-sheet.png shows the mark, light-screen context, round/squircle crops, and actual-size and enlarged 32 px artwork. review/validation.json records dimensions, file sizes, color profiles and the maskable safety check. Visual interpretation still needs owner review.

source/ contains reproducible artwork scripts, design notes, and the openly licensed Cormorant Garamond variable font and Work Sans Regular font, with their licenses. To reproduce: run source/build.cjs with Node.js and Sharp; then source/finish.py with Python and Pillow. Both font files are bundled for portable reproduction.

Use icon-192.png and icon-512.png with manifest purpose `any`; use icon-512-maskable.png with purpose `maskable`. Use icon-180.png as the Apple touch icon, favicon.svg as the SVG favicon, icon-32.png as the PNG fallback, and og-card.png as the social image. Preserve the full square background; let the operating system apply its own corner mask.

No paid services were used. The attached ZIP is the handoff; files have not been uploaded to Google Drive.
