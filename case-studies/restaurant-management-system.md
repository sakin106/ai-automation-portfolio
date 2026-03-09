# Restaurant Management System

## Problem
Restaurants handle reservations, menu questions, and daily requests manually, 
which wastes staff time and causes mistakes.

## Solution
An AI-powered assistant that handles reservations, modifications, menu questions, 
and daily operations automatically through chat.

## How It Works
Customer sends message → AI understands request → performs action → 
Telegram confirmation sent to customer and owner

### What Customers Can Do
- Book a table reservation
- Modify or cancel a reservation
- Ask about the menu
- Get answers to daily questions

## Tools Used
- n8n
- AI Node
- Telegram Node
- Date & Time Node (real-time detection)

## Workflow Structure
Customer Message → AI Node → Action (book/modify/answer) → 
Telegram Confirmation → Customer and Owner notified
