# Salon AI Automation System

An AI-powered salon customer support and appointment automation system built using n8n, WhatsApp Business Cloud API and Google Gemini.

## Overview

Salon AI Automation is designed to streamline salon customer interactions through an AI-powered WhatsApp assistant.

The system uses workflow automation and conversational AI to handle customer enquiries, retrieve salon service information and assist with appointment-related interactions.

## Key Features

- WhatsApp-based customer interaction.
- AI-powered conversational responses.
- Customer message validation.
- Salon service lookup.
- Customer information lookup.
- Conversation history and context management.
- Automated response processing.
- Email-related workflow integrations.

*Feature descriptions should reflect the functionality currently implemented.*

## Technology Stack

- n8n – Workflow Automation
- Google Gemini – Generative AI
- WhatsApp Business Cloud API – Messaging Integration
- Webhooks – Event Handling
- REST APIs – System Integration
- JSON – Workflow Configuration

## Workflow Architecture

1. WhatsApp Trigger – Receives incoming messages.
2. Message Validation – Validates incoming customer messages.
3. Salon Lookup – Retrieves relevant salon information.
4. Services Lookup – Retrieves available services.
5. Customer Lookup – Retrieves customer information.
6. Conversation History – Maintains conversational context.
7. AI Agent – Processes customer queries using AI.
8. Reply Processing – Prepares the AI-generated response.
9. Response Delivery – Handles outgoing customer communication.

## Repository Structure

```text
Salon-AI-Automation/
│
├── workflows/
│   └── salon-ai-automation.json
│
├── screenshots/
├── documentation/
├── README.md
└── .gitignore
```

## Setup Instructions

1. Install or access n8n.
2. Import the workflow JSON.
3. Configure your own WhatsApp Business Cloud API credentials.
4. Configure your Google Gemini API credentials.
5. Configure any required integrations.
6. Verify webhook settings.
7. Test the workflow with sample messages.

## Security

This repository does not include private API keys, access tokens, passwords or customer information.

Users must configure their own credentials in n8n.

## Project Status

Under Development.

## Author

Hitarth Gujral

Computer Science Engineering – AI & ML

Chitkara University, Punjab

GitHub: https://github.com/hitarth16102006-ui

LinkedIn: https://www.linkedin.com/in/hitarth-gujral-513650392/
