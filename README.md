# hello-world
This file is updated on 30/06/2022
This is the test file....
First code to be merged...

# HTML Best Practices Showcase

A single-page site demonstrating modern, accessible, and performant HTML — hosted on GitHub Pages.

🔗 **Live site:** https://yourusername.github.io/repo-name/

## What this demonstrates

- Semantic HTML5 landmarks (`header`, `nav`, `main`, `section`, `article`, `footer`)
- Proper document metadata (charset, viewport, SEO tags, Open Graph/Twitter cards)
- Accessibility: skip link, labeled form inputs, `aria-labelledby`, logical heading hierarchy
- Responsive images via `srcset`/`sizes`, with `loading="lazy"` and explicit dimensions
- Performance-conscious script loading (`defer`)
- Valid, standards-compliant markup (see [Validation](#validation))

## Project structure
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── images, icons, etc.
└── README.md

## Running locally

No build step required.

```bash
git clone https://github.com/yourusername/repo-name.git
cd repo-name
# open index.html in a browser, or serve it:
python3 -m http.server
```

## Validation

This page is checked against:
- [W3C HTML Validator](https://validator.w3.org/)
- [WAVE Accessibility Evaluation Tool](https://wave.webaim.org/)
- Lighthouse (Performance/Accessibility/SEO/Best Practices)

## Deployment

Served via GitHub Pages from the `main` branch, root folder.
Settings → Pages → Source: `main` / `(root)`.

## License

MIT
