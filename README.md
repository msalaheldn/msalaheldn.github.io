# msalaheldn.github.io

Personal academic website of Mohamed Salaheldeen. Plain static HTML with no build step, served by GitHub Pages.

| File | Page |
| --- | --- |
| `index.html` | Home: research statement, diagram, interests, profile |
| `research.html` | Current project, theses, seminars, earlier research, education |
| `talks.html` | Talks, schools and masterclasses |
| `teaching.html` | Course notes and exercise sheets |
| `interests.html` | Other interests |
| `assets/style.css` | Shared styles |
| `assets/Salaheldeen_CV.pdf` | CV, linked in the menu |
| `assets/theses/` | Thesis PDFs, linked from the Research page |
| `assets/favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Browser-tab and home-screen icons (the name medallion) |

## Editing

- **Content:** edit the page's HTML directly. Each talk, thesis or school is one `<li>` block, so copy an existing one and change it.
- **Linking a PDF:** put the file in `assets/` (teaching files in `assets/teaching/<course>/`) and link it, e.g. `<a href="assets/WRT_notes.pdf">Notes</a>`.
- **Sidebar:** the sidebar (name, menu, email) is repeated in every page. If you change it, change it in all five files.

## Publishing

In **Settings → Pages**, deploy from the branch that holds these files, folder `/ (root)`.
