# SilentDrain
### Subscription, AutoPay & Hidden Payment Detection System

## About the Project

SilentDrain is a local-first financial analysis application designed to help users identify and understand recurring payments, forgotten subscriptions, unwanted AutoPay deductions, and hidden charges in their bank transactions.

Many people lose money through automatic payments without regularly noticing them. Subscriptions, OTT platforms, app memberships, free-trial renewals, loan-related recurring deductions, and other AutoPay mandates can silently deduct money from bank accounts.

SilentDrain aims to solve this problem by analyzing bank statements, detecting recurring transactions, identifying potential subscriptions, and highlighting suspicious or unnoticed payment patterns.

**Our goal is simple: Help people understand where their money goes and identify recurring payments that they may want to stop or manage.**

## Problem Statement

People frequently face financial problems because:

- Money gets automatically deducted through UPI AutoPay, debit cards, and other payment mandates.
- Forgotten subscriptions continue renewing.
- Free trials convert into paid subscriptions.
- Small recurring deductions go unnoticed.
- Users struggle to identify which merchants are repeatedly charging them.
- Tracking monthly recurring expenses manually is difficult.

SilentDrain addresses these problems through automated transaction analysis and recurring-payment detection.

## Proposed Solution

SilentDrain analyzes uploaded bank statements and helps users:

- Detect recurring payment patterns.
- Identify potential subscriptions.
- Discover unnoticed or potentially hidden recurring charges.
- Identify AutoPay-related transactions where statement information allows.
- Understand monthly and yearly recurring expenses.
- Identify merchants responsible for repeated deductions.
- Generate financial insights and downloadable reports.

**Note:** SilentDrain identifies potential recurring payments from transaction history. It does not directly cancel subscriptions or disable bank AutoPay mandates.

## Main Features

1. Bank Statement Upload
2. Transaction Processing
3. Merchant Identification
4. Recurring Payment Detection
5. Subscription Identification
6. AutoPay & Mandate-Related Payment Analysis
7. Hidden Payment Detection
8. Financial Analytics
9. Spending Pattern Analysis
10. Report Generation

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core application logic |
| Streamlit | User interface |
| SQLite | Local database |
| Pandas | Transaction processing |
| PyMuPDF | PDF statement extraction |
| OpenPyXL | Excel file processing |
| Plotly | Interactive financial visualizations |

## Application Type

Desktop-first, local-first web application.

## Privacy & Security

- Bank statements are processed locally.
- SQLite is used for local data storage.
- Financial information is not intentionally uploaded to a cloud server.
- Users maintain control over their financial data.

## Project Status

Initial Development – Architecture and foundational modules are being developed.

## Future Scope

- Improved AutoPay and UPI mandate identification.
- Advanced recurring payment detection.
- AI-based transaction classification.
- Subscription risk and spending insights.
- Automated alerts for upcoming recurring deductions.
- Better merchant recognition.
- Integration with authorized financial data sources, subject to applicable permissions.

## Project Vision

**SilentDrain – Detect the Silent Deductions. Take Control of Your Money.**