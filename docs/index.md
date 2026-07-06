---
hide:
  - navigation
---

<div class="bsg-hero" markdown>

# Welcome to the Group! 🙌

The onboarding guide for new members of the
**BYU Biophysics Simulation Group** — a.k.a. the greatest research group on campus.

<span class="bsg-badge">🍵 Tea &bull; 🏐 Handball &bull; 🦠 Bacteria &bull; 🤖 AI</span>

</div>

Most STEM majors at BYU require — or strongly prefer — that their students get experience working
as an undergraduate researcher. So first, congratulations: you have been lucky enough to stumble
upon the **greatest research group there is.** We're glad to have you. Welcome to the team.

!!! quote inline end "Hey! 👋"
    New here and already overwhelmed? That's normal. I promise it
    gets better (the headache is temporary).

Not sure where to even begin? Totally fine. This whole site exists so you don't have to figure it
out alone. Skim the cards at the bottom, then start with **[About Me](about-me.md)** and
**[The Supercomputer](getting-started.md)**.

## How research works at BYU

BYU is unusual when it comes to research assistantships: it heavily prioritizes the participation
of **undergraduate** students. Most universities reserve research for graduate students and
post-docs.

Here's the general shape of things:

- A research group is headed by one or two professors. The head professor is an expert pushing the boundaries of their field.
- A group typically has 1–2 PhD students and a handful of undergrads.
- Together they design projects that advance the field.
- A project idea gets submitted to a foundation — the [NSF](https://www.nsf.gov/),
  [DOE](https://www.energy.gov/science/office-science), [NIH](https://www.nih.gov/), or a private
  organization — as a **grant proposal**.
- If the grant is accepted, the foundation provides funding to help you accomplish your goals.
- With money in hand, the work begins! The project is divided into subtasks that researchers work
  on together or individually.
- The group meets regularly (usually weekly) to report progress, ask and answer questions, and
  discuss the project.

### A note on publishing

The way scientists gain status and recognition is by writing scientific articles that get
published in prestigious journals. It's how the scientific community reports its work so that
others can build off of it.

Often, if you have a good idea, someone else has had that idea too — scientific articles are how we
know what has and hasn't already been done in a field. Whenever significant research is done, a
paper should be written that gives a detailed and reproducible **account** of the work.

In many ways, publishing is treated as an end in itself, but it's better seen as a **means** to the
real end: scientific progress. That said — you should aim to write at least one article and submit
it for publication while you're researching here.

## Group culture: 

Our group has a unique and fun culture. We work hard and play hard. The priorities, in order:

<div class="grid cards" markdown>

- :material-account-heart:{ .lg .middle } **Healthy relationships**

    ---

    Family first. Always.

- :material-run-fast:{ .lg .middle } **Healthy lifestyle**

    ---

    Exercise! Yay! (See: handball, below.)

- :material-school:{ .lg .middle } **Learn, learn, learn**

    ---

    This never stops. It's the whole job, really.

</div>

Dr. Hart hosts weekly **Tea & Chat** meetings where we drink homemade tea and talk about our
lives, interesting things we've learned, a book we're reading together, and the cool problems we're
wrestling with in research. These meetings build unity and friendship across the group.

And then there's **handball** 🏐. Dr. Hart is president of the handball club and loves when
students come play. If you get good enough to beat him, you might just win **$100**. 🤑

!!! info "The 10-hour standard"
    Each student is expected to put in **at least 10 hours of work each week.** What your days
    actually look like is up to you, but 10 hours is the baseline. Those hours can include:

    - Reading and learning about the field and your project
    - Practicing a new skill (e.g. picking up a new programming language)
    - Meeting with fellow researchers
    - Problem-solving within your project
    - Writing up and recording your work

    The focus shifts based on the project's current needs.

### Deciding what to do

We take a **hands-off** approach to work. There will be **no one telling you exactly what to do.**

!!! warning "This is a feature, not a bug"
    Yes, really. Your job is to ask questions, do research, and find ways to contribute to the
    project. It feels uncomfortable at first — and then it becomes the best part.

Set up **regular meetings** with Dr. Hart, [Braxton](contacts.md), or someone else in the group to
discuss how you can best contribute and to get feedback on the problems you're facing.

## What is the field? (The cool stuff. The science.)

The group is the **Biophysics Simulation Group (BSG)**. Broadly, our goal is to figure out how
different parts of bacteria actually work. The team splits into two complementary halves.

=== "Half 1 — Simulation 🧬"

    **One part** of the team runs computer simulations of known bacterial structures and tests how
    they behave down to the atomic level.

    The idea: if we can figure out how bacteria work, chemical and biomedical engineers can design
    drugs that strategically kill *harmful* bacteria — or even harness the properties of *useful*
    bacteria — to save lives.

    <figure markdown="span">
      ![Cross-section of an effector protein pushing the plug up the T4SS channel](https://github.com/user-attachments/assets/ba3ba411-d7bf-45fd-ac78-600a95b52630){ width="360" }
      ![Accompanying force diagram of the simulation](https://github.com/user-attachments/assets/b7f4f3d2-0e9f-4842-82e0-1f493c2dc8b6){ width="340" }
      <figcaption>A cross-sectional view of an effector protein pushing the plug up the channel of
      the Type IV Secretion System (T4SS), with its accompanying force diagram — simulated by
      Cayson Hamilton.</figcaption>
    </figure>

    ➡️ Learn the math behind it on the [Machine Learning](machine-learning.md) page.

=== "Half 2 — Imaging (CryoET) 🔬 & AI"

    **The other part** of the team works a few steps earlier in the pipeline. Before you can
    simulate a protein structure, you have to *know its shape.* How did we figure out which
    proteins the T4SS is made of? How did we know the shape of the structure?

    The (extremely oversimplified) answer: **we just looked at it.** Yes — we looked at a bacterium.

    "But Josh! Bacteria are *way* too small to see — especially with your bad eyesight!" Correct on
    both counts, my friend; glasses don't help. That's where the **electron microscope** comes in.

    In 1931, German scientists Ernst Ruska and Max Knoll built the world's first
    [electron microscope](https://www.aaas.org/membership/scientia/development-electron-microscope),
    which used the tiny wavelength of electrons (about 100,000× smaller than visible light) to reach
    a resolution of about 0.1 nm. That invention made it possible to visualize bacteria in
    incredible detail.

    The specific subset we focus on is **Cryogenic Electron Tomography (CryoET)** — collecting and
    imaging *in situ* bacterial samples with an electron microscope. Limits in the microscope and
    the imaging process make the resulting 3D images (**tomograms**) rather blurry. Our team
    improves the methods that extract the important pieces from tomograms and prepare them to become
    atomic models.

    <figure markdown="span">
      ![A flagellar motor being extracted and averaged from a tomogram](https://github.com/user-attachments/assets/8e7f08da-fac5-4f0f-ba83-ff4812fe3bd0){ width="640" }
      <figcaption>A bacterial structure (here, the flagellar motor) being extracted from a tomogram.
      Repeat this hundreds of times, then average the copies to produce a higher-resolution image —
      which can be turned into an atomic model and simulated, like above.</figcaption>
    </figure>

    ➡️ Full study path on the [Understanding CryoEM](cryoem.md) page.

## Where to next?

<div class="grid cards" markdown>

-   :material-account:{ .lg .middle } **About Me**

    ---

    Who made this and why. (Spoiler: to save you a 3-month headache.)

    [:octicons-arrow-right-24: Read Josh's note](about-me.md)

-   :material-server-network:{ .lg .middle } **The Supercomputer**

    ---

    Your new best friend. What it is and how to get on it.

    [:octicons-arrow-right-24: Get started](getting-started.md)

-   :material-microscope:{ .lg .middle } **Understanding CryoEM**

    ---

    Grant Jensen, the field, and the one chapter that matters.

    [:octicons-arrow-right-24: Study the field](cryoem.md)

-   :material-brain:{ .lg .middle } **Machine Learning**

    ---

    AI is just math. Here's the gentle on-ramp.

    [:octicons-arrow-right-24: Learn ML](machine-learning.md)

-   :material-link-variant:{ .lg .middle } **Resources**

    ---

    Every link on this whole site, in one tidy place.

    [:octicons-arrow-right-24: Browse resources](resources.md)

-   :material-help-circle:{ .lg .middle } **FAQ & Glossary**

    ---

    Decode the jargon and get your questions answered.

    [:octicons-arrow-right-24: FAQ](faq.md) &bull; [Glossary](glossary.md)

</div>

## In conclusion

This was just a brief introduction to the group and what we do. You almost certainly still have
questions — good. The rest of this site points you in the right direction and gives you things you
can start learning **today.**

Once again: welcome to the greatest group on campus. 😃 We hope you're ready to do some great things.

!!! tip "About Dr. Hart"
    Dr. Gus Hart is the reason this group is as good as it is. He cares deeply about the students and is also really cool! He is an excellent teacher and the best mentor you could hope to have. He has been very successful in his work, developing many algorithms and open source codes that have changed the field of materials science. Check out his [Google scholar profile](https://scholar.google.com/citations?user=4Qiq3VEAAAAJ&hl=en). In 2022, Dr. Hart shifted his research focus to data science and computational biophysics, with a particular focus on developing AI for bacterial tomograms. 

*
