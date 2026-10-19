<div align="center">

<h1>Sales Prospecting &amp; Pipeline Skill</h1>

<p>A structured AI workflow for finding better prospects, writing evidence-based outreach,<br>advancing sales conversations and managing digital projects.</p>

<p><strong>Find businesses where the digital infrastructure has not kept up with the business itself.</strong></p>

<p>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-2563eb" alt="License: MIT"></a>
  <a href="SKILL.md"><img src="https://img.shields.io/badge/Agent-Skill-334155" alt="Agent Skill"></a>
</p>

<p><a href="#quick-start">Quick start</a> · <a href="SKILL.md">Read the skill</a> · <a href="#input--output-example">See an example</a></p>

</div>

**PROSPECT → ANALYSE → CONTACT → QUALIFY → DISCOVER → PROPOSE → CLOSE → DELIVER → EXPAND**

## What this does

A basic prospecting workflow might stop at **find a business → inspect the website → generate a cold message**. This skill provides operating instructions for the full sales and delivery journey.

It helps an agent:

- Research businesses across websites, social profiles and connected links.
- Separate evidence from assumptions, identify commercially relevant gaps and prioritise leads.
- Draft concise outreach and advance interested prospects without repeating the pitch.
- Maintain pipeline context through discovery, pricing, proposals and approval.
- Switch to project delivery after approval and identify expansion only when justified.

Designed for freelancers, agencies and consultants selling websites, booking and registration flows, portals, education platforms, memberships, admin systems, integrations and operational web applications.

## Core idea

> **Is there a gap between how developed the business is and the digital infrastructure supporting it?**

An old website is not automatically an opportunity. A beautiful website does not prove that the customer journey is resolved. Multiple tools do not automatically mean a fragmented operation.

Assess both layers:

| Presentation / frontend | Digital infrastructure |
| --- | --- |
| Visual quality | Booking |
| Brand credibility | Registration |
| Mobile experience | Accounts |
| Information hierarchy | Memberships |
| Conversion | Payments |
| Responsiveness | Courses |
| Trust | Admin workflows |
| User experience | Integrations |

Preserve systems and technology partners that already work well. Recommend a complementary layer, integration or replacement only when evidence supports it.

## Evidence first

| Label | Meaning | Illustrative finding |
| --- | --- | --- |
| **FACT** | Direct observation supported by a source | All inspected “Book Now” buttons lead to the same enquiry form. |
| **HYPOTHESIS** | Possibility requiring validation | Staff may need additional coordination after submission. |
| **UNKNOWN** | Not established by available evidence | Whether the form already feeds an automated CRM workflow. |

Do not invent pain, budget, buying intent or manual processes. Do not claim “no website” because a Linktree lacks a website link, or criticise existing tools without inspecting their role.

## Research beyond the homepage

Cross-check available sources across the journey:

1. **Social presence:** Instagram/profile → bio and direct links → Linktree/Beacons.
2. **Public offer:** website → services/programmes → booking/registration.
3. **Connected operation:** courses/memberships/events → forms/payments/external platforms.
4. **Customer journey:** inspect the handoffs, recent operating activity and accessible decision maker.

These are cross-checks, not a mandatory linear browsing sequence. Record sources, inspection dates and access limitations. An inaccessible profile is not proof of inactivity.

Use proportionate research: inspect enough to support a useful first contact; investigate more deeply for exceptional opportunities, interested prospects and proposals.

## Lead classification

| Class | Meaning | Action |
| --- | --- | --- |
| **A+** | Strong observable opportunity, active business, accessible decision maker and credible commercial fit | Contact with priority |
| **A** | Good fit with a useful opportunity and practical entry | Contact |
| **B** | Potential, but weaker evidence, access or urgency | Do not prioritise |
| **DISCARD** | Inactive, poor fit, no worthwhile gap, opt-out or uneconomic pursuit | Do not pursue |

| Opportunity type | Typical entry |
| --- | --- |
| **Quick Close** | Clear pain, accessible owner and simple approval: website/redesign, enquiry, registration or simple booking |
| **Standard** | Professional website, information architecture, conversion and practical integrations |
| **High-Ticket** | Validated operational scope involving accounts, programmes, memberships, dashboards, admin or integrations |

**High-Ticket means validated operational complexity and value—not simply a large company.** Neither follower count nor company size establishes budget or ease of closing.

## Never move a warm lead backwards

