# Signals Terminal UI — v0.2.0

Responsive React + TypeScript + Vite prototype for the Signals Terminal Telegram Mini App.

## Included
- Graphite + silver visual system
- Dashboard and sidebar navigation
- Terminal preview (OTC / Forex, asset and timeframe selectors)
- Signals, strategies, academy, journal, analytics and AI Coach module placeholders
- Pricing page with DEMO / REFERRAL / PREMIUM
- Monthly / annual pricing switch ($65 / $499)
- Trial presentation (7 days; proposed setting)
- Demo UI counter and plan-preview selector
- Responsive mobile layout

## Run locally
```bash
npm install
npm run dev
```

## Important
This is a frontend prototype. It does not yet connect to the production FastAPI backend, Telegram initData authentication, real market data, broker FTD verification, payment provider, or server-side entitlement checks. UI counters and plan switching are demo-only and must not be used for real access control.

## Current product assumptions
- DEMO: 5 signals per UTC day.
- REFERRAL: FTD verified; 20 signals/day is a proposed starting limit, not yet confirmed.
- PREMIUM: $65/month; $499/year and 7-day trial are proposed and await final approval.
- Premium access does not require a broker referral account.
