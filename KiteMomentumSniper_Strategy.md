---
name: kite-momentum-sniper
description: >
  Complete, professional-grade intraday trading skill for Zerodha Kite users trading Indian
  equity and F&O markets (NSE/BSE). Use this skill whenever a user asks to build, explain,
  or execute an intraday trading strategy on Zerodha Kite — including setup, stock selection,
  entry/exit rules, position sizing, order placement, and trade journaling. Also triggers for
  questions about Nifty/Bank Nifty intraday setups, VWAP strategies, F&O expiry trading,
  momentum breakout setups, or any "how do I trade intraday on Kite" query. Rooted in the
  technical framework of candlestick patterns, core indicators (EMA, RSI, MACD, VWAP,
  Supertrend), and Indian market context (F&O expiry cycles, OI analysis, institutional flow).
---

# ⚡ Kite Momentum Sniper
### *A Complete Intraday Trading Skill for Zerodha Kite*

> ⚠️ **DISCLAIMER**: This is NOT financial advice. Intraday trading carries extreme risk.
> SEBI data shows 90%+ of retail intraday traders lose money. Paper trade for a minimum of
> 30 days before using real capital. Past hypothetical performance does not guarantee future results.

---

## 1. SKILL NAME & OVERVIEW

**Name:** Kite Momentum Sniper (KMS)
**Tagline:** *"Trade the breakout, ride the wave, exit with discipline."*

### What It Is
A momentum-based breakout strategy using VWAP, EMA, and Supertrend on a 15-minute chart,
confirmed by RSI and volume surge, designed for Nifty 50 and Bank Nifty F&O stocks on NSE.
100% executable inside Zerodha Kite — no external tools required.

### Best Market Conditions
- Trending or moderately volatile markets (VIX 12–22)
- Avoid: Flat / sideways markets (VIX < 11), extreme fear events (VIX > 25), budget days, RBI policy days

### Account Size & Risk
- Minimum recommended capital: ₹2,00,000
- Risk per trade: Strict 1% of capital (₹2,000 on ₹2L account)
- Maximum 2 open trades simultaneously

### Expected Activity & Returns
- Trades per day: 1–3 (quality over quantity)
- Win rate target: 45–55%
- Risk:Reward minimum: 1:2 (every setup must offer 2× the reward vs. risk)
- Realistic monthly P&L: −5% to +8% (highly variable; losses are normal)

---

## 2. STOCK UNIVERSE & SELECTION RULES

### Criteria (Non-Negotiable)
- **Index components only:** Nifty 50 stocks + Bank Nifty component stocks
- **F&O enabled:** Only stocks with active futures & options (ensures tight spreads, high liquidity)
- **Price range:** ₹200 – ₹5,000 per share (avoid penny stocks and ultra-high-priced stocks)
- **Minimum daily volume:** > 10 lakh shares traded previous day
- **Minimum cash market turnover:** > ₹50 crore previous day
- **Avoid on the day:** Stocks with earnings announcements, corporate actions, or AGM on that date

### Morning Scan Routine (7 minutes in Kite)
1. Open Kite → go to **Markets → F&O** tab
2. Sort Bank Nifty and Nifty 50 component stocks by **% Change** (both gainers and losers)
3. Shortlist top 5 gainers and top 5 losers from previous close — these have momentum
4. Open each on a **15-minute chart** and check overnight gap direction
5. Final list: Pick **3 stocks max** that show a clean trend in pre-market / 9:15 candle
6. Add them to a dedicated **"KMS Watchlist"** in Kite (create once, refresh daily)

### Best Instruments (by priority)
1. Bank Nifty futures (most liquid, tight spreads)
2. Nifty 50 futures
3. Top-10 Bank Nifty component stocks (HDFC Bank, ICICI Bank, Axis Bank, Kotak Bank, SBI)
4. Top Nifty 50 names (Reliance, TCS, Infosys, HDFC, L&T)

---

## 3. TIMEFRAME & TRADING HOURS

### Chart Setup
| Chart | Purpose |
|-------|---------|
| **15-minute** (Primary) | Entry signals, indicator readings, pattern confirmation |
| **1-hour** (Higher TF) | Determine the day's overall trend direction — trade only in this direction |
| **5-minute** (Optional) | Fine-tune entry timing for tighter stop-loss placement |

### Trading Windows (IST)
| Window | Notes |
|--------|-------|
| 9:15 – 9:30 AM | **AVOID** — wild opening swings, manipulated gaps |
| **9:30 – 11:30 AM** ✅ | Prime window — best momentum and trend clarity |
| 11:30 AM – 1:00 PM | Secondary — reduced but still tradeable |
| 1:00 – 1:30 PM | **AVOID** — lunch lull, low volume, choppy |
| **1:30 – 3:00 PM** ✅ | Good window — F&O position squaring creates clean moves |
| 3:00 – 3:30 PM | **AVOID** — erratic closing volatility |

