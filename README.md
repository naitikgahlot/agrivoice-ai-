# AgriVoice AI

**AI-powered crop disease diagnosis for farmers — built for IgniteX HackFest 2026**

AgriVoice AI lets a farmer photograph a crop leaf, describe what they're seeing, and get an instant diagnosis, treatment plan, and prevention tips — in their own language. No app install, no account, works on any phone browser.

**[Live Demo](#)** — *(replace with your Netlify link)*

## The Problem

Smallholder farmers across India lose a significant share of crop yield every year to diseases and pests that go undiagnosed until it's too late, largely because agricultural extension officers and agronomists are scarce relative to the number of farms. A wrong or delayed diagnosis can mean an entire season's income lost, and guesswork treatment also drives pesticide misuse.

## The Solution

A zero-install, multilingual web app. A farmer uploads or captures a leaf photo, optionally adds a note about symptoms, and a multimodal AI model returns a structured field report: what's wrong, how to treat it, and how to prevent it next season. Built to run on low-end Android phones over a basic connection.

## Features

- **Photo-based diagnosis** — upload or capture a leaf photo directly
- **Multilingual** — English, Hindi, and Tamil, extendable to any language
- **Structured guidance** — diagnosis, treatment steps, and prevention tips, not just a chat response
- **Zero install** — runs entirely in the browser, no backend server required

## Tech Stack

- HTML, CSS, JavaScript (no framework)
- Google Gemini API (multimodal — vision + text understanding)
- Netlify (static hosting)

## Running Locally

1. Clone this repo
2. Get a free API key from [Google AI Studio](https://aistudio.google.com/apikey)
3. Open `index.html` in your browser
4. Paste your API key into the setup box, upload a leaf photo, and click **Diagnose crop**

## Why It Scales

The app has no backend to maintain or scale — it's a static page that calls an AI API directly, so hosting cost stays near zero regardless of usage. Adding a new language is a small code change, not a rebuild. It's straightforward to extend into a WhatsApp or SMS-based version for farmers without reliable smartphone data.

## Future Scope

- Voice input for non-literate users
- Offline mode for low-connectivity areas
- Field history tracking per farmer/plot
- Integration with local weather data to time treatments

## Disclaimer

AI-generated guidance is a starting point — always confirm with a local agricultural extension office before applying chemical treatments.


Naitik Gahlot
