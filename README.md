# Dr. Qunish Dash — Physiotherapy Website

A minimal, new-age landing page for Dr. Qunish Dash, Consultant Physiotherapist.

## Stack
- Pure HTML / CSS / JS — zero build step, zero dependencies
- Google Fonts (Cormorant Garamond + Outfit) loaded via CDN
- WhatsApp deep link as the sole booking CTA

## Deploy to Vercel (via GitHub)

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import from GitHub
3. Select the repo — Vercel auto-detects it as a static site
4. Click **Deploy** — done

No build command or output directory needed.

## Customise

### Replace the doctor photo
In `index.html`, find the `<div class="hero-image-frame">` block and replace the `<svg>` placeholder with:
```html
<img src="./photo.jpg" alt="Dr. Qunish Dash" />
```
Put `photo.jpg` in the same folder. Recommended: a transparent-background PNG of the doctor, cropped from the waist up.

### Change the WhatsApp number
Search for `wa.me/918217021530` and update the number (country code + phone, no spaces or dashes).

### Change the phone number display
Search for `+91 82170 21530` in the HTML.

## File Structure
```
dr-qunish-dash/
├── index.html      ← entire site
├── vercel.json     ← Vercel routing config
└── README.md
```
