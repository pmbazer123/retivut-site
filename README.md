# Retivut Landing Page

## Files
- `index.html` , the landing page
- `styles.css` , the styling
- `config.js` , live editable config
- `config.example.js` , starter template
- `SEO-PLAN.md` , current SEO and rollout plan

## Current target
- **Niche:** leak detection only
- **City:** Modiin (מודיעין-מכבים-רעות)
- **Domain:** `retivut.co.il`
- **Phone:** 055-290-7103 (live, via 019)
- **WhatsApp:** active on same number

## Live configuration
Edit `config.js` for business details. Current live values are already wired:
- phone / WhatsApp: `055-290-7103`
- lead form: Formspree endpoint in `formAction`
- canonical domain: `https://retivut.co.il/`

## Scope note
Keep the site positioned around **diagnosis / detection**.
Do not blur it into a generic plumbing page unless we later choose to expand.

## Hosting
Source repo: `pmbazer123/retivut-site`.

Cloudflare Pages project: `retivut`.

Temporary Pages URL:

```text
https://retivut.pages.dev
```

Custom domains:
- `retivut.co.il`
- `www.retivut.co.il`

The custom domains depend on the registrar nameservers pointing to the active Cloudflare zone.

## Local preview
From this folder run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```
