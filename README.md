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
#### Control Group (Variant A – Standard Reminder)
  - Message Type: Transactional / neutral reminder
  - Purpose: Represents the current baseline messaging used in recovery campaigns

  - Message:
     - “Your loan repayment is overdue. Please make payment immediately to avoid additional charges.”

#### Test Group (Variant B – Empathetic Framing)
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


## Process Flow & Data Set

Click here to access the process and data set used.

