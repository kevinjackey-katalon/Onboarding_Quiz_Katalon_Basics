# Katalon Studio Web & API Testing Quiz

An interactive professional training quiz based on the *Web and API Testing with Katalon Studio* playbook (May 2025).

## Features

- 25 questions covering all training sections
- Questions shuffle on every load/retake
- Instant per-answer feedback with explanations
- 🔥 Streak counter for consecutive correct answers
- Results screen with animated score ring, per-category breakdown, and full answer review

## Topics Covered

| Category | Questions |
|---|---|
| Configuration & Project Settings | 3 |
| Locator Strategies | 4 |
| Test Creation (Web, AI, Keywords, API) | 5 |
| Debugging | 3 |
| Test Data & Profiles | 5 |
| Test Execution | 5 |

## Deploying to Vercel

### Option A — Vercel CLI

```bash
npm i -g vercel
vercel
```

### Option B — Vercel Dashboard

1. Push this repo to GitHub / GitLab / Bitbucket
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the repository
4. Leave all settings as default — Vercel auto-detects a static site
5. Click **Deploy**

No build step or framework configuration required.

## Local Development

Open `index.html` directly in any browser — no server needed.

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

## Project Structure

```
katalon-quiz/
├── index.html      # Self-contained quiz app (HTML + CSS + JS)
├── vercel.json     # Vercel routing config
└── README.md       # This file
```

## License

Internal training use only.
