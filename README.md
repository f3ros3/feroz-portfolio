# Feroz — Data & Quality Analyst Portfolio

A single-page portfolio site built with plain HTML, CSS, and JavaScript — no build step, no dependencies to install. Features a liquid-glass navigation bar, an animated "live dashboard" hero, a work experience timeline, a tech stack section with scattered gaussian-blurred logos, and a contact section with a glass-style "Get in Touch" form and social links.

**Live demo:** _add your GitHub Pages link here once deployed, e.g. `https://<your-username>.github.io/<repo-name>/`_

## What's inside

- `index.html` — the entire site (HTML, CSS, and JS are all in this one file)

## Tech used

- HTML5 / CSS3 (backdrop-filter glassmorphism, CSS animations & keyframes)
- Vanilla JavaScript (tab navigation, count-up KPIs, scattered tech badges, form handling)
- [Google Fonts](https://fonts.google.com/) — Sora, Inter, JetBrains Mono
- [Font Awesome](https://fontawesome.com/) (via CDN) — icons

No frameworks, no npm install, no build process. Open the file and it works.

## Running it locally

Just double-click `index.html`, or open it in your browser directly. For a closer-to-production preview (some browsers restrict certain features on `file://` URLs), serve it locally instead:

```bash
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Publishing on GitHub Pages

See the step-by-step deployment guide in the chat where this file was generated, or follow these steps:

1. Create a new repository on GitHub (public).
2. Push this folder's contents to the repository's `main` branch, with `index.html` at the repo root.
3. In the repo, go to **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`, then **Save**.
4. Wait 1–2 minutes, then visit `https://<your-username>.github.io/<repo-name>/`.

## Customizing

- **Contact form:** the "Get in Touch" form is front-end only right now — submitting it just shows a local confirmation message, it does not send an email anywhere. To make it functional, connect it to a service like [Formspree](https://formspree.io/) or [EmailJS](https://www.emailjs.com/) (both offer free tiers and require only a few lines of change in the form's `action`/JS).
- **Social links:** update the `href="#"` attributes in the Contact section with your real Instagram, LinkedIn, GitHub, and Facebook URLs.
- **Work experience dates:** update the placeholder "Add your dates" text in the Experience section.
- **Colors/fonts:** all design tokens (colors, radii, easing) are defined as CSS custom properties at the top of the `<style>` block in `index.html` under `:root`.

## License

Personal portfolio — feel free to fork the structure/approach for your own site, but please don't reuse the personal content as-is.
