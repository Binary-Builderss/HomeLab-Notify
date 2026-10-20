# Homelab Notify website

Landing page, support and privacy policy for Homelab Notify, served by GitHub
Pages from `main` at https://binary-builderss.github.io/HomeLab-Notify/.

- `index.html`: landing page; `#support` is the App Store Support URL.
- `privacy.html`: privacy policy (English and Italian), the App Store Privacy
  Policy URL.
- `assets/`: logo, favicons and social image from the brand kit; screenshots
  from the iOS app's demo mode.
- `assets/fonts/`: Geist and Geist Mono (SIL Open Font License, `OFL.txt`),
  self-hosted so visitors load nothing from third parties. Icons are Phosphor
  Light (MIT), inlined as an SVG sprite in `index.html`.

Plain HTML and CSS, no build step. Preview locally with
`python3 -m http.server` and open http://localhost:8000.
