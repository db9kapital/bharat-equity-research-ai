# HTML Report Generator Prompt

**Purpose**: Generate beautiful, token-efficient HTML reports with ASCII charts for stock analysis

## Prompt for AI Models

---

I want you to generate a **complete investment analysis report in HTML format** for **[COMPANY NAME]** (NSE/BSE: [TICKER]).

### Output Requirements

**Format**: Single HTML file (self-contained, no external dependencies)

**Styling**:
- Dark mode theme (dark background, light text)
- Use intuitive colors:
  - 🟢 **GREEN** (#10B981 or similar) for GOOD metrics (positive, buy signals)
  - 🟡 **YELLOW/AMBER** (#F59E0B) for CAUTION/MEDIUM (hold, watch)
  - 🔴 **RED** (#EF4444) for BAD/UGLY (negative, avoid signals)
  - 🔵 **BLUE** (#3B82F6) for NEUTRAL/INFO
- Responsive design (works on mobile and desktop)

**Charts**: Use ASCII art charts to minimize tokens:
- Bar charts for trend analysis
- Line charts for valuation ranges
- Heatmaps for risk matrices
- Sparklines for quick trends

**Structure**: Include these 8 sections with HTML organization

---

## HTML Report Sections

### Section 1: Executive Summary
```html
<!-- Hero section with key metrics -->
- Company name and ticker
- Quality rating (0-10) with color coding
- Valuation assessment (Undervalued/Fair/Overvalued) with color
- Risk level (Low/Medium/High) with color
- Overall recommendation (BUY/HOLD/AVOID) with prominent color
- Key investment thesis (2-3 sentences)
```

### Section 2: Business Overview
```html
<!-- Structured company information -->
- What the company does
- Key products/services
- Market position and rank
- Competitive landscape
```

### Section 3: Quality Assessment with Color Coding
```html
<!-- Scorecard with intuitive colors -->

Profitability Score: 9/10
█████████░ [GREEN] Excellent margins, stable

Cash Flow Quality: 9/10
█████████░ [GREEN] FCF > Net Income

Management Quality: 9/10
█████████░ [GREEN] Proven track record

Overall Quality Score: 8.5/10
████████░░ [GREEN - GOOD]

Include ASCII mini-table:
┌─────────────────┬────────┬─────────────────────────────────────────┐
│ Metric          │ Score  │ Status                                  │
├─────────────────┼────────┼─────────────────────────────────────────┤
│ Profitability   │ 9/10   │ ████████░ [GREEN] Excellent            │
│ Cash Flow       │ 9/10   │ ████████░ [GREEN] Strong               │
│ Balance Sheet   │ 10/10  │ ██████████ [GREEN] Fortress            │
│ Management      │ 9/10   │ ████████░ [GREEN] Proven               │
└─────────────────┴────────┴─────────────────────────────────────────┘
```

### Section 4: Competitive Moat Analysis
```html
<!-- Moat visualization -->

Moat Type & Strength:

[Brand Moat]     ★★★★☆ [AMBER] 4/5 - Strong
[Switching Cost] ★★★★★ [GREEN] 5/5 - Very Strong
[Scale Moat]     ★★★★☆ [GREEN] 4/5 - Strong

Overall Moat: ★★★★★ VERY STRONG [GREEN]
Sustainability: 15-20 years [GREEN]

ASCII Moat Strength Chart:
┌─────────────────────────────────────────┐
│ Moat Strength Over Time                 │
├─────────────────────────────────────────┤
│ 5Y Ago: ████████░░ 8/10                 │
│ Today:  █████████░ 9/10 [GREEN ↗]       │
│ In 5Y:  ██████████ 10/10 [GREEN Proj]   │
└─────────────────────────────────────────┘
```

### Section 5: Financial Analysis with Trend Charts
```html
<!-- Key metrics with ASCII charts -->

Revenue Trend (Last 5 Years):
┌─ FY20 → FY24                           ┐
│                        ╱               │
│                      ╱                 │
│  21.5Cr          ╱ 31.9Cr [GREEN ↗]    │
│ ────────────────╱────────── CAGR: 12%  │
└─────────────────────────────────────────┘

Net Margin Trend:
┌─ Last 5 Years                          ┐
│ 20.5% → 22.7% → 23.9% → 23.8% → 22.9% │
│  [STABLE at 22-24%] [GREEN ✓]          │
└─────────────────────────────────────────┘

Key Financial Metrics Table:
┌──────────┬───────────┬───────────┬───────────┬─────────────────┐
│ Metric   │ FY22      │ FY23      │ FY24      │ Trend           │
├──────────┼───────────┼───────────┼───────────┼─────────────────┤
│ Revenue  │ 26.2 Cr   │ 28.5 Cr   │ 31.9 Cr   │ ↗ [GREEN] GOOD  │
│ Margin   │ 23.9%     │ 23.8%     │ 22.9%     │ ↔ [AMBER] WATCH │
│ ROE      │ 32.4%     │ 31.8%     │ 30.2%     │ ↘ [AMBER] WATCH │
│ FCF      │ 6.9 Cr    │ 7.2 Cr    │ 8.1 Cr    │ ↗ [GREEN] GOOD  │
└──────────┴───────────┴───────────┴───────────┴─────────────────┘
```

### Section 6: Valuation Analysis with DCF Range
```html
<!-- Intrinsic value with color-coded assessment -->

DCF Valuation Summary:
┌─────────────────────────────────────────┐
│ INTRINSIC VALUE ESTIMATE                │
├─────────────────────────────────────────┤
│ Bear Case:   INR 3,729 [RED - Avoid]    │
│ Base Case:   INR 4,128 [BLUE - Fair]    │
│ Bull Case:   INR 4,989 [GREEN - Buy]    │
└─────────────────────────────────────────┘

Valuation Range Chart:
    UNDERVALUED          FAIR            OVERVALUED
       ↓                  ↓                 ↓
₹3,400  ┼─────[BEAR]─────[BASE]─────[BULL]─────₹5,100
        │ [GREEN]        [BLUE]       [YELLOW]  [RED]
        └────────────────────────────────────────
Current Price: ₹3,850 [BLUE] = Fairly Valued

Sensitivity Analysis (Growth vs WACC):
┌──────────┬──────────┬──────────┬──────────┐
│ Growth ↓ │ WACC 8.5%│ WACC 9.5%│WACC 10.5%│
├──────────┼──────────┼──────────┼──────────┤
│ 10%      │ ₹4,625   │ ₹4,128   │ ₹3,729   │
│ 12%      │ ₹5,103   │ ₹4,542   │ ₹4,061   │
│ 14%      │ ₹5,621   │ ₹4,989   │ ₹4,429   │
└──────────┴──────────┴──────────┴──────────┘

P/E Multiple vs Peers:
  TCS    Infosys  Wipro   Industry
┌──────┬──────────┬──────┬────────┐
│ 25.2x│   26.1x  │16.8x │ 22.7x  │
│[AMB.]│  [RED]   │[GRN] │        │
└──────┴──────────┴──────┴────────┘
Verdict: FAIR [BLUE] - Small margin of safety
```

### Section 7: Risk Assessment Heat Map
```html
<!-- Color-coded risk matrix -->

Risk Assessment Matrix:
┌────────────────────┬──────────┬──────────┬──────────┐
│ Risk               │ Impact   │ Prob.    │ Status   │
├────────────────────┼──────────┼──────────┼──────────┤
│ AI Disruption      │ HIGH     │ MEDIUM   │ [AMBER]  │
│ US Recession       │ HIGH     │ MEDIUM   │ [AMBER]  │
│ Talent Attrition   │ MEDIUM   │ MEDIUM   │ [AMBER]  │
│ Margin Compression │ MEDIUM   │ LOW      │ [GREEN]  │
│ Regulation         │ LOW      │ LOW      │ [GREEN]  │
└────────────────────┴──────────┴──────────┴──────────┘

Overall Risk Rating: [GREEN] LOW RISK

Risk Level Gauge:
[LOW]  ▓▓▓░░░░░░░░░░░░░░░░░  [HIGH]
       ↑
     Current
```

### Section 8: Investment Decision
```html
<!-- Final recommendation with action items -->

FINAL VERDICT
═════════════════════════════════════════════════

Quality Score:        ████████░░ 8.5/10 [GREEN]
Valuation:           ███████░░░ Fair   [BLUE]
Moat Strength:       ██████████ V.Str. [GREEN]
Risk Level:          ██░░░░░░░░ LOW    [GREEN]
Management Quality:  █████████░ 9/10   [GREEN]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

RECOMMENDATION: [HOLD / BUY ON DIPS]

Current Price:     ₹3,850
Fair Value:        ₹4,128
Margin of Safety:  Only 7% [AMBER - Limited]

BUY TRIGGER:       Below ₹3,500 [GREEN - Good Entry]
SELL TRIGGER:      Above ₹4,500 [YELLOW - Fair Exit]

Investment Thesis:
"Wonderful company at a fair price. Hold existing
positions. Buy on dips to ₹3,500 for new capital."

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Quarterly Monitoring Checklist:
☑ Revenue Growth (must be 10%+)
☑ Net Margins (should stay 22-24%)
☑ FCF > Net Income (quality test)
☑ Client retention (watch for losses)
☑ Attrition Rate (keep below 20%)

Red Flags That Would Prompt SELL:
🚨 Margins compress below 20%
🚨 FCF turns negative
🚨 Major client defection
🚨 Management changes
```

---

## HTML Styling Requirements

```css
/* Dark Mode Theme */
Background:    #0F172A (Dark Navy)
Text:          #F1F5F9 (Light Gray)
Accents:       #64748B (Slate Gray)

/* Status Colors */
GOOD (Green):  #10B981 (Emerald) - bg: #065F46
CAUTION (Amber): #F59E0B (Amber) - bg: #78350F
BAD (Red):     #EF4444 (Red) - bg: #7F1D1D
NEUTRAL (Blue): #3B82F6 (Blue) - bg: #1E3A8A

/* Typography */
Headers:       28px, Bold, Light Color
Subheaders:    20px, Bold, Light Color
Body Text:     16px, Regular, Light Gray
Numbers:       18px, Bold, Colored
```

---

## ASCII Chart Examples

**Simple Trend Line**:
```
FY20 → FY21 → FY22 → FY23 → FY24
  ╱       ╱       ╱       ╱
 ╱       ╱       ╱       ╱  [GREEN ↗]
```

**Horizontal Bar Chart**:
```
Profitability:  ▓▓▓▓▓▓▓▓▓░ 9/10 [GREEN]
Cash Flow:      ▓▓▓▓▓▓▓▓▓░ 9/10 [GREEN]
Management:     ▓▓▓▓▓▓▓▓░░ 8/10 [AMBER]
```

**Box Gauge**:
```
Risk Level:
[LOW]  ▓▓░░░░░░░░░░░░░░░░░  [HIGH]
       ↑
```

**Heat Map**:
```
Impact vs Probability:
HIGH    ┌─────┐
        │ AMB │ RED
MEDIUM  │ AMB │ RED
        │ GRN │ AMB
LOW     └─────┘
        LOW  HIGH
        Probability
```

---

## Important Instructions for AI

1. **Keep it concise**: Use ASCII charts instead of long descriptions
2. **Token efficient**: ASCII charts save ~80% tokens vs descriptions
3. **Self-contained HTML**: No external CSS/JS links, everything embedded
4. **Mobile responsive**: Use viewport meta tag
5. **Print friendly**: Works well when printed to PDF
6. **No external images**: Only ASCII and emojis
7. **Fast loading**: Minimal file size for quick sharing
8. **One file**: Single HTML that can be saved and shared

---

## Usage

**After running analysis prompts, ask the AI:**

> "Now generate an HTML report file with all the analysis above. Use:
> - Dark mode theme
> - ASCII charts for all trends
> - Green/Amber/Red color coding
> - One self-contained HTML file
> - Save as 'COMPANY_NAME_ANALYSIS.html'"

Then:
1. Copy the entire HTML code
2. Save as `.html` file
3. Open in any browser
4. Print to PDF if needed
5. Share with others or keep as record

---

## Token Savings Example

**Traditional Report** (Text with descriptions): 4,000-6,000 tokens  
**With ASCII Charts**: 1,500-2,500 tokens  

**Savings**: ~60-70% tokens! 🎉

---

## Example Output File Name

```
TCS_Quality_Analysis_2024-07-06.html
HDFC_Bank_Valuation_Report_2024-07.html
Infosys_Complete_Research_2024.html
```

Keep these files organized in a folder for record-keeping and easy reference!

