# AI Lead Capture Automation (n8n + OpenAI)

## Overview
This project is an AI-powered lead capture automation built using n8n and OpenAI.  
The workflow receives leads from a webhook form, uses AI to qualify the lead, stores the lead information in Google Sheets, and sends a confirmation email automatically.

## Tools Used
- n8n
- OpenAI API
- Webhook Trigger
- Google Sheets
- Gmail

## Workflow
Webhook → AI Lead Qualification → Store Lead in Google Sheets → Send Confirmation Email

## How It Works
1. A user submits a lead form connected to the webhook.
2. The webhook triggers the n8n workflow.
3. OpenAI analyzes the lead information.
4. The lead is stored in Google Sheets.
5. A confirmation email is automatically sent to the lead.

## Setup
1. Import the `workflow.json` file into n8n.
2. Configure your credentials for OpenAI, Gmail, and Google Sheets.
3. Activate the workflow.

## Note
API keys are not included in this repository for security reasons.
