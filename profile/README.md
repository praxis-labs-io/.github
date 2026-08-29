# Praxis Labs

Praxis Labs builds software, design, and content. The software is developer tools, and it all lives here.

Tools that run where the work already happens. A terminal, and a family of clients that share its keybindings and its restraint. No browser tab, no context switch. Each one does a single job completely, and all of it is open source under MIT.

## ZenTerm

**A dev-first terminal for macOS, on a libghostty core.**

Panes tile in any direction and move by direction rather than by order. Two drawers per tab each hold their own shell, and any command you name in the config becomes a float over your work on a chord you pick. Workspaces pair a folder with a layout, so a project opens the way you left it. 17 themes color the whole app rather than the terminal text alone, and there is no telemetry, no analytics, and no account.

[praxis-labs-io/zen-term](https://github.com/praxis-labs-io/zen-term)

## ZenOcto

**A terminal client for GitHub.**

A pull request end to end without a browser: read it, discuss it, watch its CI, merge it. The list is divided into sections you define, each one a GitHub search query, so what is on screen is whatever you told it to watch. Review comments sit against the lines they were written on, and one key adds a new one scoped to the line under the cursor. It rides the GitHub CLI's token instead of asking for one of its own.

[praxis-labs-io/zen-octo](https://github.com/praxis-labs-io/zen-octo)

## ZenReview

**A code review engine for AI-generated code.**

What you have read is stored as line ranges and carried through every new version of the changeset. A range that survives moves with its code. A range the rewrite destroyed comes back unread, so a second pass covers only what actually changed. Comments carry the agent's response along with the lines that response replaced.

[praxis-labs-io/zen-review](https://github.com/praxis-labs-io/zen-review)

## ZenLinear

**A terminal client for Linear.**

Your Linear sidebar is the navigation tree, favorites and all, and the issue list groups, sorts, and filters the way the web app does. The details pane is one scrolling page holding the issue, its description, and its comments. Every field on it is editable in place and saves as you go. Unofficial and third-party, built on Linear's public API.

[praxis-labs-io/zen-linear](https://github.com/praxis-labs-io/zen-linear)

## ZenNotes

**One notepad per day, in the terminal.**

Run it from anywhere and you land in today's note, already open. Markdown is highlighted as you type and edited with vim motions, and a line holding nothing but an image reference draws the picture under it. There is no save key: the buffer reaches disk within half a second of an edit. No color is hardcoded, so the palette comes from your terminal theme instead of fighting it.

[praxis-labs-io/zen-notes](https://github.com/praxis-labs-io/zen-notes)

## ZenNavigator

**Ctrl-hjkl across Neovim splits and ZenTerm panes as one motion.**

Press Ctrl-h at the left edge of your Neovim splits and focus crosses into the ZenTerm pane on the left. Detection and hand-off both ride ZenTerm's nav socket, so nothing has to probe for processes. Outside ZenTerm every mapping falls back to a plain wincmd, which keeps your config portable.

[praxis-labs-io/zen-navigator.nvim](https://github.com/praxis-labs-io/zen-navigator.nvim)

## ZenTheme

**Neovim follows ZenTerm's theme.**

Pick a theme in ZenTerm and your editor recolors with the terminal and the chrome, live, with no restart. ZenTerm publishes the theme it resolved to a JSON state file, and each theme names the Neovim colorscheme to wear in its own `.ghostty` file. Light and dark flip together, because the background setting comes from the published theme's own reading.

[praxis-labs-io/zen-theme.nvim](https://github.com/praxis-labs-io/zen-theme.nvim)

## Elsewhere

[praxis-labs.io](https://praxis-labs.io) covers the design and content work alongside the software. Anything else: info@praxis-labs.io
