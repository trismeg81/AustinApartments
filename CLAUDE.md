# CLAUDE.md — Apartment Deals Austin
## Project Instructions for Claude Code
Last updated: April 27, 2026

---

## Who I Am
I'm Taylor Boykin, a licensed real estate agent and full-time apartment locator based in Austin, TX.
- **Business:** Apartment Deals Austin
- **Website:** https://www.apartmentdealsaustin.com
- **Phone:** 972-754-7790 ← this is the #1 conversion point on the entire site
- **Email:** taylor@myapartmentfinders.com
- **Market:** Austin, TX and surrounding areas (Cedar Park, Leander, Round Rock, Pflugerville,
  Georgetown, Buda, Kyle, Taylor TX, Hutto, Manor, Liberty Hill)

### My Value Proposition
I find Austin renters the best apartment deals in the city — move-in specials, weeks free, waived
fees — completely free to them. I'm compensated by the properties I place clients in. I'm a
local market expert, not just a search tool.

---

## What This Codebase Is
- **URL:** https://www.apartmentdealsaustin.com
- **Stack:** Jekyll + Beautiful Jekyll theme, hosted on GitHub Pages
- **Repo:** github.com/trismeg81/AustinApartments
- **Auto-deploys:** on push to main branch
- **Purpose:** Convert website visitors into text message leads at 972-754-7790
- **Design system:** See DESIGN.md in repo root (Pinterest light theme design tokens)

---

## Current Status (as of April 27, 2026)

### Completed ✅
- Full site overhaul — 9-section structure per spec below
- Complete CSS rewrite with design token system (inspired by apartmentlist.com)
- System font stack, sticky nav, deal cards in CSS Grid
- SMS CTAs throughout (sms:9727547790)
- SEO meta tags + Open Graph tags in _config.yml
- JSON-LD LocalBusiness + RealEstateAgent schema markup
- sitemap.xml + robots.txt created
- Canonical URL set
- Footer updated to "Apartment Deals Austin"
- Photo filenames renamed (no property names)
- CLAUDE.md + DESIGN.md committed to repo
- Google Business Profile optimized
- Google Form intake connected to Gmail + Google Sheets
- HTTPS enforced via GitHub Pages + Namecheap DNS

### Still To Do ⏳
- Replace 3 placeholder deal cards with real current listings
- Build _data/deals.json for automated deal card updates
- Replace placeholder testimonials with real client quotes
- Set up Google Search Console + submit sitemap.xml
- Write first SEO blog post (target keyword: "free apartment locator Austin TX")
- List on Yelp, Thumbtack, Bark.com, Alignable

---

## #1 Goal — Primary Conversion
**Get the visitor to text 972-754-7790 immediately.**

This is the single most important outcome of every page. Every section, every CTA, every design
decision should serve this goal. Taylor responds fast and closes leads through human conversation —
the website's job is to hand off that warm lead via text.

- CTA button text: "Text Me Now", "Get Your Free List", "Text Taylor"
- Phone number 972-754-7790 must be visible, tappable, and prominent above the fold
- Secondary CTA: fill out the Google intake form (for visitors not ready to text yet)
- Never bury the phone number below the fold on mobile

---

## Page Structure (Home Page)
Sections top to bottom:

1. **Hero** — headline, subheadline, primary CTA (sms:9727547790), secondary link (Google Form)
2. **How It Works** — 3 steps: Tell me → I find deals → You move in free
3. **Current Deals** — active concession deals by neighborhood, NO property names, each card has text CTA
4. **Rent Calculator** — input: base rent + weeks free + lease term → output: effective monthly rent
5. **Why Use a Locator** — saves time, saves money, licensed agent credibility
6. **About Taylor** — short, warm, personal, photo if available
7. **Testimonials** — 3–5 client quotes (placeholders with TODO comment until real quotes added)
8. **Final CTA** — full-width, bold: "Ready to find your place? Text me now."
9. **Footer** — name, phone, email, license info, page links

---

## Concession Math Formula
**Effective monthly = Base rent × (Lease months - Free weeks ÷ 4.33) ÷ Lease months**

Examples:
- 8 wks free / 12-mo lease: Base × 10 ÷ 12
- 10 wks free / 14-mo lease: Base × 11.5 ÷ 14
- 12 wks free / 16-mo lease: Base × 13 ÷ 16
- 1 month free / 12-mo lease: Base × 11 ÷ 12

---

## Rules — Always Follow These

### Never Do
- **Never name a specific apartment complex or property** — this lets visitors bypass Taylor
  and go straight to the leasing office. Describe the area and the deal only.
- Never give a full address or cross streets that would identify a specific building
- Never use the word "luxury" or "luxury living"
- Never make the phone number non-tappable on mobile — always use tel: or sms: links
- Never remove or bury the primary CTA
- Never push directly to main for anything beyond minor SEO/content fixes
- Never break the Jekyll/Beautiful Jekyll theme structure without confirming first

### Always Do
- Keep the phone number 972-754-7790 accurate everywhere it appears
- Use `sms:9727547790` for text CTAs and `tel:9727547790` for call links
- Keep mobile experience the top priority — test every change at mobile viewport
- Write clean, commented code — this site may be handed to other developers
- Preserve the rent calculator functionality — it's a key differentiator
- Keep tone warm, local, and human — never corporate or generic
- Reference DESIGN.md for all color, spacing, and typography decisions

---

## Voice & Tone (for any copy written)
- Casual and direct — like a knowledgeable Austin local, not a salesperson
- First person — always "I" not "Taylor" or "we"
- Short sentences, short paragraphs
- Lead with the benefit to the renter
- Always explain that the service is free and the property pays
- Sign off as Taylor or Taylor | Apartment Deals Austin

---

## Git Workflow
- Main branch: `main` (production — auto-deploys to GitHub Pages)
- Feature branches for all changes: `git checkout -b feature/description`
- Descriptive commit messages: `git commit -m "Replace placeholder deal cards with live listings"`
- Minor SEO/content fixes may go direct to main
- Git identity: Taylor Boykin / taylor@myapartmentfinders.com
- Remote: origin → https://github.com/trismeg81/AustinApartments.git

---

## File Structure
```
~/Documents/Businesses/apartmentdealsaustin/
├── AI Tools/
│   ├── CLAUDE.md                    ← this file (also in repo root)
│   ├── DESIGN.md                    ← design token system
│   └── listing-copy-generator.md   ← generates FB Marketplace listings
├── AustinApartments/                ← Git repo (website)
├── Marketing/
│   ├── Facebook Marketplace/
│   └── SEO/
├── Clients/
└── Resources/
```

Property photos: `/Volumes/SPEED/Real Estate/Austin IMAGES/` (235+ folders by property name)

---

## Questions to Ask Before Making Changes
1. Does this affect the primary CTA or phone number visibility?
2. Does this work on mobile?
3. Does this help or hurt SEO?
4. Does this move a visitor closer to texting 972-754-7790?
5. Does this conflict with anything already built (check Current Status above)?
