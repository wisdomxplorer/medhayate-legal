---
title: Privacy Policy
---

# Privacy Policy for Medhayate

**Last updated: 22 August 2026**

## The short version

**Medhayate collects nothing.** No account, no sign-in, no analytics, no advertising,
no tracking, no crash reporting, and no personal information of any kind. Nothing you
do in the app is transmitted anywhere, because the app has no ability to transmit
anything at all.

## Why that claim is verifiable

Medhayate does not request the `INTERNET` permission. On Android this is not a setting
or a promise — an app without that permission is blocked by the operating system from
opening a network connection. The app therefore *cannot* send your data anywhere, even
if it were asked to.

The app requests **no permissions at all**. It has no access to your contacts, camera,
microphone, location, files, or any other device data. The build itself enforces this:
every release is checked against its own merged manifest and fails to build if any
permission appears.

## What is stored, and where

Everything Medhayate saves stays in the app's private storage on your device. Nothing
is uploaded, shared, or sold — there is nowhere for it to go.

| What | Why it exists |
|---|---|
| Your settings — the theme, whether hints highlight the board, your play-limit choice, and any developer options you have switched on | So the app looks and behaves the same next time you open it |
| Play time used, and when the current 4-hour window began | To apply the 15-minutes-per-4-hours play limit |
| Fastest win in Minesweeper, Sudoku and Nonogram, per difficulty | To show your best time |
| Fewest moves in Tower of Hanoi, per difficulty | To show your record |
| Fewest flips in Pairs, per board size | To show your record |
| The game in progress in each of the eight games | So closing the app mid-game does not lose the board |

A game in progress means the position itself — the squares dug, the disks stacked, the
digits written — together with what the game needs to carry on: the options that round
was started with, the clock in a timed game, and the running score in a game that keeps
one for the sitting. It is overwritten as you play and replaced when you start a new
round.

That is the complete list. None of it identifies you: there are no names, no email
addresses, no device identifiers, no advertising ID, and no usage history — nothing
records when you played, how often, or for how long beyond the single 4-hour window
the play limit is currently counting.

## Backups are switched off

Android can copy an app's data to a user's Google Drive automatically. Medhayate
disables this (`allowBackup="false"`), so even your theme choice, your best times and
your saved games stay on the device and are never copied off it. The other side of that
choice is worth saying plainly: they do not survive moving to a new phone either.

## Deleting your data

Uninstalling Medhayate deletes everything it has stored, permanently. You can also
clear it without uninstalling, from **Settings → Apps → Medhayate → Storage → Clear
data**. There is no server-side copy to request the deletion of, because there is no
server.

## Children

Medhayate collects no data from anyone, of any age. There is no personal information
to gather, no profile to build, no advertising, and no content submitted by users.

## Google Play

If you installed Medhayate from Google Play, Google collects information about the
installation itself — such as the download and basic crash diagnostics — under
[Google's own privacy policy](https://policies.google.com/privacy). That happens
between your device and Google; Medhayate neither sees nor receives any of it.

## Changes to this policy

If the app ever begins handling data differently, this policy will be updated before
that version is released, and the date at the top will change. Given the design, any
such change would be a significant departure and would be described plainly rather
than buried here.

## Contact

Questions about this policy: gajanand.bihani@gmail.com
