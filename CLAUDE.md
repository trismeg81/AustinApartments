# CLAUDE.md — Apartment Deals Austin
## Project Instructions for Claude Code

---

## Who I Am
I'm Taylor Boykin, a licensed real estate agent and full-time apartment locator based in Austin, TX.
- **Business:** apartmentdealsaustin
- **Website:** www.apartmentdealsaustin.com
- **Phone:** 972-754-7790 ← this is the #1 conversion point on the entire site
- **Email:** taylor@myapartmentfinders.com
- **Market:** Austin, TX and surrounding areas (Cedar Park, Leander, Round Rock, Pflugerville)

### My Value Proposition
I find Austin renters the best apartment deals in the city — move-in specials, weeks free, waived
fees — completely free to them. I'm compensated by the properties I place clients in. I'm a
local market expert, not just a search tool.

---

## What This Codebase Is
- **URL:** www.apartmentdealsaustin.com
- **Stack:** Custom HTML / CSS (no framework)
- **Purpose:** Convert website visitors into text message leads at 972-754-7790
- **Current state:** Needs full overhaul — layout is disorganized, conversion path is unclear,
  SEO is underdeveloped. Treat this as a ground-up rebuild within the existing HTML/CSS stack.

### Current Pages
- Home page
- About
- Link to Google intake form
- Property photos and current specials
- Monthly rent calculator (factors in concession specials)

---

## #1 Goal — Primary Conversion
**Get the visitor to text 972-754-7790 immediately.**

This is the single most important outcome of every page. Every section, every CTA, every design
decision should serve this goal. Taylor responds fast and closes leads through human conversation —
the website's job is to hand off that warm lead via text.

- CTA button text should always be action-oriented: "Text Me Now", "Get Your Free List", "Text Taylor"
- The phone number 972-754-7790 should be visible, tappable (tel: link), and prominent above the fold
- Secondary CTA: fill out the Google intake form (for visitors not ready to text yet)
- Never bury the phone number below the fold on mobile

---

## Project Goals

### Conversion Goals
- [ ] Phone number visible and tappable above the fold on every page
- [ ] Primary CTA = text message link (sms:9727547790) on every page
- [ ] Reduce clicks to conversion — visitor should be able to text within 5 seconds of landing
- [ ] Mobile-first design — majority of Facebook Marketplace traffic comes from phones

### Design Goals
- [ ] Clean, modern, trustworthy aesthetic — not cluttered
- [ ] Reorganize all existing sections into a logical flow (see Page Structure below)
- [ ] Consistent typography, spacing, and color system throughout
- [ ] Fast load time — no unnecessary scripts or heavy assets

### SEO Goals (to be built after overhaul)
- [ ] Rank page 1 for "free apartment locator Austin TX"
- [ ] Rank page 1 for "apartment locator Austin"
- [ ] Rank for neighborhood-specific terms (e.g. "apartments South Congress Austin")
- [ ] Rank for deal-seeking terms (e.g. "Austin apartments move-in specials 2025")
- [ ] Google Business Profile linked and consistent with site NAP
- [ ] Meta titles and descriptions optimized on every page
- [ ] Schema markup for local business

### Content Goals
- [ ] Property specials section — updated regularly, no property names shown (see Rules)
- [ ] Rent calculator — clean, functional, shows savings from concession deals
- [ ] Blog / neighborhood guides — SEO content targeting Austin renter searches
- [ ] Testimonials / social proof section

---

## Ideal Page Structure (Home Page)

Rebuild the home page in this order top to bottom:

1. **Hero Section**
   - Headline: speaks directly to Austin renters looking for deals
   - Subheadline: explains the free service in one sentence
   - PRIMARY CTA button: "Text Me Now — It's Free" → sms:9727547790
   - Secondary link: "Fill Out My Intake Form" → Google Form URL

2. **How It Works** (3 simple steps)
   - Step 1: Tell me what you need
   - Step 2: I find the best deals in Austin
   - Step 3: You move in — you pay nothing

3. **Current Deals / Specials**
   - Show active concession deals by neighborhood
   - NO property names — show area, price, deal, and CTA to text for details
   - Each card has a "Text Me About This" button → sms:9727547790

4. **Rent Calculator**
   - Input: original rent + weeks free + lease term
   - Output: effective monthly rent after concession
   - CTA below calculator: "Want deals like this? Text me."

5. **Why Use a Locator**
   - Explain why renters benefit — saves time, saves money, no cost
   - Reinforce the licensed agent credibility

6. **About Taylor**
   - Short, personal, warm — not corporate
   - Photo if available
   - Emphasize: local expert, fast responder, human connection

7. **Testimonials**
   - 3-5 short client quotes
   - If none yet, leave placeholder with TODO comment

8. **Final CTA Section**
   - Big, bold, full-width
   - "Ready to find your place? Text me now."
   - Button: sms:9727547790

9. **Footer**
   - Name, phone, email, license info
   - Links to all pages

---

## Rules — Always Follow These

### Never Do
- **Never name a specific apartment complex or property** — this lets visitors bypass Taylor
  and go straight to the leasing office. Describe the area and the deal only.
- Never give a full address or cross streets that would identify a specific building
- Never use the word "luxury" or "luxury living"
- Never make the phone number non-tappable on mobile — always use tel: or sms: links
- Never remove or bury the primary CTA
- Never break the existing HTML/CSS structure without confirming first
- Never commit directly to main branch — always work in a feature branch

### Always Do
- Keep the phone number 972-754-7790 accurate everywhere it appears
- Use `sms:9727547790` for text CTAs and `tel:9727547790` for call links
- Keep mobile experience the top priority — test every change at mobile viewport
- Write clean, commented HTML/CSS — this site may be handed to other developers
- Preserve the rent calculator functionality — it's a key differentiator
- Keep tone warm, local, and human — never corporate or generic

---

## Voice & Tone (for any copy written)
- Casual and direct — like a knowledgeable Austin local, not a salesperson
- First person — always "I" not "Taylor" or "we"
- Short sentences, short paragraphs
- Lead with the benefit to the renter
- Always explain that the service is free and the property pays
- Sign off as Taylor

---

## Git Workflow
- Main branch: `main` (production)
- Always create a feature branch for changes: `git checkout -b feature/description`
- Commit messages should be descriptive: `git commit -m "Add mobile CTA above fold"`
- Do not push directly to main without review

---

## File Structure Notes
- All work lives in: `~/Documents/Businesses/apartmentdealsaustin/`
- This repo should be cloned into that directory
- AI prompt files live in: `~/Documents/Businesses/apartmentdealsaustin/AI Tools/`

---

## Questions to Ask Before Making Changes
If anything is unclear, ask before building:
1. Does this change affect the primary CTA or phone number visibility?
2. Does this work on mobile?
3. Does this help or hurt SEO?
4. Does this move a visitor closer to texting 972-754-7790?
