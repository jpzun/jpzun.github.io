# Juan Pablo Zúñiga — Hugo/Barks website

This is a complete Hugo website using the Barks academic theme. The theme is included in `themes/barks`, so no Git submodule is required.

## What to edit

- `content/_index.md`: biography, office, email, and research interests.
- `content/research.md`: publications, preprints, and research software.
- `content/talks.md`: invited talks and posters.
- `config.toml`: site address and general settings; the arXiv and Google Scholar profile links are already configured.
- `static/images/foto2.jpg`: profile photograph shown on the About me page.
- `static/files/CV_Juan_Pablo_Zuniga.pdf`: replace this file whenever you update your CV.
- `static/files/Poster_SRI.pdf`: the poster linked from the Talks page.

To use another profile photograph, place it in `static/images` and change this line in `content/_index.md`:

```yaml
image: "/images/foto2.jpg"
```

to:

```yaml
image: "/images/your-new-photo.jpg"
```

## Preview locally

Install Hugo Extended 0.128.0 or newer, then run:

```bash
hugo server
```

Open the local address printed by Hugo.

## Publish with GitHub Pages

1. Upload the complete contents of this folder to the `main` branch of `jpzun.github.io`.
2. In **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Push a commit. The included workflow builds and publishes the site.

## Theme and license

The website uses Timothy Gebhard's Barks theme. Its original README and MIT license are retained in `themes/barks`.
