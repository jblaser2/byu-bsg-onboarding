# Machine Learning

A lot of what we do — cleaning up blurry tomograms, extracting structures, classifying what we find
— leans on machine learning. Here's the gentle on-ramp I wish I'd had.

## Start with 3Blue1Brown

Grant Sanderson's **Neural Networks** series is the best visual introduction to how neural networks
actually work. Watch it before anything else.

[:material-youtube: 3Blue1Brown — Neural Networks](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi){ .md-button .md-button--primary }

## Take linear algebra

I can't overstate this: **taking a linear algebra course helps enormously.**

!!! quote "The big reveal"
    AI is just math — matrices, vectors, dot products, gradients. Once you see it, the "magic" of
    AI turns out to be linear algebra and calculus.

If you've already taken linear algebra, dust it off. If you haven't, put it on your schedule.

## Read Glassner's *Deep Learning*

I really enjoyed this book. It gives a **conceptual** approach to deep learning without diving too
far into math and code — a great way to build genuine intuition before you start wrangling
equations and PyTorch.

[:material-book-open-page-variant: Andrew Glassner — *Deep Learning: A Visual Approach*](https://glassner.com/homepage/books/non-fiction-gallery/book-deep-learning/){ .md-button }

## Build an MNIST classifier

The fastest way to make the intuition stick is to build something. **MNIST** — 70,000 small
images of handwritten digits — is the classic first project: small, well-documented, and
forgiving if you mess something up.

Pick a language and an environment, and build a simple classifier that guesses which digit an
image shows:

- **Python, in Google Colab** — no setup required. Follow a
  [PyTorch MNIST tutorial](https://pytorch.org/tutorials/) directly in the browser.
- **Python, in VS Code** — same idea, running locally with PyTorch installed.
- **Julia, in VS Code** — [FluxML's model zoo](https://github.com/FluxML/model-zoo) has a working
  MNIST example to learn from.

The shape of the project is the same either way: load the data, build a small neural network,
train it for a few epochs, check its accuracy, and look at a few digits it got wrong. Getting this
working end to end teaches you more than reading about it ever will.

## Explore Kaggle

Once you've built your own classifier, browse [Kaggle](https://www.kaggle.com/competitions) —
especially the beginner-friendly "Getting Started" competitions. Kaggle even has its own
[Digit Recognizer](https://www.kaggle.com/c/digit-recognizer) competition built on MNIST, which is
a natural next step after your own classifier. Try submitting an entry; public notebooks from
other participants are a great way to see different approaches to the same problem.

The group has also been involved with a real cryoET competition on Kaggle — see
[Past Accomplishments](accomplishments.md) for how that went.

## A suggested order

<div class="grid cards" markdown>

-   **1. Intuition**

    ---

    3Blue1Brown series → Glassner's book. Build the mental model first.

-   **2. Foundations**

    ---

    Linear algebra (and a little calculus). This is the math under the hood.

-   **3. Practice**

    ---

    Build an MNIST classifier, then try a Kaggle competition. After that, apply what you've
    learned to a real group problem — ask a teammate what's currently useful. See
    [Who's Who](contacts.md).

</div>

!!! note
    You don't need to become a machine-learning expert before you're useful. Build enough intuition
    to follow conversations and read the code, then learn the rest *on* a real problem. That's how
    it sticks.
