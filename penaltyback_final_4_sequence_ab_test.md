# PenaltyBack / Recover Tax Final Outbound Sequences

Prepared for: Nick Woytowitz  
Use case: Instantly AI cold email deployment  
Objective: Test CTA type across two audiences while keeping the core narrative consistent.

---

## 1. Campaign Structure

This campaign tests two variables:

1. **Audience**
   - SMBs
   - CPAs / accounting firms

2. **CTA type**
   - Link-driven CTA
   - Meeting-driven CTA

That creates four total sequences:

| Sequence | Audience | CTA Type | Primary CTA |
|---|---|---|---|
| Sequence A | SMB | Link-driven | Check eligibility / reply for link |
| Sequence B | SMB | Meeting-driven | Book or agree to a quick call |
| Sequence C | CPA | Link-driven | Refer clients / review criteria via link |
| Sequence D | CPA | Meeting-driven | Book a partnership call |

Each sequence has four emails:

1. Pattern interrupt
2. Clarification
3. Credibility
4. Final nudge

The narrative should stay consistent. The major difference between A and B, or C and D, should be the CTA.

---

## 2. Messaging Rules

Keep the copy short, plain, and direct.

Avoid large refund claims, average refund claims, or hard promises.

Do not say:

```text
You are owed money.
```

Do not say:

```text
Businesses are getting back an average of $X.
```

Do not say:

```text
The IRS owes you money.
```

Use safer framing:

```text
Some businesses that paid IRS penalties or interest during the COVID period may have a recovery opportunity worth reviewing.
```

```text
This is worth checking only if the business paid penalties, interest, or had IRS balance-due issues from the COVID period.
```

```text
Eligibility depends on the facts, notices, transcripts, and payment history.
```

---

## 3. Personalization Hook Format

Every email starts with:

```text
[Personalized Hook]
```

This should be generated dynamically by an LLM.

Good examples:

```text
Looks like {{company_name}} was operating during the COVID period.
```

```text
I was looking at {{industry}} businesses that were active from 2020 to 2023.
```

```text
Noticed you work with small-business tax clients, so this may be relevant.
```

```text
Looks like {{company_name}} has been operating since before the pandemic.
```

Do not make the personalized hook too long. It should be one short sentence.

---

## 4. Recommended Footer

Use a plain footer.

```text
PenaltyBack
[Physical Mailing Address]

If this is not relevant, reply “not interested” and I will not follow up.
```

For Recover Tax collaboration language:

```text
Recover Tax
[Physical Mailing Address]

Recover Tax helps businesses evaluate possible tax recovery opportunities and collaborates with PenaltyBack for specialist review. This message is not legal or tax advice. Eligibility depends on the facts of each case.

If this is not relevant, reply “not interested” and I will not follow up.
```

---

# Sequence A – SMB Link-Driven

Audience: SMB owners, operators, CFOs, controllers, finance contacts  
Sender voice: Direct, simple  
CTA: Reply to receive eligibility link or check eligibility through website  
Best sender domain: `penaltyback.co`  
Alternative trust path: `recovertax.net` landing page after reply

---

## Email 1 – Pattern Interrupt

**Subject options**

```text
IRS penalties
```

```text
COVID tax penalties
```

```text
Quick tax question
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some businesses that paid IRS penalties or interest during the COVID period may have a recovery opportunity worth checking.

This mainly applies if {{company_name}} had penalties, interest, IRS notices, tax balances, PPP, ERC, or payroll disruption from 2020 to 2023.

I can send over a short eligibility check.

Worth sending?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject options**

```text
2020–2023 IRS penalties
```

```text
Re: IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The quick question is whether {{company_name}} paid IRS penalties or interest tied to the COVID period.

Best-fit cases usually involve:

- IRS penalties or interest
- balance-due notices
- late filings or delayed payments
- installment agreements
- PPP, ERC, or payroll disruption

If any of that happened, it may be worth a quick check.

Should I send the eligibility link?
```

---

## Email 3 – Credibility

**Subject options**

```text
Quick diagnostic
```

```text
Checking this properly
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

A common reason businesses ignore this is because they assume reviewing old tax years means digging through piles of paperwork.

That is not the goal here.

The first step is just a quick diagnostic to see whether there is even anything worth reviewing. If there is no penalty or interest history, it is probably not relevant.

Want me to send the secure eligibility link?
```

---

## Email 4 – Final Nudge

**Subject options**

```text
Should I close this out?
```

```text
Closing the loop
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Last note from me.

If {{company_name}} did not pay IRS penalties or interest from the COVID period, this is probably not relevant.

