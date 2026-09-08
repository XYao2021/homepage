# Xin Yao — personal homepage

Source of https://xyao2021.github.io/homepage/, a single-page academic
homepage written in plain HTML and CSS (no build step).

## Layout
- `docs/index.html` — all page content: contact block, bio, news,
  research overview, publications, talks, posters, awards.
- `docs/style.css` — colors, fonts and layout. The variables at the top of
  the file control the palette and sidebar width.
- `docs/assets/` — profile photo (`profile.jpg`) and CV (`Xin_Yao_CV.pdf`).

## Editing
Edit `docs/index.html` directly. Each list (news, papers, talks) is a
two-column table: copy an existing `<tr>` row, change the date or tag in the
first cell and the text in the second. Update the "Last updated" line in the
footer when you make changes.

To replace the CV, overwrite `docs/assets/Xin_Yao_CV.pdf` with the same
filename. To replace the photo, overwrite `docs/assets/profile.jpg`
(square, about 480 by 480 pixels).

## Deploy
Every push to `main` runs `.github/workflows/deploy.yml`, which publishes
`docs/` to the `gh-pages` branch. The site updates one to two minutes after
the push.

## Preview locally
```
python3 -m http.server 8000 --directory docs
```
Then open http://localhost:8000/.
