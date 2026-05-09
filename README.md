# Sacred Sounds of India

A small Dutch knowledge channel for Hindustani classical music — a curated guide
to good teachers and good concerts of Indian classical music in the Netherlands,
plus a short primer on the tradition.

We don't teach. We don't perform. We just point you to people who do it well.

## Stack

- Single static `index.html`
- Tailwind via CDN
- Cormorant Garamond + Outfit + Tiro Devanagari Sanskrit (Google Fonts)

## Local preview

Open `index.html` directly in a browser, or serve it from any static server:

```sh
python3 -m http.server 3000
```

## Deploy

Hosted on Cloudflare Pages. To redeploy:

```sh
wrangler pages deploy . --project-name=sacred-sounds-of-india
```