If you did, it may be worth checking before refund windows continue aging out.

Should I send the eligibility link, or close this out?
```

---

# Sequence B – SMB Meeting-Driven

Audience: SMB owners, operators, CFOs, controllers, finance contacts  
Sender voice: Direct, simple  
CTA: Book or agree to a short call  
Best sender domain: `penaltyback.co`  
Recommended test: Use one dedicated mailbox for this sequence so call-setting performance can be measured cleanly.

---

## Email 1 – Pattern Interrupt

**Subject options**

```text
IRS penalties
```

```text
COVID tax penalties
```

```text
Quick tax question
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some businesses that paid IRS penalties or interest during the COVID period may have a recovery opportunity worth checking.

This mainly applies if {{company_name}} had penalties, interest, IRS notices, tax balances, PPP, ERC, or payroll disruption from 2020 to 2023.

I can ask a few quick questions and tell you whether this is even worth reviewing.

Open to a quick call?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject options**

```text
2020–2023 IRS penalties
```

```text
Re: IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The quick question is whether {{company_name}} paid IRS penalties or interest tied to the COVID period.

Best-fit cases usually involve:

- IRS penalties or interest
- balance-due notices
- late filings or delayed payments
- installment agreements
- PPP, ERC, or payroll disruption

If any of that happened, it may be worth a quick screen.

Open to a 10-minute call this week?
```

---

## Email 3 – Credibility

**Subject options**

```text
Quick diagnostic
```

```text
Checking this properly
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

A common reason businesses ignore this is because they assume reviewing old tax years means digging through piles of paperwork.

That is not the goal here.

The first step is just a quick diagnostic to see whether there is even anything worth reviewing. If there is no penalty or interest history, it is probably not relevant.

I can walk through the screen with you quickly.

Worth a short call?
```

---

## Email 4 – Final Nudge

**Subject options**

```text
Should I close this out?
```

```text
Closing the loop
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

Audience: CPAs, accounting firms, tax preparers, enrolled agents  
Sender voice: Advisory, partner-oriented  
CTA: Reply for client-screening checklist or partner page  
Best sender domain: `penaltyback.org`  
Optional trust path: Recover Tax partner page

---

## Email 1 – Pattern Interrupt

**Subject options**

```text
Client penalty review
```

```text
COVID penalty refunds
```

```text
2020–2023 IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some business clients that paid IRS penalties or interest during the COVID period may have recovery opportunities worth reviewing.

This is most relevant for clients with penalties, interest, balance-due notices, late filings, installment agreements, PPP, ERC, or payroll disruption from 2020 to 2023.

I can send over the short client-screening checklist.

Worth sending?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject options**

```text
Potential client refunds
```

```text
Re: client penalty review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The basic screen is simple: did any of your business clients pay IRS penalties or interest during the COVID period?

If yes, it may be worth reviewing before refund windows continue aging out.

We are not trying to replace the CPA relationship. This is a focused review for a narrow penalty and interest issue.

Should I send the checklist?
```

---

## Email 3 – Credibility

**Subject options**

```text
Checking alongside the CPA
```

```text
Specialized review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

A lot of firms are already handling normal compliance, but this is more specific.

Think of it as a narrow diagnostic for COVID-era penalty and interest issues. It is meant to help identify which clients are worth a closer look and which are not.

If useful, I can send the review criteria your team can use internally.

Worth sending?
```

---

## Email 4 – Final Nudge

**Subject options**

```text
Close the loop?
```

```text
Should I close this out?
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

I’ll close the loop here.

If none of your clients paid IRS penalties or interest during the COVID period, this probably is not relevant.

If some did, it may be worth screening them before refund windows continue aging out.

Should I send the client-screening checklist, or close this out?
```

---

# Sequence D – CPA Meeting-Driven

Audience: CPAs, accounting firms, tax preparers, enrolled agents  
Sender voice: Advisory, partner-oriented  
CTA: Book or agree to a partnership call  
Best sender domain: `penaltyback.org`  
Recommended test: Use one dedicated mailbox or a clearly tagged Instantly campaign.

---

## Email 1 – Pattern Interrupt

**Subject options**

```text
Client penalty review
```

```text
COVID penalty refunds
```

```text
2020–2023 IRS penalties
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Some business clients that paid IRS penalties or interest during the COVID period may have recovery opportunities worth reviewing.

This is most relevant for clients with penalties, interest, balance-due notices, late filings, installment agreements, PPP, ERC, or payroll disruption from 2020 to 2023.

I can walk you through the client-screening criteria in a quick call.

Open to a short partnership conversation?

Best,
{{sender_name}}
```

