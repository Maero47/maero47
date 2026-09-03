<p align="center">
  <img src="assets/profile-header.png" width="100%" alt="Header banner: Mehmet Ali, computer science student building AI-driven products" />
</p>

<p align="center">
  <a href="https://mehmetali.cv"><img src="https://img.shields.io/badge/Portfolio-mehmetali.cv-2dd4bf?style=flat-square&labelColor=0b1020" alt="Portfolio at mehmetali.cv" /></a>
  <img src="https://img.shields.io/badge/University_of_Birmingham-Computer_Science-f43f5e?style=flat-square&labelColor=0b1020" alt="Computer Science student at the University of Birmingham" />
</p>

Computer Science student at the University of Birmingham. I work on the seam where a
language model meets live data and an interface someone actually has to use — the part
that demos easily and is hard to make trustworthy.

Four projects below, all of them things I built end to end: a market-analysis platform,
a macOS browser that Claude Code can drive, an AI reception desk, and a cooking app
that refuses to take itself seriously. I would rather finish one thing you can open than
start five you can only read about.

## Projects

### [StockMind](https://github.com/Maero47/Stockmind)

[![StockMind — AI-supported stock and crypto analysis](assets/cards/stockmind.png)](https://github.com/Maero47/Stockmind)

Stock and crypto analysis that runs on your own API key: the AI chat streams its
analysis through whichever of Groq, OpenAI, Anthropic or Gemini you bring, and the key
is encrypted before it is stored. Underneath it are Binance and Finnhub WebSockets for
sub-second crypto and live stock trade ticks, the indicator set you would expect — RSI,
MACD, Bollinger, EMA, ATR, support and resistance — and an XGBoost model trained on two
years of daily data that calls next-day direction with a confidence score. Headlines come
scored for sentiment, the watchlist and price alerts sync to your account through
Supabase, and the whole thing installs as a PWA.

`Next.js` · `FastAPI` · `XGBoost` · `WebSockets` · `Supabase`

### [Cherry Browser](https://github.com/Maero47/Cherry-Internet-Browser)

[![Cherry Browser — a macOS browser with an on-device model and an MCP server](assets/cards/cherry-browser.png)](https://github.com/Maero47/Cherry-Internet-Browser)

A Mac browser with an MCP server inside it: switch it on and Cherry serves nine tools on
`127.0.0.1` behind a bearer token, so Claude Code or Codex can list your tabs, read the
page you are looking at, search your history or open one — and only click and type after
you allow it in a dialog. The AI side panel reads the current page and researches across
several open tabs with citations, running on Apple's on-device model or a local Qwen you
download yourself; nothing about your page leaves the Mac. It renders with `WKWebView`,
the engine Safari uses, so Cherry is the browser around the engine rather than a new one
— signed and notarized, outside the App Store, macOS 26.2 or later. There is also a cat
called Pearl, who lives on your pages and doubles as the offline-page game.

`Swift` · `SwiftUI` · `WebKit` · `AppKit` · `MCP`

### [AI Receptionist](https://github.com/Maero47/AI-recepcionist)

[![AI Receptionist — AI reception and lead-capture platform](assets/cards/ai-receptionist.png)](https://github.com/Maero47/AI-recepcionist)

An AI front desk for small businesses: it answers from a knowledge base you control,
handles FAQs and services, takes chat and voice through webhooks, sends notifications,
and hands the owner a dashboard for everything it captured.

`Next.js` · `TypeScript` · `Supabase`

### [Chaos Kitchen](https://github.com/Maero47/Chaos-Kitchen)

[![Chaos Kitchen — a playful AI cooking experience](assets/cards/chaos-kitchen.png)](https://github.com/Maero47/Chaos-Kitchen)

Cooking with the recipe fighting back. It swaps your ingredients, walks you through
what to do about it, and narrates the whole thing out loud with generated speech.

`Next.js` · `Groq` · `Tailwind CSS` · `Text to Speech`

## Tools

<p>
  <img src="https://skillicons.dev/icons?i=ts,nextjs,react,tailwind,python,fastapi,supabase,swift,git,github&perline=10" alt="TypeScript, Next.js, React, Tailwind CSS, Python, FastAPI, Supabase, Swift, Git and GitHub" />
</p>

## Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Maero47/maero47/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Maero47/maero47/output/github-contribution-grid-snake.svg" />
  <img width="100%" alt="Animated snake eating through Mehmet Ali's GitHub contribution graph" src="https://raw.githubusercontent.com/Maero47/maero47/output/github-contribution-grid-snake.svg" />
</picture>

---

Interested in AI-native products, macOS software and fintech. Case studies and
contact details live at **[mehmetali.cv](https://mehmetali.cv)**.