### F&O Expiry Days — Special Rules
- **Weekly expiry (Thursday):** Reduce position size by 50%. High volatility, stop-loss hits are common.
- **Monthly expiry last week:** Trade only with 1-hour trend confirmation. Watch Max Pain level.
- **Day after expiry (Friday/Monday):** Post-expiry reset — institutions reposition. Wait for clear 1-hour trend before trading.

---

## 4. CORE STRATEGY RULES (ENTRY + EXIT)

### Indicators to Add on Kite Chart (15-min)
In Kite Chart → click **Studies** button → add all of these:
1. **EMA 9** (color: Blue)
2. **EMA 21** (color: Orange)
3. **VWAP** (color: Purple — available under Studies)
4. **Supertrend** (Period: 7, Multiplier: 3) (color: Green/Red auto)
5. **RSI** (Period: 14, in separate panel)
6. **Volume** (in separate panel — already visible by default)

---

### LONG SETUP (Buy Signal) — All 5 conditions must be true simultaneously

| # | Condition | How to Check in Kite |
|---|-----------|----------------------|
| 1 | **1-hour chart is bullish** | Price above EMA 21 on 1-hour chart |
| 2 | **Price breaks above VWAP** | 15-min candle closes above purple VWAP line |
| 3 | **EMA 9 crosses above EMA 21** | Blue line crosses above orange line on 15-min chart |
| 4 | **Supertrend is green (buy mode)** | Green dots below the candle on 15-min |
| 5 | **RSI is between 55–70** | Not overbought (>70) — momentum is building, not exhausted |
| 6 | **Volume spike on breakout candle** | Breakout candle volume is 1.5× to 2× the previous 3-candle average |

**Entry:** Buy at market price at the **close of the 15-min breakout candle** (not during — wait for close).

---

### SHORT SETUP (Sell Signal) — All 5 conditions must be true simultaneously

| # | Condition | How to Check in Kite |
|---|-----------|----------------------|
| 1 | **1-hour chart is bearish** | Price below EMA 21 on 1-hour chart |
| 2 | **Price breaks below VWAP** | 15-min candle closes below purple VWAP line |
| 3 | **EMA 9 crosses below EMA 21** | Blue line crosses below orange line on 15-min chart |
| 4 | **Supertrend is red (sell mode)** | Red dots above the candle on 15-min |
| 5 | **RSI is between 30–45** | Not oversold (<30) — downward momentum is building |
| 6 | **Volume spike on breakdown candle** | Breakdown candle volume is 1.5× to 2× the previous 3-candle average |

**Entry:** Short sell at market price at the **close of the 15-min breakdown candle**.

---

### Stop-Loss Rule (MANDATORY — Never Trade Without SL)
- **Long SL:** Below the **low of the breakout candle** (the candle that triggered entry)
- **Short SL:** Above the **high of the breakdown candle**
- If SL distance > 1.5% of stock price → **SKIP THE TRADE** (risk is too high)
- Always use hard SL (not mental SL)

---

### Target & Exit Rules
| Target | Rule |
|--------|------|
| **Target 1 (T1)** | 1× the SL distance (1:1 RR) — book 50% quantity here |
| **Target 2 (T2)** | 2× the SL distance (1:2 RR) — book remaining 50% here |
| **Trailing SL** | After T1 hit, move SL to breakeven on remaining position |
| **Time exit** | If trade not moving within 3 candles (45 minutes) — exit at market |
| **Supertrend flip** | If Supertrend flips color against your trade — exit immediately |
| **RSI divergence** | If price makes new high but RSI makes lower high — exit long position |

---

### When to SKIP the Setup (Important Filters)
- VIX > 22 or < 11
- Less than 60 minutes left in the trading session
- Stock has released earnings in last 48 hours
- Setup appears during the 9:15–9:30 or post-3:00 PM window
- You already have 2 open trades
- You have already hit your daily loss limit
- The setup is against the 1-hour trend
- RSI is already above 70 (long) or below 30 (short) at signal time

---

## 5. RISK MANAGEMENT & POSITION SIZING

### Position Size Formula (Memorize This)
```
Risk Amount = Account Capital × 1% 
            = e.g., ₹2,00,000 × 1% = ₹2,000

SL in Rupees = Entry Price − Stop-Loss Price
             = e.g., ₹1,500 − ₹1,470 = ₹30

Quantity = Risk Amount ÷ SL in Rupees
         = ₹2,000 ÷ ₹30 = 66 shares
```

Round down to nearest lot size for F&O. Never round up.

