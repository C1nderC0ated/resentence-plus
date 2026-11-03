# resentence-plus

An agent skill for editing prose. It strips generic AI texture, keeps the author's own voice, and adapts text to where it is going: email, Slack, LinkedIn, blogs, docs, code comments, or commit messages. It also covers Russian and mixed Russian-English writing.

It is one `SKILL.md` file in the Agent Skills format (version 1.2.0), with no scripts and no external APIs.

## What it does

- **Four modes.** `rewrite` cleans up text and is the default. `detect` audits without changing anything. `edit` fixes a named file in place. `draft` writes something new from a brief.
- **An edit contract.** Meaning, facts, uncertainty, quotes, code and the author's voice stay as they are. The skill never invents experience, numbers, quotes or reasons, and it stops after two editing passes.
- **A tiered pattern catalog.** Word and phrase lists come with thresholds and context exceptions, so a match is a candidate to review, not an automatic edit.
- **Context and voice profiles.** Contexts: LinkedIn, blog, technical blog, investor email, docs, casual. Voices: casual, professional, technical, warm, blunt, or matched to a writing sample.
- **Russian.** Rare and coined words, needless loanwords, calques and false friends, officialese, and the Russian rules for dashes and commas.

A pattern match is not evidence that a machine wrote something, and the skill says so. Don't use it to accuse anyone of using AI.

## Install

**Claude Code:** clone it into your skills folder.

```
git clone https://github.com/C1nderC0ated/resentence-plus ~/.claude/skills/resentence-plus
```

**Claude apps:** zip a folder containing `SKILL.md` and upload it as a custom skill.

**Other agents:** point the agent at `SKILL.md`, or paste it into its rules or system prompt.

## Examples

- "Detect only: what in this email sounds generic?"
- "Rewrite this LinkedIn post and keep my voice."
- "Edit README.md in place, light cleanup only."
- «Почисти этот текст: убери канцелярит и кальки.»

## Credits and license

The skill combines and adapts material from several projects. [NOTICE.md](NOTICE.md) lists each one, what it contributed, and its license. Seven of the sources are MIT-licensed, and their notices are reproduced there. One source, The Humanizer, carries no license, so no license is offered for the combined `SKILL.md`.

If you wrote one of these sources and want something changed or removed, please open an issue.
