# autoclaude

An endless, self-running mockup of a Claude Code terminal session — a single
self-contained `index.html` with no dependencies. Open it in a browser and it
continuously simulates Claude Code working on a front-end project: planning
todos, exploring files, editing HTML/CSS/JS with inline diffs, running tests,
builds, and commits, forever.

## Usage

Open `index.html` directly in a browser. No server, build step, or network
access required.

## Controls

| Key       | Action                              |
|-----------|-------------------------------------|
| ↑ / ↓     | Increase / decrease animation speed |
| Enter     | Pause / resume the session          |
| + / −     | Increase / decrease text size       |

The session suspends automatically while the tab is hidden and caps its
scrollback DOM, so it stays light on CPU and memory even after hours.
