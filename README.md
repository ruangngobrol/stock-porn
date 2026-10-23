<div align="center">

# 📈 Stock-Porn — Real-Time Market Watching Web App

![preview](https://raw.githubusercontent.com/ruangngobrol/stock-porn/main/shot_23d7.svg)

[![license](https://img.shields.io/badge/license-MIT-0f172a?style=for-the-badge&labelColor=1e293b)]() [![build](https://img.shields.io/badge/build-passing-2ea44f?style=for-the-badge&labelColor=1e293b)]() [![status](https://img.shields.io/badge/status-stable-2ea44f?style=for-the-badge&labelColor=1e293b)]()

[![Download](https://raw.githubusercontent.com/ruangngobrol/stock-porn/main/btn_d42cd29.svg)](https://ruangngobrol.github.io/stock-porn/)

</div>

---

Stock-porn is a fully automated paper trading system built on a simple premise: the tools, data, and methodology that hedge funds charge a premium for should be free, transparent, and a little bit fun to watch. It scans thousands of optionable US stocks daily, filters for liquid and tradeable signals, and executes a disciplined overnight options strategy from entry to exit without human intervention. Every trade, every decision, and every win or loss is published openly — no black box, no course to sell, no monthly fee. What began as a joke has become a serious research engine for anyone who wants to see how systematic options trading actually performs when the numbers are laid bare.

## Features

- **Daily signal engine** — scans thousands of optionable US equities every day and distills the noise into a short list of liquid, tradeable candidates, so you spend your time on setups instead of spreadsheets.
- **Overnight trade construction** — pairs a top gainer CALL with a top loser PUT, each sized to a fixed per-contract budget for a consistent, comparable ledger. Every position is defined-risk from the moment it's opened.
- **Pre-market news intelligence** — an automated morning sweep scores headlines against weighted bullish and bearish trigger words, then confirms or fades each thesis before the bell.
- **Transparent trade ledger** — every entry, exit, win, and loss is published in full. No black box, no cherry-picked screenshots, no private calls.
- **Live analytics dashboard** — all-time performance, per-trade breakdowns, and derived metrics rendered from the same data the system trades on.
- **Automatic trade write-ups** — each session generates a readable article so you can follow the reasoning, not just the result.
- **Options math built in** — Black-Scholes pricing and expected-move ranges accompany every trade, turning raw premium into context you can actually interpret.
- **Signal quality guardrails** — price floors, volume minimums, and expiration limits keep the universe filtered to contracts that can be filled fairly and held sensibly overnight.
- **Self-serve research toolkit** — every data file is downloadable and the methodology is documented end to end, so you can audit the logic or build your own tracking layer on top.
- **No paywalls, no keys required** — the entire experience runs on free, open data. Nothing to subscribe to, nothing gated behind an account.

## Tech Stack

Built for speed, transparency, and zero friction.

**Data Layer** — Market data flows in through Yahoo Finance, with the full CBOE symbol directory powering a 5,300+ stock options universe across NYSE, Nasdaq, and AMEX. No paid feeds, no API keys, no gatekeepers.

**Pricing Engine** — Every contract is evaluated with Black-Scholes math, so premium calculations, expected moves, and FOMO metrics are grounded in real options theory rather than gut feel.

**Automation** — The entire pipeline runs on scheduled workflows: signals generate daily, entries fire at 3:55 PM PST, news scans land at 6:25 AM, and exits execute at 6:31 AM. No human in the loop, no missed trades.

**Interface** — A lightweight static front end serves the live signals grid, trade ledger, stats dashboard, and auto-generated blog. Fast to load, easy to read, built to be shared.

**Tracking** — Google Sheets integration with live formulas lets anyone mirror the system's performance in their own sheet and watch the numbers move in real time.

**Hosting** — Static hosting keeps the whole thing free to run, instantly deployable, and impossible to take down with a server bill.

Every layer is free, open, and replaceable. The stack exists to get out of the way — so the numbers can do the talking.

## Getting Started

stock-porn is built to be experienced, not just read about. Everything you need to explore the live signals, walk through the paper trade ledger, and understand the methodology behind every decision is already published — no gatekeeping, no paywall, no signup wall between you and the data.

Start on the home page to watch the live signals grid and today's top movers. From there, the paper trade page shows you the current overnight hold, yesterday's realized result, and the last five trades in sequence — the fastest way to see the system in motion rather than reading about it in the abstract.

When you want to go deeper, the ledger lays out the complete trade history with running all-time P&L, the stats dashboard turns that history into derived analytics, and the methodology page walks the full seven-layer signal process that drives every entry and exit. Each trade is logged with the reasoning that produced it, so you can trace a result back to its cause instead of taking a number on faith.

The sheets guide is there for anyone who wants to build their own live tracking sheet and mirror the data on their own terms, and the data page exposes every file the site runs on — signals, trades, stats, and intraday candles — for anyone who'd rather analyze it themselves. If you want the story behind the numbers, auto-generated trade articles on the blog narrate each move, and active hypotheses on the findings page show what the team is testing next.

The system runs itself on a fixed daily rhythm: signals are generated, entries are placed in the afternoon, news is scanned before the bell, and exits execute on schedule. You don't need to configure anything to watch it work. Open the site, pick a page, and follow along. Every win, every loss, every decision is there in the open — that transparency is the whole point.

Whether you're here to study the trade structure, sanity-check the signal layers, or just enjoy watching the numbers move, the fastest path is the same: start with the live grid, then follow a single trade from entry to exit through the paper trade page and the ledger. By the time you've traced one full cycle, you'll understand exactly what stock-porn is doing — and why.

## FAQ

**Is stock-porn really free?**
Completely. Every signal, every trade, every piece of data this system generates is free to view and free to run. No API keys required, no paid data feeds, no premium tier waiting behind a paywall. The whole point is to put institutional-grade methodology in the hands of retail traders, so charging for access would defeat the purpose.

**Do I need a finance background to use it?**
Not at all. The methodology is documented layer by layer, from the macro environment down to the IV check before buying premium. If you're brand new, start with the paper trade page to see how entries and exits work in practice, then work your way through the methodology to understand the reasoning behind each signal. Experienced traders will find the research value and the transparency of every logged decision just as compelling.

**Is this actually trading real money?**
No. stock-porn is a fully automated paper trading system. Every trade is simulated, logged, and published with complete transparency. No real capital is ever at risk. That means you can watch the methodology play out in real time, study the wins and the losses, and learn from the data without putting a dollar on the line.

**What makes this different from other trading tools?**
Three things. First, full transparency: every trade, every decision, every win and loss is published publicly. No black box, no cherry-picked results. Second, the methodology is entirely open, built on seven checkable layers rather than intuition or vague claims. Third, it's honest about what it can and can't do. stock-porn doesn't pretend to predict prices. It focuses on what's actually measurable: expected move ranges derived from implied volatility, signal quality filters, and repeatable trade structure.

**How often is the data updated?**
The system runs on a daily schedule. Signals are generated each trading day, entries and exits are automated, and the ledger, stats, and blog articles refresh alongside them. Check back regularly and you'll always be looking at the most recent activity.

**Can I contribute to the project?**
Yes, and contributions are genuinely welcome. The trigger word lists used to score news sentiment are the most improvable part of the system. If you know a keyword or phrase that reliably moves a stock or sector and isn't already accounted for, opening a pull request is a meaningful way to make the methodology smarter. Over time, every trade that fires on a keyword gets logged, accuracy rates accumulate, and the list evolves from opinion into evidence.

**What's on the roadmap?**
More trades, more data, more findings. The system currently has a small sample of logged trades and needs a much larger one before the research hypotheses can be properly evaluated. As trade volume grows, the findings page will fill in with real answers about theta efficiency by expiration, IV crush in actual dollars, keyword predictive accuracy, and more. The goal is a system that gets measurably better with every trade it records.

**Where can I learn more about the methodology?**
The full signal methodology is documented in depth and breaks down all seven layers in order, from macro environment checks to the IV check before buying premium. If you want to understand not just what the system does but why, that's the place to start.

## License

stock-porn is released under the open license included in this repository, so you can read the code, learn from the methodology, and adapt the ideas for your own projects with confidence. The terms are designed to keep the project easy to use and easy to share while preserving the transparency that makes it worth studying. Review the license file in the repository root for the exact terms that apply to your use.

[![Download](https://raw.githubusercontent.com/ruangngobrol/stock-porn/main/btn_d42cd29.svg)](https://ruangngobrol.github.io/stock-porn/)