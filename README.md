# NASDAQ_AI_TRADING_MEGABOT
FULL-AUTO Trading Bot: PineScript  entry + exit + 3 diffrent Trailing Stop + 4 diffrent TP's + Smart manegment when in position VIA Machine\Deep Learning Custom self made TraidingView ''Indicator'' → JSON Webhooks VIA TraidingView Alerts + DNS + Revers Proxy (WITH SSL) → NGINX → Flask ON REMOTE SERVER → NinjaTrader. Includes PnL blockers, trading hours rule, news blocker,MAX Position Limit , MAX Contracts per day Limit, GUI/CPU/Flask/NGINX monitoring , smart Discord alerts and more.


# MegaBot (CENSORED RELEASE)

> **What this is:** A production-grade trading operations daemon I built for real-time control, health monitoring, and risk enforcement around a discretionary/automated workflow (Windows + NinjaTrader UI, Flask API, Discord alerts).
> **Why censored:** This repo demonstrates architecture, scope, and code quality without disclosing proprietary logic.

## Key Capabilities
- **REST API (Flask):** `/************`, `/**********`, `/************`, `/**********`, health checks.
- **UI Automation (pywinauto):** Button-level control of Basic Entry (Buy Mkt / Sell Mkt / Close), Account Data parsing.
- **Risk Controls:**
  - Daily PnL blocker (live + realized), single-trade max loss, forced close, and 24h lock.
  - Time-of-day guardrails and position size caps.
- **Monitoring & Alerts:**
  - Process/GUI watchdog, CPU/RAM thresholds, network latency checks (HTTP + ping), Discord webhook notifications.
- **Schedulers & Safety:**
  - Auto close time rule, cool-down on alerts, structured logs and daily trade journal.

## Tech Stack
Python 3.11+, Flask, pywinauto (UIA), psutil, requests, logging, subprocess, threading, Windows-only (NinjaTrader GUI).

## Notes
- This file is **censored** intentionally. All functions, endpoints, and flows are preserved with redactions (`*****`) for proprietary details.
- Exact line count and structure are preserved to show the real complexity and engineering effort.

## Contact
For serious B2B inquiries (prop firms, family offices, boutique funds): **DM on LinkedIn**.
