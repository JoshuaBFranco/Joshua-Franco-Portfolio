# Joshua Franco — Portfolio

Personal portfolio site. Single-page Bootstrap 5 build covering my background,
resume, and project work.

**Live:** https://joshuafranco.netlify.app

## Stack

- HTML5 / CSS3 / JavaScript
- Bootstrap 5
- AOS, Isotope, Typed.js, Swiper
- Netlify (hosting + form handling)

## Structure

```
index.html        Single-page site — all sections live here
thanks.html       Post-submission confirmation page
netlify.toml      Deploy config and cache headers
assets/
  css/main.css    Template styles
  js/main.js      Nav scroll, filtering, animations
  img/            Photos and project thumbnails
  vendor/         Bootstrap and JS libraries
```

## Local development

No build step. Open `index.html` directly, or use the VS Code Live Server
extension for auto-reload.

## Deploying

Connected to Netlify. Pushing to `main` triggers a deploy automatically.

## Contact form

Handled by Netlify Forms via the `data-netlify="true"` attribute on the form in
`index.html`. Submissions appear under **Forms** in the Netlify dashboard.
A honeypot field filters bot traffic.

## Credits

Built on the Craftivo template by BootstrapMade.
