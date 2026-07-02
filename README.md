# byu-bsg-onboarding

Onboarding instructions, resources, and tips for students joining the **BYU Biophysics
Simulation Group (BSG)** — Dr. Gus Hart's research group at Brigham Young University.

> 📖 **This repo is a website.** The content lives in Markdown under [`docs/`](docs/) and is
> published as a MkDocs Material site.

## 🔗 Read the live site

Once GitHub Pages is enabled, the site will be live at:

**https://jblaser2.github.io/byu-bsg-onboarding/**

## ✍️ Editing the content

Everything is plain Markdown — no web-dev experience required. To change a page, edit the
matching file in [`docs/`](docs/):

| Page | File |
| --- | --- |
| Welcome / intro | `docs/index.md` |
| About Me | `docs/about-me.md` |
| The Supercomputer | `docs/getting-started.md` |
| Understanding CryoEM | `docs/cryoem.md` |
| Machine Learning | `docs/machine-learning.md` |
| Conferences | `docs/conferences.md` |
| Tips & Tricks | `docs/tips.md` |
| Resources (link hub) | `docs/resources.md` |
| Glossary | `docs/glossary.md` |
| Who's Who | `docs/contacts.md` |
| FAQ | `docs/faq.md` |

Commit to `main` and the site rebuilds and redeploys automatically (see
`.github/workflows/deploy.yml`).

## 🖥️ Previewing locally (optional)

```bash
pip install -r requirements.txt
mkdocs serve
# open http://127.0.0.1:8000
```

## 🚀 First-time setup for the maintainer

1. Merge this into `main`.
2. In the repo, go to **Settings → Pages** and set **Source: GitHub Actions**.
3. Push to `main` — the workflow builds and deploys the site.

---

_Search this repo for `TODO` to find the few spots that still need group-specific details
(book list, contact info, etc.)._
