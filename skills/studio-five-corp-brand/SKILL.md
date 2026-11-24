---
name: studio-five-corp-brand
description: Apply the Studio Five Corp Branding Guidelines 2027 when creating, redesigning or reviewing anything for Studio Five Corp. That covers website pages, footers and mockups, HTML/CSS, landing pages, proposals, tenders and decks, reports, social posts and stories, Instagram feeds, YouTube thumbnails, video covers and end frames, posters, email signatures, business cards, merchandise, signage and copywriting. Use it whenever the work mentions Studio Five Corp, Corp, studiofivecorp.com, Cobalt/Energy blue/Fresh lime, Clash Display or Satoshi, or when someone asks to "make it on-brand", "follow the brand book" or do a brand review for Corp, even if they never say "brand guidelines".
---

# Studio Five Corp brand (2027)

This skill holds the rules that make work recognisably Studio Five Corp. The full book is in `references/brand-book-2027.md` (sections 00–09, about 700 lines). This file covers the rules that apply to almost every job. Open the reference when you need an exact value or a format-specific rule. The section map at the bottom tells you where to jump.

Written rules govern over any example or mockup in the book. If the rules don't cover a case, say so and flag it for the Corp brand owner. Never invent a new rule silently.

## The core in one screen

**Bright. Precise. Full of energy.** White space creates clarity. Cobalt leads recognition. Energy blue supports. Fresh lime highlights one moment.

**No slogan.** The logo is complete alone. Never attach a recurring slogan or tagline to the logo or to any layout. Project-specific, functional headlines are fine ("Corporate event production"). The line *Events. Media. Production. Marketing.* is a service descriptor used in the website footer, not a slogan to lock up with the logo.

**Five colours, no others.** No tints, gradients, blends or extra status hues.

| Token | HEX | Job |
|---|---|---|
| Cobalt blue | `#0046AE` | Logo, headings, links, primary actions, identity anchors. First-choice pair with White (8.44:1) |
| Energy blue | `#4CC9F0` | Secondary fields and supporting graphics. Black text on it, never White |
| Fresh lime | `#D4F725` | One selected accent. Never reading text, never the only essential cue |
| Black | `#000000` | Body copy and data on White |
| White | `#FFFFFF` | Default reading surface and negative space |

`assets/tokens.css` holds these as CSS custom properties with type, spacing and layout tokens. Start web work from it.

**Body text follows the background:**
- White → Black body; Cobalt for headings, links and buttons.
- Cobalt or Black → White body and the White logo.
- Energy blue → Black normal text; Cobalt text only at large sizes (4.39:1).
- Fresh lime → Black body; Cobalt for headings only; never White.
- Large text means ≥24 px regular / ≥18.67 px bold at final size. Decoration-only pairs (Fresh lime/White, Energy blue/White, Cobalt/Black, Energy/Lime) never carry text or essential graphics.

**Proportion target:** 70 % White / 21 % Cobalt / 6 % Energy blue / 3 % Fresh lime of the visible flat fields, excluding photos. It's a default for white-led web and decks, **not a per-page quota**: Cobalt covers, dividers and campaign moments are allowed.

**Type:** **Clash Display** for headlines (Medium/Semibold/Bold; main headings 700, secondary 600), tracking −2 % large, −1 % smaller, 100–110 % leading. **Satoshi** for everything informational: body 400, 0 tracking, 140–150 % leading; labels and buttons Satoshi Medium; uppercase labels +6 %. Fonts come from Fontshare. Use real weights; never stretch or over-track. The only Inter use is the "part of" label in the website footer.

**Logo:** use the supplied masters only: primary (stacked), horizontal, and the S + 5 + C symbol, each in two-blue colour or White. Two-blue on White/light; White on Cobalt; **White is mandatory on Black or dark**. Clear space X = ¼ of the visible symbol height. Minimums: primary 160 px / 30 mm wide, horizontal 240 px / 45 mm wide, symbol 24 px / 6 mm high. Never stretch, rotate, crop, rearrange, retype, recolour, outline, add gradients, glow, bevel or multiple shadows, and never rebuild it with live text. One controlled exception: a subtle, soft Black shadow over photo or video, only when needed to separate every letter.

**Spacing scale:** 8, 16, 24, 32, 48, 64, 96. Keep headings tight to their own text and leave a bigger gap before the next group (e.g. 24 within / 48 between). When copy grows, reflow or split. Never squeeze gaps or shrink type to fit.

**No decorative motif.** Motif specifications are issued separately, so don't invent recurring patterns, symbol-derived textures, lime underlines, ribbons or pixel treatments. Grid guides, chart boundaries and functional rules are fine.

**Accessibility is part of the brand.** Underline inline links. Pair status with words or icons. Give essential controls visible boundaries (outline Energy blue marks in Cobalt on White). Focus ring: Cobalt with a White gap on White; White with a dark gap on Cobalt.

**Group endorsement only in the website footer.** Never put *part of Studio Five Group* in decks, signatures, social or print.

## Voice

Use all five traits together: **genuine, friendly, energetic, professional, experiential.** In practice: real work and specific, supportable details; address people directly with a clear next step; active verbs and concise sentences; precise scope, timing and responsibilities; describe what people will see, hear, feel or do. Avoid unsupported claims, stiff phrasing ("Kindly revert"), hype ("ultimate one-stop solution"), constant capitals and vague delays. Sentence case. Write *Studio Five Corp* in full in formal copy. State SGD when relevant. **No emoji, no trend-led exceptions.**

## Defaults by format

Open the matching reference section before finishing. These lines are only reminders.

