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
- Dr. Hart also has a
  [getting-started tutorial](https://github.com/msg-byu/getting-started) written for his other
  research group that walks through git/GitHub plus the basics of writing tested, documented
  scientific code. Some of the specific services it references are dated, but the git/GitHub
  fundamentals still apply.
- Dr. Hart's [BSG getting-started repo](https://github.com/glwhart/getting-started) also has a
  recommended [GitHub tutorial video](https://www.youtube.com/watch?v=DVRQoVRzMIY) — note that the
  branch the video calls "master" is now typically called "main." The section on branches (around
  the 27-minute mark) is worth a second look once you're past the basics.
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
[:material-open-in-new: Boris Tane — How I use Claude Code](https://boristane.com/blog/how-i-use-claude-code/#feedback-during-implementation){ .md-button }

The second link is a good practical walkthrough of a workflow: research and plan first, get that
plan reviewed *before* any code gets written, then give short, targeted feedback during
implementation rather than re-explaining context Claude already has.

!!! warning "Stay in the loop"
    It's easy to let the AI do something you don't fully understand, or to miss a mistake it
    made because you weren't reading closely. Review what it writes, ask it to explain choices you
    don't follow, and keep building your own understanding — the tool should speed up your
    learning, not replace it.

!!! tip "Using the BYU Claude account"
    Sign up using your BYU student email — **`netid@student.byu.edu`** — not a personal email.

## 4. Learn the field

Get oriented in what the group actually studies. See [Understanding CryoEM](cryoem.md) for the
full study path; a few additional things worth knowing early:

- **[The CryoET Data Portal](https://cryoetdataportal.czscience.com/)** — a public repository,
  built by the Chan Zuckerberg Initiative, of annotated cryo-electron tomography datasets. It's
  meant to give researchers standardized data to train and test new annotation methods on.
- **What the CZI grant is for** — the group's work in this area is funded by a grant from the
  Chan Zuckerberg Initiative to develop AI methods for interpreting cryo-electron tomograms of
  bacteria — using machine learning to help identify and reconstruct bacterial structures from
  blurry 3D tomogram images. See
  [this BYU Physics & Astronomy article](https://physics.byu.edu/department/news/2023-09-using-machine-learning-to-get-a-better-view-of-bacteria)
  for more.
  !!! note "TODO"
      *Josh: confirm/expand this description of the grant.*
- **[The Kaggle competition](https://www.kaggle.com/competitions/byu-locating-bacterial-flagellar-motors-2025)**
  — *BYU - Locating Bacterial Flagellar Motors 2025*, our group's own competition, which asked
  contestants to build ML models that locate flagellar motors in cryoET tomograms. See
  [Past Accomplishments](accomplishments.md) for how it went.
- **What a tomogram actually is** — a 3D image reconstructed from a tilt series, and usually quite
  blurry. Learn to view and navigate one using:
    - [napari](https://napari.org/) — a general-purpose multi-dimensional image viewer.
    - [IMOD](https://bio3d.colorado.edu/imod/) — the standard tool for tomogram reconstruction and
      visualization in the field.
- **The packages we use regularly:**
    - [napari](https://napari.org/)
    - [IMOD](https://bio3d.colorado.edu/imod/)
    - [teamtomo](https://teamtomo.org/) — a collection of composable, well-maintained cryo-ET
      tools worth being aware of.

### Simulation & biophysics background reading

The simulation side of the group draws on a broader biophysics literature. A few papers, books,
and lectures Dr. Hart has pointed new members to (from his
[getting-started repo](https://github.com/glwhart/getting-started)):

**Papers**

- [E. coli Peptidoglycan Structure and Mechanics as Predicted by Atomic-Scale Simulations](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003475)
- [Coarse-Grained Molecular Dynamics Simulations of the Bacterial Cell Wall](https://www.researchgate.net/publication/304020343_Coarse-Grained_Molecular_Dynamics_Simulations_of_the_Bacterial_Cell_Wall)
- [Coarse-grained simulations of bacterial cell wall growth reveal that local coordination alone can be sufficient to maintain rod shape](https://www.pnas.org/content/112/28/E3689.long)
- [Simulations of Proposed Mechanisms of FtsZ-Driven Cell Constriction](https://journals.asm.org/doi/10.1128/JB.00576-20)

**Books**

- Howard C. Berg, *Random Walks in Biology*
- Carl Zimmer, *Microcosm: E. coli and the New Science of Life*
- Rob Phillips, *Physical Biology of the Cell*
- Philip Nelson, [*Physical Models of Living Systems*](https://www.physics.upenn.edu/biophys/PMLS2e/index.html)
- Philip Nelson, [*Biological Physics*](https://www.physics.upenn.edu/biophys/BPse/)

**Lectures**

- [James C. Gumbart](https://www.youtube.com/watch?v=tp-FPanCaWM)
- [Grant J. Jensen](https://www.youtube.com/watch?v=FSOrXcWOMJU)
- [Sven van Teeffelen](https://www.youtube.com/watch?v=oYY03X2mZgw)
- [Cécile Morlot](https://www.youtube.com/watch?v=71c3rET3qAI)
- [Bart Hoogenboom](https://www.youtube.com/watch?v=y-I0thStOv0)
- [Seamus Holden](https://www.youtube.com/watch?v=7GP5zZyTRPY)

## 5. Languages: Python and Julia

The group works in both. **Julia** is the group's primary language for simulation work — it's
fast like C but reads like Python, which avoids having to prototype in one language and rewrite in
another for speed (the "two-language problem"). **Python** is used heavily on the machine-learning
and tomogram side.

- Install [Julia](https://julialang.org/downloads/) and work through a few tutorials:
    - [A concise Julia tutorial](https://syl1.gitbook.io/julia-language-a-concise-tutorial/) — also
      covers setting up Julia with VS Code.
    - [A video introduction to Julia syntax](https://www.youtube.com/watch?v=sE67bP2PnOo)
    - [Julia Plots tutorial](https://docs.juliaplots.org/latest/tutorial/)
- Then practice with the exercises in Dr. Hart's
  [getting-started repo](https://github.com/glwhart/getting-started), starting with a random walk
  simulation and moving on to problems from **Nicholas Giordano's *Computational Physics*
  textbook** — bicycle motion, cannonball trajectory, and the natural pendulum. (This is likely
  what "Giordano" refers to if you've heard the name — reference solutions are in that repo's
  `code_solutions/` folder if you get stuck.)
- Practice Python with a classic starting project: train a simple model on the
  [MNIST](http://yann.lecun.com/exdb/mnist/) handwritten-digit dataset using
  [PyTorch](https://pytorch.org/tutorials/). It's a small, well-documented project that touches
  most of the basics.

## 6. Overleaf and paper writing

Writing happens on [Overleaf](https://www.overleaf.com/) using LaTeX. If you haven't used LaTeX
before, Overleaf's own templates and tutorials are a good way to get comfortable with the syntax
before you need it for a real paper.

---

Once you're through the basics above, keep building depth in whichever areas your project needs
most — and check in regularly with Dr. Hart or a teammate about what to prioritize next.
