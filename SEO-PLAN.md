# SEO Plan — retivut.co.il

## Current Status

- **Site:** `https://retivut.pages.dev`
- **Target domain:** `https://retivut.co.il`
- **Niche:** איתור נזילות בלבד
- **City:** מודיעין-מכבים-רעות
- **Primary query:** `איתור נזילות במודיעין`
- **Primary conversion:** WhatsApp / phone / short form

The site is live on Cloudflare Pages. The only current launch blocker for the real domain is the registrar-side nameserver update at Internic.

Required nameservers:

```text
cortney.ns.cloudflare.com
nero.ns.cloudflare.com
```

Do not start Google Search Console work until the domain resolves through Cloudflare.

---

## Strategy

This is not a pure long-cycle SEO project.

The right path is **local lead-gen validation first, SEO compounding underneath**:

1. Get the domain live.
2. Get Google to index the page.
3. Capture and log every lead.
4. Use small Google Ads spend to prove demand before organic SEO matures.
5. Build local SEO assets only after the first page is technically clean and converting.

SEO alone will probably not produce meaningful leads in the first 60 days. That is fine. The SEO work should make the site stronger over months while ads and outreach prove the business model faster.

---

## Target Keywords

### Main Money Keywords

- `איתור נזילות במודיעין`
- `איתור נזילות מודיעין`
- `איתור נזילות מים במודיעין`
- `איתור נזילה במודיעין`
- `מאתר נזילות במודיעין`
- `איתור נזילות ללא הרס במודיעין`
- `איתור נזילות במצלמה טרמית מודיעין`

### Problem-Aware Long Tail

- `רטיבות בקיר מודיעין`
- `נזילה סמויה מודיעין`
- `חשבון מים גבוה מודיעין`
- `כתמי רטיבות בקיר מודיעין`
- `בדיקת רטיבות במודיעין`
- `דוח איתור נזילות לביטוח מודיעין`

### Nearby Area Terms

Use only after the main page is indexed and stable:

- `איתור נזילות במכבים`
- `איתור נזילות ברעות`
- `איתור נזילות בבוכמן`
- `איתור נזילות בכרמים`
- `איתור נזילות בכפר רות`

---

## Technical SEO Checklist

### Already Present

- Title tag focused on `איתור נזילות במודיעין`
- Meta description
- Canonical URL for `https://retivut.co.il/`
- `LocalBusiness` JSON-LD
- Mobile-friendly static page
- Fast Cloudflare Pages hosting

### Add After Domain Works

- `robots.txt`
- `sitemap.xml`
- Google Search Console domain property
- Submit sitemap in GSC
- Inspect `https://retivut.co.il/` and request indexing
- Run Google Rich Results Test for the schema
- Run PageSpeed Insights on mobile

### Schema Improvements

Current schema is a good start. Later improve it with:

- `OpeningHoursSpecification` if we define service hours
- `areaServed` as a list: מודיעין, מכבים, רעות, כפר רות
- `hasOfferCatalog` or `Service` for איתור נזילות
- `sameAs` links after citations/Facebook exist

Do not invent a physical address or fake Google Business Profile.

---

## Content Plan

### Phase 1 — Improve The Current Page

Goal: make the main page less generic and more locally convincing.

Tasks:

- Rewrite 2-3 sections with specific Modiin language.
- Mention local areas naturally: בוכמן, הכרמים, מכבים, רעות, כפר רות.
- Add real scenarios:
  - חשבון מים שקפץ פתאום
  - רטיבות ליד מקלחת
  - קיר שמתנפח אחרי כמה שבועות
  - ריח טחב בארון / חדר שירות
- Add stronger scope clarity: detection first, not generic plumbing.
- Add 3-5 more FAQs.

Suggested FAQ additions:

- כמה עולה איתור נזילות במודיעין?
- האם אפשר לאתר נזילה בלי לשבור קיר?
- האם מקבלים דוח לביטוח?
- כמה זמן לוקחת בדיקת איתור נזילה?
- מה עושים אם חשבון המים קפץ אבל לא רואים נזילה?

### Phase 2 — First Supporting Pages

