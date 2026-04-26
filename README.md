# AI Telegram Bot — n8n Workflow

## What It Does
An AI-powered Telegram bot that handles customer 
inquiries automatically. It understands user intent, 
replies intelligently using OpenAI, and remembers 
conversation context across messages.

## Workflow
Telegram Trigger → Code (Build History) → 
HTTP Request (OpenAI) → Code (Save Reply) → Telegram

## Tech Stack
- n8n
- Telegram Bot API
- OpenAI API (gpt-4o-mini)

## Features
- Handles 5 user intents automatically
- Context memory across conversation
- Responds in user's language
- Real-time reply under 3 seconds

## Setup
1. Import the workflow JSON into your n8n instance
2. Create a Telegram bot via @BotFather and add token
3. Add OpenAI API key as HTTP header credential
4. Update system prompt with your business details
5. Activate the workflow

## Supported Intents
1. General business questions
2. Service inquiries
3. Pricing questions
4. Consultation booking
5. General AI and automation questions

## Use Case
Small businesses that want to automate customer 
support and lead qualification without hiring 
extra staff.

## Result
- 24/7 automated customer support
- Instant replies under 3 seconds
- Context-aware conversation memory
- Zero manual response needed

## Additional Features
- Automatic error monitoring with Telegram alerts