---

## Email 2 – Clarification

**Subject options**

```text
Potential client refunds
```

```text
Re: client penalty review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

Following up briefly.

The basic screen is simple: did any of your business clients pay IRS penalties or interest during the COVID period?

If yes, it may be worth reviewing before refund windows continue aging out.

We are not trying to replace the CPA relationship. This is a focused review for a narrow penalty and interest issue.

Open to a 10-minute call to see if this applies to your client base?
```

---

## Email 3 – Credibility

**Subject options**

```text
Checking alongside the CPA
```

```text
Specialized review
```

**Body**

```text
Hi {{first_name}},

[Personalized Hook]

A lot of firms are already handling normal compliance, but this is more specific.

Think of it as a narrow diagnostic for COVID-era penalty and interest issues. It is meant to help identify which clients are worth a closer look and which are not.

I can walk through the criteria and partnership flow quickly.

Worth a short call?
```

---

## Email 4 – Final Nudge

**Subject options**

```text
Close the loop?
```

```text
Should I close this out?
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

## If prospect says yes to eligibility link

```text
Hi {{first_name}},

Great. Here is the eligibility check:

{{eligibility_link}}

The quick screen is meant to determine whether there is anything worth reviewing. Refund amounts vary by taxpayer and depend on the facts, notices, transcripts, and payment history.

Let me know if you run into any questions.
```

---

## If prospect says yes to call

```text
Hi {{first_name}},

Great. Happy to walk through it.

Does {{time_option_1}} or {{time_option_2}} work?

If easier, here is my calendar:

{{calendar_link}}
```

---

## If CPA says yes to checklist

```text
Hi {{first_name}},

Great. The quick client screen is:

1. Did the client pay IRS penalties or interest tied to 2020–2023?
2. Did they receive balance-due notices, late-filing penalties, late-payment penalties, or installment-agreement charges?
3. Did they have PPP, ERC, payroll disruption, or COVID-related operating disruption?
4. Are notices, transcripts, or payment records available?

If the answer is yes to the first question and at least one of the others, it may be worth a closer review.

Happy to send over the partner page or walk through the process.
```

---

## If SMB asks what this is about

```text
We help businesses review whether IRS penalties or interest paid during the COVID period may have been improperly assessed or worth challenging.

The first step is a short screen. If there is no penalty or interest history, it is probably not relevant.
```

---

## If they say not interested

```text
Understood. I will not follow up.

Best,
{{sender_name}}
```

---

## If they say wrong person

```text
Thanks for letting me know.

Who would be the right person to ask about IRS penalties, tax notices, or finance/tax matters for {{company_name}}?
```

---

# Instantly AI Deployment Notes

## Campaign Tags

Use separate campaign tags so performance does not get mixed.

```text
SMB_LINK_A
SMB_MEETING_B
CPA_LINK_C
CPA_MEETING_D
```

## Required Custom Fields

```text
{{first_name}}
{{company_name}}
{{industry}}
{{title}}
{{state}}
{{personalized_hook}}
{{sender_name}}
{{eligibility_link}}
{{calendar_link}}
```

## CTA Type Field

Create a field called:

```text
cta_type
```

Allowed values:

```text
link
meeting
```

## Recommended Cadence

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
- Wrong person, then find another contact

Continue if:

- Delivered but unopened
- Opened but no reply
- No click
- No site visit

Open tracking should not drive core decisions.

---

# Test Design

## Primary Metric

```text
Positive replies per 1,000 sends
```

## Secondary Metrics

```text
Booked calls per 1,000 sends
Qualified reviews per 1,000 sends
Bounce rate
Unsubscribe rate
Negative reply rate
```

## Test Interpretation

If link-driven wins on replies but meeting-driven wins on booked calls, compare downstream qualified reviews.

If meeting-driven gets fewer replies but more qualified calls, it may still be better.

If link-driven gets more total replies but many are low intent, use it as the top-of-funnel CTA and push calls only after affirmative replies.

---

# Final Recommendation

Launch all four tests, but keep the first sample size small.

Suggested starting allocation:

| Sequence | Initial Send Volume |
|---|---:|
| SMB Link | 250–500 |
| SMB Meeting | 250–500 |
| CPA Link | 250–500 |
| CPA Meeting | 250–500 |

Do not expand until bounce rate, unsubscribe rate, negative reply rate, and positive reply quality are reviewed.

The first winner should be chosen by qualified positive replies, not open rate.
