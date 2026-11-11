# Jam Studio Photography — Cinematic 3D Portfolio

Immersive dark portfolio for **Jam Studio Photography** ([@jam_studio_official.pk](https://www.instagram.com/jam_studio_official.pk/)) — Rahim Yar Khan & Sadiqabad, Pakistan.
Weddings · Portraits · Events & Family · Editorial.

## Preview it on GitHub Pages (2 minutes, no build step)

1. Create a new repository on github.com (e.g. `jam-studio`).
2. Upload `index.html` (and this README) to the repo root — drag & drop works.
3. Repo **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
4. Your site is live at `https://<username>.github.io/jam-studio/` within ~1 minute.

Everything is in the single `index.html` — no build, no dependencies to install, works offline of any bundler. Fonts + photos load from CDNs.

## ★ Before going live for real clients — 2 edits in `index.html` (search `CONFIG`)

1. **WhatsApp number** — set `WHATSAPP_NUMBER` (digits only, international format, e.g. `923001234567`).
   Until then, booking buttons safely open the Instagram profile instead of a wrong/fake number, and the booking form copies the message + opens Instagram DM.
2. **Real photos** — replace the `src` values in the `PHOTOS` list with Jam Studio's own photographs.
   Drop the files into an `images/` folder and use `images/your-photo.jpg`. Categories: `wedding`, `portrait`, `event`, `editorial` — these drive the reel, the archive filters and the lightbox.

## What's inside

- Cinematic hero: perspective grid floor, layered realistic camera lens (engraved markings, glass, reflections, mouse parallax)
- Infinite curved 3D reel: continuous loop, hover focus (hovered photo enlarges, neighbours lift, rest dim), drag / scroll to scrub, click opens full-screen lightbox that **pauses the reel in place** and resumes from the same spot (Esc to close)
- Archive with category filters, pricing as honest "Request a Quote" (no invented prices), WhatsApp booking form (service + date + name + phone → pre-written WhatsApp message)
- Fully responsive, reduced-motion support, SEO + Open Graph meta
