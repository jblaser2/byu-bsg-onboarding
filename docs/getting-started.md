# Getting Started: The Supercomputer 🖥️

## We get to use a supercomputer!

I know. It sounds super high-tech and futuristic.

It *is.*

But let's demystify it, because the word "supercomputer" makes it sound scarier than it is. Really,
it's just **a computer without a screen that you connect to from your own computer.** That's the
whole idea.

!!! abstract "Why we use it"
    - **Storage** — it holds large files that would choke your laptop.
    - **Compute** — it runs big projects your personal computer was never built to withstand.
    - **GPUs** — it has some of the newest GPUs, which are essential for running many of the
      programs we use (simulations, machine learning, image processing).

## Your go-to website

Everything supercomputer-related lives at **BYU Research Computing**:

[:material-open-in-new: rc.byu.edu](https://rc.byu.edu/){ .md-button .md-button--primary }

On that site you can:

- Request an account
- Read the documentation
- **Submit tickets** if you run into any issues
- Find the Research Computing office location

!!! tip "Go in person — seriously"
    When you're getting started, I *strongly* recommend visiting the Research Computing office **in
    person.** They'll walk you through a great introductory course and get you set up far faster
    than you'd manage alone. It's one of the highest-return hours you'll spend early on.

## What to learn first

<div class="grid cards" markdown>

-   :material-console:{ .lg .middle } **The basics of Linux**

    ---

    The supercomputer runs Linux. Learn to move around the terminal, manage files, and run jobs.

    Good news for Mac users: **Unix is very similar to Linux**, so you can practice right on your
    Mac's Terminal.

-   :material-book-open-variant:{ .lg .middle } **The RC intro course**

    ---

    Research Computing offers an introduction that covers *what the supercomputer is* and how to
    use it. Take it early.

    [:octicons-arrow-right-24: rc.byu.edu](https://rc.byu.edu/)

</div>

!!! note "A quick mental model"
    When you "log in" to the supercomputer, you're opening a text-based connection (over SSH) to a
    machine sitting in a data center somewhere on campus. You type commands, it runs them, and it
    sends the text results back to you. No mouse, no windows — just you and the terminal. It feels
    alien for about a week, and then it feels like a superpower.

## Your first-week checklist

- [ ] Visit (or email) the Research Computing office and request an account
- [ ] Take the RC introductory course
- [ ] Practice basic Linux/Unix commands (`cd`, `ls`, `pwd`, `mkdir`, `cp`, `mv`, `nano`/`vim`)
- [ ] Learn how to connect via SSH from your own computer
- [ ] Find out where your group's shared storage lives (ask in [Who's Who](contacts.md))
- [ ] Submit a test ticket or ask a teammate to confirm you can run a small job

Once you can log in and move around, come back and dig into
[Understanding CryoEM](cryoem.md) and [Machine Learning](machine-learning.md) — that's the work
you'll actually be running on all this horsepower.