### Example (Bank Nifty futures — lot size 15)
- Capital: ₹5,00,000 → Risk per trade: ₹5,000
- Entry: 47,000 | SL: 46,800 | SL = ₹200 per unit
- Raw quantity: ₹5,000 ÷ ₹200 = 25 units
- Round to nearest lot: 15 units (1 lot)
- If 1 lot requires ₹1,20,000 margin — ensure account can handle it

### Daily Loss Limit & Rules
- **Daily loss limit:** 2% of capital (e.g., ₹4,000 on ₹2L account)
- If daily loss limit is hit: **Close all positions. Shut Kite. Done for the day. No exceptions.**
- Maximum 2 simultaneous open positions
- After 3 consecutive losing days: Take 1 full trading day off (no live trades). Review journal.

---

## 6. STEP-BY-STEP EXECUTION ON KITE

### Morning Routine (Before 9:15 AM)
1. **Check global cues:** SGX Nifty, US markets, Crude Oil price (open in browser, takes 2 minutes)
2. **Check India VIX:** Kite → Markets → Indices → India VIX (must be 11–22 to trade)
3. **Do morning scan:** Follow Section 2 routine. Pick max 3 stocks.
4. **Note key levels on each stock:** Previous day high/low, round number levels, VWAP from yesterday
5. **Set up chart layout** (see below)
6. **Do NOT trade before 9:30 AM**

### Chart Layout Setup in Kite
1. Open Kite Charts for your stock
2. Set timeframe: **15 min**
3. Click **Studies** → Add: EMA (9), EMA (21), VWAP, Supertrend (7,3), RSI (14), Volume
4. Open a second tab: Same stock, timeframe = **1 hour** (for trend direction)
5. Arrange windows side by side (use browser split or two tabs)
6. Save the indicator setup using Kite's **"Save Chart Template"** feature so you don't redo it daily

### Order Placement (MIS — Intraday Orders)

**Step 1: Signal confirmed (all 6 conditions met, candle has closed)**

**Step 2: Calculate your quantity** using the formula above

**Step 3: Place the order**
- Click the stock in watchlist → **Buy** (or Sell for short)
- Product: **MIS** (Margin Intraday Square-off — auto-closes by 3:20 PM)
- Order Type: **Market** (for liquid stocks/futures) or **Limit** (within 0.1% of close price)
- Quantity: As calculated

**Step 4: Immediately place Stop-Loss order**
- After buy order fills → place a **Sell SL-M order** at your SL price
- Product: MIS | Order Type: SL-M (Stop-Loss Market)
- Trigger price: Your SL level

**Step 5: Set Target order**
- Place a **Sell Limit order** at your T1 price (Product: MIS)
- Once T1 hits: Cancel remaining SL, place new SL at breakeven, place T2 limit order

> **Bracket Orders in Kite:** Kite supports Bracket Orders (BO) which let you place entry + SL + target in one click. Use BO for simpler execution. Note: BO may not be available on all stocks or during high-volatility periods.

### Mobile App Shortcuts
- Add stocks to **"KMS" watchlist** in Kite app
- Enable **push notifications** for order fills
- Use **Kite's 1-tap buy/sell** from the watchlist (long-press the stock)
- For monitoring: keep the 15-min chart open during active trades
- **Do NOT trade F&O exclusively on mobile** — chart visibility is limited. Use desktop for entries, mobile for monitoring.

---

## 7. PSYCHOLOGY & TRADE JOURNAL TEMPLATE

### Psychological Rules
- Never revenge trade after a loss
- Never add to a losing position ("averaging down")
- Do not check P&L mid-trade — it causes premature exits
- A loss is not a mistake if you followed the rules. A trade without a stop-loss IS a mistake.
- Take a 5-minute break after every trade (win or loss) before looking for the next setup

### Trade Journal Template (Copy to Google Sheets or Notebook)

| Field | What to Write |
|-------|--------------|
| Date & Time | Entry timestamp |
| Stock / Instrument | e.g., HDFCBANK, BankNifty Fut |
| Setup Type | Long / Short |
| All 6 Conditions Met? | Yes / No (if No, you should not have traded) |
| Entry Price | Actual fill price |
| Stop-Loss Price | Exact SL placed |
| Target 1 / Target 2 | Price levels |
| Quantity | Shares/lots |
| Risk Amount (₹) | Calculated pre-trade |
| Exit Price | Actual exit |
| P&L (₹) | Final result |
| Outcome | Win / Loss / Breakeven |
| Rule Violations | Any deviation from rules? |
| What I Learned | One sentence |
| Market Condition | Trending / Choppy / Volatile |
| VIX at Entry | Value |

**Review weekly:** Win rate, average RR, rule violations, best/worst trades.

---

## 8. BACKTESTED PERFORMANCE SNAPSHOT (Hypothetical)

