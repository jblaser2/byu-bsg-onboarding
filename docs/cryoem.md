# Understanding CryoEM 🔬

To contribute to the imaging side of the group, you need a working understanding of the field of
**Cryo-Electron Microscopy (CryoEM)**. It has two main branches:

<div class="grid cards" markdown>

-   :material-atom:{ .lg .middle } **Single Particle Analysis (SPA)**

    ---

    Imaging many copies of a purified molecule and averaging them into a high-resolution structure.

-   :material-cube-scan:{ .lg .middle } **Cryogenic Electron Tomography (CryoET)**

    ---

    Imaging structures *in situ* (inside the cell) as 3D tomograms. **This is our focus.**

</div>

Below is the study path I recommend, roughly in order.

## 1. Watch Grant Jensen's YouTube series

Grant Jensen is a legend in the field, and his lecture series is the single best on-ramp to
understanding CryoEM. Start here.

[:material-youtube: Grant Jensen's CryoEM series](https://www.youtube.com/playlist?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-){ .md-button .md-button--primary }

## 2. Read the Wan & Briggs chapter

The University of Wisconsin–Madison is something of a hub for the field. Read this chapter on
subtomogram averaging — it's a focused, practical introduction:

[:material-file-pdf-box: Wan & Briggs, *Methods in Enzymology* (2016) — PDF](https://cryoem.wisc.edu/wp-content/uploads/sites/341/2024/09/Wan_MethodsEnzymology2016.pdf)

You can also explore the broader UW–Madison CryoEM center:

[:material-open-in-new: cryoem.wisc.edu](https://cryoem.wisc.edu/)

## 3. Dip into the full book (via BYU login)

We have access to the entire book — *Methods in Enzymology*, Vol. 579 — through your BYU login:

[:material-book: Methods in Enzymology, Vol. 579 (ScienceDirect)](https://www.sciencedirect.com/bookseries/methods-in-enzymology/vol/579/suppl/C)

It covers the *entire* field of CryoEM. It's useful for understanding the basics broadly, **but the
work we do primarily focuses on what's discussed in Chapter 13.**

!!! note "Chapter 13 — unlucky, I guess 🐈‍⬛"
    Don't let the number spook you. Chapter 13 is the one that maps most directly onto what our
    group actually does. Read the basics broadly, then live in Chapter 13.

## 4. Learn the parts of the cell

It helps enormously to understand what you're actually *looking at*. Dr. Jensen — our wonderful
**Dean** — built a gorgeous site with detailed animations covering different prokaryote cell types
and the structures inside them. These structures are exactly what we hunt for in our 3D pictures of
bacteria.

[:material-animation-play: The Cell Structure Atlas](https://www.cellstructureatlas.org/introduction.html){ .md-button }

!!! tip "How this connects to your work"
    When you extract a structure from a tomogram (like the flagellar motor on the
    [home page](index.md)), it helps to already know what that structure is, where it sits in the
    cell, and what it does. The Cell Structure Atlas gives you that vocabulary.

---

Once the field makes sense, head over to [Machine Learning](machine-learning.md) — a lot of the
methods we build for cleaning up and interpreting tomograms lean on ML.
