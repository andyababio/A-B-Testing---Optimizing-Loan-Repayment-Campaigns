# A/B Testing - Optimizing Loan Repayment Campaigns

# Logo

# PAYZEN
PayZen is a digital financial platform empowering individuals across Africa to take control of their finances with ease. From managing repayments and accessing instant loans to making smart investments, PayZen simplifies financial decisions with transparency, flexibility, and innovative technology, wuth a mission to create financial freedom and inclusion for everyone, whether in city centers or rural communities

## Problem Statement

Digital loan recovery campaigns at PayZen rely heavily on automated SMS and WhatsApp reminders. However, repayment rates in early-stage delinquency remain inconsistent, and it is unclear which message framing most effectively motivates customers to take action. Current campaigns use generic reminder language, which may not resonate equally across customer segments or behavioral contexts. This results in the following baseline KPI standings:

 - Repayment Rate: 41%
 - Repayment Mix: 73% Partial | 27% Full
 - Response Rate: 7.5%

## Campaign Objective

To increase loan repayment rates in early-stage delinquency (1–7 days past due) by optimizing the messaging used in automated recovery campaigns, while maintaining a positive customer experience.

## Hypothesis

#### Primary Hypothesis

Customers who receive empathetic, supportive repayment messages will have a higher repayment rate than customers who receive standard, transactional repayment reminders.

#### Null Hypothesis

There is no significant difference in repayment rates between customers who receive empathetic messages and those who receive standard repayment reminders.


## Test Scope & Assumptions

 - Campaign Type:
    - Automated digital recovery campaign
 - Channel:
    - Whatsapp
 - Customer Stage:
    - Early-stage delinquency (1–7 Days Past Due)
 - Test Duration:
    - Fixed campaign window (14 days)

## Variants Definition
 - Control Group (Variant A – Standard Reminder)
     - Message Type: Transactional / neutral reminder
     - Purpose: Represents the current baseline messaging used in recovery campaigns

  - Message:
     - “Your loan repayment is overdue. Please make payment immediately to avoid additional charges.”

 - Test Group (Variant B – Empathetic Framing)
     - Message Type: Supportive / empathetic reminder
     - Purpose: Tests whether emotional and supportive language improves repayment behavior

  - Message:
     - “We understand that unexpected challenges can arise. Making your repayment today helps you stay in good standing and continue accessing our services.”

#### Variable Being Tested
  - Single Variable: Message framing (tone and wording)
  - All other factors remain constant:
     - Channel
     - Timing
     - Frequency
     - Customer eligibility
   

## Target Population
Customers who meet all of the following criteria:
 - Active loan customers
 - 1–7 days past due (DPD)
 - Loan size: Small, Medium & Large
 - No active dispute or repayment plan
 - Eligible for automated digital recovery outreach


## Process Flow & Data Model

Click [here](https://github.com/andyababio/A-B-Testing---Optimizing-Loan-Repayment-Campaigns/blob/main/Procees_%26_data.md) to access the process and data set used.

## Insights
1. Campaign Coverage & Eligibility

 - The customer base consisted of 243 total customers, out of which 162 customers (≈67%) were in early-stage delinquency (1–7 DPD) and eligible for the campaign.
 - This indicates a significant portion of the portfolio is recoverable through early intervention, making digital recovery campaigns a high-impact lever.
 - Focusing the test on this segment was appropriate, as early-stage delinquent customers are more responsive to messaging-based nudges.

2. Repayment Performance by Variant

 - The empathetic message variant outperformed the control across the primary KPI:
    - Control repayment rate: 41.25%
    - Variant repayment rate: 56.10%
    - This represents a +14.85 percentage point uplift in repayment rate for the empathetic messaging.
    - The magnitude of uplift suggests that message framing plays a meaningful role in influencing repayment behavior, not just reminder frequency.

3. Repayment Quality (Partial vs Full)
 - Repayment composition was largely consistent across both variants:
    - Control: 80% partial | 20% full
    - Variant: 81% partial | 19% full
    - While the empathetic message significantly increased overall repayment likelihood, it did not materially change repayment completeness.
    - This indicates the campaign primarily drives action initiation rather than the ability to fully settle balances.

4. Customer Engagement & Response
 - The empathetic variant generated higher customer engagement:
    - Control response rate: 7.50%
    - Variant response rate: 10.98%
    - This reflects a ~46% relative increase in response rate, suggesting empathetic language encourages customers to engage rather than ignore messages.
    - Higher response rates likely contributed to the observed improvement in repayment outcomes.

5. Behavioral Insight Summary
 - Customers are more likely to act when messages acknowledge challenges and offer reassurance, rather than using strictly transactional language.
 - Increased engagement appears to correlate with improved repayment behavior, reinforcing the importance of tone and framing in digital collections.
 - However, repayment amounts remain constrained, implying financial capacity, not willingness, limits full repayment.

6. Key Takeaway

 - The test demonstrates that empathetic messaging is a low-cost, high-impact optimization for early-stage digital recovery campaigns.
 - While it does not shift repayment mix, it meaningfully improves repayment rates and customer engagement, validating its use at scale.

