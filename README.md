# AI Telegram Customer Engagement Automation

## Overview

This project is an AI-powered automation workflow built with n8n. It automatically sends personalized Monday greetings to Telegram subscribers using Gemini AI while reminding them that KEA's Company is available to provide its services throughout the week.

## Business Problem

Manually sending weekly greetings to customers is repetitive and time-consuming. Businesses need an efficient way to maintain regular engagement with their subscribers.

## Solution

This workflow automatically:
- Retrieves Telegram subscribers from Google Sheets.
- Generates personalized Monday greetings using Gemini AI.
- Sends messages automatically through a Telegram bot every Monday.
- Removes duplicate subscribers before sending messages.

## Technologies Used

- n8n
- Telegram Bot API
- Google Sheets
- Google Cloud Console
- Gemini AI

## Workflow

Schedule Trigger
↓
Google Sheets
↓
Remove Duplicates
↓
Gemini AI
↓
Telegram

## Features

- Automated Monday greetings
- AI-generated messages
- Google Sheets integration
- Telegram Bot integration
- Duplicate subscriber handling
- Scheduled workflow execution

## Screenshots

### Workflow
Shows the complete n8n automation workflow.

![Workflow](workflow%20kea.JPG)

### Successful Execution
Shows the workflow executing successfully.

![Execution](execution%20kea.JPG)

### Google Sheets
Stores the Telegram subscribers used by the workflow.

![Google Sheets](google%20sheet%20kea.JPG)

### Telegram Message
Example of the AI-generated Monday greeting sent to subscribers.

![Telegram Message](telegram%20message%20kea.JPG)

## Author

*Mustapha kemi*
