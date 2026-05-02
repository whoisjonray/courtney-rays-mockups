# Courtney Ray's — Site Redesign Pitch

**Date:** 2026-05-02
**Pitched by:** Jon Ray
**Audience:** Courtney Ray + team
**Mockups:** open `index.html` in this folder

---

## What's wrong with the current site

You've had the same Shopify theme for years. It pre-dates the new packaging, the freeze-dried line, and the TikTok-led world we're now trying to sell into. Specifically:

1. **It doesn't match the new packaging.** The bold script logo, the candy-store stripes, the starburst taglines — none of that energy is on the site. The packaging is doing 100% of the brand lifting; the site is muting it.
2. **It's not built for TikTok-driven discovery.** No UGC wall, no "as seen on TikTok" social proof, no creator integration, no shoppable video. When someone watches a brittle TikTok and lands on the site, the energy drops.
3. **CRO is thin.** No bundle promotion above the fold. No subscribe-and-save module. No sensory copy on PDPs. Reviews aren't surfaced as social proof. Add-to-cart CTA isn't sticky on mobile.
4. **The freeze-dried line buried.** Freeze-dried candy is the biggest TikTok candy trend of 2025–2026 (4.7B TikTok views; Mars and Ferrara are entering the space). Yours should be a hero, not a tab.

The Shopify theme isn't the problem. The DESIGN is. We're keeping the platform; we're refreshing what sits on top.

---

## The new direction in three sentences

**Loud where the packaging is loud, quiet where it isn't.** Cream backgrounds, big breathing room, then full-bleed flavor color blocks that explode with personality. Let the packaging photography do the heavy emotional lifting — the site frames it like art.

**Per-flavor palettes, not one site palette.** Every flavor card and PDP inherits the exact colors of its bag (peanut → blush pink, pecan → lavender purple, bacon → butter yellow, hatch → lavender + pink, freeze-dried → cream + flavor accent). One brand, six distinct moods. Same system the packaging already uses.

**TikTok-native at the structural level, not as a bolt-on.** UGC wall on the homepage. Sensory-first PDP copy ("first bite: shatter · mid-chew: melt"). Freeze-dried gets viral-drop framing with limited-quantity language. Built for the new buyer.

---

## What's in the mockup pack

Seven HTML pages, all responsive, all linked. Open `index.html` to see them all.

1. **homepage.html** — Bold script hero with new pink packaging as the centerpiece. Retail trust strip (QVC, Hallmark, H-E-B). Six-flavor color shelf with each flavor in its own palette. Believer Box bundle promo. TikTok UGC wall. Reviews. Subscribe & Save module. Why-it's-different cards. New footer.

2. **collection.html** — All Brittle. Filter pills (Classic, Freeze Dried, Vegan, Spicy, Bundles). Featured Believer Box at the top. Each flavor card uses its full per-flavor palette. Subscribe & Save promo at the bottom.

3. **product-freeze-dried.html** — The TikTok hero PDP. Cream background, hot-pink accents, "VIRAL DROP · LIMITED RUN" badge. Sensory-first copy ("first bite: shatter · mid-chew: melt · finish: warm caramel"). Sticky add-to-cart with subscribe toggle. FAQ section. Ingredients table. Full TikTok wall. Cross-sells.

4. **product-peanut.html** — Flagship PDP in the pink palette. Same template, different colors. Shows how the system flexes flavor-to-flavor.

5. **product-hatch-chile.html** — Same template, full purple palette. Proves the system works across all six flavors without redesign cost.

6. **bundles.html** — The Believer Box (all six), Build Your Own 3-pack, Freeze Dried Duo, Texas Trio, Corporate/Wholesale. Bundles is where AOV gets unlocked.

7. **about.html** — The Uncle Ray → Courtney narrative. Stats bar (35 years / 6 flavors / 100K+ bags / 1 copper kettle). Crunch for a Cause section. Brittle timeline 1990 → 2026.

---

## Design system at a glance

**Type stack:**
- Display script: **Lobster** (closest free Google Font to the packaging script — production version should commission a custom or use a paid match)
- Cursive: **Pacifico** (for the small "Courtney Ray's®" mark)
- Body: **DM Sans** + **Inter**

**Universal palette:**
- Ink: `#2A1810` (deep brittle-brown)
- Cream: `#F4ECDA` (the freeze-dried bag bg)
- Hot pink: `#E5286F` (primary script color)
- Orange: `#F58A2B`
- Yellow: `#FCE56C`
- Purple: `#6E4691`

**Per-flavor (CSS classes, drop on body or section):**
- `.flavor-peanut` → blush pink bg, hot pink script, orange/yellow stripes
- `.flavor-pecan` → lavender bg, purple script, pink/purple stripes
- `.flavor-bacon` → yellow bg, hot pink script, pink/cream stripes
- `.flavor-hatch` → lavender bg, purple script, orange/yellow stripes, pink starburst
- `.flavor-fd-peanut` → cream bg, hot pink script, orange callout, pink/purple stripes
- `.flavor-fd-pecan` → cream bg, purple script, orange callout, pink/purple stripes

