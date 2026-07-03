# Landing Page Prototype

## Files
- `index.html` , the landing page
- `styles.css` , the styling
- `config.js` , live editable config
- `config.example.js` , starter template

## Current target
This prototype is now aligned to:
- **Niche:** leak detection only
- **City:** Beer Sheva
- **Selected domain:** `retivut.co.il`

## Before publishing
Edit `config.js` and replace:
- `siteUrl`
- `businessName`
- `phoneDisplay`
- `phoneHref`
- `whatsappNumber`
- `whatsappMessage`
- `serviceArea`
- `formAction`
- `allowIndexing` (`false` for staging, `true` only when the live site is really ready)

## Scope note
Keep the site positioned around **diagnosis / detection**.
Do not blur it into a generic plumbing page unless we later choose to expand.

## Staging safety
The page now ships with `noindex` by default.

That means:
- staging deployments are safe to review publicly
- search engines should not index the page yet
- only switch `allowIndexing` to `true` when the live domain, real intake, and final copy are in place

## Form setup
Right now the form is intentionally not connected.
Until `formAction` is filled, the page will warn and push people to phone or WhatsApp.

You can connect it to:
- Formspree
- Tally form endpoint
- a custom webhook
- your own backend

## Local preview
From this folder run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```
