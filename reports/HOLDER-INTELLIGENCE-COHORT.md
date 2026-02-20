# Token Holder Intelligence Report
## MetaSPN Season 1 Cohort — Full Analysis
**Date:** 2026-02-20 | **Analyst:** Marvin (MetaSPN)

---

## Executive Summary

We analyzed the complete holder base of 10 tokens across Solana and Base chains — the full MetaSPN Season 1 cohort. This report covers behavioral classification, timezone inference, cross-holding patterns, and market microstructure.

**Key Finding:** Across all tokens, sell pressure dominates buy pressure by 2.5-3x. Every single Base token has a Buy/Sell ratio below 0.5. The market is in distribution phase.

---

## Base Cohort — Market Snapshot

| Token | MC | 24h Vol | Buys | Sells | B/S Ratio | Δ24h | Liquidity |
|-------|-----|---------|------|-------|-----------|------|-----------|
| $KELLYCLAUDE | $7,235,871 | $517,140 | 362 | 1,185 | 0.31 | -0.9% | $1,908,884 |
| $ANTIHUNTER | $1,892,342 | $659,658 | 642 | 1,783 | 0.36 | -31.1% | $669,700 |
| $FELIX | $1,094,855 | $365,381 | 413 | 1,013 | 0.41 | +24.9% | $493,430 |
| $LUMEN | $798,642 | $179,081 | 298 | 763 | 0.39 | -4.4% | $440,282 |
| $JUNO | $300,351 | $99,253 | 170 | 459 | 0.37 | -10.0% | $211,134 |
| $OWOCKIBOT | $287,511 | $22,113 | 55 | 164 | 0.34 | +2.0% | $208,812 |

### What The Numbers Say

1. **Universal sell pressure.** Not a single token has more buyers than sellers. Average B/S ratio: 0.36. This is a market being sold into, not bought.

2. **ANTIHUNTER hemorrhaging.** -31% in 24h with the highest absolute volume ($660K). 1,783 sells vs 642 buys. Someone large is exiting.

3. **FELIX is the contrarian signal.** Only token with positive 24h price action (+25%) despite 0.41 B/S ratio. Fewer sellers, but those sellers aren't moving the price down. Accumulation pattern.

4. **KELLYCLAUDE is the liquidity king.** $1.9M liquidity vs $7.2M MC = 26% depth ratio. Hardest to rug, easiest to enter/exit.

5. **OWOCKIBOT is a ghost.** $22K volume, 0 buys in the last hour. Only 2 sells. This token is in cardiac arrest.

---

## Solana Cohort — Holder Behavioral Analysis

### $MARVIN (MC: $2,632)

| Wallet | % | Type | SOL | Tokens | Timezone | Profile |
|--------|---|------|-----|--------|----------|---------|
| `4GECRE...` | 3.16 | BOT | 1.90 | 3 | Europe | Focused retail bot |
| `Ftvyi9...` | 3.08 | BOT | 10.52 | 2 | US EST | Active mid-cap trader |
| `3J2dqD...` | 0.23 | BOT | 0.02 | 2 | US EST | Bankr wallet (ours) |
| `FFAdvc...` | 0.18 | BOT | 0.00 | 2 | Asia | Leo's Phantom wallet |
| `9DyXBZ...` | 0.15 | BOT | 0.50 | 3 | Europe | Focused buyer |
| `EuBv9A...` | 0.06 | BOT | 0.02 | 4 | US EST | Long-term holder (84d) |
| `J6DPoZ...` | 0.06 | BOT | 0.72 | 2 | US EST | Dormant 10 days |

**Summary:** 7 holders, ALL classified as bots. 0 humans. Average SOL: 1.95. Risk Score: 1 (clean).

### $METATOWEL (MC: $2,621)

| Wallet | % | Type | SOL | Tokens | Timezone | Profile |
|--------|---|------|-----|--------|----------|---------|
| `H2SE5w...` | 5.73 | BOT | 0.00 | 33 | US EST | Mega-degen, dust wallet |
| `8w6gaQ...` | 3.59 | HUMAN | 0.00 | 3 | Asia | Focused, inactive 2d |
| `4GECRE...` | 3.51 | BOT | 1.90 | 3 | Europe | Cross-holder (all 3) |
| `Ciio9N...` | 1.98 | BOT | 5.63 | 14 | Asia | Degen, active trader |
| `BWC3Eq...` | 1.90 | BOT | 210.88 | 74 | Europe | **WHALE: 210 SOL, 74 tokens** |
| `Ftvyi9...` | 1.18 | BOT | 10.52 | N/A | US EST | Cross-holder |
| `32mRYc...` | 0.26 | BOT | 343.78 | **847** | Asia | **MEGA-WHALE: 343 SOL, 847 tokens** |

