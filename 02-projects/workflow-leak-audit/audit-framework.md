# Workflow Leak Audit Framework

## Purpose
Turn the Workflow Leak Audit into a repeatable, practical delivery system without expanding it into a software build.

The audit lens is simple: find where attention, ownership, timing, or information breaks down between a customer action and the business response.

## Source of Truth
Use this folder with:

- `01-business/offers.md`
- `02-projects/workflow-leak-audit/offer.md`
- `02-projects/workflow-leak-audit/ideal-clients.md`
- `04-proof-and-examples/wins-and-receipts.md`

## Leak Categories

### 1. Lead Capture Leaks
Lead capture leaks happen when new opportunities are not captured, routed, or acknowledged consistently.

Questions to ask:

- Where do new inquiries arrive?
- Are all lead sources visible in one place?
- Who owns the first response?
- How quickly does follow-up happen?
- What happens to missed calls, voicemails, website forms, social messages, and referrals?
- Are any lead sources checked only when someone remembers?

### 2. Follow-Up Leaks
Follow-up leaks happen when an opportunity receives an initial response but does not receive consistent next steps.

Questions to ask:

- What happens after the first reply?
- Are quotes, estimates, or proposals tracked?
- Are there reminders for second and third touches?
- Does follow-up stop when the owner or staff get busy?
- What follow-up happens after a customer asks for information but does not book?
- What follow-up happens after an estimate is sent?

### 3. Handoff Leaks
Handoff leaks happen when ownership moves between people, tools, or stages without a clear next action.

Questions to ask:

- Where does responsibility move between people or tools?
- What information gets retyped, missed, or misunderstood?
- Are next steps clear after each handoff?
- Who confirms that the handoff was completed?
- Where do handoffs depend on memory, sticky notes, texts, or informal reminders?

### 4. Customer Recovery Leaks
Customer recovery leaks happen when stale, canceled, inactive, or completed customer opportunities are not reviewed.

Questions to ask:

- Are no-shows, cancellations, stale quotes, or inactive customers reviewed?
- Is there a process for reactivation or follow-up recovery?
- Are completed jobs used for reviews, referrals, repeat work, or next-step offers?
- Who owns recovery follow-up?
- How often are old opportunities reviewed?

### 5. Visibility Leaks
Visibility leaks happen when the owner or team cannot quickly see what is stuck, aging, unassigned, or at risk.

Questions to ask:

- Can the owner quickly see what is stuck?
- Are important workflows hidden in email, text, spreadsheets, personal memory, or disconnected tools?
- Which reports, lists, dashboards, or check-ins are missing?
- What does the owner have to ask manually to understand the current state?
- What information is available only by searching across multiple systems?

## Intake Questions

### Business Owner Questions
- What parts of the business feel most dependent on your memory?
- Where do you suspect opportunities are slipping through the cracks?
- What do you wish you could see at a glance each week?
- Which follow-up tasks are most likely to be delayed when the team is busy?
- Where do customers most often wait, get confused, or need to ask again?
- What would make the business feel more controlled without adding unnecessary complexity?

### Lead Source Questions
- Where do new leads come from today?
- Which sources create calls, forms, texts, emails, social messages, referrals, or walk-ins?
- Which sources are checked manually?
- Which sources are connected to a CRM, spreadsheet, inbox, or calendar?
- What happens if a lead arrives after hours?
- What happens if the first contact attempt fails?

### Missed Calls, Forms, Quotes, Estimates, and Follow-Up Questions
- How are missed calls reviewed?
- How are voicemails assigned?
- How are website forms confirmed and followed up?
- How are quotes or estimates tracked after they are sent?
- How many follow-up attempts are expected before an opportunity is closed?
- Who owns stale quotes, pending estimates, no-shows, and unscheduled leads?
- What messages are approved for follow-up, and what messages need human review?

### Handoff and Manual Process Questions
- Where does work move from sales to scheduling, service, delivery, billing, or support?
- What information is copied from one tool to another?
- What information is often missing at the next step?
- Which tasks are done in spreadsheets, email folders, text threads, or staff memory?
- What must be approved by a person before it moves forward?
- Which tasks should not be automated without explicit approval?

### Current Tools Questions
- Which inboxes, CRMs, calendars, spreadsheets, phone systems, forms, or project tools are used?
- Which tools are trusted by the team?
- Which tools are ignored, duplicated, or used inconsistently?
- What reports or exports are available?
- What tool access can be reviewed safely during the audit?
- Which tool changes are off limits unless separately approved?

## Scoring Model
Score each finding from 1 to 5 in each category.

### Ease Score
- 1 = Hard to fix; likely requires major process or tool changes.
- 3 = Moderate effort; requires owner decision and some process cleanup.
- 5 = Easy to fix; likely a checklist, reminder, message, view, or simple operating rule.

