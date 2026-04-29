# Student Discount Model — Copilot Pro

Interactive financial model that tests whether offering a discounted/free student version of Copilot Pro is worth the investment.

**[Open the Dashboard →](https://joeingraham.github.io/student-discount-model/)**

## What It Models

- **CAC**: Total cost to acquire a converting student (trial infra + marketing)
- **Upsell Rate**: Trial → paid conversion, driven by toggles
- **Profit per User**: 40% of spend with a $10/mo floor, weighted by plan mix (Pro / Pro+ / overage)
- **Retention**: Two-phase churn curve (early + steady-state)
- **Full P&L**: Month-by-month cumulative profit/loss over a configurable horizon

## Toggles

| Toggle | Effect |
|--------|--------|
| **Credit Card Required** | Reduces signups but lifts conversion (CC on file = higher commitment) |
| **Student Price** | $0 = free trial; >$0 = discounted sub (offsets trial costs, lifts conversion) |
| **Auto-Upsell** | Auto-convert to full price after trial (requires CC to be fully effective) |
| **Trial Duration** | Longer trials cost more; sweet spot for conversion is 1-2 months |

## Quick Start

Just open `index.html` in a browser — no build step, no dependencies.
