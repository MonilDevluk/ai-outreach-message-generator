# AI Outreach Message Generator (n8n + Gemini)

## Overview

This project automates the generation of personalized outreach messages using an LLM.

The workflow reads lead information from a Google Sheet, sends the data to the Gemini API to generate a personalized message, and writes the generated message back to the sheet.

This demonstrates how LLMs can be integrated into automation workflows for scalable communication.

## Workflow

Google Sheets → Gemini API → Generated Message → Google Sheets

## Tech Stack

- n8n (workflow automation)
- Google Sheets API
- Google Gemini API
- JSON-based workflow orchestration

## Features

- Reads lead data from a spreadsheet
- Generates personalized outreach messages
- Updates records with generated content
- Simple automation pipeline for AI-assisted communication

## Example Input

```
Name: John
Role: CTO
Company: StartupX
Pain Point: hiring engineers
```

## Example Output

```
Hi John, noticed you're leading engineering at StartupX. Scaling teams quickly can get messy. I've been exploring ways to streamline this process with automation. Curious how you're currently handling it?
```

## Future Improvements

- Add rate limiting and error handling
- Integrate lead enrichment APIs
- Add automated message delivery via browser automation
- Add lead scoring using LLMs
