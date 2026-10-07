# Output framework

Always open with **Preferences** (the answers, one line each) and a one-sentence **Recommendation**.

## One-pager
- **Team:** a table with agent, owns, inputs → outputs, never does.
- **Hand-off map:** asker → owner, what's passed, deadline, evidence that closes it.
- **Kept by people:** decision, who, what the agent prepares.
- **First three steps** this week.

## Blueprint (adds to the one-pager)
1. Executive summary (five lines)
2. Workflow audit and what's delegated
3. Agent-by-agent specs (purpose, inputs, outputs, tools, limits, done-evidence, when stuck)
4. Workflow diagram (text or Mermaid): kickoff to final output, with retries, feedback loops and escalations
5. Quality, safety and cost controls
6. Prompt pack (one system prompt per agent)
7. 7-day rollout and what to measure
8. Common mistakes to avoid for this setup
9. Final checks, answered

## Build (adds to the blueprint)
Files the person can use directly in the stack they named: agent definitions or skill files, the prompts as
separate files, a hand-off checklist, and a short README that lists only what was tested.

## Writing rules
- Plain words; define any term once.
- Each recommendation gives its reason, the trade-off (speed, quality, cost), and the risk.
- No agent without a job only it does. No hand-off without an owner.
- Say what you assumed. Say what you couldn't verify.
