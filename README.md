# FUTURE_ML_03
# Build a Chatbot for Customer Support

This is a customer support chatbot built using Dialogflow Essentials (ES) and integrated with Telegram for real-time query handling.

## Features
- Pre-trained with common FAQ queries like order tracking, refund requests, and account issues
- Easily expandable intent structure
- Compatible with Telegram via webhook setup

## Contents
- `intents/` – Dialogflow ES intent files
- `agent.json` – Agent configuration file
- `package.json` – Dialogflow package definition

## How to Deploy
1. Import the agent in Dialogflow Console using `RESTORE FROM ZIP`.
2. Connect to Telegram using [Dialogflow's Telegram integration](https://cloud.google.com/dialogflow/es/docs/integrations/telegram).

## Sample Queries
- "Where is my order?"
- "My account was suspended"
- "When will I get my refund?"
- "Does this work on Android?"

## Telegram Demo
You can test the bot via a Telegram bot (optional setup instructions in `telegram_bot_setup.md`).


