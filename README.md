# Landing Page Prototype

## Files
- `index.html` , the landing page
- `styles.css` , the styling
- `config.js` , live editable config
- `config.example.js` , starter template

## Current target
- **Niche:** leak detection only
- **City:** Modiin (מודיעין-מכבים-רעות)
- **Domain:** `retivut.co.il`
- **Phone:** 055-290-7103 (live, via 019)
- **WhatsApp:** active on same number

## Before publishing
Edit `config.js` — phone and WhatsApp are already wired. The only remaining value to fill:
- `formAction` — paste your Formspree, Tally, or webhook URL here once the form is set up

## Scope note
Keep the site positioned around **diagnosis / detection**.
Do not blur it into a generic plumbing page unless we later choose to expand.

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
