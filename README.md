# Sophireak Soeng — Portfolio

Personal portfolio website. Modern minimal design with dark mode, live GitHub project feed, and contact form.

**Live site:** https://sophireaks.github.io/portfolio (update after deploy)

## Stack
- Single-file HTML, CSS, JavaScript (no build step)
- GitHub REST API for live project cards
- Formspree for contact form submissions

## Local preview
Just open `index.html` in your browser. That's it.

## Deploy to GitHub Pages (free hosting)
See `DEPLOY.md` for step-by-step instructions.

## Configuration
Open `index.html` and search for `Config (EDIT ME)`:

```js
const GITHUB_USER = "sophireak";       // your GitHub username
const FORMSPREE_ID = "YOUR_FORM_ID";   // get one at formspree.io
```

## Customize
- **Resume:** drop your `resume.pdf` next to `index.html`
- **Social links:** edit the `<a class="social-link">` URLs in the contact section
- **Bio / skills:** edit the text in the About and Skills sections
- **Projects:** auto-pulled from your GitHub — just push code to public repos

---

Built with care. Secured by design.
