# Peng Kuang's personal website

A responsive, static academic homepage for [Peng Kuang](https://krumperisok.github.io/), built with semantic HTML and CSS. No JavaScript, build step, or external font downloads are required.

## Preview locally

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Then visit `http://127.0.0.1:4173`.

## Updating the page

- Edit the biography, profile links, and publication content in `index.html`.
- Add news items to the `news-list` in `index.html`, newest first. Use confirmed milestone or announcement months in both the visible date and `<time datetime="YYYY-MM">`, or just `YYYY` when the month is unknown. Keep news focused on 2026 onward, conference publications, and career milestones; omit preprint announcements. Show up to five recent entries and place older updates in “Earlier news.” Conference publication updates use the conference month, not an inferred acceptance date.
- Adjust colors and typography using the variables at the top of `stylesheet.css`.
- Keep publication figures in `images/`; the layout displays them without cropping.
- The profile photo is `images/peng.jpeg`.
- `Research_Reseme*.pdf` files are private reference material. Keep them ignored, unlinked, and out of commits and deployments. Do not disclose submission venues on the public page.
- Import any new bibliography entries verbatim from a trustworthy online source and maintain the required provenance log; never reconstruct or edit bibliography metadata by hand.
- Official citation exports for the October 2026 publication update are in `_bibliography/`, with source URLs, retrieval dates, and SHA-256 checksums in `_bibliography/provenance.json`. These files are excluded from the built site. KV-PRM's NeurIPS 2026 venue label follows the author-provided résumé; its arXiv citation export is preserved unchanged.
