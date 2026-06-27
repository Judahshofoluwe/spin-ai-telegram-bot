# | [SPIN AI](https://github.com/Judahshofoluwe/spin-ai-telegram-bot) | Telegram AI assistant with web search & persistent memory | n8n, OpenAI, Tavily, Supabase |

A production-ready Telegram AI assistant with real-time web search 
and persistent memory, built entirely with n8n.

## Features
- 🔍 Real-time web search powered by Tavily
- 🧠 Persistent memory across conversations (Supabase/Postgres)
- 💬 Natural conversation via Telegram
- 📊 Conversation logging to Google Sheets
- ⚡ Powered by OpenAI GPT-4.1 Mini

## Tech Stack
| Tool | Purpose |
|------|---------|
| n8n | Workflow orchestration |
| OpenAI GPT-4.1 Mini | Language model |
| Tavily | Real-time web search |
| Supabase | Persistent chat memory |
| Telegram Bot API | User interface |
| Google Sheets | Conversation logging |

## Architecture
Telegram Trigger → AI Agent → Send Message → Log to Sheets
                      ↕
              Postgres Chat Memory
                      ↕
                Tavily Search

## Setup
1. Import the workflow JSON into n8n
2. Add your credentials (OpenAI, Tavily, Supabase, Telegram)
3. Create the Supabase table (SQL in workflow notes)
4. Activate the workflow

## Author
Judah Shofoluwe — Automation Engineer
📍 Lagos, Nigeria
