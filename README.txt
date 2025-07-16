📘 JobZillaGov - Full Auto System (with Article Page Support)

1. Upload `index.html` to GitHub Pages
2. Create a Google Sheet with columns:
   section | title | slug | applyLink | pdfLink | lastDate | description

3. Make your Sheet PUBLIC (anyone with link can view)
4. Copy your Sheet ID and replace in `index.html` at:
   https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/gviz/tq?tqx=out:json

5. For each job (row in Sheet), duplicate `job-template.html` and rename to `slug.html`
6. Replace {{...}} values with the real job content

You’re done! 🚀 Your site is now fully automatic and article-ready.
