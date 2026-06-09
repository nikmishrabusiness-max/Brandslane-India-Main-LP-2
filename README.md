# Brandslane India — Main Landing Page

Editorial redesign of the Brandslane India landing page and its supporting pages. Pure static HTML/CSS/JS — no build step, no dependencies. All media (images + videos) is self-hosted under `Content/`.

## Pages

| Page | File |
|------|------|
| Landing page | `index.html` |
| Contact | `contact-us.html` |
| Privacy Policy | `privacy-policy.html` |
| Refund Policy | `refund-policy.html` |
| Terms & Conditions | `terms-and-conditions.html` |
| Thank-you (post-booking) | `typage.html` |

## Assets

```
Content/
├── logos/        brand client logos
├── partners/     platform partner logos
├── case-studies/ case-study images
├── dashboards/   paid-ads dashboard screenshots
├── creatives/    performance-creative stills
├── why/          "Why & When" card images
├── charts/       growth chart
└── videos/       reel + creative .mp4 files and poster thumbnails
```

## Run locally

```bash
python3 -m http.server 8000
# then open http://127.0.0.1:8000/
```

## Design system

- **Type:** Geist (UI/headlines), Instrument Serif (italic accents), JetBrains Mono (labels) — loaded from Google Fonts
- **Palette:** warm off-white `#F4F1EB` base, ink `#14110C`, accent `#E5482A`
