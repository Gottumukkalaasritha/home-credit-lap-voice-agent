# Home Credit Loan Against Property — AI Voice Agent

## Project Overview

This project is an AI-powered voice agent built using Bolna for preliminary Loan Against Property (LAP) eligibility screening for Home Credit.

The agent conducts a natural-language conversation with customers, collects relevant property and financial eligibility information, and provides a preliminary eligibility outcome based on the information shared.

## Objectives

- Automate preliminary loan eligibility conversations.
- Ask customers clear questions one at a time.
- Collect and verify relevant eligibility information.
- Handle unclear answers through appropriate clarification.
- Route eligible customers to a senior loan expert for further assistance.
- Follow responsible communication and customer privacy safeguards.

## Technology Used

- **Bolna:** Voice agent platform
- **Prompt Engineering:** Conversation flow, instructions, and guardrails
- **GitHub:** Project documentation and version control

## Eligibility Screening Workflow

The agent asks about:

1. Customer identity and availability to talk.
2. Property type: residential, commercial, industrial, or agricultural.
3. Property ownership: sole or joint.
4. Property location.
5. Availability of original property documents.
6. Existing loan against the property.
7. Occupation: salaried or self-employed.
8. Income mode: bank account or cash.
9. Approximate property market value.
10. Requested loan amount, up to ₹75 lakh.
11. Preferred repayment tenure, between 3 and 15 years.

Agricultural property and cash-based income do not meet the stated eligibility criteria. Other answers are assessed according to the configured screening rules.

## Conversation Handling

The agent is designed to:

- Confirm the customer's identity before revealing offer details.
- Ask one question at a time.
- Clarify ambiguous answers without unnecessarily repeating questions.
- Handle busy customers and declined offers politely.
- Escalate existing property-loan or EMI-reduction enquiries to a specialist.
- Refer questions about exact interest rates to a senior loan expert.

## Safety and Guardrails

- Never guarantee loan approval.
- Never invent interest rates or promise unconfirmed callback times.
- Do not request OTPs, passwords, card details, or bank account credentials.
- Do not disclose offer details to the wrong person.
- Make clear that final approval depends on the lender's assessment.

## Testing

Initial testing was performed through the Bolna call history. The first recorded test covered property details, joint ownership, income mode, property value, requested loan amount, and repayment tenure.

Further scenario testing is pending, including ineligible property types, unclear answers, busy customers, and escalation cases.

## Project Links

- **Bolna Agent:** https://bolna.ai/a/193da399-e009-4788-bb1c-4fc44f366f68
- **Call Recordings and Transcripts:** Available in the Bolna call history, subject to access permissions.

## Project Status

The initial voice agent and GitHub documentation have been created. Additional testing and final assignment evidence are still in progress.
