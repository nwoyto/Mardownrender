# PenaltyBack Final 4-Sequence A/B Test

Prepared for: Nick Woytowitz  
Use case: Instantly AI cold email deployment  
Objective: Test link-driven vs meeting-driven CTAs across SMB and CPA audiences.

---

## 1. Campaign Structure

We are testing two audiences and two CTAs.

| Sequence | Audience | CTA Type | CTA |
|---|---|---|---|
| A | SMB | Link-driven | Send overview after reply |
| B | SMB | Meeting-driven | Quick call |
| C | CPA | Link-driven | Send client overview after reply |
| D | CPA | Meeting-driven | Partnership call |

Each sequence has four emails:

1. Pattern interrupt
2. Clarification
3. Credibility
4. Final nudge

The message stays consistent. The CTA is the main variable.

---

## 2. Core Message

Some businesses that paid IRS penalties or interest during the COVID period may have a recovery opportunity worth reviewing.

This is most relevant for companies that had:

- IRS penalties or interest
- balance-due notices
- late filings or delayed payments
- installment agreements
- PPP, ERC, or payroll disruption
- COVID-related operating disruption from 2020 to 2023

Do not imply they qualify. Do not promise a refund. Do not mention average refund size in cold email.

Use:

```text
May be worth reviewing.
```

Do not use:

```text
You are owed money.
```

---

## 3. Industry-Driven Personalized Hooks

Every email should start with:

```text
[Personalized Hook]
```

Use one short industry-driven line. Pick the relevant industry bucket and insert one sentence.

The hook should create relevance without sounding invasive.

### Healthcare

Use for medical practices, dental offices, therapy clinics, home health, urgent care, behavioral health, and specialty practices.

```text
Healthcare practices were hit hard during COVID, especially around staffing, shutdowns, and payment timing.
```

### Restaurants / Hospitality

Use for restaurants, bars, catering, hotels, food service, and hospitality groups.

```text
Restaurants and hospitality businesses had some of the messiest COVID-era operating disruption.
```

### Construction / Trades

Use for contractors, HVAC, electrical, plumbing, roofing, concrete, and specialty trades.

```text
Construction and trade businesses dealt with major project, payroll, and cash-flow disruption during COVID.
```

### Professional Services

Use for law firms, agencies, consultants, engineering firms, architecture firms, and other service businesses.

```text
Professional service firms often had payroll and tax-timing issues during the COVID period.
```

### General SMB Fallback

Use when industry is unknown or does not fit a priority vertical.

```text
Many businesses operating through 2020–2023 dealt with unusual tax and cash-flow timing issues.
```

### CPA / Accounting Firm

Use for CPAs, tax firms, enrolled agents, and accounting practices.

```text
Many CPA firms have business clients who may still need a second look at COVID-era penalties and interest.
```

---

## 4. CTA Rules

Do **not** put the work link in the cold email.

Use this structure:

```text
Cold email → micro-CTA → prospect replies → send overview link
```

Do not use:

```text
Reply Y.
```

Do not use “checklist.” It sounds like a PDF worksheet. The next step is an overview page or quick screen, so the language should match that.

Best link-driven CTA:

```text
Should I send the overview?
```

Best CPA link-driven CTA:

```text
Should I send the client overview?
```

Best meeting-driven CTA:

```text
Open to a quick call?
```

Best final-touch CTA:

```text
Should I close this out, or send the overview?
```

For the call-setting test, use one dedicated mailbox so we can measure whether direct-call CTAs outperform the overview CTA.

---

## 5. Footer

Use a plain footer.

```text
PenaltyBack
[Physical Mailing Address]

If this is not relevant, reply “not interested” and I will not follow up.
```

For Recover Tax:

```text
Recover Tax
[Physical Mailing Address]

Recover Tax helps businesses evaluate possible tax recovery opportunities and collaborates with PenaltyBack for specialist review. This message is not legal or tax advice. Eligibility depends on the facts of each case.

If this is not relevant, reply “not interested” and I will not follow up.
```

