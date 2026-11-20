# effective-writing

An [Agent Skill](https://agentskills.io) for writing, restructuring, and polishing Chinese or English prose with a natural human voice.

## What it does

- **Light edit** — preserve structure and wording where they work; fix distracting formulas, vagueness, repetition, and unnatural transitions.
- **Reconstruction** — when the argument or flow is weak, reorganize around the central point and the reader's needs, without quietly changing the argument.
- **Drafting** — build from supplied material and purpose; match the genre and flag missing evidence instead of inventing it.
- **Audit** — show the affected passage, explain its specific effect, and offer a concrete revision.

It targets empty significance claims, formulaic transitions, inflated vocabulary, reflexive "不是……而是……" contrasts, and defensive academic habits (gratuitous apology, repetitive self-disqualification, evasion of fair comparison) — while preserving the author's voice, technical terms, and factual claims.

## Install

Copy `SKILL.md` into your agent's skills directory, e.g. for OpenAI Codex CLI:

```bash
git clone https://github.com/mingeric/effective-writing.git
cp effective-writing/SKILL.md ~/.codex/skills/effective-writing/SKILL.md
```

Or for Claude Code:

```bash
cp effective-writing/SKILL.md ~/.claude/skills/effective-writing/SKILL.md
```

## Usage

The skill triggers when you ask your agent to write, rewrite, or polish prose; remove AI-like phrasing; strengthen an article; or audit defensive academic writing.

## License

MIT
