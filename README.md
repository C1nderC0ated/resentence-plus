# resentence-plus

An agent skill for editing prose. It strips generic AI texture, keeps the author's own voice, and adapts text to where it is going: email, Slack, LinkedIn, blogs, docs, code comments, commit messages, or fiction. It also translates, and it covers Russian and mixed Russian-English writing.

Version 1.3.0 is a short `SKILL.md` plus five reference files that it reads only when a task needs them. There are no scripts and no external APIs.

## What it does

- **Five modes.** `rewrite` cleans up text and is the default. `detect` audits without changing anything. `edit` fixes a named file in place. `draft` writes something new from a brief. `translate` renders text in another language and ends with a list of choices for you to review.
- **An edit contract.** Meaning, facts, uncertainty, quotes, code and the author's voice stay as they are. The skill never invents experience, numbers, quotes or reasons, and it stops after two editing passes.
- **A tiered pattern catalog.** Word and phrase lists come with thresholds and context exceptions, so a match is a candidate to review, not an automatic edit. Where Avoid AI Writing has measured a pattern, the catalog gives the counts, including the patterns that turned out more common in human writing.
- **A context-fit check.** It catches words and set phrases that are correct but wrong for the scene, such as «задраили люки» on a wreck that no longer floats.
- **Fiction.** It relaxes the rhythm rules that misfire on deliberate story pacing, and adds checks for stock comparisons, a summary where a scene should be, and invented facts about an existing canon.
- **Context and voice profiles.** Contexts: LinkedIn, blog, technical blog, investor email, docs, casual, fiction. Voices: casual, professional, technical, warm, blunt, or matched to a writing sample.
- **Russian.** Rare and coined words, rare senses of common words, needless loanwords, calques and false friends, officialese, and the Russian rules for dashes and commas.

A pattern match is not evidence that a machine wrote something, and the skill says so. Don't use it to accuse anyone of using AI.

## Layout

| File | Read when |
| --- | --- |
| `SKILL.md` | Always: the contract, modes, workflow, routing, and context-fit check |
| `references/patterns.md` | Audits, edits, and English rewrites over about 150 words |
| `references/russian.md` | Any Russian text |
| `references/channels.md` | Email, LinkedIn, Slack, blogs, product copy, review scores |
| `references/conversational.md` | Chat, PR comments, code comments, commit messages |
| `references/fiction.md` | Stories, scenes, scripts, fan fiction |

The core is about 7,000 tokens; all six files together are about 54,000.

## Install

**Claude Code:** clone it into your skills folder.

```
git clone https://github.com/C1nderC0ated/resentence-plus ~/.claude/skills/resentence-plus
```

**Claude apps:** download `resentence-plus.zip` from the [latest release](https://github.com/C1nderC0ated/resentence-plus/releases/latest) and upload it as a custom skill. It holds the folder with `SKILL.md` and `references/`.

**Other agents:** point the agent at `SKILL.md`; its routing table says which reference file to read for each task. To paste the skill into a system prompt instead, include `SKILL.md` and the reference files your tasks need.

## Examples

- "Detect only: what in this email sounds generic?"
- "Rewrite this LinkedIn post and keep my voice."
- "Edit README.md in place, light cleanup only."
- "Review this chapter of my fan fiction."
- «Почисти этот текст: убери канцелярит и кальки.»
- «Переведи рассказ на русский.»

## Credits and license

The skill combines and adapts material from several projects. [NOTICE.md](NOTICE.md) lists each one, what it contributed, and its license. Seven of the sources are MIT-licensed, and their notices are reproduced there. One source, The Humanizer, carries no license, so no license is offered for the combined skill.

If you wrote one of these sources and want something changed or removed, please open an issue.