Ship one page at a time. Do not create dozens of thin city pages.

Recommended first pages:

1. `חשבון מים גבוה במודיעין — איך בודקים אם יש נזילה סמויה`
2. `איתור נזילות במכבים ורעות`
3. `כמה עולה איתור נזילות במודיעין`

Each page must:

- Answer a real question.
- Link back to the main page.
- Include a clear CTA.
- Avoid copy-paste city-template language.

### Phase 3 — Case-Study Style Content

Once real leads arrive, turn anonymized patterns into content:

- “רטיבות בקיר ליד מקלחת — מה בודקים קודם”
- “חשבון מים חריג בלי סימן נראה לעין”
- “איך יודעים אם צריך מאתר נזילות או אינסטלטור”

No fake case studies. Use only real patterns, anonymized.

---

## Local Citations

After the domain works, create consistent listings.

NAP must be identical everywhere:

- **Name:** רטיבות — איתור נזילות במודיעין
- **Phone:** 055-290-7103
- **Area:** מודיעין-מכבים-רעות
- **Website:** `https://retivut.co.il`

Priority:

1. B144
2. d.co.il / דפי זהב, if free listing exists
3. easy.co.il
4. Facebook page
5. Modiin local portals, if they allow business listings
6. Midrag / Pro only if relevant and legitimate

Do not create fake addresses.

Google Business Profile is deferred until there is a real operator/business presence that can be verified.

---

## Google Search Console

Do this only after `retivut.co.il` resolves correctly.

1. Add domain property: `retivut.co.il`.
2. Verify through Cloudflare DNS TXT.
3. Submit sitemap.
4. Inspect the homepage and request indexing.
5. Check coverage after 48-72 hours.

Initial queries to monitor:

- `איתור נזילות במודיעין`
- `איתור נזילות מודיעין`
- `רטיבות בקיר מודיעין`
- `חשבון מים גבוה מודיעין`

Early success is impressions, not rankings.

---

## Google Ads As Proof Engine

SEO is slow. Ads are for proof.

Start only after:

- domain works,
- form is tested,
- WhatsApp and phone work,
- lead logging is ready.

Initial campaign:

- Search only
- Hebrew
- Modiin + 15km radius
- Budget: about ₪70/day
- Exact/phrase match around the main keywords

Negative keywords:

- עבודה
- קורס
- מדריך
- עשה זאת בעצמך
- חינם
- עירייה
- אינסטלטור
- סתימה
- משכורת

Track:

- phone clicks
- WhatsApp clicks
- form submits
- qualified lead rate

The goal is not ad optimization perfection. The goal is to prove whether people in Modiin actually contact this page for leak detection.

---

## Lead Logging

Every contact must be logged.

Minimum fields:

- date
- source: organic / ads / direct / unknown
- name
- phone
- city
- issue summary
- qualified: yes/no
- status
- notes

Qualified lead:

- in service area
- leak / hidden moisture / water damage diagnosis need
- real phone number
- not spam
- not duplicate

---

## 60-Day Targets

### Day 14

- Domain live
- GSC verified
- Homepage indexed or submitted
- Ads test running or ready
- 3+ qualified contacts if ads are active

### Day 30

- 10+ qualified contacts cumulative
- first citations created
- first supporting content page published
- operator prospect list prepared

### Day 60

- 20+ qualified contacts cumulative, or enough data to pivot
- one operator pilot running or clear reason why not
- GSC impressions visible for the core query

---

## Weekly Rhythm

Sunday:

- Review leads and source quality.
- Check GSC queries.
- Ship one SEO task.

Daily if ads are running:

- Check search terms.
- Add obvious negatives.
- Log every call/WhatsApp/form.

Thursday:

- Review whether the week produced enough proof to continue.

---

## Current Next Actions

1. Wait for Internic/registrar to fix nameserver status.
2. Confirm `retivut.co.il` resolves through Cloudflare.
3. Add `robots.txt` and `sitemap.xml`.
4. Verify Google Search Console.
5. Submit homepage for indexing.
6. Rewrite current page with stronger local Modiin language.
7. Prepare Google Ads only after tracking/logging is ready.

