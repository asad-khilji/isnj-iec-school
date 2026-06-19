# ISNJ IEC School Static Site

This version replaces the PHP/MySQL site with HTML, CSS, JavaScript, and JSON.

## Files

- `index.html` — home page
- `about.html`, `admissions.html`, `tuition.html`, `documents.html`, `contact.html` — public pages
- `admin.html` — browser-only JSON editor for quick previews
- `data/site.json` — editable site content
- `assets/css/style.css` — styles
- `assets/js/app.js` — rendering and form behavior

## Run locally

Because the JavaScript loads `data/site.json`, use a local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Important static-site note

Forms are saved to the browser's localStorage for demo purposes. To receive submissions by email or store them online, connect a form service such as Netlify Forms, Formspree, or a custom backend.
