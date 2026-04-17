# Image Generation Log — Pete Carlson's Golf & Tennis

No API image generations for this build. All imagery is hotlinked directly from petecarlsonsgolf.com's WordPress uploads directory — the existing interior department photos (shoe walls, club walls, racquet walls, apparel racks, stringing workshop, grip workshop, storefront exterior) are the site's strongest asset and anchor both mockups visually.

## Hotlinked images used

**Storefront / exterior**
- `wp-content/uploads/2020/12/pete-carlsons-golf-and-tennis-store.jpg` — hero photo (editorial direction), story section (full-court direction), card 2 background (selector)

**Interior — departments**
- `wp-content/uploads/2019/09/front-page-golf-dept.jpg` — full-court golf bento
- `wp-content/uploads/2019/09/front-page-tennis-dept.jpg` — full-court tennis bento
- `wp-content/uploads/2020/12/golf-club-dept-photo-1.jpg` — editorial golf section, full-court hero strip
- `wp-content/uploads/2019/09/tennnis-racket-image-1.jpg` — editorial tennis section, full-court hero strip
- `wp-content/uploads/2022/03/mens-golf-shoes-wall-1.jpg` — editorial Chapter I feature image, full-court hero strip, selector card 1 background
- `wp-content/uploads/2022/03/womens-golf-shoes-wall-1.jpg` — full-court footwear bento
- `wp-content/uploads/2022/04/mens-golf-apparel-department-image-01.jpg` — full-court apparel bento
- `wp-content/uploads/2022/04/tennis-apparel-department-tennis-shirts-and-shorts.jpg` — editorial pickleball section

**Interior — workshop / services**
- `wp-content/uploads/2019/09/tennis-strings-1.jpg` — editorial Chapter III feature image, full-court services image, hero strip
- `wp-content/uploads/2018/06/golf-shaft-replacement-1.jpg` — editorial Chapter III
- `wp-content/uploads/2018/06/golf-grips-1.jpg` — editorial Chapter III

**Map**
- `wp-content/uploads/2020/12/pcgt-map.jpg` — editorial Chapter V visit section

All images load with `loading="lazy"` and have `onerror` fallbacks to styled CSS placeholders with labels, so even if the source CDN goes dark the mockups still render cleanly.

## Why no Grok generations

The site already has documentary-quality interior shots that sell the store's actual inventory and physical identity. Generating atmospheric filler (desert light, generic racquet hands, etc.) would have diluted the grounded feel without adding meaningful information. Saved the $0.10–$0.15 Grok budget for future builds.

## Optional upgrade prompts — for Zack to generate in Grok Imagine

If Zack wants to punch up either direction further with atmospheric filler (never recreating the actual store), here are ready-to-use prompts following `GROK_IMAGE_PROMPTS.md` format. Each is optional — the mockups stand on their own without them.

### Upgrade 1 — Racquet stringing hands close-up
- **Slot**: Chapter III / Bench Work workshop feature (both directions)
- **Aspect ratio**: 3:2 landscape
- **Prompt**: "Extreme close-up photograph of weathered hands threading synthetic gut string through the grommets of a tennis racquet on a stringing machine, soft amber afternoon light angling in from the left, shallow depth of field throwing the mains out of focus behind the cross string being tensioned. Visible worn wedding band on the left hand, calm concentration, no face in frame. Warm earth palette of amber, bone, and deep desert green, documentary photography feel, 50mm lens, film grain."
- **Why**: Would replace or overlay the existing stringing photo with a more intimate craft detail, emphasizing the bench work story.

### Upgrade 2 — Desert golf mood
- **Slot**: Potential hero background for editorial direction, or bento accent for full-court
- **Aspect ratio**: 16:9 landscape
- **Prompt**: "Wide-angle photograph of an empty desert golf course fairway at golden hour, the San Jacinto mountains hazy and purple in the far distance, long diagonal shadows stretching across closely-mown grass, a single flagstick visible in the middle distance. No people. Warm amber light, atmosphere haze softening the background, muted palette of sage green, dusty cream, and terracotta mountains. Cinematic wide-angle, shot on 35mm film, natural color grading, quiet and reverent mood."
- **Why**: Could replace the hero or live as an atmospheric break between sections, reinforcing the Coachella Valley geography.

### Upgrade 3 — Pickleball paddle on court
- **Slot**: Pickleball bento card (full-court direction) — currently uses solid optic yellow
- **Aspect ratio**: 1:1 square
- **Prompt**: "Overhead photograph of a graphite pickleball paddle resting on the baseline of a freshly painted outdoor pickleball court, a single yellow ball beside it, crisp morning sunlight casting a clean diagonal shadow of the paddle across the blue court surface. Minimalist composition, saturated color, high-contrast, no people. Shot from directly above, sport editorial style, reminds of a well-art-directed Wilson or Selkirk campaign shot."
- **Why**: Would give the pickleball card a visual anchor beyond color alone.

### Upgrade 4 — Jazz atmosphere
- **Slot**: Community / Jazz section (both directions)
- **Aspect ratio**: 3:2 landscape
- **Prompt**: "Evening photograph of a double bass leaning against a chair on a small outdoor patio stage strung with warm string lights, a folded music stand behind it, the suggestion of palm fronds silhouetted against a dusky desert sky. Amber and bronze tones dominate, smoky atmosphere, soft focus on the background audience chairs in the foreground blur. No faces. Documentary music photography feel, 85mm lens, natural warm light, nostalgic mood."
- **Why**: Replaces the dated 2015 jazz-banner assets with something more evocative of the decade-long concert series.

### Upgrade 5 — Expo driving range
- **Slot**: Events / Golf Expo section (both directions)
- **Aspect ratio**: 16:9 landscape
- **Prompt**: "Wide photograph of an outdoor golf driving range at dusk in the Coachella Valley, rows of equipment manufacturer tents with pennants catching the last light, golfers in silhouette testing clubs down the range, the dark outline of distant mountains on the horizon. Warm festival atmosphere, amber tungsten lights beginning to glow in the tents, cinematic wide lens, documentary event photography feel, no identifiable faces. Shallow haze in the air, golden hour fading to twilight."
- **Why**: Replaces the dated 2019 Expo reminder graphic with an atmospheric scene-setter.

**Running total**: $0.00 (no API calls this build)