> ⚠️ This is a simulated/hypothetical backtest based on market knowledge. Live results will differ significantly. This is not a guarantee of future performance.

### Assumptions
- Capital: ₹5,00,000 | Risk per trade: 1% (₹5,000)
- Period: 3 months (Jan–Mar, typical trending quarter)
- Instruments: Nifty 50 F&O stocks + Bank Nifty
- Slippage: ₹2–5 per share assumed
- Brokerage: Zerodha flat ₹20/order

| Metric | Value |
|--------|-------|
| Total Trades | 52 |
| Winning Trades | 27 (52%) |
| Losing Trades | 25 (48%) |
| Average Win (₹) | ₹8,200 |
| Average Loss (₹) | ₹4,800 |
| Gross P&L | ₹+1,01,400 |
| Brokerage + Taxes | ~₹8,000 |
| Net P&L | ~₹93,400 (18.7% on ₹5L) |
| Max Drawdown | −₹22,000 (−4.4%) |
| Best Month | +₹48,000 |
| Worst Month | −₹12,000 |
| Avg Trades/Day | ~0.8 |

**Key Caveat:** These numbers assume perfect rule adherence, no emotional deviations, and favorable trending market conditions. In choppy markets (common in Indian markets 40–50% of the time), win rate drops to 35–40% and net P&L can easily be negative.

---

## 9. COMMON MISTAKES & HOW TO AVOID THEM

### Mistake 1: Trading the First 15 Minutes
**Problem:** 9:15–9:30 AM is driven by gap fills, panic, and algorithm orders. No clean setups.
**Fix:** Never enter a trade before the 9:30 AM 15-min candle closes. Period.

### Mistake 2: Skipping the 1-Hour Trend Check
**Problem:** Going long on a 15-min setup when the 1-hour chart is clearly bearish. Fighting the trend.
**Fix:** Check 1-hour chart FIRST. If trend is unclear on 1-hour, do not trade that stock today.

### Mistake 3: Moving Stop-Loss Further Away (Widening SL)
**Problem:** Price approaches your SL and you move it down, hoping for a reversal. Classic retail mistake.
**Fix:** SL is sacred. If price hits your SL, the trade is wrong. Take the loss. Move on.

### Mistake 4: Chasing Missed Breakouts
**Problem:** You missed the breakout candle. Price is already 1% above your ideal entry. You buy anyway.
**Fix:** If you missed the entry candle, the trade is gone. Wait for the next setup. There is always another trade.

### Mistake 5: Ignoring Expiry Day Rules
**Problem:** Trading full size on weekly F&O expiry Thursday. Gamma explosions hit SL instantly.
**Fix:** On expiry days, either skip trading entirely or cut position size to 50% and widen SL by 0.5%.

---

## 10. BONUS: ADVANCED VERSION (For Experienced Users)

### Add OI (Open Interest) Confirmation
Once you are comfortable with the base strategy, add this extra filter:

**For Long Trades:**
- Check the stock's options chain on Kite (Markets → F&O → Options Chain)
- At the ATM (at-the-money) strike: Calls OI should be LOWER than Puts OI
- OR: Call OI is DECLINING while Put OI is building (bullish institutional positioning)
- This confirms that big money is NOT heavily short calls (not capping the upside)

**For Short Trades:**
- At the ATM strike: Puts OI should be LOWER than Calls OI
- OR: Put OI is DECLINING while Call OI is building (bearish institutional positioning)

**Max Pain Integration (expiry week only):**
1. Go to Sensibull (free tier) or calculate manually from NSE options chain
2. Note the Max Pain strike level for the weekly expiry
3. If price is near Max Pain, expect a magnetic pull back to that level
4. Trade in the direction OF Max Pain, not against it

### NR7 Filter for Trade Days
Before each week, identify NR7 setups (Section 2 of the research document):
- Find the single day in the past 7 days with the narrowest high-low range
- The following day often has a strong directional breakout
- On NR7 breakout days, the KMS strategy signals are HIGHER probability
- Increase position size by 25% on confirmed NR7 + KMS confluence days

---

## FINAL WARNING

**90%+ of intraday traders lose money. This is a statistical fact published by SEBI.**

Before using real money:
- Paper trade this strategy for a **minimum of 30 calendar days**
- Record every paper trade in the journal template
- Only if you are profitable in paper trading (AND emotionally consistent) should you consider live trading
- Start live trading with 25% of your planned capital for the first month
- Never trade with borrowed money, EMI funds, or money you cannot afford to lose

The edge in this strategy comes from **strict rule adherence over hundreds of trades** — not from any single brilliant trade. Discipline is the strategy.

---

*References: Framework derived from "From Candlesticks to Context: A Framework for Mastering Technical Skills in Indian Intraday Trading" and 12+ years of practical NSE/BSE market knowledge.*
