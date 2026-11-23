# Hedwig Nora Nordlinder — academic homepage

A minimalist, responsive academic homepage, hosted with GitHub Pages at
<https://hedwignordlinder.github.io/>. The homepage is plain HTML and CSS in
`index.html`; no build step or dependencies are needed.

## Updating the homepage

- Edit the biography, research interests, education, and contact information
  directly in `index.html`.
- Add `photo.jpg` to the repository root and replace the photograph placeholder
  with the `<img>` example in the adjacent HTML comment.
- Copy a `<li>...</li>` block under **Published / accepted** or **Preprints** for
  additional papers. Link titles to a DOI or preprint page, for example:

  ```html
  <a class="paper-title" href="https://doi.org/YOUR-DOI">Your paper title</a>
  ```

- Update the date in the footer when you make changes.

The paper list was checked against
[Google Scholar](https://scholar.google.com/citations?user=7M4EylUAAAAJ) on
23 November 2026. The two NeurIPS 2026 papers were also confirmed in the
[conference programme](https://neurips.cc/Downloads/2026). Paper titles and author
lists link to arXiv or bioRxiv; contact information comes from the public
[KI profile](https://ki.se/en/people/hedwig-nordlinder). These are static entries,
so new papers and changes in publication status need a manual update.

Example contact link:

```html
<a href="mailto:you@university.edu">you@university.edu</a>
```

## Preview locally

Open `index.html` directly, or serve the directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8000/>. Use the local server when checking old note
links, since the notes viewer loads their contents with `fetch`.

## Publish

GitHub Pages is configured to deploy the repository root from the `main` branch.
Commit and push changes to `main` to update the homepage. `.nojekyll` tells GitHub
Pages to serve these static files without Jekyll processing.

The existing `survival_analysis/` files are retained. Previously shared
`?md=...` links are forwarded to `notes.html`, which preserves the original notes
viewer. The homepage itself uses no external fonts, libraries, or tracking.
