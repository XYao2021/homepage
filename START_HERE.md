# Xin Yao's homepage — how to maintain it

This site uses the [Academic Pages](https://academicpages.github.io/)
template (Jekyll, MIT-licensed), the most widely used template for academic
personal websites. It is served at https://xyao2021.github.io/homepage/.

## Deploy
Every push to the `main` branch of `XYao2021/homepage` runs the GitHub
Actions workflow in `.github/workflows/deploy.yml`, which builds the site and
publishes it to the `gh-pages` branch. Changes are live one to two minutes
after the push.

## Profile links
Google Scholar, LinkedIn and GitHub are set in the `author:` block of
`_config.yml`. Add `orcid` there if you get an ORCID.

## Ongoing edits
- **Publications:** copy a file in `_publications/`, name it
  `YYYY-MM-DD-short-title.md`, and fill in the fields.
  `category: manuscripts` → Journal Articles, `category: conferences` →
  Conference Papers. Add `paperurl` (DOI link) when available.
  The FORGE-LoRa entry still needs the conference name once it is announced.
- **Talks:** same pattern in `_talks/`.
- **Projects:** edit the files in `_portfolio/`; add photos to `images/`.
- **News:** edit the News list at the bottom of `_pages/about.md`.
- **CV:** edit `_pages/cv.md`; the PDF download button points to
  `files/Xin_Yao_CV.pdf`. Upload a new PDF with the same filename to update it.
- **Photo:** replace `images/profile.png` with a square image of the same name.
- Teaching and Blog pages are hidden from the menu; re-enable them in
  `_data/navigation.yml` when you have content.

## Preview locally
With Docker installed: `docker compose up`, then open
http://localhost:4000/homepage/.
