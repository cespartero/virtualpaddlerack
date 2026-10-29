# Court Manager

A virtual paddle rack for pickleball clubs. Players add their names to a queue and the board calls them onto a court when it's their turn.

- **Open the app:** https://cespartero.github.io/virtualpaddlerack/
- **Quick start guide:** https://cespartero.github.io/virtualpaddlerack/help.html

## What's in this repo

| File | What it is |
| --- | --- |
| `index.html` | Court Manager, offline edition. One self-contained file: fonts and app code are built in, and it runs without internet. |
| `help.html` | The quick start guide for players and admins. |
| `CHANGELOG.md` | What changed in each version. |

## How the offline edition stores data

Everything is saved in the browser on the device that opens the app. Other devices don't share the board. Use **Admin Menu → Download backup** to save the data, and **Restore backup** to load it on another computer.

## Making changes

Changes go through pull requests: each change is made on its own branch, reviewed, then merged into `main`. GitHub Pages republishes the site from `main` within a minute or two of a merge.
