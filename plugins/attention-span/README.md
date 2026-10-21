# attention-span

Output styles that make Claude answer first, skip the filler, and format replies so you can skim them. Designed with ADHD readers in mind, and useful for anyone who wants shorter, clearer answers.

## What you get

- **Three output styles:** Attention-kind (warm, answer-first, easy to scan), Spartan (maximum signal, zero warmth) and Rundown (TL;DR, checklist, numbered choices).
- **The same three as skills** you invoke yourself: `/attention-kind`, `/spartan`, `/rundown`. They cost no context until you call one, and they work in the Claude apps too.
- **`/tldr`** turns a long doc, thread or transcript into a short briefing.
- **`/style`** switches your active output style from a popup.

## Install

```
/plugin install attention-span --marketplace alexgreensh/attention-span
```

Then pick a style under `/config` → *Output style*, or type a skill like `/attention-kind` for one conversation.

## Privacy

Text only. No hooks, no MCP servers, no network calls, nothing collected. `/style` reads and writes only the `outputStyle` key in `~/.claude/settings.json` or the project's `.claude/settings.local.json`.

Full docs, benchmarks and other agents: https://github.com/alexgreensh/attention-span

License: AGPL-3.0
