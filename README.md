# Western Sangha List, statistics: the password-protected page

**The page: https://yoboss283.github.io/western-sangha-list-page/**
Open the link and enter the password. Ask the owner for the password, and please don't share it outside the Sangha.

## What this repository is

This repository is only the **shop window**: it holds the finished page, `index.html`, locked with a password.
That is why the file looks like unreadable text: it is encrypted on purpose. Without the password nothing in it can be read.
It has to be a public repository because the free GitHub Pages service only publishes public repositories.

## Where the readable source is

The working project is a separate **private** repository, `yoBoss283/western-sangha-list`. It has the normal source code, the
data, the update instructions (UPDATE.md) and the full README. Anyone the owner invites as a collaborator can read all of it
there (GitHub: the repository's Settings, then Collaborators).

## What the page shows

Statistics from the "Western" Sangha List that Ajahn Cunda keeps (bhikkhus and sāmaṇeras in Western monasteries linked to
Wat Pah Pong and Wat Pah Nanachat), together with what the Sangha community lists add:
- how many ordained each year, how old they were, where and with whom they ordained;
- who is in robes, who disrobed and after how many vassas, and who died in robes;
- a lookup: type a name and see that person's card, where they stayed over the years and how long at each place;
- Thai titles with the year each was received, and the Western preceptors.

It is a small, light exercise to show how the community has changed. The list is Cunda's own, unofficial and incomplete,
and this page does not try to be complete or exactly accurate.

## Updating this page (for the owner and their AI)

The page is rebuilt in the private repository. Then `node encrypt_page.js report.html index.html` locks it (the password is
given as `PAGE_PASSWORD` for that one command and is never saved), and the new `index.html` is pushed here.
The details are in the private repository's `CLAUDE.md` and `UPDATE.md`.