---

# Sequence A – SMB Link-Driven

Audience: SMB owners, operators, CFOs, controllers, finance contacts  
Sender: `penaltyback.co`  
CTA: Send overview after reply

---

## Email 1 – Pattern Interrupt

**Subject**

```text
IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some businesses that paid IRS penalties or interest during the COVID period may have a recovery opportunity worth reviewing.

This mainly applies if {{company_name}} had penalties, interest, IRS notices, tax balances, PPP, ERC, or payroll disruption from 2020 to 2023.

Should I send the overview?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject**

```text
2020–2023 IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The quick question is whether {{company_name}} paid IRS penalties or interest tied to the COVID period.

If yes, it may be worth checking before refund windows continue aging out.

Should I send the overview?
```

---

## Email 3 – Credibility

**Subject**

```text
Quick diagnostic
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

The first step is not a full tax review.

It is just a quick diagnostic to see whether there is even anything worth pursuing. If there is no penalty or interest history, this probably is not relevant.

Should I send the overview?
```

---

## Email 4 – Final Nudge

**Subject**

```text
Should I close this out?
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Last note from me.

If {{company_name}} did not pay IRS penalties or interest from the COVID period, this is probably not relevant.

If you did, it may be worth checking before refund windows continue aging out.

Should I close this out, or send the overview?
```

---

# Sequence B – SMB Meeting-Driven

Audience: SMB owners, operators, CFOs, controllers, finance contacts  
Sender: one dedicated call-setting mailbox  
CTA: Quick call

---

## Email 1 – Pattern Interrupt

**Subject**

```text
IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some businesses that paid IRS penalties or interest during the COVID period may have a recovery opportunity worth reviewing.

This mainly applies if {{company_name}} had penalties, interest, IRS notices, tax balances, PPP, ERC, or payroll disruption from 2020 to 2023.

I can ask a few quick questions and tell you whether this is even worth reviewing.

Open to a quick call?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject**

```text
2020–2023 IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The quick question is whether {{company_name}} paid IRS penalties or interest tied to the COVID period.

If yes, it may be worth a short screen before refund windows continue aging out.

Open to a 10-minute call this week?
```

---

## Email 3 – Credibility

**Subject**

```text
Quick diagnostic
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

The first step is not a full tax review.

It is just a quick diagnostic to see whether there is even anything worth pursuing. If there is no penalty or interest history, this probably is not relevant.

I can walk through the screen quickly.

Worth a short call?
```

---

## Email 4 – Final Nudge

**Subject**

```text
Should I close this out?
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Last note from me.

If {{company_name}} did not pay IRS penalties or interest from the COVID period, this is probably not relevant.

If you did, it may be worth checking before refund windows continue aging out.

Should we set up a quick call, or should I close this out?
```

---

# Sequence C – CPA Link-Driven

Audience: CPAs, tax preparers, enrolled agents, accounting firms  
Sender: `penaltyback.org`  
CTA: Send client overview after reply

---

## Email 1 – Pattern Interrupt

**Subject**

```text
Client penalty review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some business clients that paid IRS penalties or interest during the COVID period may have recovery opportunities worth reviewing.

This is most relevant for clients with penalties, interest, balance-due notices, late filings, installment agreements, PPP, ERC, or payroll disruption from 2020 to 2023.

Should I send the client overview?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject**

```text
Potential client refunds
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The basic screen is simple: did any of your business clients pay IRS penalties or interest during the COVID period?

If yes, it may be worth reviewing before refund windows continue aging out.

Should I send the overview?
```

---

## Email 3 – Credibility

**Subject**

```text
Specialized review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

This does not replace the CPA relationship.

It is a narrow diagnostic for COVID-era penalty and interest issues. The goal is to identify which clients are worth a closer look and which are not.

Should I send the client overview?
```

---

## Email 4 – Final Nudge

**Subject**

```text
Close the loop?
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

I’ll close the loop here.

