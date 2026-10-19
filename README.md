<div align="center">
  Sales Prospecting & Pipeline Skill

A structured AI workflow for finding better prospects, writing evidence-based outreach, advancing sales conversations and managing digital projects.

Find businesses where the digital infrastructure has not kept up with the business itself.





PROSPECT → ANALYSE → CONTACT → QUALIFY → DISCOVER → PROPOSE → CLOSE → DELIVER → EXPAND

</div>

What this does

Most AI prospecting workflows stop at:

Find a business → inspect the website → generate a cold message.

This skill treats prospecting as a complete sales and delivery system.

It helps an AI agent:

research businesses across websites, social profiles and connected links;

distinguish verified facts from assumptions;

identify practical website, system or platform opportunities;

prioritise leads based on evidence rather than superficial signals;

draft short, relevant cold outreach;

advance interested prospects without repeating the original pitch;

maintain context through pricing, proposals and approval;

switch from sales mode to project delivery once a deal closes;

identify expansion opportunities only when there is evidence for them.

The goal is not to generate more leads.

The goal is to identify better opportunities and take the correct next action at every stage.

The core idea

A business does not necessarily need a new website because its current website looks old.

The more useful question is:

Is there a gap between how developed the business is and the digital infrastructure supporting it?

A company may already have:

a good website;

active social media;

ecommerce;

booking software;

online courses;

forms;

memberships;

multiple locations or programmes.

And still have an important gap somewhere in the customer journey.

The skill investigates both:

Presentation

Digital infrastructure

Visual quality

Booking

Brand credibility

Registration

Mobile experience

Accounts

Information hierarchy

Memberships

Conversion

Payments

Responsiveness

Courses

Trust

Admin workflows

User experience

Integrations

A polished website does not automatically mean the underlying customer journey is strong.

And multiple tools do not automatically mean the operation is broken.

The skill is designed to investigate before recommending.

Evidence first

One of the most important rules in the skill is:

Do not turn signals into facts.

Instead, separate findings into:

FACT

Something directly observed and supported by a source.

All inspected “Book Now” buttons lead to the same enquiry form.

HYPOTHESIS

A reasonable possibility that still requires confirmation.

Staff may need additional coordination after the form is submitted.

UNKNOWN

Something that cannot currently be determined.

Whether the enquiry form already feeds an automated CRM workflow.

This prevents common AI prospecting mistakes such as inventing operational pain, assuming manual processes or claiming a company has no website without properly checking.

Research beyond the homepage

A Linktree without a website link does not mean the business has no website.

The workflow cross-checks available sources such as:

Instagram / social profile
        ↓
Bio and direct profile links
        ↓
Linktree / Beacons / link hub
        ↓
Website
        ↓
Services / programmes
        ↓
Booking / registration
        ↓
Courses / memberships / events
        ↓
Forms / payments / external platforms
        ↓
Customer journey

Recent business activity and accessible decision-maker information also matter.

Inactive businesses, poor commercial fits and businesses with no meaningful opportunity should be discarded rather than added to the pipeline just to increase lead volume.

Lead classification

The skill deliberately avoids fake numerical probabilities such as:

“82% chance of closing.”

Instead, leads are classified using practical evidence.

Class

Meaning

Action

A+

Strong observable opportunity, active business, accessible decision maker and credible commercial fit

Contact with priority

A

Good fit with a useful opportunity and practical entry

Contact

B

Potential exists, but evidence, access or urgency is weaker

Do not prioritise

DISCARD

Inactive, poor fit, no worthwhile gap or uneconomic pursuit

Do not pursue

Opportunities are also separated by implementation type:

Quick Close — clear and relatively simple website or conversion opportunity.

Standard — professional website, information architecture and practical integrations.

High-Ticket — validated operational scope involving accounts, programmes, memberships, dashboards, admin workflows or integrations.

High-Ticket describes operational scope.

It does not mean “large company”.

Never move a warm lead backwards

Cold prospecting and active sales conversations require different behaviour.

Once a prospect has already requested:

an idea;

examples;

a portfolio;

pricing;

a proposal;

implementation details;

the skill prevents the agent from returning to:

“Would you like me to send you an idea?”

Before every follow-up, it checks what has already been sent.

The next message should advance the conversation toward:

Interest
   ↓
Relevant information
   ↓
Operational question
   ↓
Price
   ↓
Timeline
   ↓
Scope
   ↓
Approval

The core rule is simple:

Does this message advance the deal or repeat something the prospect already knows?

Sales does not end at the close

The same workflow continues after approval.

PROSPECT
   ↓
ANALYSE
   ↓
CONTACT
   ↓
QUALIFY
   ↓
DISCOVER
   ↓
PROPOSE
   ↓
CLOSE
   ↓
DELIVER
   ↓
EXPAND

Once a prospect becomes a client, the skill changes behaviour.

It begins tracking:

approved scope;

current implementation task;

client dependencies;

assets;

feedback;

blockers;

revisions;

risks;

next client communication.

New requests are classified as:

Minor adjustment
Reasonable inclusion
Scope expansion
Future phase

This helps prevent uncontrolled scope growth while keeping client communication consistent.

Quick start

1. Clone the repository

git clone https://github.com/gabrielsystems-ai/sales-prospecting-pipeline-skill.git

2. Add it to your agent environment

For Codex, place the skill folder inside your configured skills directory.

A common location is:

~/.codex/skills/sales-prospecting-pipeline-skill/

Your environment may use a different location, so follow the current loading instructions for your agent.

3. Invoke the skill

Example:

Use $sales-prospecting-pipeline-skill.

Analyse this business using public sources.