When a prospect requests an idea, portfolio, examples, price, proposal or implementation details, fulfil that request. Do not return to a cold CTA such as “Would you like me to send you an idea?”

> **Does this message advance the deal or repeat something the prospect already knows?**

Progress toward **interest → relevant information → operational question → price → timeline → scope → approval**. Skip questions already answered; ask only what materially changes the project. Use the actual contact date and respect agreed decision dates when planning follow-ups.

See the [warm lead progression example](examples/warm-lead-followup.md).

## After approval: delivery mode

Switch from prospecting to tracking **approved scope, current task, client dependencies, blockers, assets, feedback, revisions, risks and next client communication**.

Classify new requests against the approved agreement:

| Request category | Treatment |
| --- | --- |
| Minor adjustment | Make the targeted correction and verify its effects |
| Reasonable inclusion | Check against the agreed scope and delivery commitments |
| Scope expansion | Agree changed scope, price and timeline before implementation |
| Future phase | Record separately from current launch obligations |

Preserve approved work and verify desktop/mobile effects when responding to feedback. See the [active project example](examples/active-project.md).

## Quick start

### 1. Clone the repository

```bash
git clone https://github.com/gabrielsystems-ai/sales-prospecting-pipeline-skill.git
```

### 2. Add the folder to your agent environment

For Codex, place the cloned folder inside your configured skills directory. A common location is:

```text
~/.codex/skills/sales-prospecting-pipeline-skill/
```

The location and loading behaviour vary by environment and configuration; follow your host's current instructions. The clone command downloads the project—it does not install or activate it by itself.

For other agents/GPTs, provide [SKILL.md](SKILL.md) as the operating instructions and make the referenced examples available. [agents/openai.yaml](agents/openai.yaml) supplies interface metadata for compatible hosts.

### 3. Invoke the skill

```text
Use $sales-prospecting-pipeline-skill.

Analyse this business using public sources: [business URL].

Cross-check the website, social profiles and connected links.
Separate facts from hypotheses.
Determine whether there is a commercially relevant digital opportunity.
Recommend one practical entry project.
```

Research requires browsing or user-supplied evidence. The skill provides instructions; it does not install integrations, maintain persistent CRM storage or send messages automatically.

## Input / output example

**Fictional fixture:** the business, contact roles and observations below are invented training data, not live research.

**Input**

> Analyse the fictional Alderfield Fitness Academy. Supplied inspection notes show three current programmes, recent social activity, a responsive website and registration buttons leading to the same enquiry form. The published owner is directly reachable. Assess the entry opportunity without assuming the backend is manual.

**Illustrative output**

```markdown
# ALDERFIELD FITNESS ACADEMY — FICTIONAL MARKET

Class: A+
Opportunity Type: Standard

## CONTACTS
Website: https://alderfield.example
Instagram: Recent activity in the supplied fictional inspection notes
WhatsApp: Unknown; do not generate a wa.me link
Email: Not supplied
Decision maker: Owner, directly reachable in the fictional fixture

## FACTS
- Three current programmes are listed.
- The inspected registration buttons lead to the same enquiry form.
- The website is responsive and social activity is recent.
Sources: supplied fictional inspection notes; not verified live research.

## HYPOTHESES / UNKNOWNS
- Programme-specific handoffs may help visitors choose the correct next step.
- Backend automation, operational impact, budget and buying intent are unknown.

## MAIN OPPORTUNITY
Clarify programme discovery and registration handoffs.

## RECOMMENDED ENTRY
Improve programme pages and the registration journey, retaining working systems.

## EXPANSION POTENTIAL
None established; validate any integration need in discovery.

## VERDICT
CONTACT WITH PRIORITY
Priority reflects the supplied fit and access, not a guaranteed sale.

## OUTREACH
Hi, I was looking through Alderfield's programmes and noticed the registration
links lead to the same enquiry form. I had an idea for helping visitors find
the right programme and next step while retaining your current systems.
Could I send a short outline?
```

In live research, include source URLs and inspection dates for material facts. Use **B** or **DISCARD** when evidence or commercial fit is insufficient; the output is not always A+.

## Cold outreach

**Specific observation → one relevant opportunity and clear benefit → simple CTA**

Aim for approximately **35–75 words**. The first contact should earn a meaningful response, not explain the whole project. Avoid feature lists, fake urgency, unsupported criticism and invented ROI.

