# Bella's Restaurant AI Chatbot

An AI-powered customer service chatbot for Bella's Restaurant, built with the Botpress ADK. Handles menu enquiries, allergen information, opening hours, and table reservations through natural conversation.

## Features

- Menu browsing with prices and dietary labels (vegan, gluten-free, vegetarian)
- Table reservation flow (collects name, date, time, party size)
- Opening hours and location info
- Allergen guidance

## Demo

[Try the live bot here](https://cdn.botpress.cloud/webchat/v3.6/shareable.html?configUrl=https://files.bpcontent.cloud/2026/07/01/08/20260701085032-TZ48GHU5.json)

## Built With

- Botpress ADK
- TypeScript
- Claude AI (via Botpress)

## Getting Started

1. Install dependencies:
A Botpress Agent built with the ADK.

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start development server:

   ```bash
   adk dev
   ```

3. Deploy your agent:
   ```bash
   adk deploy
   ```

## Project Structure

- `src/actions/` - Define callable functions
- `src/workflows/` - Define long-running processes
- `src/conversations/` - Define conversation handlers
- `src/tables/` - Define data storage schemas
- `src/triggers/` - Define event subscriptions
- `src/knowledge/` - Add knowledge base files

## Preview
![Chatbot Preview](https://github.com/user-attachments/assets/61ec3a61-c18d-470a-93b9-c922d8cb3a71)

## Learn More

- [ADK Documentation](https://botpress.com/docs/adk)
- [Botpress Platform](https://botpress.com)
