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
- Adjust colors and typography using the variables at the top of `stylesheet.css`.
- Keep publication figures in `images/`; the layout displays them without cropping.
- The profile photo is `images/peng.jpeg`.
- `Research_Reseme.pdf` is private reference material. Keep it ignored, unlinked, and out of commits and deployments. Do not disclose submission venues on the public page.
- Import any new bibliography entries verbatim from a trustworthy online source and maintain the required provenance log; never reconstruct or edit bibliography metadata by hand.
