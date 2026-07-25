# Day 59 – Community Showcase

## Product
RecognitionIQ – AI-powered Employee Recognition Assistant

## User Problem
HR teams spend significant time reviewing nominations and drafting recognition messages. RecognitionIQ standardizes recommendations while reducing manual effort.

## System Architecture

User → HTML UI → Claude API → Recommendation Engine → Recognition Report

## Three Engineering Decisions

1. Built as a single HTML application for easy deployment.
2. Used a structured system prompt for consistent recognition recommendations.
3. Included graceful error handling and loading states for better user experience.

## Evaluation

- Accuracy: 90/100
- Usability: 94/100
- UI: 95/100
- Performance: 92/100

## If rebuilding today

Add user authentication, workflow approvals, Microsoft Teams integration, and analytics dashboards.
Peer Reviews

## Review 1

Strength:
Excellent dashboard design.

Question:
Why did you choose local storage instead of a database?

Suggestion:
Add export to PDF for reporting.

---

## Review 2

Strength:
Clear navigation.

Question:
# 
How is prompt consistency maintained?

Suggestion:
Include retry handling for API failures.

---

## Review 3

Strength:
Responsive interface.

Question:
How will you scale for multiple users?

Suggestion:
Implement role-based access control.