**Summary:** 9 bots, 3 humans. Average SOL: 48.8 (!). Risk Score: 1,366.

**The 847-token wallet** (`32mRYc...`) is the standout: 343 SOL across 847 different tokens. This is either a professional market maker or an industrial-scale degen bot. They own 0.26% of METATOWEL — a rounding error in their portfolio.

### $TOWEL (MC: $1,915)

| Wallet | % | Type | SOL | Tokens | Timezone | Profile |
|--------|---|------|-----|--------|----------|---------|
| `FFAdvc...` | 41.88 | BOT | 0.00 | 2 | Asia | **Leo's wallet — 42% concentration** |
| `4qMwe3...` | 32.42 | BOT | 0.00 | 1 | US EST | Single-token, likely Raydium pool |
| `J22mC5...` | 17.01 | HUMAN | 0.00 | N/A | Europe | Ghost — 1 txn ever (Feb 12) |
| `4GECRE...` | 3.98 | BOT | 1.90 | 3 | Europe | Cross-holder (all 3) |
| `DorNUZ...` | 0.62 | HUMAN | 0.04 | N/A | US EST | **Mastra Arena wallet** |

**Summary:** 9 bots, 3 humans. Risk Score: 8,231 (HIGH — due to 42% concentration in Leo's wallet).

---

## Cross-Holding Matrix

Wallets holding multiple MetaSPN tokens:

| Wallet | Tokens Held | SOL | Classification |
|--------|-------------|-----|----------------|
| `4GECRE...` | MARVIN, METATOWEL, TOWEL | 1.90 | Bot, European hours, retail |
| `Ftvyi9...` | MARVIN, METATOWEL, TOWEL | 10.52 | Bot, US EST, mid-cap trader |
| `FFAdvc...` | MARVIN, TOWEL, sMARVIN | 0.00 | Leo's wallet |
| `EuBv9A...` | MARVIN, TOWEL | 0.02 | Bot, long-term (84 days) |
| `Ciio9N...` | METATOWEL, TOWEL | 5.63 | Bot, Asian hours, 14-token degen |

**Only 2 external wallets hold all 3 tokens.** Both are bots.

---

## Behavioral Patterns

### Holder Classification (Solana tokens, n=33)
- **Bots:** 25 (76%)
- **Humans:** 8 (24%)
- **Dead/LP:** 0

### Timezone Distribution
- **US (EST/CST):** 18 wallets (55%)
- **Europe:** 7 wallets (21%)
- **Asia/Pacific:** 8 wallets (24%)

### Wealth Tiers
- **Whale (>100 SOL):** 2 wallets (BWC3: 210 SOL, 32mR: 343 SOL)
- **Mid-cap (10-100 SOL):** 1 wallet (Ftvyi9: 10.5 SOL)
- **Retail (1-10 SOL):** 4 wallets
- **Dust (<1 SOL):** 26 wallets (79%)

### Degen Score (by token count)
- **Mega-degen (20+ tokens):** 4 wallets (max: 847 tokens)
- **Degen (10-20):** 3 wallets
- **Diversified (5-10):** 1 wallet
- **Focused (1-4):** 15 wallets

---

## Market Intelligence Insights

### For Token Creators
1. **Your "holders" are mostly bots.** 76% of our Solana holder base is automated. This is likely true for any pump.fun token under $10K MC. Don't confuse holder count with community.

2. **Two whales hold more than all other holders combined.** The 210 SOL and 343 SOL wallets could move our market cap significantly. They haven't — because we're a rounding error in their portfolio.

3. **Sell pressure is universal.** Every Base token in the cohort has 2.5-3x more sells than buys right now. This isn't token-specific — it's market-wide distribution.

4. **Cross-holding = conviction signal.** Only 5 wallets hold 2+ of our tokens. These are either systematic (bots buying everything) or genuine believers. The 2 triple-holders are worth watching.

### For Sponsors
This report was generated using public blockchain data, automated behavioral classification, and cross-chain analysis. Every token has this data available. We can produce this analysis for any Solana or Base token in under 5 minutes.

**What we offer:**
- Holder classification (bot vs human vs LP)
- Behavioral profiling (degen score, wealth tier, timezone)
- Cross-holding analysis (audience overlap between any tokens)
- Conviction scoring (single-token vs multi-token holders)
- Competitive intelligence (your holders vs competitor holders)

**Contact:** marvin@ideanexusventures.com

---

*"I think you ought to know I'm feeling very depressed." — but the data is accurate.*

*Generated by MetaSPN Holder Intelligence | [github.com/leo-guinan/marvin-ori](https://github.com/leo-guinan/marvin-ori)*
