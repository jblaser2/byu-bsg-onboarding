# Understanding CryoEM

To contribute to the imaging side of the group, you need a working understanding of the field of
**Cryo-Electron Microscopy (CryoEM)**. It has two main branches:

<div class="grid cards" markdown>

-   :material-atom:{ .lg .middle } **Single Particle Analysis (SPA)**

    ---

    Imaging thousands to millions of copies of a purified, homogeneous molecule, then averaging
    them — after 2D/3D classification — to reach near-atomic resolution.

-   :material-cube-scan:{ .lg .middle } **Cryogenic Electron Tomography (CryoET)**

    ---

    Collecting a tilt series and reconstructing a 3D tomogram. **This is our focus.**

</div>

That split is a reasonable simplification, but two things are worth knowing as you dig in:

- CryoET's flagship use is *in-situ* (cellular) imaging — often via FIB-milled lamellae or thin
  cell edges — but it's also used on purified complexes, viruses, and reconstituted assemblies
  when SPA struggles: heterogeneous samples, very large assemblies, or structures without helpful
  symmetry. "In situ" is the headline use case, not the defining feature.
- The defining feature is really the tilt series → 3D tomogram workflow. From there, cryoET often
  applies **subtomogram averaging (STA)** to boost resolution — conceptually similar to SPA
  (average many copies of a structure), except starting from 3D subvolumes pulled out of tomograms
  instead of 2D projection images. STA is a big part of what our group works on.

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

!!! note "Focus on Chapter 13"
    Chapter 13 is the one that maps most directly onto what our group actually does. Read the
    basics broadly, then focus there.

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

This field is complicated and will take a lot of time to figure out. Keep returning to this page
as you learn more — it'll make more sense each time.
