# Portfolio (local)

This is a simple static portfolio site. Below are quick instructions to run and update the resume section.

## Run locally

From the project root run a static server (example with Python):

```bash
python3 -m http.server 8000
```

Open the site at:

http://localhost:8000/portfolio-v2-with-modals.html

## Resume

- The site expects a file named `resume.pdf` in the project root.
- To update the resume, replace `resume.pdf` with your latest PDF file (keep the file name).
- The Resume section includes a "Download Resume" button and an embedded preview (iframe). Some browsers may block embedded PDF previews — downloading will still work.

## Notes / Next steps

- Accessibility: consider adding ARIA attributes and focus trapping for modals.
- Performance: move inline CSS to `styles.css` and minify for caching.
- Deployment: deploy to GitHub Pages / Netlify for a live URL.
