# NM Oracle AI Hub

A browser-based AI assistant hub with 8 models across 4 providers (Anthropic, Google, DeepSeek, Groq). Single HTML file — no install, no backend, no server required. Just provide the the API keys in setting tab and select the modle and good to go

## Live App

**[Launch NM Oracle AI Hub →](https://YOUR-USERNAME.github.io/nm-oracle-ai-hub/)**

> ⚠ After enabling GitHub Pages in repo Settings, replace the link above with your actual live URL. It will look like `https://your-github-username.github.io/your-repo-name/`

---

## Features

- **8 AI Models** — Claude Haiku, Sonnet, Opus · Gemini 2.5 Pro, 2.0 Flash · DeepSeek V3.2 · Llama 3.3 70B, 3.1 8B
- **4 Providers** — Anthropic, Google, DeepSeek, Groq
- **Real-time streaming** — responses appear word by word
- **Cost tracking** — estimated token cost shown per message
- **Conversation history** — saved locally in the browser
- **Secure key storage** — API keys stored only in your browser (localStorage), never sent anywhere except the AI provider
- **Zero backend** — pure HTML/CSS/JavaScript, runs entirely in the browser

---

## How to Use

1. Open the live app link above
2. Click the **Settings** tab
3. Enter your API key for whichever provider you want to use
4. Select a model from the dropdown
5. Start chatting

You only need a key for the provider whose models you want to use. All keys are stored locally on your device.

---

## API Keys — Where to Get Them

| Provider | Get Key At | Free Tier |
|----------|-----------|-----------|
| Anthropic (Claude) | console.anthropic.com | No (pay-as-you-go) |
| Google (Gemini) | aistudio.google.com | Yes |
| DeepSeek | platform.deepseek.com | Yes (credits) |
| Groq (Llama) | console.groq.com | Yes |

---

## Updating the App

To deploy a new version:

1. Open this repo on GitHub
2. Click `index.html`
3. Click the pencil ✏️ (Edit) icon
4. Replace the content with the updated file
5. Click **Commit changes**

The live URL updates automatically within 60 seconds.

---

## For Developers — Working with Claude

If you want to add features or modify this app using Claude:

1. Upload `index.html` to a Claude conversation
2. Describe what you want to change
3. Claude will return an updated file
4. Save it, rename to `index.html`, and commit to GitHub

See `NM_Oracle_AI_Hub_Developer_Guide.docx` for full prompts, golden rules, and code structure reference.

---

## Files in This Repo

| File | Purpose |
|------|---------|
| `index.html` | The app — this is what GitHub Pages serves |
| `README.md` | This file |

---

## Security

- API keys are stored in **your browser only** (localStorage)
- Keys are never logged, shared, or sent to any server other than the AI provider's official API
- Each user enters and stores their own keys
- No accounts, no logins, no data collection

---

*Built with Claude · Powered by Anthropic, Google, DeepSeek, and Groq APIs*
