# Blue Compile – Website

Marketing site for **Blue Compile**, a software development studio.
Static HTML/CSS/JS, no build step. Hebrew, RTL.

## Files
- `index.html` – page content and sections
- `styles.css` – design tokens (`:root`) and layout
- `hero3d.js` – animated 3D particle hero (canvas, no dependencies)
- `main.js` – footer year and contact-form handling

## Run locally
Open `index.html` in a browser, or:

```bash
npx serve .
```

## Before launch
- Replace every `[placeholder]` (stats, projects, testimonials, phone, response time)
- Connect the contact form to a backend (e.g. Formspree or Web3Forms) via the form's `action`
- Add privacy policy and accessibility statement pages
- Add favicon and an Open Graph image

## Deploy
Works as-is on GitHub Pages, Vercel or Netlify. Point `bluecompile.com` at the host.
