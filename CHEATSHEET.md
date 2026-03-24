# Claude Code Cheat Sheet

## Launching Claude

| Command | What it does |
|---------|-------------|
| `claude` | Normal mode — asks permission before each action |
| `cskip` | Auto-approve mode — runs without asking (faster) |

To switch modes: type `/exit` to quit, then relaunch with the other command.

## What is auto-approve mode?

`cskip` runs `claude --dangerously-skip-permissions`. This tells Claude to execute commands, edit files, and make changes without asking you first. It's faster for setup scripts and guided sessions. Use normal mode (`claude`) when you want to review each action before it happens.

**Warp Terminal bonus:** If you use Warp, press `Shift+Tab` inside a Claude session to toggle permissions on/off without restarting.

## Inside a Claude Session

| Command | What it does |
|---------|-------------|
| `/exit` | Quit Claude |
| `/help` | Show all available commands |
| `/permissions` | Check current permission settings |
| `/clear` | Clear the conversation |
| `/compact` | Summarize conversation to save context |
| `!command` | Run a shell command without leaving Claude |

## Tips

- Claude remembers context within a session. If it's getting confused, use `/compact` to reset.
- You can paste file paths, URLs, and error messages directly — Claude will read and understand them.
- To start fresh, just exit and relaunch.
