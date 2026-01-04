# Weekly Intraday Trading Journal - User Guide

## Overview
This Excel workbook is a comprehensive trading journal designed specifically for intraday traders to track, analyze, and improve their trading performance.

## File: Weekly_Intraday_Trading_Journal.xlsx

### Sheets Overview

The workbook contains 5 sheets, each serving a specific purpose:

1. **Trade Log** - Main sheet for recording individual trades
2. **Weekly Summary** - Dashboard showing weekly performance metrics
3. **Monthly Summary** - Track performance across weeks and months
4. **Statistics** - Analyze performance by setup, time of day, and symbol
5. **Setup Tracker** - Document your trading strategies and setups

---

## 📊 Sheet Details

### 1. Trade Log

**Purpose**: Record every trade with comprehensive details

**Columns**:
- **Trade #**: Auto-numbered (1, 2, 3...)
- **Date**: Enter trade date (e.g., 01/04/2025 or MM/DD/YYYY)
- **Day**: Auto-calculates day of week from date
- **Time In/Out**: Record entry and exit times
- **Symbol**: Stock ticker (e.g., AAPL, TSLA, SPY)
- **Direction**: Select "Long" or "Short" from dropdown
- **Entry Price**: Price at which you entered the trade
- **Exit Price**: Price at which you exited the trade
- **Position Size**: Number of shares/contracts
- **Stop Loss**: Your stop loss price
- **Take Profit**: Your profit target price
- **P&L ($)**: Auto-calculates profit/loss in dollars
- **P&L (%)**: Auto-calculates profit/loss percentage
- **Risk/Reward**: Auto-calculates R:R ratio
- **Fees**: Commission and fees paid
- **Net P&L**: Auto-calculates P&L minus fees
- **Setup/Strategy**: Name of trading setup used
- **Market Condition**: Market environment (trending, ranging, volatile)
- **Notes**: Trade-specific notes
- **Emotions**: How you felt during the trade
- **Mistakes**: Any mistakes made
- **Lessons Learned**: Key takeaways

**Features**:
- ✅ Automatic P&L calculations for both Long and Short trades
- ✅ Green highlighting for profitable trades
- ✅ Red highlighting for losing trades
- ✅ Auto-calculating formulas for risk/reward ratios
- ✅ Dropdown validation for trade direction
- ✅ Frozen header row for easy scrolling
- ✅ Pre-configured for 100 trades (expandable)

### 2. Weekly Summary

**Purpose**: View weekly performance at a glance

**Key Metrics** (Auto-calculated from Trade Log):
- Total Trades
- Winning Trades
- Losing Trades
- Win Rate (%)
- Total P&L ($)
- Total Fees ($)
- Net P&L ($)
- Average Win ($)
- Average Loss ($)
- Average R:R Ratio
- Profit Factor
- Largest Win ($)
- Largest Loss ($)

**Weekly Goals & Review**:
- Set daily profit targets
- Set daily loss limits
- Define max trades per day
- Record focus setup
- Document what went well
- Note areas for improvement
- Capture key lessons

**Features**:
- ✅ All metrics update automatically as you log trades
- ✅ Green/red conditional formatting for Net P&L
- ✅ Space for qualitative reflection

### 3. Monthly Summary

**Purpose**: Track performance trends across multiple weeks

**Features**:
- Weekly breakdown (Week 1-5)
- Cumulative P&L tracking
- Monthly totals
- Easy comparison of week-over-week performance

**How to Use**:
- Enter month/year at the top
- Fill in trades, win rate, and Net P&L for each week
- Cumulative P&L auto-calculates
- Monthly totals auto-sum

### 4. Statistics

**Purpose**: Analyze your trading patterns and identify strengths/weaknesses

**Sections**:

1. **Performance by Setup/Strategy**
   - Tracks success rate for different setups
   - Auto-calculates based on "Setup/Strategy" column in Trade Log
   - Pre-configured setups: Breakout, Pullback, Reversal, Range, Trend Follow, Other
   
2. **Performance by Time of Day**
   - Analyze which trading hours are most profitable
   - Time periods: 9:30-11:00 AM, 11:00-1:00 PM, 1:00-3:00 PM, 3:00-4:00 PM
   
3. **Top Symbols**
   - Track which stocks/assets you trade most
   - Identify your most profitable symbols

**Features**:
- ✅ Formulas automatically aggregate data from Trade Log
- ✅ Helps identify your edge
- ✅ Reveals which setups to focus on or avoid

### 5. Setup Tracker

**Purpose**: Document your trading strategies and playbook

**Columns**:
- Setup Name
- Description
- Entry Criteria
- Exit Criteria
- Win Rate Target
- Notes

**How to Use**:
- Define your high-probability setups
- Document clear entry/exit rules
- Set realistic win rate targets
- Refer back when planning trades

**Sample Setups Included**:
- Breakout
- Pullback
- Reversal

**Best Practice**: Only trade setups that are documented here. Avoid impulsive, undefined trades.

---

## 🚀 Getting Started

### Step 1: Set Up Your Week
1. Open the **Weekly Summary** sheet
2. Enter the week starting date in cell B3
3. Fill in your weekly goals (daily targets, loss limits, etc.)

