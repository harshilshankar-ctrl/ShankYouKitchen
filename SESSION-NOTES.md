# Session Notes — July 16, 2026 (closeout)

## Brand (final)
- Name: **Shank You Very Much** · Tagline: **"The best thing in your fridge."**
- Chef Harshil Shankar · Fresno & Clovis · No "Central Valley" in branding
- Voice: elegant with one wink (italic *You*). No supper-club vibe — home, not restaurant.
- Palette: warm ivory + terracotta (delivery) / espresso + gold (custom) / leaf green (freshness). Fonts: Cormorant Garamond, Inter, Caveat.

## Site structure (index.html — single file, complete)
- **Gate**: full-screen, no scroll, two doors only. Delivery = 6-tile food collage; Custom = warm 2-shot kitchen. Buttons centered/symmetric, hover pop, no photo zoom. Logo / "see the other side" reopens gate.
- **Two strict paths** — never visible together:
  - Weekly Table: set chef's menu (soup star, salad, dressing, 1 lb tiger shrimp + 1 lb steak + 1–2 lbs fish, couscous carb, fruit), fridge-first cards (packed in parts, sauced & carded, glass/deli), polaroids, 30-second signup with 20-min time chips (Sunday 6:00–7:40).
  - In-Home Chef: invitation, talk→shop→cook (cleaning included), "good food is expensive. it's supposed to be.", consultation form.
- Shared: letter from Harshil, footer. Deep links (#weekly-signup, #chef-form) skip gate onto right path.

## Business decisions
- Weekly Table: **$300–500/wk** by household size. One evening, one route, no customization ever (that's what Custom is for). Portion slightly under. Week-to-week, skip freely, no subscription.
- In-Home: groceries at cost + $200–350 session fee, quote only after consultation.
- Market (researched): Fresno competition is $10–15/meal tray prep; chef weeks run $600–1,100+. We sit in the empty middle. Protein trend data supports the basket.

## To edit before launch (config block, bottom of index.html)
`BUSINESS_EMAIL` · `BUSINESS_PHONE` · `FORMSPREE_ID` (formspree.io, free) · `DELIVERY_DAY` / `DELIVERY_TIMES` (delete a time when claimed) · `SLOTS_REMAINING`
Forms fall back to pre-filled email until Formspree ID exists.

## Photos (photos/README.txt = full shot brief)
soup (hero), containers, fridge close-up, prep, steak (no fries), salmon, chef kitchen (no people), counter, ribeye, salad. Rules: no fries, **no wine glasses ever**, no people. Stock placeholders load until real files dropped in.

## Parked for next session
- **Domain**: buy shankyouverymuch.com (+ chefshankar.com redirect). Fallbacks: shankyou.kitchen, eatshankyou.com.
- Deploy: Netlify Drop (drag folder at app.netlify.com/drop) + QR code for event table.
- Legal/structure: LLC, food handler cert, county cottage-food rules, liability insurance — before charging strangers.
- Retention loop: Thursday opt-in text ("In for Sunday?"), waitlist backfill, seasonal menu resets. (Details in LAUNCH-PLAN.md.)

## Files
`index.html` (the site) · `LAUNCH-PLAN.md` (strategy, market research, pricing, retention, checklist) · `photos/README.txt` (shot list) · `SESSION-NOTES.md` (this file)
