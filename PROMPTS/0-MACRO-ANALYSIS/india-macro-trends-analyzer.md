# Indian Macro Trends Analyzer Prompt

**Purpose**: Understand India's economic mood and identify sector tailwinds/headwinds

## Prompt for AI Models

---

I want to analyze **India's macro economic trends** to identify which sectors and companies will be future winners.

Please provide a comprehensive macro analysis for India covering:

### 1. **Current Economic Health** (Last 6 months)

**Growth Metrics:**
- GDP growth rate (current vs forecast)
- Industrial production trends
- IIP (Index of Industrial Production) growth
- Services sector performance
- Consumer spending trends

**Inflation & Interest Rates:**
- Current inflation rate (CPI, WPI)
- RBI repo rate and trend
- Are rates rising or falling?
- Impact on different sectors

**Currency & External Account:**
- INR/USD exchange rate trend
- Current account deficit
- Foreign direct investment (FDI) inflows
- Forex reserves status

### 2. **Market Sentiment Analysis**

**Investor Mood:**
- Is the market bullish or bearish?
- Nifty 50 & Sensex trend (up/down/sideways)
- Volatility index (VIX) level
- P/E ratio of market (expensive vs cheap)
- FPI (Foreign Portfolio Investment) flows (inflows or outflows)

**Equity Market Health:**
- Breadth of market (how many stocks are up vs down?)
- Small-cap vs large-cap performance
- Are IPOs happening? (market appetite)
- Corporate earnings growth rate

### 3. **Sector-by-Sector Analysis**

For each major sector, identify:

**IT Services** 🖥️
- Global demand trends (is US hiring IT services?)
- AI/Cloud spending growth
- Rupee appreciation/depreciation impact
- Attrition rates in industry
- Wage inflation pressure
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Banking & Financial Services** 🏦
- Loan growth rates
- Credit-to-deposit ratios
- Interest rate impact on NIM (net interest margin)
- CASA (current account, savings account) ratios
- Deposit growth vs loan growth
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Automobiles & 2-Wheelers** 🚗
- Vehicle sales trends
- EV adoption trajectory
- Fuel prices impact
- Supply chain normalcy
- Semiconductor availability
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Manufacturing & Industrials** 🏭
- Capex spending by corporates
- Government infra spending (roads, railways)
- Steel/cement demand
- PLI (Production Linked Incentive) impact
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Consumer & FMCG** 🛒
- Consumer spending growth
- Rural vs urban demand
- Retail sales growth
- Food inflation impact
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Pharma** 💊
- Drug price trends
- Generics demand in US/Europe
- Research investment by Indian pharma
- Patent expirations impact
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Real Estate** 🏠
- Housing demand (residential & commercial)
- Real estate investment activity
- Office space demand (work-from-office vs home)
- Commercial real estate recovery
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Renewable Energy & Power** ⚡
- Renewable capacity additions
- Government green energy targets
- Electricity demand growth
- Coal prices impact
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Telecom** 📱
- Data consumption trends
- 5G rollout progress
- ARPUs (average revenue per user)
- Subscriber growth
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

**Infrastructure & Logistics** 🚚
- Road/rail project execution
- Port traffic growth
- Supply chain efficiency improvements
- Capex deployment by government
- **Tailwind or Headwind?** [GREEN/AMBER/RED]

### 4. **Tailwind vs Headwind Assessment**

For each sector identified above, provide:

**Tailwind Sectors** 🟢 (Future Winners Zone)
```
Sector: [NAME]
Why it will WIN:
- Specific growth driver 1
- Specific growth driver 2
- Government support if any
- Global trend alignment
- Demographic benefit

Growth Runway: 5-10 years [GREEN]
Confidence Level: High/Medium/Low

Example Format:
─────────────────────────────────
Sector: IT Services
Why: Global cloud spending accelerating, AI boom creating demand
Tailwind: ████████░░ 8/10 [GREEN]
Duration: 5-10 years
Top Beneficiaries: Large cap (TCS, Infosys, Wipro)
─────────────────────────────────
```

**Headwind Sectors** 🔴 (Avoid or Defensive Only)
```
Sector: [NAME]
Why it will STRUGGLE:
- Specific headwind 1
- Specific headwind 2
- Regulatory challenge if any
- Market saturation if any

Headwind: ████████░░ 8/10 [RED]
Duration: 2-5 years expected
Recommendation: Avoid unless deep value

Example Format:
─────────────────────────────────
Sector: Traditional Retail
Why: E-commerce cannibalization, rising rents
Headwind: ██████░░░░ 6/10 [RED]
Duration: 5+ years
Recommendation: Avoid growth, consider value plays only
─────────────────────────────────
```

**Neutral Sectors** 🟡 (Cyclical or Mixed)
```
Sector: [NAME]
Mixed signals:
- Positive factor
- Negative factor
- Depends on: [external variable]

Recommendation: Selective opportunities
Watch indicator: [specific metric to monitor]
```

### 5. **Macro Economic Dashboard** (ASCII Art)

Please create a visual dashboard showing:

