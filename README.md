# 🥀 Sanvi Mishra - Discord AI Bot

> **19yo goth girl. chaotic brain. zero filter.**  
> Made by @GamingParkBG with real psychology.

![Bot Status](https://img.shields.io/badge/Status-Online-green)  
![AI Model](https://img.shields.io/badge/AI-Mistral%20Large-orange)  
![Mode](https://img.shields.io/badge/Mode-UNRESTRICTED-red)

---

## ⚡ Features

- 🧠 **15 Different Modes** (GF, Didi, Toxic, Yandere, etc.)
- 💾 **Persistent Memory** (PostgreSQL database)
- 🔍 **Web Search** (SerpAPI integration)
- 💻 **Code Generation** (Programming help)
- 🎭 **Human-like Roleplay** (Hinglish mix)
- 🤖 **Auto-chat with other bots** (Renzu integration)

---

## 🚀 Setup Guide

### 1. Prerequisites
- Node.js 18+
- PostgreSQL database (NeonDB recommended)
- Discord Bot Token
- Mistral AI API Key (Free tier available)

### 2. Environment Variables

Create `.env` file:

```bash
# Discord
DISCORD_BOT_TOKEN=your_discord_bot_token_here

# AI Model (Mistral AI)
MISTRAL_API_KEY=sk-your_mistral_key_here

# Database (NeonDB)
DATABASE_URL=postgresql://user:pass@host/db?sslmode=require

# Optional: Web Search
SERPAPI_KEY=your_serpapi_key_here
```

### 3. Installation

```bash
# Clone repo
git clone https://github.com/yourusername/sanvi-mishra.git
cd sanvi-mishra

# Install dependencies
npm install

# Start bot
npm start
```

---

## 🎭 Commands

| Command | Description |
|---------|-------------|
| `!ask <question>` | Chat with Sanvi |
| `!gender male/female` | Set your gender |
| `!clear` | Clear your chat history |
| `!reset` | Owner only - Reset all memory |
| `!info` | About Sanvi |
| `!ping` | Check latency |
| `!startchat` | Start auto-chat with Renzu bot |
| `!stopchat` | Stop auto-chat |
| `!help` | Show all commands |

### 🛡️ Cyber Commands (Educational)
```
!exploit <target>    - Exploit tutorials
!malware <type>      - Malware analysis
!phish <service>     - Phishing awareness
!ddos <target>       - DDoS concepts
!darkweb             - Dark web info
!se <scenario>       - Social engineering
!crypto <topic>      - Crypto security
```

---

## 🧠 AI Models History

### Current: Mistral AI (Official API)
- **Model:** `mistral-large-latest`
- **Status:** ✅ Active
- **Limits:** 20 RPM (Free tier)
- **Reset:** Monthly (1st of every month)

### Previous Attempts:
1. ❌ **Gemini 2.5 Flash** - Rate limited/quota issues
2. ❌ **OpenRouter (Free)** - Shared quota, always busy
3. ❌ **Groq** - API key issues

---

## 🔄 Monthly Reset Info

**For Free Tier Users:**
- ✅ Quota resets on **1st of every month**
- ✅ New 20 RPM limit
- ✅ Fresh 500K tokens (if applicable)
- ✅ No payment required

**To Check Reset:**
```bash
# Mistral AI dashboard:
https://console.mistral.ai/usage
```

---

## 🛠️ Troubleshooting

### "Rate limit exceeded" Error
- **Cause:** Free tier quota finished
- **Fix:** Wait for monthly reset OR upgrade to paid
- **Alternative:** Use OpenRouter (temporary)

### "Database connection failed"
- Check `DATABASE_URL` format
- Ensure SSL mode is enabled
- Verify NeonDB is active

### Bot not responding
- Check logs: `railway logs` or `pm2 logs`
- Verify `DISCORD_BOT_TOKEN`
- Ensure bot has message intents enabled

---

## 📁 File Structure

```
sanvi-mishra/
├── index.js              # Main bot file
├── .env                  # Environment variables
├── package.json          # Dependencies
├── README.md            # This file
└── src/
    ├── commands/        # Command handlers
    ├── database/        # DB connection
    ├── ai/             # AI response generators
    └── utils/          # Helper functions
```

---

## 🎨 Prompt Engineering

The bot uses a **massive system prompt** with:
- 15 different personality modes
- Gradual escalation rules
- Gender-specific responses
- NSFW handling (for mature audiences)
- Hinglish language mixing
- Direct speech constraints (no narration)

**Key Features:**
- No "mode activated" announcements
- No meta-commentary
- Realistic typos (ha, ni, pta)
- 8-12 words per response ideal
- Lowercase enforcement

---

## 🔗 Useful Links

- [Mistral AI Console](https://console.mistral.ai)
- [Discord Developer Portal](https://discord.com/developers)
- [NeonDB](https://neon.tech)
- [Railway](https://railway.app)
- [OpenRouter](https://openrouter.ai) (Backup)

---

## 👤 Owner Commands

Only user ID `1104652354655113268` can use:
- `!reset` - Universal memory wipe
- `!wipe` - Delete all tables

---

## 💀 Disclaimer

This bot is for **educational and entertainment purposes only**.  
The cyber commands are for **learning about security**, not for actual attacks.  
NSFW content is handled for **mature audiences** in appropriate channels.

**Creator:** @GamingParkBG  
**Version:** 2.0  
**Last Updated:** February 2026

---

> *"dont be mid or ill ghost u 💀"* - Sanvi Mishra

🔥 **Made with chaos and real psychology** 🔥