Cross-check the website, social profiles and connected links.
Separate facts from hypotheses.
Determine whether there is a commercially relevant digital opportunity.
Recommend one practical entry project.

Example

Input

Analyse this fitness academy.

They have an active Instagram account and appear to run several programmes.

I want to know whether they are a good prospect for a website or digital system project.

Possible output structure

# BUSINESS — LOCATION

Class: A+
Opportunity Type: Standard

## CONTACTS

Website:
Instagram:
WhatsApp:
Email:
Decision maker:

## FACTS

- The business currently promotes three active programmes.
- Registration links lead to an external form.
- A website exists and is mobile responsive.
- Instagram has recent operating activity.

## HYPOTHESES / UNKNOWNS

- It is unknown whether form submissions already feed an internal CRM.
- The registration handoff may create unnecessary friction, but operational impact has not been verified.

## MAIN OPPORTUNITY

Improve the programme discovery → registration journey while preserving the existing registration infrastructure where appropriate.

## RECOMMENDED ENTRY

Website and conversion-flow improvement with registration integration.

## VERDICT

CONTACT WITH PRIORITY

## OUTREACH

Short evidence-based outreach focused on the observed registration journey.

The skill should not invent revenue, budget, manual work, buying intent or technical limitations that were not observed.

Cold outreach

Cold outreach defaults to a short structure:

Specific observation
        ↓
One relevant opportunity
        ↓
One clear benefit
        ↓
Simple CTA

Usually around 35–75 words.

The objective is not to explain the entire solution in the first message.

The objective is to earn a meaningful response.

Avoid:

Huge diagnosis
Feature lists
Generic AI copy
Fake urgency
Unverified criticism
Invented ROI

Prefer:

Specific context
Plain language
One useful idea
One next action

Pipeline context

For an active prospect, the skill keeps track of:

# BUSINESS / CLIENT

Stage:
Decision maker:
Already sent:
Approved:
Open questions:
Current blocker:
Next action:
Last contact date:

Stages include:

A — PROSPECT

B — COLD CONTACT

C — WARM / INTERESTED

D — ACTIVE NEGOTIATION

E — CLIENT / PROJECT

F — WAITING / CLIENT DEPENDENCY

Waiting does not erase the underlying relationship stage.

A client waiting to provide content is still a client.

Commercial metrics

The skill can also help structure pipeline measurement.

Useful metrics include:

Metric

Meaning

Leads researched

Unique businesses actually analysed

Leads contacted

Businesses that received outreach

Meaningful response rate

Substantive responses / contacted prospects

Interest rate

Genuinely interested prospects / contacted prospects

Proposal rate

Proposals / interested prospects

Close rate

Approved projects / proposals

Average project value

Agreed project value / closed projects

Time to close

Time from first outreach to approval

Expansion rate

Existing clients purchasing additional work

Drafted messages and actually sent messages should be tracked separately.

Revenue agreed and revenue collected should also remain separate.

Repository structure

sales-prospecting-pipeline-skill/
│
├── SKILL.md
│   └── Main operating instructions
│
├── README.md
│   └── Project overview and usage
│
├── LICENSE
│   └── MIT License
│
├── agents/
│   └── openai.yaml
│
└── examples/
    ├── lead-analysis.md
    ├── cold-outreach.md
    ├── warm-lead-followup.md
    └── active-project.md

The examples are fictional and are intended to demonstrate behaviour without exposing private prospect or client information.

Example use cases

Use the skill when you want an agent to:

Research and qualify a new business
Analyse a website and customer journey
Determine whether a prospect is worth contacting
Draft cold WhatsApp / DM / email outreach
Continue an existing sales conversation
Prepare a follow-up without repeating the pitch
Structure discovery
Advance toward pricing and approval
Manage an active client project
Identify genuine expansion opportunities
Review pipeline performance

What this skill deliberately does not do

It does not:

guarantee replies or sales;

invent closing probabilities;

automatically send outreach;

scrape private information;

submit prospect forms;

trigger bookings or payments;

assume every business needs a redesign;

assume every disconnected-looking tool should be replaced;

turn every website opportunity into a CRM project;

treat follower count as proof of budget;

represent hypotheses as verified facts.

Sending messages or modifying external systems requires appropriate tools and explicit authorisation.

Designed for digital service businesses

The workflow is particularly suited to freelancers, agencies and consultants selling:

Websites
Website redesigns
Booking and registration flows
Client / member portals
Education platforms
Membership systems
Digital platforms
Admin systems
Integrations
Operational web applications

The recommended solution should always follow the evidence.

Not the seller's preferred technology.

Privacy

Real prospect pipelines, private conversations and client information should remain outside the public repository.

Public examples should not include:

real prospect identities;

private conversations;

personal contact information;

confidential project values;

private operational information;

identifiable combinations of client details.

All examples included in this repository are fictional.

Roadmap

Potential future improvements include:

More industry-specific examples

Evaluation scenarios for common prospecting mistakes

Additional pipeline output templates

Reference modules for research, outreach and project delivery

Improved compatibility guidance for different agent environments

The objective is to keep the core workflow small, understandable and useful rather than adding complexity for its own sake.

Contributing

Feedback, issues and improvements are welcome.

If you find a situation where the skill:

makes an unsupported assumption;

repeats a previous sales message;

incorrectly classifies a lead;

recommends unnecessary scope;

misses an important part of the customer journey;

open an issue with a fictional or anonymised reproduction when possible.

License

Released under the MIT License.

<div align="center">

Useful?

If this workflow improves how your agent researches prospects or manages sales conversations, consider giving the repository a ⭐.

Better research → better opportunities → better next actions.
</div>
