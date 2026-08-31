# byu-bsg-onboarding

Onboarding instructions, resources, and tips for students joining the **BYU Biophysics
Simulation Group (BSG)** — Dr. Gus Hart's research group at Brigham Young University.

> **This repo is a website.** The content lives in Markdown under [`docs/`](docs/) and is
> published as a MkDocs Material site.

## Read the live site

Once GitHub Pages is enabled, the site will be live at:

**https://jblaser2.github.io/byu-bsg-onboarding/**

## Editing the content

Everything is plain Markdown — no web-dev experience required. To change a page, edit the
matching file in [`docs/`](docs/):

| Page | File |
| --- | --- |
| Welcome / intro | `docs/index.md` |
| Getting Started | `docs/getting-started.md` |
| Learning Path | `docs/learning-path.md` |
| The Supercomputer | `docs/supercomputer.md` |
| Understanding CryoEM | `docs/cryoem.md` |
| Machine Learning | `docs/machine-learning.md` |
| Past Accomplishments | `docs/accomplishments.md` |
| Reading & Writing | `docs/reading-writing.md` |
| Conferences | `docs/conferences.md` |
| Tips & Tricks | `docs/tips.md` |
| Resources (link hub) | `docs/resources.md` |
| Glossary | `docs/glossary.md` |
| Who's Who | `docs/contacts.md` |
| Contact (last item in the top nav) | `docs/contact.md` |
| About Me (not in nav — linked only from Contact) | `docs/about-me.md` |

Commit to `main` and the site rebuilds and redeploys automatically (see
`.github/workflows/deploy.yml`).

**New group members:** if you spot something on the site that's out of date or missing, make a
note of it and email Josh (joshuablaser@gmail.com) — he'll add you as a collaborator so you can
edit the repo directly and help keep it current.

## Previewing locally (optional)

```bash
pip install -r requirements.txt
mkdocs serve
# open http://127.0.0.1:8000
```

## First-time setup for the maintainer

1. Merge this into `main`.
2. In the repo, go to **Settings → Pages** and set **Source: GitHub Actions**.
3. Push to `main` — the workflow builds and deploys the site.

---

_Search this repo for `TODO` to find the few spots that still need group-specific details
(book list, contact info, etc.)._
