# Changelog

Every release of NX9, newest first.  Download any of them from the [releases page](https://github.com/functional-dev/nx9-releases/releases).

## 1.1.0

The first release published here.

- **Two windows on one project.**  Choosing a project that is already open in another box opens a second window on it, instead of swapping the two boxes.  Each window keeps its own conversation, last answer and status.
- **Blue lasts long enough to see.**  A session that has just answered stays blue for five seconds after you look at it, and an answer in the window you have open shows blue too.
- **Whole lines only.**  A session's screen no longer shows a line cut in half at its top or bottom edge.
- **iPhone status bar.**  The top of the grid and of an open window is no longer blurred under the status bar on iOS 26 and later.  If you added NX9 to your Home Screen before this version, remove it and add it again to get the new status bar.
- **Claude Code's first-run screens.**  Choosing a theme, a login method and signing in to Claude can all be answered from NX9, with the sign-in link one tap away.
- **Questions with several answers.**  When Claude asks you to tick more than one option, NX9 shows the ticks and a Submit button, and the answer goes through.
- **Voice answers questions to the end.**  After you answer by voice, NX9 reads whatever the window asks next, such as the next tick or the review page.  Say "done" to submit a question with several answers.
- **Voice talks to the window you already chose.**  Switching to voice mode no longer asks you to tap the highlighted window again, and what you sent is read back only while you are still on that window.
- **Links in questions.**  An address that wraps inside a question's frame opens as one link.
- **Setup on a Mac with Tailscale.**  Finishing setup now waits for NX9 to start, which can take a few minutes while Tailscale issues its certificate, instead of opening an address that does not answer yet.
- **Credits** open in a new tab, and now include the license.
- **License.**  NX9 is now free to use for personal and commercial work, under the NX9 Software License.

## 1.0.1

- Search a window's transcript.
- Tables are drawn the way the terminal draws them.
- Drop a folder straight onto a window.
- A Continue button for screens waiting on Enter.

## 1.0.0

The first version.
