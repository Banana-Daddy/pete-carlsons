# Pete Carlson's Golf & Tennis — Design Brief

## Brand Synopsis

Pete Carlson's Golf & Tennis is a 45-year family-owned specialty retailer on Highway 111 in Palm Desert — the Coachella Valley's only full-line golf, tennis, and pickleball shop. Opened September 10, 1981 by Peter and Edna Carlson, the store has operated continuously from the same 14,000-square-foot location, now surrounded by two PGA Tour Superstores within a mile, a Club Champion fitting studio, a PXG studio, and big-box competitors that trade on scale. Pete Carlson's trades on the opposite: independence, tenure, bench work, and community.

The shop stocks over 100 name brands across more than a dozen departments — roughly 2,500 golf clubs, hundreds of racquets and paddles, thousands of pairs of shoes, and a deep apparel mix. Certified stringers and club repair staff handle the custom work big boxes contract out. The Carlsons anchor two desert institutions alongside the retail floor: the annual Pete Carlson Golf Expo at the College of the Desert (20+ years, ~4,000 attendees each February) and the Jazz for Jazz Lovers concert series on the back patio (since 2010, in partnership with the nonprofit American Jazz Institute).

The current website is a 2014-era WordPress theme that buries the brand's real identity — the family, the murals, the bench work, the community programming — under a grid of department tiles and faded review badges. The mockup's job is to surface the *place* and the *people*.

## Design Decisions

### Direction I — Pete & Edna (Editorial Heritage)

- **Mood**: A love letter to 45 years in the desert — warm, literary, specific. Reads like a Coachella Valley feature in Monocle or T Magazine.
- **Fonts**: Fraunces (display serif, variable with optical-size + SOFT axis) + Instrument Sans (body)
- **Colors**: Terracotta `#C65D3B` (primary accent), cream `#F0E6D2` (primary bg), cream-deep `#E6D8BC` (alt bg), pine `#1F2B25` (text + inverted sections), sand `#8B7355` (tertiary/captions)
- **Layout**: Editorial magazine with Roman-numeral chapter structure (I–V), asymmetric grids, oversized italic display type as callouts, pull quotes with terracotta bar, generous white space, small-caps captions
- **Signature element**: Running Roman-numeral chapter thread across all sections, paired with the recurring "Since MCMLXXXI / 1981" motif — treats the site like a five-chapter magazine story about one family and one block
- **Trends used**: Big impact typography (oversized serif display with italic cuts), editorial/magazine layout grid, marquee ticker, grain/texture overlay on desert-gradient backgrounds, chapter-style numerals as navigation

Key flourishes: drop-cap first letters in chapter intros, SVG grain texture overlay for warmth, ornamental rule line before the brand marquee, hours rendered as a display-font definition list ("9 — 6"), stats rendered as oversized terracotta display numerals with small-caps labels.

### Direction II — Full Court (Modern Desert Sport)

- **Mood**: Sport-first, confident, BNP Paribas-adjacent. Tennis-ball pop meets clay-court saturation meets deep desert court green. Confident, bold, commercial-retail but still premium.
- **Fonts**: Unbounded (display, black weight condensed) + Space Grotesk (body)
- **Colors**: Optic yellow `#D8E649` (signature accent, used for highlights + CTAs + ticker dots), bone `#F8F7F1` (primary bg), court green `#1C2B23` (inverted sections + nav + footer), clay `#A8472C` (events section + tennis accents)
- **Layout**: Bento grid of departments (golf dominant 4-col, tennis + pickleball 2-col, apparel + footwear 3-col), four-up image strip under hero, full-bleed services section in court green with A01–A06 mono-caps catalog indexing, optic-yellow Visit section
- **Signature element**: Endless auto-scrolling brand marquee on optic yellow separating every major section — the retail flex of 45 years of relationships shown as a continuous ticker
- **Trends used**: Bento layouts, brutalist big-type display (huge hero in Unbounded Black), marquee/ticker, mono-cap sport indexing (A01–A06, 01–05 sticker numbering), highlight strokes behind key words (optic yellow underline on "BALL" and "desert"), oversized footer wordmark at the end (16vw "PALM DESERT.")

Key flourishes: `●` (pickleball dot) as a typographic motif throughout nav and tickers, sticker-style chips with rounded pill shape, hover lifts on bento cards with subtle scale on images, arrow CTAs that offset on hover.

## Content Inventory

