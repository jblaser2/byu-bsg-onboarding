# Learning Path

A rough order for picking up the tools and background knowledge the group relies on. You don't
need to master any of this before you start — just work through it steadily, roughly in this
order, alongside your actual project work.

## 1. GitHub

This is the most important tool to get comfortable with early. We use GitHub to track changes to
code and documents, collaborate, and keep a history of everything we've done — including this
website.

- Start with GitHub's own [Hello World guide](https://docs.github.com/en/get-started/quickstart/hello-world)
  to learn the basic flow: repositories, commits, branches, and pull requests.
- **Use AI to help you learn it.** Tools like Claude Code (see below) are very good at explaining
  git errors, walking you through a merge conflict, or reviewing a pull request before you send
  it. Ask questions instead of guessing.

## 2. VS Code and the terminal

[Visual Studio Code](https://code.visualstudio.com/) is the editor most of the group uses. Install
it, get comfortable with its integrated terminal, and learn the basics of moving around the
command line (`cd`, `ls`, `pwd`, `mkdir`, `cp`, `mv`).

Know your resources:

- **Documentation** — get in the habit of reading a tool's actual docs instead of only searching
  for a quick answer. It's slower at first and faster later.
- **[Google Colab](https://colab.research.google.com/)** — a good, low-friction way to start
  writing and running Python without setting anything up locally.

## 3. AI coding tools (Claude Code, Codex)

These tools are extremely useful — and easy to lean on too much. Use them to move faster, not to
skip understanding what's actually happening in your code.

[:material-open-in-new: Anthropic — Claude Code best practices](https://www.anthropic.com/engineering/claude-code-best-practices){ .md-button }

!!! warning "Stay in the loop"
    It's easy to let the AI do something you don't fully understand, or to miss a mistake it
    made because you weren't reading closely. Review what it writes, ask it to explain choices you
    don't follow, and keep building your own understanding — the tool should speed up your
    learning, not replace it.

## 4. Learn the field

Get oriented in what the group actually studies. See [Understanding CryoEM](cryoem.md) for the
full study path; a few additional things worth knowing early:

- **The CryoET Data Portal** — a public repository (from the Chan Zuckerberg Initiative) of
  cryo-electron tomography datasets.
  !!! note "TODO"
      *Josh: add the current link to the CryoET Data Portal.*
- **What the CZI grant is for** — the group's work in this area is funded by a grant from the
  Chan Zuckerberg Initiative.
  !!! note "TODO"
      *Josh: add a short paragraph on what the grant actually funds.*
- **The Kaggle competition** — a relevant machine-learning competition the group has been
  involved with.
  !!! note "TODO"
      *Josh: add a link to the specific competition.*
- **What a tomogram actually is** — a 3D image reconstructed from a tilt series, and usually quite
  blurry. Learn to view and navigate one using:
    - [napari](https://napari.org/) — a general-purpose multi-dimensional image viewer.
    - [IMOD](https://bio3d.colorado.edu/imod/) — the standard tool for tomogram reconstruction and
      visualization in the field.
- **The packages we use regularly:**
    - [napari](https://napari.org/)
    - [IMOD](https://bio3d.colorado.edu/imod/)
    - [teamtomo](https://github.com/teamtomo) — a collection of composable, well-maintained
      cryo-ET tools worth being aware of.

## 5. Languages: Python and Julia

Python is the language you'll use most. Julia comes up for some of the group's simulation work.

- Practice Python with a classic starting project: train a simple model on the
  [MNIST](http://yann.lecun.com/exdb/mnist/) handwritten-digit dataset using
  [PyTorch](https://pytorch.org/tutorials/). It's a small, well-documented project that touches
  most of the basics.
- Install [Julia](https://julialang.org/downloads/) when your work calls for it.
  !!! note "TODO"
      *Josh: add the Julia learning resource you had in mind (Giordano?).*

## 6. Overleaf and paper writing

Writing happens on [Overleaf](https://www.overleaf.com/) using LaTeX. If you haven't used LaTeX
before, Overleaf's own templates and tutorials are a good way to get comfortable with the syntax
before you need it for a real paper.

---

Once you're through the basics above, keep building depth in whichever areas your project needs
most — and check in regularly with Dr. Hart or a teammate about what to prioritize next.