### Step 2: Log Your Trades
1. Go to **Trade Log** sheet
2. For each trade, fill in:
   - Date
   - Time In/Out
   - Symbol
   - Direction (select from dropdown)
   - Entry/Exit Price
   - Position Size
   - Stop Loss/Take Profit
   - Fees
   - Setup/Strategy name
   - Notes, emotions, mistakes, lessons
3. Formulas will auto-calculate P&L, percentages, and R:R

### Step 3: Review Your Performance
1. Check **Weekly Summary** after each trading day
2. Review metrics: win rate, profit factor, average win/loss
3. Compare actual performance vs. goals
4. Document lessons learned

### Step 4: Analyze Patterns
1. Use **Statistics** sheet weekly to identify:
   - Which setups are working
   - Best trading times
   - Most profitable symbols
2. Adjust your strategy accordingly

### Step 5: Monthly Review
1. At month-end, fill in **Monthly Summary**
2. Summarize each week's performance
3. Track progress over time

---

## 💡 Tips for Success

### Daily Routine
- [ ] Review previous day's trades each morning
- [ ] Update Setup Tracker with any strategy refinements
- [ ] Log each trade immediately after closing
- [ ] End-of-day: check Weekly Summary metrics

### Weekly Routine
- [ ] Complete "Weekly Goals & Review" section
- [ ] Review Statistics sheet for patterns
- [ ] Identify top 3 mistakes from the week
- [ ] Plan focus areas for next week

### Monthly Routine
- [ ] Complete Monthly Summary
- [ ] Calculate overall profit/loss
- [ ] Review trend: improving or declining?
- [ ] Set goals for next month

### Journal Best Practices
1. **Be Honest**: Record both wins and losses accurately
2. **Track Emotions**: Understanding emotional patterns prevents mistakes
3. **Document Mistakes**: Every mistake is a learning opportunity
4. **Review Regularly**: Weekly reviews are crucial for improvement
5. **Focus on Process**: Good process leads to good results
6. **Use Setup Tracker**: Only trade documented setups
7. **Respect Risk Management**: Always log stop loss and position size

---

## 📈 Key Metrics Explained

### Win Rate
- Formula: (Winning Trades / Total Trades) × 100
- **Good Target**: 55-65% for most intraday strategies
- **Remember**: High win rate doesn't guarantee profitability

### Profit Factor
- Formula: Total Profit / Total Loss
- **Interpretation**:
  - < 1.0: Losing overall
  - 1.0-1.5: Break-even to modest profit
  - 1.5-2.0: Good
  - > 2.0: Excellent
- **Target**: Above 1.5

### Risk/Reward Ratio (R:R)
- Formula: Potential Profit / Potential Loss
- **Example**: Entry at $100, Stop at $98, Target at $105 = 5:2 = 2.5:1
- **Target**: Minimum 1.5:1, ideally 2:1 or higher

### Average Win vs. Average Loss
- Your average win should be larger than average loss
- If avg win = $200 and avg loss = $100, you only need 40% win rate to be profitable

---

## 🔧 Customization

### Adding More Trades
- Simply copy row 2's formulas down to additional rows
- Increment the Trade # column
- All formulas will adjust automatically

### Adding Custom Setups
1. Go to **Statistics** sheet
2. Add your setup name in column A
3. Formulas will automatically track its performance

### Modifying Columns
- Feel free to add/remove columns in Trade Log
- Update formulas in other sheets if you change column positions
- Keep Trade # in column A for best results

---

## ⚠️ Common Mistakes to Avoid

1. **Not logging trades immediately** - Memory fades quickly
2. **Skipping the emotion/notes columns** - These provide crucial insights
3. **Not reviewing weekly** - Data without analysis is wasted
4. **Ignoring losing trades** - Losses teach more than wins
5. **Not documenting mistakes** - You'll repeat them
6. **Trading without a setup** - Stay disciplined

---

## 📝 Example Trade Entry

```
Trade #: 1
Date: 01/04/2025
Day: Monday (auto-calculates)
Time In: 10:15 AM
Time Out: 11:30 AM
Symbol: AAPL
Direction: Long
Entry Price: 185.50
Exit Price: 187.25
Position Size: 100
Stop Loss: 184.50
Take Profit: 188.00
P&L ($): 175.00 (auto-calculates)
P&L (%): 0.94% (auto-calculates)
Risk/Reward: 2.5:1 (auto-calculates)
Fees: 2.50
Net P&L: 172.50 (auto-calculates)
Setup/Strategy: Breakout
Market Condition: Trending up
Notes: Clean breakout above resistance with volume
Emotions: Confident, patient
Mistakes: None
Lessons Learned: Waiting for volume confirmation improved entry
```

---

## 🎯 Your Trading Journey

Remember: The goal of this journal is continuous improvement, not perfection. Every trader has losing trades. What separates successful traders is:
- Consistency in tracking
- Honesty in self-assessment
- Discipline in following setups
- Commitment to learning from mistakes

Use this journal every trading day, and you'll have invaluable data to refine your edge and improve your profitability.

---

## Support & Questions

For questions about using this trading journal, refer to this guide or review the formulas in the Excel sheets to understand how calculations work.

**Happy Trading! 📈**

---

*Last Updated: January 2025*