If none of your clients paid IRS penalties or interest during the COVID period, this probably is not relevant.

If some did, it may be worth screening them before refund windows continue aging out.

Should I close this out, or send the overview?
```

---

# Sequence D – CPA Meeting-Driven

Audience: CPAs, tax preparers, enrolled agents, accounting firms  
Sender: dedicated advisory/call-setting mailbox  
CTA: Partnership call

---

## Email 1 – Pattern Interrupt

**Subject**

```text
Client penalty review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some business clients that paid IRS penalties or interest during the COVID period may have recovery opportunities worth reviewing.

This is most relevant for clients with penalties, interest, balance-due notices, late filings, installment agreements, PPP, ERC, or payroll disruption from 2020 to 2023.

I can walk through the client review criteria in a quick call.

Open to a short partnership conversation?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject**

```text
Potential client refunds
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The basic screen is simple: did any of your business clients pay IRS penalties or interest during the COVID period?

If yes, it may be worth reviewing before refund windows continue aging out.

Open to a 10-minute call to see if this applies to your client base?
```

---

## Email 3 – Credibility

**Subject**

```text
Specialized review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

This does not replace the CPA relationship.

It is a narrow diagnostic for COVID-era penalty and interest issues. The goal is to identify which clients are worth a closer look and which are not.

Worth a short call?
```

---

## Email 4 – Final Nudge

**Subject**

```text
Close the loop?
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

I’ll close the loop here.

If none of your clients paid IRS penalties or interest during the COVID period, this probably is not relevant.

If some did, it may be worth screening them before refund windows continue aging out.

Should we set up a quick partnership call, or should I close this out?
```

---

# Reply Handlers

## If They Say Yes to the Overview

```text
Hi {{first_name}},

Great. Here’s the overview:

{{overview_link}}

It explains what the review looks for, when it may apply, and what information is needed to determine whether there is anything worth pursuing.

The first step is just a quick screen. If there is no penalty or interest history, this probably is not relevant.

Best,
{{sender_name}}
```

---

## If a CPA Says Yes to the Client Overview

```text
Hi {{first_name}},

Great. Here’s the client overview:

{{overview_link}}

It explains the types of client situations that may be worth reviewing, how the process works, and where PenaltyBack fits into the recovery workflow.

Best,
{{sender_name}}
```

---

## If They Say Yes to Call

```text
Hi {{first_name}},

Great. Happy to walk through it.

Does {{time_option_1}} or {{time_option_2}} work?

If easier, here is my calendar:

{{calendar_link}}
```

---

## If They Ask What This Is About

```text
We help businesses review whether IRS penalties or interest paid during the COVID period may have been improperly assessed or worth challenging.

The first step is a quick screen. If there is no penalty or interest history, it is probably not relevant.
```

---

## If They Say Not Interested

```text
Understood. I will not follow up.

Best,
{{sender_name}}
```

---

# Instantly Deployment

## Campaign Tags

```text
SMB_LINK_A
SMB_MEETING_B
CPA_LINK_C
CPA_MEETING_D
```

## Required Fields

```text
{{first_name}}
{{company_name}}
{{industry}}
{{title}}
{{state}}
{{personalized_hook}}
{{sender_name}}
{{overview_link}}
{{calendar_link}}
```

## Cadence

```text
Email 1: Day 1
Email 2: Day 4
Email 3: Day 9
Email 4: Day 18
```

## Stop Rules

Stop immediately on:

- Reply
- Unsubscribe
- Bounce
- Complaint
- Not interested
- Wrong person

Continue if:

- Delivered but unopened
- Opened but no reply
- No click
- No site visit

---

# Test Metrics

Primary metric:

```text
Positive replies per 1,000 sends
```

Secondary metrics:

```text
Booked calls per 1,000 sends
Qualified reviews per 1,000 sends
Bounce rate
Unsubscribe rate
Negative reply rate
```

Winner selection should be based on qualified positive replies and booked reviews, not open rate.