**Signature design elements (lifted from the packaging):**
- **Striped section borders** — orange/yellow stripes between sections
- **Starburst tagline badges** — SVG starburst with cursive script ("sweet n' salty," "crispy & nutty")
- **Pill diet callouts** — white-cream pill with colored border (matches packaging exactly)
- **Diagonal "handmade · small batch" ribbon** — referenced subtly
- **Bold script display headlines** — every section title uses Lobster
- **Stripe dividers between sections** — keeps the candy-store rhythm alive

---

## What we're applying from TikTok candy winners

Researched 15 brands killing it on TikTok and DTC right now. Full report at `/seo/tiktok-candy-research-2026-05-02.md`. The plays we're stealing:

| Tactic | Where you'll see it | Why it works |
|---|---|---|
| Sensory PDP copy ("first bite: shatter") | Every PDP `.sense-grid` | Freeze Dried Candy Store, Sour Strips. ASMR copy converts because TikTok primed buyers to think this way. |
| Sticky add-to-cart on mobile | All PDPs | Olipop, Last Crumb. Removes the most common cart abandonment cause. |
| Bundle-forward IA | Homepage + Bundles page | Sour Strips, Sugarfina. AOV jumps 30–50% when bundles are front and center. |
| "As Seen On TikTok" UGC wall | Homepage section | Behave, Hormbles. Social proof that converts on the moment of arrival. |
| Subscribe & Save with skip-anytime | Every page footer + PDP | Olipop, Smartsweets. Recurring revenue from a snack is real now. |
| Limited drop / scarcity language | Freeze Dried PDP | Last Crumb (200K waitlist for $140 cookie box). Drives FOMO + pre-orders. |
| Branded reviews ("Brittle Believers") | All review modules | Crumbl. Naming the customers builds tribe. |
| Founder-led storytelling | About page | Sour Strips (sold to Hershey for $75.5M off founder content). The Uncle Ray story is your equivalent. |

What we're NOT stealing: neon-loud Sour Strips/Behave aesthetic. The new packaging is already plenty bold. The site should give it room to breathe — Sugarfina/Last Crumb/Olipop level of editorial restraint, just with our color punch.

---

## What this changes for the business

| Lever | Before | After (target) |
|---|---|---|
| Average order value | ~$22 (single bag) | ~$38 (bundle-forward) |
| Subscription % of revenue | ~0% | 20–30% within 6 months |
| TikTok-driven sessions | Direct dropoff | UGC wall + sensory PDP copy match the visitor's expectation |
| New-flavor launches | Buried under existing nav | "VIRAL DROP" framing makes them events |
| Brand consistency | Site doesn't match packaging | Per-flavor palettes baked into every product touchpoint |

These aren't promises. They're what the design enables when paired with TikTok content + retargeting. We measure with GA4 + Shopify analytics monthly.

---

## Build estimate

This is a Shopify Liquid theme refactor, not a platform migration. We keep:
- Shopify checkout (proven, unchanged)
- Shop Pay, Apple Pay, all payment methods
- Existing product database, customer accounts, order history
- ShipHero fulfillment integration
- Klaviyo (email)
- Existing reviews app data — we just need to inject `aggregateRating` into the Product schema (CRO fix from the SEO audit)

We change:
- Theme files (Liquid templates, CSS, JS)
- All product/collection/page templates
- Cart drawer + checkout customization (where Shopify allows)
- Schema markup (FAQPage, AggregateRating, BreadcrumbList — fixes the SEO audit findings)

**Estimated build time:** 4–5 weeks (development + QA + content migration)
**Estimated launch:** ~6 weeks from green-light
**Risk:** low — we're rebuilding the theme, not the store. All e-commerce infrastructure stays.

---

## What I need from Courtney to move forward

1. **Direction sign-off** on the look + voice in these mockups. Even just "yes, more of this" or "no, soften the pink" is enough.
2. **Product photography update** for the freeze-dried line (PDP needs lifestyle / hand-held bag shots, not just packaging). I can shoot or art-direct a contractor.
3. **Decision on subscription + bundle pricing tiers.** I have suggestions; we should agree before launch.
4. **Brittle Believers review name** sign-off. Or pick a different one — happy to brainstorm.
5. **TikTok creator pipeline.** This redesign performs best when paired with 5–10 creator partnerships in month one. We can start the outreach list now.

---

## How this connects to the SEO audit

The redesign isn't a substitute for SEO. It's a complement. The SEO audit identified four high-leverage fixes that ALL get addressed by this rebuild:

1. **Product schema AggregateRating** — fixed in the new Liquid templates
2. **FAQPage schema** — every PDP includes a FAQ section that doubles as schema fuel
3. **BreadcrumbList schema** — added to every page
4. **Sensory + depth content** — the new PDPs are 1,000+ words of substantive content vs the current ~200, which directly fixes the "thin content" diagnosis

The redesign doesn't replace the recipe-blog content engine I recommended in the SEO audit. That's a separate workstream that runs in parallel.

---

## TL;DR

Keep Shopify. Refresh the theme to match the new packaging. Bake TikTok-era CRO patterns into the structure. Per-flavor palettes lifted from the bags. 6 weeks to launch. Low platform risk. High CRO + brand-trust upside.

Next step: walk through the mockups, tell me what to keep and what to change.

— Jon
