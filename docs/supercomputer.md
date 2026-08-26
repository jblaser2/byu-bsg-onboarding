# The Supercomputer

At some point you'll need access to BYU's Research Computing (RC) systems — the cluster is called
**Marylou**, though most people just call it "the supercomputer." It's not the first or most
important thing to figure out (see [Getting Started](getting-started.md) for that), but you'll
want it before long, since a lot of our work needs more storage and compute than a laptop can
provide.

## What it is

Really, it's just a computer without a screen that you connect to from your own computer.

!!! abstract "Why we use it"
    - **Storage** — it holds large files that would fill up your laptop.
    - **Compute** — it runs jobs that are too big for a personal computer.
    - **GPUs** — it has GPUs available, which many of our tools rely on (simulations, machine
      learning, image processing).

## Requesting an account

Everything lives at BYU Research Computing:

[:material-open-in-new: rc.byu.edu](https://rc.byu.edu/){ .md-button .md-button--primary }

To request your own account, go here:

[:material-account-plus: rc.byu.edu/account/create](https://rc.byu.edu/account/create/){ .md-button }

Follow the instructions on that page. A few specifics that trip people up:

- **Password:** you'll be asked to set one for your RC account — make one now.
- **Organization:** select **Physics and Astronomy.**
- **Sponsor's Net ID:** enter **`glh43`** (Dr. Hart).
- **Protected data:** select **No.**
- **Justifying your need for an account:** there's a paragraph where you explain what you'll use
  the account for. You can copy and adapt this outline:

    > What research are you doing? (a short paragraph)
    > What software will you use?
    > What resources do you anticipate needing? (number of cores, GB of RAM per job, number of
    > jobs running at once, expected application run time, and how much disk storage you'll need)

Submit the request and it's typically approved within a few days.

!!! note "One more step after you're approved"
    Once your account is active, you still need to be **added to the group's shared file system**
    where our data lives — that doesn't happen automatically. Ask in [Who's Who](contacts.md) who
    can add you.

!!! tip "Go in person if you can"
    Research Computing has a walk-in office and runs an introductory course. Going in person and
    taking that course is one of the fastest ways to get comfortable with the system.

## What to learn first

<div class="grid cards" markdown>

-   :material-console:{ .lg .middle } **The basics of Linux**

    ---

    The supercomputer runs Linux. Learn to move around the terminal, manage files, and run jobs.
    BYU's own [Marylou Unix tutorial](https://marylou.byu.edu/documentation/unix-tutorial/) is a
    good place to start.

    Mac users have a head start: macOS's Terminal is Unix-based, which is similar enough to
    practice on.

-   :material-book-open-variant:{ .lg .middle } **The RC intro course**

    ---

    Research Computing offers an introduction that covers what the supercomputer is and how to
    use it. Take it early.

    [:octicons-arrow-right-24: rc.byu.edu](https://rc.byu.edu/)

</div>

!!! note "A quick mental model"
    Logging in to the supercomputer opens a text-based connection (over SSH) to a machine in a
    data center on campus. You type commands, it runs them, and sends the results back as text.
    No mouse, no windows — just the terminal. It feels unfamiliar for about a week, and then it
    starts to feel normal.

## Checklist

- [ ] Request an account at [rc.byu.edu/account/create](https://rc.byu.edu/account/create/)
- [ ] Take the RC introductory course
- [ ] Practice basic Linux/Unix commands (`cd`, `ls`, `pwd`, `mkdir`, `cp`, `mv`, `nano`/`vim`)
- [ ] Learn how to connect via SSH from your own computer
- [ ] Ask in [Who's Who](contacts.md) to be added to the group's shared file system
- [ ] Confirm you can run a small test job
