# Inventory Management System

## Problem
Businesses manually update inventory using spreadsheets, which is slow and causes errors.

## Solution
An AI-powered chat system where the client simply types commands to manage inventory. 
No manual spreadsheet editing needed.

## How It Works
Client types a command → AI understands the request → Google Sheets updates automatically

### Example Commands
- "Add 50 units of rice"
- "Remove product X"
- "What items are running low?"
- "Show me current stock"

## Tools Used
- n8n
- AI Node
- Google Sheets

## Workflow Structure
Chat Input → AI Node → Google Sheets (update/read/delete) → AI Response to client
