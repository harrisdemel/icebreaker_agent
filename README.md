# 🧊 Team Icebreaker Agent

A lightweight AI-powered tool for project managers. Enter your team members' names and instantly get a fun, conversation-starting trivia fact for each person — perfect for project kickoffs and introductions.

![screenshot](https://via.placeholder.com/640x400?text=Team+Icebreaker+Agent)

## What it does

Type in your team members' names (comma-separated or one per line), and the agent generates a unique trivia fact for each person — covering name origins, famous namesakes, cultural connections, and more.

## Features

- No backend or server required — runs entirely in the browser
- Free to use via Google Gemini API
- Works on desktop and mobile
- Light and dark mode support
- Single file — easy to deploy anywhere

## Getting Started

### 1. Get a free Gemini API key

1. Go to [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Sign in with a Google account
3. Click **Create API key** — it's free and instant

### 2. Run the app

**Option A — Open locally:**
Just download `index.html` and open it in any browser. No install needed.

**Option B — Host on GitHub Pages:**
1. Fork or clone this repo
2. Go to your repo's **Settings → Pages**
3. Set the source to the `main` branch, `/ (root)` folder
4. Your app will be live at `https://yourusername.github.io/icebreaker-agent`

### 3. Use it

1. Paste your Gemini API key into the key field and click **Save**
2. Type in your team members' names
3. Click **Generate icebreakers**

> Your API key is only stored in memory for the current browser session and is never sent anywhere except directly to Google's API.

## Tech stack

- Plain HTML, CSS, and JavaScript — no frameworks, no dependencies
- [Google Gemini 2.0 Flash](https://ai.google.dev/) for AI generation
- Fully client-side — no server, no database, no cost to host

## Customization

Want to change the type of trivia generated? Open `index.html` and find the `prompt` variable inside the `generateTrivia()` function. Edit the instructions there to tailor the output to your team's style.

## License

MIT — free to use, modify, and share.
