# Interactive CV Presentation

A cinematic, single-file interactive presentation for **Mohammed Salah Deeb** — E-commerce Operations & Technical Support Specialist.

🔗 **GitHub Pages:** https://m7mm745.github.io/interactive-presentation/

🔗 **Cloudflare Pages:** https://m7mm745-interactive-presentation.mhamd77deep.workers.dev/

## Run locally

Open `index.html` in any modern browser. No build step or installation required.

## Features

- 8 data-driven slides: cover, snapshot, domains, comparison, journey, live scenarios, takeaways, contact
- Arabic (RTL) by default with a full English (LTR) switcher
- Dark / light themes, progress bar, slide counter, overview grid, fullscreen
- Keyboard arrows, mouse wheel, touch swipe, and on-screen navigation
- Animated KPI counters and three interactive scenario simulations
- Responsive from projectors down to mobile devices

## Deploy to Cloudflare Pages

With Wrangler installed and authenticated (`npx wrangler login`), run:

```bash
wrangler deploy
```

The deployed URL is configured in `wrangler.jsonc`.

## Customization

Edit the `CONFIG` and `SLIDES` objects near the top of the inline `<script>` in `index.html`. All content is bilingual via `{ ar, en }` pairs.

## Controls

| Action | Shortcut |
| --- | --- |
| Next / Previous | `→` / `←` (or wheel / swipe) |
| Overview grid | `O` |
| Fullscreen | `F` |
| Toggle theme | `T` |
| Toggle language | `L` |
