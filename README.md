# My first AI Email Assistant

This n8n workflow automates email generation and delivery using AI. The system is triggered via chat, processes data from Google Sheets through OpenAI, and automatically composes and sends tailored email messages.

## Business Benefits
- Saves Hours of Manual Work: Eliminates the need for a human to manually copy data, draft text, and hit send on repetitive emails.
- 24/7 Instant Responses: Ensures clients or leads receive highly personalized email follow-ups instantly at any time of day.
- Reduces Data Entry Errors: Automatically pulls direct information from Google Sheets, removing the risk of typos or sending emails to the wrong address.
- Scalable Customer Outreach: Allows a single team member to handle hundreds of inquiries effortlessly without losing a personalized touch.

## Features
- Automated Workflows: Processes data and dispatches emails with zero manual intervention.
- AI-Powered Copywriting: Utilizes OpenAI to analyze context and draft custom email responses.
- Data Integration: Seamlessly reads input data directly from Google Sheets.
- Chat-Triggered: Initiates the entire automation sequence immediately from a chat interface.

## How it Works
1. A user starts the workflow via a chat trigger.
2. The workflow gets data from the Google Sheet.
3. OpenAI processes the information to draft a personalized, contextual email message.
4. n8n automatically sends the finalized email to the target recipient.

## Requirements
- An account with n8n.
- An OpenAI API key.
- A Google Workspace account (Google Sheets and Gmail).
