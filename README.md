# Floare de Cireș — Catering

Static landing page for Floare de Cireș Catering (Chișinău, Moldova), a social
enterprise catering service. Bilingual RO / EN.

## Contents

- `index.html` — the complete site. Self-contained: fonts, images and scripts
  are all embedded, so there are no external asset requests at runtime.
- `vercel.json` — static deployment config (no build step).

## Local preview

Open `index.html` in a browser, or serve the directory:

```sh
python3 -m http.server 8000
```

## Deployment

Deployed on Vercel as a static site. Pushes to the connected branch publish
automatically; no build command runs.