Adapt to the recipient's language and published contact preferences. A listed phone number does not confirm WhatsApp. See [cold outreach examples](examples/cold-outreach.md) for weak versus useful messages.

## Pipeline context

Keep this record in an authorised private workspace:

```text
# BUSINESS / CLIENT
Stage:
Decision maker:
Already sent:
Approved:
Open questions:
Current blocker:
Next action:
Last contact date:
```

| Stage | Relationship |
| --- | --- |
| A — PROSPECT | Not contacted |
| B — COLD CONTACT | Contacted; no confirmed interest |
| C — WARM / INTERESTED | Requested an idea, information or buying discussion |
| D — ACTIVE NEGOTIATION | Discussing scope, proposal, pricing or implementation |
| E — CLIENT / PROJECT | Approved or started |
| F — WAITING / CLIENT DEPENDENCY | Waiting for content, payment, approval, access, feedback or decision |

**Waiting does not erase the underlying stage.** A client waiting to provide content remains a client. Retain the underlying stage, dependency owner and return condition. Silence is not approval.

## Metrics

| Metric | Definition |
| --- | --- |
| Leads researched | Unique businesses checked against the research checklist |
| Leads contacted | Unique businesses receiving initial outreach |
| Meaningful response rate | Prospects with substantive replies / contacted prospects |
| Interest rate | Genuinely interested prospects / contacted prospects |
| Proposal rate | Prospects receiving proposals / interested prospects |
| Close rate | Approved projects / proposals |
| Average project value | Total agreed value of closed projects / closed projects |
| Time to close | Days from first outreach to approval |
| Expansion rate | Eligible clients purchasing additional work / eligible clients in a defined window |

Use consistent cohorts, currencies, dates and eligibility windows; mark zero denominators **N/A**. A substantive refusal may count as a meaningful response, but not interest.

**Drafted messages ≠ sent messages. Agreed revenue ≠ collected revenue.** Track them separately. Planning targets are not performance guarantees.

## Repository structure

- [SKILL.md](SKILL.md) — detailed operating instructions.
- [README.md](README.md) — project overview and usage.
- [LICENSE](LICENSE) — MIT License.
- **agents/**
  - [openai.yaml](agents/openai.yaml) — metadata for compatible skill hosts.
- **examples/**
  - [lead-analysis.md](examples/lead-analysis.md) — complete fictional lead assessment.
  - [cold-outreach.md](examples/cold-outreach.md) — weak versus useful first messages.
  - [warm-lead-followup.md](examples/warm-lead-followup.md) — interest through pricing and follow-up.
  - [active-project.md](examples/active-project.md) — delivery, dependencies and scope control.

## Use cases

- Research a business, inspect its customer journey and decide whether to contact it.
- Draft cold outreach or continue a warm conversation without repeating the pitch.
- Prepare follow-ups, structure discovery and move toward pricing and approval.
- Manage an active project and identify justified expansion.
- Review pipeline performance and commercial priorities.

## What it does not do

- Guarantee replies or sales, invent closing probabilities or promise conversion gains.
- Send outreach automatically or access private information without authorisation.
- Submit prospect forms, create bookings or execute payments.
- Assume every website needs redesign or every external tool needs replacement.
- Turn every opportunity into a CRM, treat followers as budget evidence or present hypotheses as facts.

Sending messages or modifying external records requires appropriate tools and explicit authorisation. Research remains limited by source availability and the quality of supplied evidence.

## Privacy

Keep real pipelines, private conversations, personal contact data, confidential project values, private operational information and identifiable client combinations outside this public repository.

Included examples are fictional. For issue reports, prefer fictional reproductions; anonymised material must remove both direct identifiers and contextual clues that could identify a real person or business.

## Roadmap

Potential future improvements—not current capabilities or delivery commitments:

- More industry-specific examples.
- Evaluation scenarios for common prospecting mistakes.
- Additional pipeline output templates.
- Reference modules for research, outreach and project delivery.
- Improved compatibility guidance across agent environments.

## Contributing

Open an issue when the skill makes unsupported assumptions, repeats previous messages, misclassifies a lead, recommends unnecessary scope or misses an important part of the customer journey.

Include a fictional or safely anonymised reproduction, the observed output and the expected behaviour. Keep proposals focused and consistent with [SKILL.md](SKILL.md).

## License

Released under the [MIT License](LICENSE).

If this workflow improves how your agent researches prospects or manages sales conversations, consider giving the repository a star.

**Better research → better opportunities → better next actions.**