### Impact Score
- 1 = Low operational or customer impact.
- 3 = Meaningful improvement to consistency, visibility, or customer experience.
- 5 = High missed-opportunity potential or major owner/staff pain.

### Urgency Score
- 1 = Can wait.
- 3 = Should be addressed soon.
- 5 = Actively causing delay, confusion, missed follow-up, or visible owner pain.

### Confidence Score
- 1 = Mostly hypothesis; needs more evidence.
- 3 = Supported by examples or process review.
- 5 = Clearly visible in tools, records, owner examples, or repeated patterns.

### Priority Ranking Logic
Use this practical ranking formula:

`Priority Score = Impact + Urgency + Confidence + Ease`

Then sort findings by:

1. Highest priority score.
2. Highest impact score.
3. Highest urgency score.
4. Easiest safe quick win.
5. Kevin's judgment when context requires it.

Do not present the score as guaranteed financial value. Use it to guide practical order of operations.

## Report Outline

### 1. Executive Summary
- What was reviewed.
- The main workflow leakage pattern.
- The top 3 opportunities to improve consistency.
- What remains `TBD`.

### 2. Top Workflow Leaks
For each leak:

- Leak category.
- Where it appears.
- Why it matters.
- Evidence or observation source.
- Confidence level.

### 3. Ranked Recovery Opportunities
Include a ranked table with:

- Finding name.
- Leak category.
- Ease score.
- Impact score.
- Urgency score.
- Confidence score.
- Priority score.
- Recommended first action.

### 4. Recommended Quick Wins
List practical fixes that can improve the workflow without major tool changes.

Examples:

- Create a daily missed-call review rule.
- Add a stale-estimate follow-up list.
- Define owner for each inbound source.
- Create a weekly stuck-opportunity check.
- Write approved follow-up message templates.

### 5. Recommended System Fixes
List larger improvements that may require separate approval.

Examples:

- CRM cleanup.
- Inbox routing rules.
- Reporting view.
- Follow-up workflow design.
- Human-approved AI draft support.

### 6. Implementation Boundaries
Clarify what is included in the audit and what requires separate approval.

### 7. Next-Step Options
Offer practical next steps without pressure or guaranteed outcomes.

Examples:

- Review findings with Kevin.
- Approve quick wins.
- Scope implementation separately.
- Add missing tool access or data.
- Park lower-priority items.

## Example Finding Format

```markdown
## Finding: [Leak title]

- Leak category: [Lead capture / Follow-up / Handoff / Customer recovery / Visibility]
- Where it appears: [Tool, step, team handoff, or process area]
- Why it matters: [Plain-English operational risk]
- What is likely being lost: [Missed responses, stale estimates, owner time, customer clarity, etc.]
- What to fix first: [Smallest practical next action]
- AI-assisted opportunity: [Drafting, triage, reminders, summaries, visibility, etc.]
- Human approval needed: [Yes / No / TBD]
- Ease score: [1-5]
- Impact score: [1-5]
- Urgency score: [1-5]
- Confidence score: [1-5]
- Priority score: [Total]
- Confidence level: [Low / Medium / High]
- TBD items: [Missing access, examples, owner decision, approved wording, etc.]
```

## Recommendation Style
Recommendations should be practical, specific, and tool-aware without requiring a new system unless the workflow clearly needs one.

Use plain English. Lead with missed opportunity, missed follow-up, operational leakage, and workflow clarity rather than AI hype.

## Implementation Handoff Boundaries

### The Audit Includes
- Review of current workflow patterns based on provided information.
- Identification of likely workflow leaks.
- Scoring and ranking of findings.
- Practical quick-win recommendations.
- Suggested system fixes that may be scoped separately.
- Clear `TBD` items where more information is needed.

### The Audit Does Not Automatically Include
- Building automations.
- Changing CRMs or tools.
- Writing production software.
- Connecting accounts or databases.
- Sending messages on behalf of the business.
- Replacing human approval for sensitive decisions.

### Requires Separate Approval
- Any implementation work.
- Any customer-facing message automation.
- Any tool change, data migration, or integration.
- Any use of private customer data beyond the audit scope.
- Any AI-generated message that would be sent externally.

### Should Not Be Automated Without Approval
- Pricing changes.
- Discounts or refunds.
- Legal, medical, financial, or compliance-sensitive responses.
- Hiring, firing, or employee discipline communication.
- Customer promises, guarantees, or commitments.
- Messages involving complaints, disputes, or sensitive personal information.

## TBD Items
- Final delivery format.
- Timeline.
- Pricing.
- Required tool access.
- Report template design.
- Whether implementation is sold separately or bundled.
