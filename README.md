# Xin Yao — personal homepage

Source of https://xyao2021.github.io/homepage/, a single-page academic
homepage written in plain HTML and CSS (no build step).

## Layout
- `index.html` — all page content: contact block, bio, news, research
  overview, publications, talks, posters, awards.
- `style.css` — colors, fonts and layout. The variables at the top of the
  file control the palette and sidebar width.
- `assets/profile.jpg` — profile photo (square, about 480 by 480 pixels).
- `assets/Xin_Yao_CV.pdf` — CV linked from the contact block.
- `.nojekyll` — tells GitHub Pages to serve the files as-is.

## Editing
Edit `index.html` directly. Each list (news, papers, talks) is a two-column
table: copy an existing `<tr>` row, change the date or tag in the first cell
and the text in the second. Update the "Last updated" line in the footer
when you make changes.

To replace the CV or photo, overwrite the file in `assets/` keeping the same
filename.

## Deploy
GitHub Pages is configured to serve the `main` branch. Every push to `main`
goes live one to two minutes later; no workflow is needed.

## Preview locally
```
python3 -m http.server 8000
```
Then open http://localhost:8000/.
