# ColdPen

**AI-powered cold email first lines that get replies.**

Paste a LinkedIn URL or prospect info → get 3 personalized openers in 5 seconds.

![ColdPen](https://img.shields.io/badge/status-MVP-orange) ![License](https://img.shields.io/badge/license-MIT-green)

## What it does

ColdPen generates personalized cold email opening lines for sales reps, recruiters, founders, and freelancers. No more "I hope this email finds you well."

**Input:** LinkedIn URL, company website, or manual prospect description  
**Output:** 3 personalized first lines (Professional, Casual, Bold) with copy-to-clipboard

## Tech Stack

- Single HTML file (zero dependencies)
- Anthropic Claude API (Sonnet 4)
- Vanilla CSS + JS
- Stripe-ready paywall (placeholder)

## Monetization

- **Free tier:** 5 generations/day
- **Pro:** $29/month — unlimited generations, Chrome extension, CSV bulk upload, API access

## Quick Start

1. Clone this repo
2. Open `index.html` in your browser
3. That's it — the API calls work client-side via Anthropic's API

> **Note:** For production, move the API call to a backend to protect your API key.

## Roadmap

- [ ] Chrome extension (generate on LinkedIn pages)
- [ ] Bulk CSV upload (100 prospects at once)
- [ ] API endpoint for CRM integrations
- [ ] A/B test tracking (which tone gets more replies)
- [ ] Stripe integration

## File Structure

```
coldpen/
├── index.html      # Full LP + working product (single file)
├── README.md
├── LICENSE
└── .gitignore
```

## License

MIT
