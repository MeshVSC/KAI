# Kai: Your Second Self on macOS

<p align="center">
  <img src="hero_banner.jpg" alt="Kai" width="100%">
</p>

> A native AI desktop environment with persistent semantic memory, 118 built-in skills, voice control, and automation workflows. Local-first. Privacy by architecture.

[![macOS](https://img.shields.io/badge/macOS-14.0+-blue.svg)](https://www.apple.com/macos/)
[![Swift](https://img.shields.io/badge/Swift-5.10-orange.svg)](https://swift.org)
[![Plugins](https://img.shields.io/badge/Plugins-118+-green.svg)]()

---

## What Kai Does

Kai is a persistent AI companion that lives in your macOS menu bar. It remembers everything, automates anything, and learns how you work over time — entirely on your Mac.

- **Persistent Memory** — Every conversation, preference, and detail is indexed and searchable by meaning, not keywords.
- **Your Notes Train Kai** — Everything you write becomes part of what Kai knows. No manual setup.
- **118 Built-in Skills** — Media processing, PDF tools, web utilities, data conversion, system control, and more.
- **Voice Control** — Speech-to-text, text-to-speech, wake word detection ("Hi Kai"), continuous conversation mode.
- **Automation Workflows** — Visual Zap builder with conditional logic, triggers, and branching.
- **Screen Awareness** — Kai sees what you're working on for context-aware assistance.
- **100% Local** — Your data lives in a local SQLite database. No cloud sync. No third-party storage.

---

## Intelligence

Kai supports both cloud and local AI models:

- **Cloud Providers**: OpenAI, Anthropic, Google Gemini, Groq, Mistral, DeepSeek, and more.
- **Local Models**: Download and run models from HuggingFace on Apple Silicon via MLX. Fully offline, token-by-token streaming.
- **Multi-Provider**: Switch between models or providers at any time.

---

## Memory System

- **Semantic Search** — Find past conversations by meaning, not keywords.
- **Fact Extraction** — Kai automatically identifies and saves facts about you (name, profession, preferences, and more).
- **Auto-Extraction** — Every 10 messages, Kai runs a deeper analysis to capture key insights.
- **Context Compaction** — Long conversations are automatically summarized to keep responses sharp.
- **Deduplication** — 30-second window prevents duplicate entries.

---

## Plugin Ecosystem

**118+ plugins across 21 categories.** All disabled by default — enable only what you need. Credentials stored in macOS Keychain.

| Category | Plugins |
|:---|:---|
| **AI/ML** | Anthropic, OpenAI, DeepSeek, Qwen, XAI, ZAI, Replicate, HuggingFace, Stable Diffusion, ElevenLabs, Whisper, LM Studio, Ollama |
| **Communication** | Discord, Slack, Teams, Twilio, WhatsApp |
| **Social** | Twitter, Instagram, Threads, LinkedIn, Reddit, Mastodon, TikTok |
| **Productivity** | Apple Notes, Apple Calendar, Apple Reminders, Contacts, Notion, Obsidian, Todoist, Trello, Airtable, Google Drive, Google Sheets, Google Calendar, OneDrive, Dropbox, Translation |
| **Development** | GitHub, GitLab, Bitbucket, Jira, Linear, Confluence, Figma, Docker, SSH, Database, Supabase, Firebase, Vercel, Netlify |
| **Cloud & DevOps** | AWS, Google Cloud, Azure, Cloudflare, DigitalOcean |
| **CRM & Marketing** | HubSpot, Salesforce, Mailchimp, SendGrid |
| **Finance** | Stripe, PayPal, Plaid, QuickBooks, CoinGecko |
| **Smart Home** | SmartThings, Home Assistant, Philips Hue |
| **Media** | Spotify, Apple Music, YouTube, Plex |
| **Monitoring** | Sentry, PagerDuty, UptimeRobot, Datadog |
| **Browser** | Brave, Comet, Safari |
| **Utilities** | Weather, Wolfram, Web, Maps, Stickies, Shortcuts, Zapier, N8N, IFTTT, Make |
| **Design** | Canva |
| **Core Tools** | FileData, PDF, Web Utilities, Video, Image Enhanced, Gaming (Steam) |

---

## Voice & Communication

- **Speech-to-Text**: Mic button or hotkey. Auto-sends on silence.
- **Text-to-Speech**: Kai reads responses aloud.
- **Continuous Mode**: Long-press mic for ongoing dialogue.
- **Wake Word**: "Hi Kai" — hands-free activation from anywhere.
- **Meeting Recording**: System audio capture, real-time transcription, AI summaries.

---

## Interface

- **Menu Bar** — Always accessible, one click.
- **Spotlight Command Bar** — `Cmd+Ctrl+Space` for instant access from any screen.
- **Anti-Gravity Hub** — Full workspace with chat, notes, canvas, automations, and context graph.
- **Canvas** — Infinite workspace with zoom, pan, and node connections.
- **Hierarchical Notes** — Book > Chapter > Page organization, all indexed into memory.

---

## Requirements

- macOS 14.0 (Sonoma) or later
- Apple Silicon recommended for local AI models

---

## Privacy & Security

- Local SQLite database (GRDB). No cloud sync.
- Credentials in macOS Keychain.
- Safety firewall with blocked commands and protected directories.
- Run fully offline with local models.
- Paid service plugins clearly marked with cost indicators.

---

## Creator

**Stephane Bessa** · Mesh Studios · Barcelona, 2026

<p align="center">
  <i>Your second hand, your second brain, your second self.</i>
</p>
