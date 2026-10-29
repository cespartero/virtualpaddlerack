# Changelog

Newest first.

## v1.5 — 29 October 2026

- **Queue names fully visible on phones.** On screens up to 600 px wide, each queue row is two lines: the position and full name on top (long names wrap instead of being cut off), then the status and buttons underneath. With admin unlocked, the status dropdown, Sit out and Remove share one line. Tablets and computers are unchanged.

## v1.4 — 29 October 2026

- **Next up highlight**: during a session, the four players the board will put on the next free court have their queue rows shaded orange and marked **Next up**. It updates as players join, sit out or get allocated.

## v1.3 — 29 October 2026

- **Players are mixed up when courts are allocated.** Near the front of the queue, the board avoids putting people who just played together straight back on court together. For example, when two courts finish back to back, the next court gets two players from each game instead of the same four again.
- Teams split last game's partners where possible, as well as splitting winners and grinners.
- **"These players have played before"**: if the only players waiting just played together, tapping Allocate asks whether to **Allocate anyway** or **Wait to mix**.
- New players still always go on first, and the limit of 2 Winners and 2 Grinners still applies.

## v1.2 — 29 October 2026

- **Move a player to the other team** during a doubles match: tap the **⇄** next to their name, then choose which player on the other team swaps across. Works during walk-on and while the match is running. Not shown on singles courts.
- Quick start guide: the swap is listed under *Fix mistakes on a court*.

## v1.1 — 29 October 2026

- **Help** button in the header (next to Admin Menu) opens the quick start guide in a new tab, so the board keeps running.
- The quick start guide has an **Open Court Manager** button to get back to the board.
- A **Source on GitHub** link at the bottom of the board and the guide opens this repo in a new tab.

## v1.0 — 28 October 2026

First baseline release of the offline edition.

- **Virtual Paddle Rack mode**: players join a queue; free courts take New players first, then up to 2 Winners and 2 Grinners, longest waiting first.
- Doubles and singles, automatic or manual allocation, 1-minute walk-on time, Unallocate and Cancel match.
- **Match scores** choice at session start: Capture scores or Winners only.
- Tabs: Board, Standings (current status, points, Avg PPG, last 5), Session status, Match history.
- Admin Menu with PIN: start and end sessions, reorder the queue, auto-add last session's players, change PIN, backup and restore.
- Round robin and court up down tournaments marked Coming soon.
- Fix: the admin PIN now works in browsers that block the built-in hashing for files opened from disk.