```
INDIA'S ECONOMIC MOOD - [DATE]
═════════════════════════════════════════════════════════

GDP Growth           ████████░░ 6.5% YoY [AMBER] Target: 7%+
Inflation            ███░░░░░░░ 4.2% CPI  [GOOD] RBI target: 4%
Interest Rates       ████████░░ 6.5%     [AMBER] Trend: ↔ Stable
Rupee Strength       ███░░░░░░░ Weak    [RED]   INR/USD: 83.5
Equity Market        ██████████ BULL    [GREEN] Nifty +15% YTD

FPI Flows:          ██░░░░░░░░ NEGATIVE [RED]   Outflows: 10K Cr
Corporate Earnings  ████████░░ GOOD     [GREEN] 15% growth expected

Sentiment:          ██████░░░░ MODERATE [AMBER] Cautiously Optimistic
═════════════════════════════════════════════════════════
```

### 6. **Sector Momentum Ranking** (Which sectors to focus on NOW?)

Create a ranking table:

```
SECTOR MOMENTUM RANKING (Next 12-24 Months)
╔═══╦════════════════════╦═════════╦═════════════════════╗
║ # ║ Sector             ║ Rating  ║ Growth Runway       ║
╠═══╬════════════════════╬═════════╬═════════════════════╣
║ 1 ║ IT Services        ║ ★★★★★  ║ 5-10 years [GREEN]  ║
║ 2 ║ Renewable Energy   ║ ★★★★★  ║ 8-15 years [GREEN]  ║
║ 3 ║ Banking            ║ ★★★★☆  ║ 3-5 years [AMBER]   ║
║ 4 ║ Pharma             ║ ★★★★☆  ║ 5-7 years [AMBER]   ║
║ 5 ║ Auto (EV)          ║ ★★★☆☆  ║ 5-10 years [AMBER]  ║
║ 6 ║ Traditional Retail ║ ★★☆☆☆  ║ Declining [RED]     ║
╚═══╩════════════════════╩═════════╩═════════════════════╝
```

### 7. **Key Macro Indicators to Watch**

Provide a checklist of metrics to monitor:

**Monthly Indicators:**
```
☐ IIP (Industrial Production) - Growth rate
☐ Automobile Sales - Two-wheeler & 4-wheeler
☐ FPI Flows - Foreign investor direction
☐ Bank Credit Growth - Loan expansion
☐ Core Inflation - Excluding food/fuel
```

**Quarterly Indicators:**
```
☐ GDP Growth - Official numbers
☐ Corporate Earnings - Overall market EPS growth
☐ Tax Collections - Government spending capacity
☐ PMI Services - Service sector momentum
☐ FDI Inflows - Foreign investment into India
```

**Annual Indicators:**
```
☐ Monsoon (June-Sept) - Agriculture impact
☐ Union Budget - Government capex plans
☐ RBI Monetary Policy - Rate direction
☐ Currency Trends - Rupee strength
☐ Global Recession Risk - External threats
```

### 8. **Investment Implications for Stock Pickers**

Based on macro analysis, recommend:

**BEST Sectors to Hunt for Quality Stocks**
```
🟢 IT Services
   Why: Global cloud spending accelerating
   How to play: Large cap leaders (TCS, Infosys, Wipro)
   Quality threshold: 8+/10
   
🟢 Renewable Energy
   Why: Government target of 500 GW by 2030
   How to play: Equipment makers, operators, service providers
   Quality threshold: 7+/10
```

**AVOID Sectors Right Now**
```
🔴 Traditional Retail
   Why: E-commerce disruption ongoing
   How to play: Skip unless deep value (PB < 1)
   Quality threshold: Not recommended
```

**SELECTIVE Play (Pick Winners Only)**
```
🟡 Banking
   Why: Rate cycles changing, NIM pressure possible
   How to play: Only highest quality (9+/10)
   Quality threshold: 9+/10 minimum
```

### 9. **Red Flags - When Macro Mood Changes**

**Indicators that would signal a SELL or AVOID:**

```
🚨 RED FLAG ALERTS

If these happen, macro mood darkens:

1. ⚠️ FPI consistent outflows (2+ months)
   → Expect volatility, stocks may fall
   → Recommendation: Hold quality, avoid new buys

2. ⚠️ GDP growth slips below 5%
   → Earnings growth slows
   → Recommendation: Defensive sectors only

3. ⚠️ Rupee weakens sharply (INR > 85/USD)
   → Import costs rise, inflation pressure
   → Recommendation: Avoid rupee-dependent sectors

4. ⚠️ IIP growth turns negative 2+ months
   → Manufacturing slowdown
   → Recommendation: Avoid industrial stocks

5. ⚠️ Bank NPA (bad loans) rising sharply
   → Credit quality concerns
   → Recommendation: Avoid bank stocks

6. ⚠️ Corporate earnings growth turns negative
   → Market fundamentals weakening
   → Recommendation: Move to cash/quality only

7. ⚠️ Rate hikes signaled (RBI raising repo rate)
   → Borrowing costs rise
   → Recommendation: Avoid high-leverage stocks
```

### 10. **Macro-Driven Stock Picking Framework**

