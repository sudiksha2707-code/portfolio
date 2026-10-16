# True Balance: Helping New-to-Credit Borrowers Make Their First Repayment

Product case study by Sudiksha Gupta · Independent concept work

> **In one line:** For a new-to-credit borrower, the first repayment decides their credit future. A clear repayment calendar, a well-explained UPI AutoPay step and timely reminders turn missed first payments into a good credit history.

---

## 1. Context

- True Balance, founded in 2014, combines payments (recharges, bill payments, wallet) with small-ticket personal loans in one app.
- Lending runs through its NBFC, True Credits Pvt Ltd, and targets underbanked and new-to-credit customers that banks often avoid.
- It has disbursed more than $30 million in loans in the current financial year and raised $10 million in debt in March 2026 to expand lending.

**Why it matters:** for small-ticket loans, a missed first payment is the earliest and strongest signal of loss. It also damages a first-time borrower's credit record before it has even started.

---

## 2. Problem

**Example user: Ramesh, 29, delivery partner, Jaipur**

| | |
| --- | --- |
| Loan | ₹8,000, his first ever |
| At disbursal | Money arrives in minutes; he skips the optional AutoPay step |
| The due date | He thinks it's the 10th; it's the 5th |
| Result | Misses the payment, gets late fees and a negative bureau entry |

Ramesh intended to pay. He just didn't know when or how much.

---

## 3. Insights

- **Many first misses are confusion, not unwillingness.** Due dates, amounts and fees are shown once, at disbursal, when the borrower is focused on getting the money.
- **AutoPay is easy to skip.** Users worry about money being taken without warning, so they decline it.
- **Reminders come too late.** A message on the due date leaves no time to arrange funds.
- **Cash flow is irregular.** Gig and daily-wage workers may have part of the amount on the due date, but not all of it.

*To validate:* first-payment default rate split by AutoPay status; reminder open rates against payment timing; calls from borrowers asking about due dates.

---

## 4. Hypothesis

If borrowers see a simple repayment calendar at disbursal, set up UPI AutoPay with a plain explanation, and get reminders days before the due date, more first repayments will be paid on time.

---

## 5. Competitive landscape

| | True Balance today | Other small-ticket lending apps |
| --- | --- | --- |
| Fast disbursal | Yes | Yes |
| Repayment calendar at disbursal | Opportunity | Varies |
| AutoPay with plain-language explanation | Opportunity | Varies |
| Part-payment before due date | Opportunity | Rare |

**Takeaway:** disbursal speed is table stakes. Repayment experience is where lenders differentiate on loss rates.

---

## 6. Solution

| Priority | Feature | What it does |
| --- | --- | --- |
| High | Repayment calendar | Shows every due date and exact amount at disbursal, saved to the phone calendar in one tap |
| High | Plain AutoPay step | Explains in simple words: what is debited, when, and how to cancel; set as the default |
| High | Early reminders | App and WhatsApp messages 3 days and 1 day before the due date, with a pay link |
| Medium | Part-pay option | Lets users pay what they can before the due date to reduce penalties |
| Medium | First-repayment reward | A small benefit (such as a higher next limit) for paying on time |

**User flow**

1. Loan approved: a calendar card shows "₹2,150 due on 5 June" for each instalment.
2. AutoPay step: "We'll take ₹2,150 on 5 June from your UPI. You'll get a message 3 days before. Cancel anytime." Set up in one approval.
3. Three days before: "Your payment of ₹2,150 is due on 5 June. Pay now or keep ₹2,150 in your account."
4. One day before: a final reminder with a one-tap pay link.
5. If the user is short: "Pay part now to reduce late fees."
6. After an on-time payment: "Great start. Your next limit can go up to ₹12,000."

---

## 7. Success metrics

| Metric | Target |
| --- | --- |
| First repayment paid on time | Primary metric |
| AutoPay set-up rate at disbursal | Increase |
| Payments made after a pre-due reminder | Increase |
| Second-loan uptake among on-time payers | Increase |
| Loan disbursal conversion | Guardrail: no drop from the extra step |

---

## 8. Risks and trade-offs

| Risk | Mitigation |
| --- | --- |
| Extra AutoPay step slows disbursal | Keep it to one screen; test default-on vs optional |
| Users feel AutoPay is risky | Clear amounts, dates, advance notice and easy cancellation |
| Reminder overload | Only two pre-due messages per instalment |
| Part-pay encourages late full payment | Show clearly how much fee is saved by paying in full on time |

---

## 9. Rollout

1. **Test:** calendar plus early reminders for all new borrowers (low effort, low risk).
2. **Test:** AutoPay as a strong default vs optional, measuring both on-time rate and disbursal conversion.
3. **Expand:** add part-pay and the on-time reward once the first two show results.

---

## 10. Conclusion

For new-to-credit borrowers, the first repayment is the moment that builds or breaks a credit history. True Balance can protect both its loan book and its customers by making the date, the amount and the payment itself impossible to miss.

---

*Sources: TechStory and CXO Digital Pulse on True Balance's $10 million debt raise (March 2026). Loan amounts and user examples are illustrative. Verify current product flows before publishing.*
