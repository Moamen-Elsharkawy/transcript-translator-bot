# Transcript Translator Bot

A paid freelance delivery: drop a DOCX transcript into Telegram and get back an Arabic translation with every timestamp preserved, delivered as a Google Drive link.

**Demo video:** https://youtu.be/UNfAMzjIiEE

## What it does

- Receives DOCX transcript files through a Telegram bot
- Translates the content to Arabic with an LLM while preserving all timestamps and structure
- Writes the translated document and delivers it back as a Drive link
- Replaces hours of manual translation work per file

## Workflow

| File | Role |
|---|---|
| `transcript-translator.json` | The full pipeline: Telegram intake, DOCX parsing, timestamped translation, Drive delivery |

## Stack

n8n, Telegram Bot API, GPT-4o-mini, Google Drive.

## Import and setup

1. Import the JSON into n8n.
2. Create credentials: Telegram bot token, OpenAI (or your LLM provider), Google Drive. Credential references are name-only placeholders.

## Note on redaction

All credentials, webhook IDs, and Drive links have been replaced with self-describing placeholders. The workflow logic is exactly what was delivered.

---

Built by [Moamen Elsharkawy](https://www.linkedin.com/in/moamen--elsharkawy/), AI Automation Engineer. More builds: [portfolio](https://www.notion.so/Moamen-Elsharkawy-AI-Automation-Specialist-c201df9dd81482998591011f978b1bda) | [GitHub profile](https://github.com/Moamen-Elsharkawy)
