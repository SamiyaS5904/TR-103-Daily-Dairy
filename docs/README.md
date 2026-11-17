# TR-103 Daily Diary — website

Plain HTML and CSS. No framework, no build step.

```
docs/
├── index.html      the site
├── style.css       the stylesheet
├── pdfs/           the eight weekly diary PDFs
├── certificates/   confirmation letter and certificate
└── assets/         logo
```

Open `index.html` in a browser to view it.

Published with GitHub Pages from this folder — **Settings → Pages → Branch:
`main`, Folder: `/docs`**. The folder must stay named `docs` or the site stops
publishing.

**Still to add** — put these into `certificates/`, then delete the italic
placeholder line in each card in `index.html`:

```
confirmation-letter.pdf
internship-certificate.pdf
```

After editing `style.css`, bump the `?v=` number on the stylesheet link in
`index.html` so browsers pick up the change.
