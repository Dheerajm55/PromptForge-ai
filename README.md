# PromptForge AI — Precision Prompt Builder

A standalone AI-powered prompt engineering agent that helps you craft detailed, accurate prompts for any project through smart conversational questioning.

## Features
- **ChatGPT-style one-at-a-time questions** with smooth animations
- **Clickable option buttons** for every detail (colors, styles, layouts, fonts, etc.)
- **Color swatch options** with hex preview for palette selection
- **Progress tracker** showing how many details collected
- **Typewriter streaming effect** for generated prompts
- **Copy & Export** generated prompts
- **API key management** — stored locally in browser
- **6 project type quick-starts**: Website, Mobile App, Dashboard, E-Commerce, Brand, SaaS

## Setup

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
2. Enter your **Anthropic API key** in the sidebar or via the "API Key" button
   - Get your key at: https://console.anthropic.com
   - Key format: `sk-ant-api03-...`
3. Click a project type chip or type your idea
4. Answer the questions by clicking options or typing custom answers
5. After ~8 questions, click **"✦ Generate My Prompt"**

## How It Works

The AI agent:
1. Analyzes your initial idea
2. Asks 7-9 targeted questions covering: type, style, colors, typography, layout, navigation, sections, features, audience, tone
3. Presents smart clickable options for each question
4. Generates a 400-600 word comprehensive AI prompt with all your specifications

## Tech Stack
- Pure HTML/CSS/JS — zero dependencies, no build step
- Anthropic Claude API (claude-sonnet-4)
- Fonts: Syne (display) + DM Sans (body) via Google Fonts

## Security Note
Your API key is stored in browser localStorage only. Never committed or sent to any third-party server. For production use, add a backend proxy to hide the API key.

## Files
- `index.html` — The entire application (single file)
- `README.md` — This file
