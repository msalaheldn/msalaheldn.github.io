# msalaheldn.github.io

Personal academic website of Mohamed Salaheldeen. A single static page, with no build step.

- `index.html`: the home page
- `teaching.html`: course notes and exercise sheets (PDFs go in `assets/teaching/<course>/`)
- `assets/style.css`: shared styles
- `assets/Salaheldeen_CV.pdf`: the CV linked from the page
- `assets/knot.svg`: the trefoil favicon
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Editing

Open `index.html` and edit the text directly. Each talk, thesis or school is one `<li>` block, so copy an existing one and change it.

To link a PDF, such as talk notes or a thesis, put the file in `assets/` and add a link inside the entry's `meta` span, for example `<a href="assets/WRT_notes.pdf">Notes</a>`.

## Publishing

In the repository's **Settings → Pages**, set **Source** to "Deploy from a branch", with branch `main` and folder `/ (root)`.
