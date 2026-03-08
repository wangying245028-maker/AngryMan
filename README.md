# AngryMan Website

## Structure

```
website/
├── index.html          # landing page
├── privacy.html        # privacy policy
├── terms.html          # terms of service
├── styles.css          # styles
├── script.js           # interactions
├── assets/
│   └── icon/
│       └── app_icon.png
└── README.md
```

## Product

AngryMan is a personal safety app designed for women living alone:
- AI voice transformation into multiple assertive male character styles
- One-tap simulated incoming call flow
- Scenario settings for different risk environments
- Fully on-device, no cloud privacy exposure, no personal data collection

## Pages

- `index.html`: product overview and core features
- `privacy.html`: on-device and zero-collection privacy policy
- `terms.html`: usage boundary and service scope

## Tech

- Responsive layout for mobile and desktop
- Modern CSS with Flexbox/Grid
- Lightweight JavaScript interactions
- Semantic HTML and metadata for SEO

## Deployment (GitHub Pages)

1. Push to `main` to trigger `.github/workflows/deploy.yml`
2. In repository Settings -> Pages, choose `GitHub Actions` as Source
3. Site URL: `https://wangying245028-maker.github.io/AngryMan/`

## Local Preview

1. Open the website directory
2. Start a local server, e.g. `python -m http.server 8000`
3. Visit `http://localhost:8000`

## 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Copyright

Website content is copyright protected by AngryMan.
