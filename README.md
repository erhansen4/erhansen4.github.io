# Eric R. Hansen — Academic Website, Version 3

A four-page static website for free hosting on GitHub Pages.

## Preview locally

Extract this ZIP file and open `index.html` in a web browser. Use the top navigation to see About, Research, Teaching, and CV. Some browsers will not render the embedded CV when opened via `file://` due to local PDF security settings; it will work when served from GitHub Pages or a local HTTP server. The Download CV link works independently.

## What is included

- `index.html`: scholar-focused homepage with actual headshot, original biography with one grammatical correction, and Contact Me section
- `research.html`: peer-reviewed articles transcribed from the attached CV (updated October 8, 2026)
- `teaching.html`: courses taught, as listed in the attached CV
- `cv.html`: embedded PDF CV plus download link
- `assets/headshot.jpg`: supplied professional headshot
- `assets/Hansen_CV.pdf`: supplied CV
- `styles.css`: styles for all pages
- `.nojekyll`: GitHub Pages compatibility

## Publish to GitHub Pages

1. Create a public GitHub repository called `YOURUSERNAME.github.io` (using your GitHub username).
2. Upload **the contents** of the extracted folder into the repository root, not the folder itself. Make sure `index.html` is at the top level.
3. In GitHub repo **Settings → Pages**, choose **Deploy from a branch**, then `main` and `/ (root)`.
4. Visit `https://YOURUSERNAME.github.io/` when deployed. The `CV` page will embed the PDF using the browser's built-in viewer.

GitHub documentation: https://docs.github.com/en/pages/quickstart

## Future updates

- Replace `assets/Hansen_CV.pdf` with a revised PDF (keep the same filename) whenever your CV changes.
- Change the homepage text in `index.html` as desired. The biography retains the wording from your previous site except for correcting “study on the relationship” to “study the relationship.” Edit the Contact Me details in the same file.
- Add/update publication blocks in `research.html`. References have no DOI links yet to avoid adding unverified links.
- Modify course entries in `teaching.html` as needed.
- The headshot is shown in a portrait crop; the unmodified original image is kept in `assets/headshot.jpg`.

Note: browsers and mobile devices vary in their support for inline PDF viewers, so the direct open/download options are retained for accessibility and reliability.