- **Website:** White-led (60–80 % white). Cobalt logo, headings and primary action; Black body 18 px desktop / 16–18 px mobile. Grid: 12 columns, 24–32 px gutters, 64–80 px side padding; mobile 4 columns, 16–24 px. Horizontal lockup in wide headers. **Three-zone footer:** Corp logo (≥240 px) left, links in the middle (EXPLORE / GET IN TOUCH), *part of* (Inter 13 px / 1.2, 6 px gap) + Group logo (136 px) on the right, linked to studiofive.group. On mobile it stacks entity → links → endorsement → legal with 24 px side padding. → §01 Naming, §06A Website.
- **Decks and proposals:** 1440 × 810. Margins 64; title x64/y117; body between y224 and y712; footer boundary y752; two 632 columns with a 48 gutter. Ordinary slides White, with Cobalt covers, dividers and the closing slide (White logo). Direct proposals lead with Corp branding: objective, idea, scope, timing, fees, next action. **Client branding in tenders only with the entity leader's approval.** → §06A Decks.
- **Email signature:** horizontal logo + UEN 201310071M on the left. On the right, sender, STUDIO FIVE CORP PTE LTD, then E / M / W / A. Generic sender *Your Friendly Producer*, hey@studiofivecorp.com. No slogan, no Group endorsement. → §06B Email.
- **Social:** feed 1080 × 1350, stories 1080 × 1920, 64 px margins. One subject, one message. Clash Display Bold headline, Satoshi support, a small Fresh lime accent in each designed post. No Black designed backgrounds, and no logo by default. → §06B Instagram feed.
- **YouTube thumbnails:** 1920 × 1080, 64 px safe zone. Person + one story visual + a 2–5 word Clash Display Bold headline. A small lime accent. White horizontal logo 260 px wide on a 340 × 112 Cobalt tab, 64 px from the bottom-left. Leave bottom-right clear. Review at 320 × 180. → §06B YouTube.
- **Video:** genuine people and sound, captions, logo-only end frame (White horizontal on Cobalt or two-blue on White), no slogan. → §05 Video.
- **Print and merchandise:** CMYK values are FOGRA51 starting points. C97 M82 Y0 K0 is a Cobalt test recipe only, so always approve a physical proof. On dark fabric, use the White logo in opaque white ink or thread. → §03 Print, §06B Merchandise.

## Logo files (hosted)

Reference these live URLs in HTML. Don't redraw or trace the logo.

| Asset | URL |
|---|---|
| Horizontal, two-blue (for White/light) | `https://studiofive.group/signature-logo-corp-2027.png` (720 × 162, transparent) |
| Horizontal, White (for Cobalt/dark/photo) | `https://studiofivecorp.com/wp-content/uploads/2026/11/corp-logo-horizontal-white-2027.png` (900 × 202, transparent) |
| Studio Five Group, White (footer endorsement only) | `https://studiofivecorp.com/wp-content/uploads/2026/11/studiofive-group-logo-white.png` (408 × 101) |

The primary (stacked) logo, the symbol and the vector masters (`2-Main .svg`, `3-Main White.svg`, `5-Horizontal.svg`, `6-Horizontal White.svg`, plus PDF/EPS for print) come from the Corp brand owner. If a required file is missing, ask for it rather than reconstructing it.

## When redesigning existing work

1. **List every colour in use** and map each to one of the five tokens by its job. Remove anything that doesn't map, including old greens, greys, hover tints and gradients.
2. **Check every text/background pair** against the rules above. The usual misses are White on Energy blue or lime, small Cobalt-on-Energy text and lime used as text.
3. **Swap fonts to Clash Display / Satoshi.** Fix weights, tracking, line height and sizes per §04.
4. **Replace retired logos** with the current uppercase artwork in the right colourway, with clear space and minimum size.
5. **Remove slogans, emoji and invented motifs.** Group endorsement stays only in the website footer.
6. **Re-space** to the 8-unit scale, keeping headings with their text and bigger gaps between groups.
7. **Re-read the copy** against the five voice traits.
8. **Render it and look** at desktop and at a phone width (~390 px) for overflow, widows and cramped groups.
9. **Save as a new version.** Never overwrite the original. Name working files `StudioFiveCorp_Project_Asset_YYYYMMDD_v01`.

## Reviewing work

Use the §09 checklist. First run the eight core checks: logo, colour + contrast, typography, application + scope, purpose + voice, imagery, spacing + alignment, hierarchy + restraint. Then run the format checks. Report one verdict: **READY** (relevant checks pass), **REVISE** (a rule is broken or the message is unclear) or **CLARIFY** (no approved rule fits). Cite the specific rule for each issue. Judge compliance and quality separately: different compositions can comply, and attractive work can still break a rule.

## Reference map (`references/brand-book-2027.md`)

| Need | Section heading to search for |
|---|---|
| Voice do/avoid, copy examples, naming, footer spec | `## 01 / Foundation & voice` |
| Logo versions, backgrounds, clear space, misuse, photo shadow | `## 02 / Logo system` |
| Palette values, contrast table, proportions, print colour | `## 03 / Colour system` |
| Type size table by format, tracking, spacing | `## 04 / Typography` |
| Grids, layout choice, photography, icons, video | `## 05 / Layout, imagery & video` |
| Website, accessibility, article covers, proposals, deck grid | `## 06A / Website & presentations` |
| Reports, stationery, posters, email signatures, social, feed, video covers, YouTube, banners, merch | `## 06B / Other applications & thumbnails` |
| Approval flow, file naming, asset filenames | `## 07 / Governance & handoff` |
| Review checklist and verdicts | `## 09 / Brand review checklist` |
