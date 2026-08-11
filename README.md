# Customer Support Agent

## Objective

An AI-powered Customer Support Agent built using n8n. It receives customer messages, classifies the request, determines urgency and sentiment, and decides whether the request can be automatically resolved or escalated to human support.

## Workflow

Customer Message
↓
Chat Trigger
↓
AI Agent
↓
MongoDB Chat Memory
↓
Classification and Support Decision
↓
IF Routing
↓
Auto-Resolve / Human Escalation
↓
Customer Response

## Technologies Used

- n8n
- Groq Chat Model
- MongoDB Chat Memory
- AI Agent

## Features

- Customer chat interface
- User/session identification
- Conversation memory
- Query classification
- FAQ/support information handling
- Urgency detection
- Sentiment detection
- Automatic resolution
- Human escalation
- Conditional routing

## Query Categories

- Account
- Billing
- How-to
- Troubleshooting
- Order/Delivery
- Refund/Cancellation
- Complaint
- Other

## Escalation Rules

The agent escalates:

- Refund requests
- Payment disputes
- Legal concerns
- Serious complaints
- Highly negative interactions
- Account security concerns
- Cases requiring human decisions

## Testing

### Auto-Resolve Test

Customer request:

"How can I change my email address?"

The request is processed by the AI Agent and routed to the auto-resolve branch.

### Escalation Test

Customer request:

"I want a refund for my payment."

The request is routed to the escalation branch and forwarded to human support.

## Project Outcome

The project demonstrates how AI agents can automate common customer support tasks while keeping high-risk requests under human supervision.
