# Automated Customer Feedback Pipeline

## Overview

In this project, I built an automated customer feedback pipeline using:

- Google Forms  
- Make (workflow automation)  
- Gemini AI  
- Google Sheets  

The system collects customer feedback, analyzes sentiment automatically, and surfaces actionable insights in real time.

The objective: eliminate manual review, reduce response lag, and turn raw feedback into structured business intelligence.

---

## Problem

Manual feedback review creates:

- Delayed response times  
- Inconsistent analysis  
- Missed negative sentiment signals  
- No centralized insight tracking  

Businesses need real-time visibility into customer sentiment without increasing labor costs.

---

## Solution Architecture

### 1. Data Collection — Google Forms

Customers submit feedback through a structured Google Form.

Captured data includes:
- Customer rating
- Open-text comments
- Service category
- Timestamp

Form submissions automatically trigger the automation workflow.

---

### 2. Automation Layer — Make

Make acts as the orchestration engine.

Workflow steps:

1. Trigger on new Google Form submission  
2. Send open-text feedback to Gemini AI  
3. Receive structured sentiment analysis  
4. Parse and format output  
5. Log results in Google Sheets  

No manual intervention required.

---

### 3. AI Processing — Gemini AI

Gemini analyzes open-text responses and returns:

- Sentiment classification (Positive / Neutral / Negative)
- Confidence score
- Key themes
- Suggested action category

This transforms unstructured feedback into structured data.

---

### 4. Reporting Layer — Google Sheets

Google Sheets functions as a live analytics dashboard.

Logged data includes:

- Customer submission data
- AI sentiment score
- Extracted themes
- Flag status for negative feedback
- Timestamp

Conditional formatting highlights high-risk feedback automatically.

Managers can filter by:
- Sentiment
- Date range
- Category
- Escalation status

---

## Workflow Summary

1. Customer submits feedback  
2. Make triggers automation  
3. Gemini performs sentiment analysis  
4. Structured output is generated  
5. Results are logged in Google Sheets  
6. Negative sentiment is flagged for follow-up  

End-to-end process time: seconds.

---

## Business Impact

- Real-time visibility into customer sentiment  
- Faster response to negative experiences  
- Reduced manual review time  
- Standardized analysis across all feedback  
- Actionable insights instead of raw comments  

This system converts qualitative feedback into measurable operational signals.

---

## Key Features

- Fully automated pipeline  
- AI-driven sentiment classification  
- Theme extraction  
- Escalation flagging  
- Live reporting dashboard  
- Zero manual processing required  

---

## Technology Stack

- Google Forms  
- Make  
- Gemini AI  
- Google Sheets  

---

## Scalability

The system can be extended to:

- Send Slack alerts for negative sentiment  
- Create CRM tickets automatically  
- Generate weekly executive summaries  
- Track sentiment trends over time  
- Feed data into BI tools  

---

## Conclusion

This project demonstrates how AI and workflow automation can transform customer feedback from static data into real-time operational intelligence.

The result: faster decisions, reduced risk, and measurable customer experience improvement.
