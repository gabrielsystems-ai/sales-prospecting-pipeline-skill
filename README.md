# Sales Prospecting and Pipeline Skill

**Find businesses whose digital infrastructure has not kept up with the business itself.**

A reusable AI skill for freelancers, agencies and digital consultants researching prospects, drafting outreach, advancing warm leads, managing projects and identifying justified expansion.

## Core idea

Don't just ask: “Does this business need a better website?”

Ask: “Is there a gap between how developed the business is and the digital infrastructure supporting it?”

Assess presentation and operations separately. Think in complete customer journeys. Preserve effective systems and technology partners; recommend integration or replacement only when evidence supports it.

## Workflow

**PROSPECT → ANALYSE → CONTACT → QUALIFY → DISCOVER → PROPOSE → CLOSE → DELIVER → EXPAND**

Cross-check social profiles, connected links and journey pages. Separate facts from hypotheses. Draft short outreach around one observation, one benefit and one CTA. Never move an interested lead back to the cold pitch. Switch to delivery after approval.

## Classification

| Lead class | Priority |
| --- | --- |
| A+ | Contact with priority |
| A | Contact |
| B | Do not prioritise |
| DISCARD | Do not pursue |

Opportunity types: **Quick Close**, **Standard**, **High-Ticket**. These describe the practical entry and operational scope, not a numerical likelihood of closing.

## Metrics

Track researched/contacted leads, meaningful response and interest rates, proposal and close rates, average agreed project value, time to close and expansion rate. Use consistent cohorts and report collected revenue separately. A target of 15 interested prospects per month is a planning example, not a guarantee.

## Installation and use

1. Clone or download this repository.
2. For Codex, place the folder under your configured skills directory, commonly `~/.codex/skills/sales-prospecting-pipeline-skill/`. Follow the host's current loading instructions if its location differs.
3. Invoke `$sales-prospecting-pipeline-skill` with the current request, public business URLs or authorised conversation history, stage and constraints.
4. For other agents/GPTs, use [SKILL.md](SKILL.md) as operating instructions and retain the examples folder.

Example requests:

- “Analyse this business using public sources. Separate facts from hypotheses and recommend one entry project.”
- “This prospect already asked for pricing. Draft the next message without repeating the pitch.”
- “The client approved the design but has not supplied assets. Record the blocker and next action.”

Research requires browsing or supplied evidence. Sending messages and changing external records require suitable tools and explicit authorisation. The skill itself does not install integrations, automate sending or store a CRM.

## Examples

All examples are fictional; no example represents a researched real prospect.

- [Lead analysis](examples/lead-analysis.md)
- [Cold outreach: weak versus useful](examples/cold-outreach.md)
- [Warm lead progression](examples/warm-lead-followup.md)
- [Active project management](examples/active-project.md)

See [SKILL.md](SKILL.md) for the full method and [agent metadata](agents/openai.yaml) for compatible hosts.

## Privacy and licence

Keep real pipeline records and private conversations outside this public repository. Examples use fictional names and reserved `.example` domains; no real phone numbers, private emails or client proposal amounts are included.

Released under the [MIT License](LICENSE).

