# Agent team designer

A skill for your coding agent (Claude Code, Codex, Cursor and others that read skills) that designs a
small, dependable team of AI agents for one real workflow, shaped by **your** preferences: how much the
agents may do on their own, which calls stay with a person, the tools you already use, your budget, and
how much detail you want back.

## Install

```sh
npx skills add ps2802/agent-team-designer
```

## Use

Ask in plain words: "design an agent team for our weekly release", "split customer onboarding between
agents and people", "audit my agent setup". It asks up to ten questions in one message, each with a
default, then hands back a design at the depth you chose:

- **One-pager:** the team, the hand-off map, what stays human, the first three steps.
- **Blueprint:** adds agent-by-agent specs, a workflow diagram, quality and cost controls, a prompt pack and a 7-day rollout.
- **Build:** adds files you can drop into your stack.

Every choice traces back to a stated preference, or is flagged as the designer's own call. It ends by
answering its own checks: is every agent needed, does every hand-off have one owner and evidence, where
could agents duplicate work or invent facts, and which calls still need a named person.

## What's inside

| File | |
|---|---|
| `SKILL.md` | The method: ask first, then audit → delegate → team → agents → hand-offs → people → quality → prompts → rollout. |
| `PREFERENCES.md` | The intake questions and their defaults. Edit the defaults to suit your team. |
| `FRAMEWORK.md` | The output templates for each depth, and the writing rules. |

## Credits

Inspired by a public agent-team prompt by @polydao; the method and wording here are our own. From the
team behind [Pantheon](https://www.joinpantheon.network), where each person's agent hands work to their
teammates' agents with an owner, a deadline and a receipt.

## License

MIT
