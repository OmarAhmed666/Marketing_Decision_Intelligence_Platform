# Business Brief (v2)

## Purpose
Help a marketing manager decide which customers a campaign should reach, so money is spent where the campaign actually changes behavior and not on customers who would have bought anyway.

## 1. Who is the user?
A CRM / marketing manager at ONE mid-sized online retailer (in-house, not an agency with many clients). They run the weekly campaign calendar with a fixed budget.

## 2. The decisions
**Version 1 supports one decision:** for this week's campaign, which customers get the message, and which are deliberately left out. "Send nothing" is always a valid choice.

**Later versions add:**
- which offer each customer gets (none, 10% off, free shipping)
- which channel to use (email, SMS, push)

**Why start with one:** the three decisions multiply together, and the first one already needs the hardest part of the project (uplift).

## 3. What success looks like
- **Incremental revenue** compared with a control group that received nothing
- **Incremental profit** = incremental revenue − discount cost − contact cost
- Supporting only: ROI (incremental profit ÷ spend), cost per incremental purchase, conversion rate

The two main KPIs matter most. Conversion rate alone says nothing about cause.

## 4. Baseline to beat (how it works today, without the platform)
- **Rule A:** send a 10% discount email to every customer active in the last 90 days.
- **Rule B:** send only to the top RFM segments (recent, frequent, high-spending customers).

The platform succeeds if it gives higher incremental profit than Rule A and Rule B at the same budget.

## 5. Constraints and control group
- One fixed budget per campaign, and a cost per contact and per discount.
- A small random hold-out group (for example 10%) never receives the campaign. It is the control that makes "incremental" measurable.

## 6. Out of scope
- Assigning tasks to team members (a project-management tool, not decision intelligence)
- Serving multiple client companies
- Real-time or streaming sending
- Creating campaign content