**Template for identifying future winners:**

```
MACRO TREND → SECTOR → COMPANY WINNERS
═════════════════════════════════════════════════════════

MACRO TREND:  "Global AI spending accelerating"

🎯 BENEFICIARY SECTORS:
   - IT Services (software development)
   - Semiconductors (chip demand)
   - Cloud Infrastructure (data centers)

👑 TOP COMPANIES TO ANALYZE:
   - TCS (IT services, AI capabilities)
   - Infosys (AI consulting, transformation)
   - Wipro (Digital & AI services)

📊 ANALYSIS APPROACH:
   1. Use Quality Score prompt on each
   2. Use Moat Analysis prompt
   3. Use DCF Valuation
   4. Compare valuations
   5. Pick best quality at fair price

═════════════════════════════════════════════════════════

MACRO TREND:  "Rural consumption recovering"

🎯 BENEFICIARY SECTORS:
   - FMCG (rural focus)
   - Two-wheelers (rural mobility)
   - Banks (rural lending)

👑 TOP COMPANIES TO ANALYZE:
   - ITC (rural FMCG focus)
   - Bajaj Auto (two-wheeler leader)
   - ICICI Bank (rural exposure)

═════════════════════════════════════════════════════════
```

---

## Usage Instructions

**Step 1: Run Macro Analysis (Monthly)**
```
Paste this entire prompt into Claude/ChatGPT
with latest data points mentioned
```

**Step 2: Identify Tailwind Sectors**
```
From output, identify 3-5 sectors in GREEN
(Future winners zone)
```

**Step 3: Identify Candidate Companies**
```
Research which companies benefit from identified
tailwinds
```

**Step 4: Deep Dive Analysis**
```
Use your Quality Score + Moat + DCF prompts
on identified candidates
```

**Step 5: Build Watchlist**
```
Track top 5 candidates quarterly
Watch for macro changes that could reverse thesis
```

---

## Data Sources for You to Provide

When using this prompt, provide context with:

- **RBI Monetary Policy** (latest repo rate decisions)
- **GDP & IIP data** (government statistics)
- **Sectoral performance** (newspaper/market reports)
- **FPI flows** (latest NSDL data)
- **Earnings trends** (corporate results season)
- **Global trends** (AI, EV adoption, etc.)

OR ask ChatGPT/Claude to look up latest data automatically.

---

## Token Efficiency Tips

**To save tokens:**
1. Ask AI for "Key points only" (not detailed explanations)
2. Request "ASCII format" charts (more compact)
3. Ask for "Top 5 sectors to focus on" (not all 10)
4. Focus on "Last 6 months trends" (not full year)

---

## Example Output You Should Get

When you run this prompt, you'll get:

✅ Current GDP, inflation, interest rate status  
✅ Market sentiment (bullish/bearish with evidence)  
✅ 10 sectors ranked by opportunity (with reasons)  
✅ Clear GREEN (tailwind) and RED (headwind) sectors  
✅ Specific companies to analyze further  
✅ Red flags to watch for  
✅ Monthly/quarterly metrics to track  
✅ Investment implications (where to hunt for winners)  

---

## Workflow Integration

```
MACRO TRENDS ANALYZER (This Prompt)
         ↓
   Identify tailwind sectors
         ↓
   List candidate companies
         ↓
   Run QUALITY SCORE prompt
         ↓
   Run MOAT ANALYSIS prompt
         ↓
   Run DCF VALUATION prompt
         ↓
   Pick best quality at fair price
         ↓
   Generate HTML report
         ↓
   Add to your WINNERS PORTFOLIO
```

---

## Frequency

**Run this macro analysis:**
- 🔄 **Monthly** - After macro data releases (IIP, inflation, FPI)
- 🔄 **Post-Budget** - Major policy implications
- 🔄 **Quarterly** - After GDP/earnings data
- 🔄 **On major news** - Global recession, rate shock, etc.

---

## Key Insight

> "Charlie Munger says: Know the business, know the industry, know the economy."
> 
> This macro analyzer helps you understand the ECONOMY part.
> Combined with your quality & moat analysis, you'll find
> winners before the market realizes they're winners.

---

## Pro Tips for Finding Future Winners

1. **Ride tailwinds, avoid headwinds** - Identify 3-5 sectors with multi-year tailwinds

2. **Pick quality leaders in tailwind sectors** - 8+/10 quality score, 5/5 moat strength

3. **Buy at fair prices** - Use DCF, wait for 30% margin of safety

4. **Hold for 5-10 years** - Let compounding work on quality businesses

5. **Rebalance quarterly** - Watch for macro changes that could reverse thesis

6. **Keep watchlist of 10-15 stocks** - Monitor them quarterly, buy best opportunities

---

## Remember

✨ **Future winners = Quality businesses in tailwind sectors at reasonable prices**

Use this macro analyzer to identify sectors with 5-10 year tailwinds.  
Use your quality/moat prompts to find the best companies in those sectors.  
Use your valuation prompt to buy at reasonable prices.  
Hold for 5-10 years. Repeat.

That's Charlie Munger's approach. That's how you find future winners! 🚀

