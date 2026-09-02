# my-cv

Personal CV website for Tom Amos — a single-page static site.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The CV page (Profile, Skills, Experience, Education, Contact). |
| `style.css` | Styling. Classy greyscale theme with light/dark support. |
| `tom_amos_cv.md` | Downloadable Markdown version of the CV, linked from the header button. |
| `CLAUDE.md` | Notes for AI-assisted edits. |

## Running locally

No build step. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Keeping the Markdown CV in sync

`tom_amos_cv.md` mirrors the CV content in `index.html`. When you change roles, bullet
points, titles, dates, skills, the profile paragraph, or contact links in the HTML,
make the matching edit in `tom_amos_cv.md` in the same commit.
