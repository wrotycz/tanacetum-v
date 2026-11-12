# tanacetum-v

Single-page company website for **Kamil Węglarz Tanacetum V**, hosted on GitHub Pages.

## Structure

- `index.html` — page content
- `styles.css` — dark cyan theme with orange accents
- `.nojekyll` — serves files as-is, without Jekyll processing

No build step, no external requests.

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8000
```

and visit <http://localhost:8000>.

## Deployment

GitHub Pages serves this repository directly — branch `main`, root folder.
