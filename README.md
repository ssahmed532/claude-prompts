# claude-prompts

A collection of reusable prompts for [Claude Code](https://claude.com/claude-code) and Claude.

## Prompts

| File | Purpose |
| --- | --- |
| [What_do_you_know_about_me.md](What_do_you_know_about_me.md) | Asks Claude to read its memory files, your global `CLAUDE.md`, and your skills, then list what it has inferred about how you work. Each inference comes with evidence and a confidence level, is ranked by how much it would affect your outcomes, and is marked as observed or guessed. Claude also points out where your stated rules contradict what you actually do. |

## Usage

Copy a prompt's text into a Claude Code session, or reference the file directly (e.g. `@claude-prompts/What_do_you_know_about_me.md`).