### Images pulled (all hotlinked from petecarlsonsgolf.com/wp-content/uploads/)
See `IMAGE_LOG.md` for the full list. Strongest assets used:
- Storefront exterior (`2020/12/pete-carlsons-golf-and-tennis-store.jpg`)
- Golf department (`2019/09/front-page-golf-dept.jpg`, `2020/12/golf-club-dept-photo-1.jpg`)
- Tennis department (`2019/09/front-page-tennis-dept.jpg`, `2019/09/tennnis-racket-image-1.jpg`)
- Shoe walls (`2022/03/mens-golf-shoes-wall-1.jpg`, `2022/03/womens-golf-shoes-wall-1.jpg`)
- Apparel (`2022/04/mens-golf-apparel-department-image-01.jpg`)
- Workshop/bench (`2019/09/tennis-strings-1.jpg`, `2018/06/golf-shaft-replacement-1.jpg`, `2018/06/golf-grips-1.jpg`)
- Location map (`2020/12/pcgt-map.jpg`)

### Key copy captured verbatim or adapted from site
- Hero tagline: "Your one-stop shop for golf, tennis, and pickleball" (adapted)
- Pete quote (Direction 1 pull quote): "At Pete's we understand that to some, golf is a game — and to others, it's a way of life."
- Carlsons' signoff (Direction 1 Chapter IV closing): "This season there will be manufacturer representative demo days, in-store fashion shows, annual Golf and Tennis Expo, and live Jazz Concerts. When in the desert, visit Pete Carlson's Golf & Tennis."
- Golf tagline adapted: "A fairway oasis." (from site's "we're your fairway oasis")

### Links preserved
- Phone (click-to-call): `tel:17605683263`
- Google Maps: `https://www.google.com/maps/place/Pete+Carlson's+Golf+%26+Tennis/@33.721,-116.3785,17z`
- Instagram: `https://www.instagram.com/petecarlsonsgolftennis`
- Facebook: `https://www.facebook.com/PeteCarlsonsGolfAndTennis`
- Twitter: `https://twitter.com/petecarlsons`
- YouTube: `https://www.youtube.com/channel/UCIi0jBf-poC6yudnx48jbKg`

## Image Generation Prompts

None generated this build — the site's existing documentary interior photography is strong enough to anchor both directions. See `IMAGE_LOG.md` for **five ready-to-use upgrade prompts** (stringing hands close-up, desert golf mood, pickleball paddle on court, jazz atmosphere, Expo driving range) that Zack can drop into Grok Imagine to enhance specific slots. All prompts follow `GROK_IMAGE_PROMPTS.md` guidance and are atmospheric filler only — never attempting to recreate the actual store, staff, or specific products.

## Suggested Next Mockups

- **Department deep-dives** — One-off page templates for Golf / Tennis / Pickleball that follow through on the bento or chapter pattern. Each with featured brands, service entry points, and staff expertise callouts.
- **The Expo page** — A dedicated event landing for the annual Pete Carlson Golf Expo, leaning into the 20-year tradition, the Al Geiberger appearances, and the ~4,000-attendee scale. Countdown to next February, archive gallery, manufacturer tent map.
- **Jazz for Jazz Lovers** — A concert-series page that honors the 15+ season history with a programmed upcoming-concerts list, tickets/donate flow for the American Jazz Institute, and editorial artist profiles.
- **The Bench** — A deep service page for custom fitting, racquet stringing, and club repair. Booking flow, turnaround expectations, pricing, technician profiles. This is the underleveraged trust asset — the "what big boxes contract out" angle deserves its own page.
- **About Pete & Edna** — A proper owner-story page with family photography, the 1981 origin, the mural story (c. 1996), and the Coachella Valley context. The thing the current site buries most.

## Production Notes

To build this into a real site, use Claude Code (Opus, high effort).

The mockups are standalone HTML with Tailwind via CDN and Google Fonts. Production would move to a CMS that lets Pete/Edna update hours, events, and featured brands without a developer. Recommend either **Next.js + Sanity** (if they want commerce later) or **Astro + Decap CMS** (if they want speed + simplicity). Image handling can stay with their current WordPress CDN or migrate to Cloudinary. Keep the `petecarlsonsgolf.com` domain and redirect the old paths — most are department landing pages that should map cleanly onto new department templates.

Two technical priorities for the real build:
1. **Bring online shopping back** — their current site has a 2020 banner that says "Online shopping has been temporarily disabled while we upgrade... coming back spring 2021." It never came back. A modern Shopify integration or Sanity-powered catalog should be table stakes in year 46.
2. **Event calendar that auto-archives** — the current Tribe Events plugin shows canceled 2020 jazz concerts and expired 2019 Expo promos. Any future CMS pattern should auto-hide past events and surface the next upcoming one prominently.

## Build Timing

| Phase | Duration |
|---|---|
| Step 1: READ (deep scrape via subagent) | ~6m 06s |
| Step 2: DIRECTION | ~1m |
| Step 3: BUILD (both directions + selector) | ~6m |
| Step 4: VERIFY | ~1m |
| Step 5: BRIEF | ~1m |
| Image Generation | 0s (none needed) |
| **Total: Prompt to Live Link** | filled in after publish |
