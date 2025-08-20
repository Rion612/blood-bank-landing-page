# Lifeline Blood Bank Landing Page

A responsive, single-page landing site for a blood donation initiative. All graphics (logo and hero) are generated with inline SVG, so no external images are required.

## Features
- Modern, responsive layout with semantic HTML
- Sticky header, announcement bar, and strong primary CTA
- Sections: Hero, Why Donate, How it Works, Eligibility, Camps, Registration, FAQ, Footer
- Accessible color contrast, focus styles, and ARIA-friendly structure
- No external JS frameworks; one tiny inline script for the year

## Structure
- `index.html` — page markup and inline SVG artwork
- `styles.css` — theme variables, layout, responsive styles

## Run locally
Open `index.html` directly in your browser, or serve the folder:

```bash
# From the project folder
python -m http.server 5500  # if Python is installed
```

Then visit http://localhost:5500 in your browser.

## Customize
- Colors: tweak CSS variables in `:root`
- Text: edit copy directly in `index.html`
- Logo/Hero: adjust inline SVGs for shapes and gradients

## Notes
This is a static demo and the registration form is non-functional. Hook it up to your backend or a form service to capture submissions.
