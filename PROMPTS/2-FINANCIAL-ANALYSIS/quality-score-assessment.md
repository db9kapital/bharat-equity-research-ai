# Quality Score Assessment Prompt

**Charlie Munger Principle**: "Price is what you pay; value is what you get."

Quality score helps identify businesses worth paying a premium for.

## Prompt for AI Models

---

I want to assess the **business quality** of **[COMPANY NAME]** (NSE/BSE: [TICKER]) using Charlie Munger's quality framework.

Please evaluate the following quality metrics and provide a composite quality score:

### 1. **Financial Quality Indicators** (Weight: 30%)

**Profitability Trends (Last 5 years)**
- Net Profit Margin trend: Improving/Stable/Declining?
- Operating Profit Margin trend
- Return on Equity (ROE) vs peers
- Return on Assets (ROA)

**Balance Sheet Strength**
- Debt-to-Equity ratio (lower is better for Munger)
- Interest coverage ratio (higher is better)
- Working capital trends
- Cash conversion cycle

**Cash Generation**
- Free cash flow (FCF) trend vs net income
- Operating cash flow vs net income (quality indicator)
- Capital intensity (CapEx as % of revenue)

### 2. **Business Quality Indicators** (Weight: 30%)

**Revenue Quality**
- Revenue growth rate (last 5 years)
- Is growth from core business or acquisitions?
- Revenue concentration risk (top customers %)
- Pricing power evidence

**Customer Retention**
- Customer churn rate
- Revenue repeat rate
- Brand strength in market
- Market share stability

**Operational Efficiency**
- Asset turnover ratio
- Inventory turnover (for manufacturing)
- Days sales outstanding (DSO)
- Improvement in operational metrics

### 3. **Management Quality** (Weight: 25%)

**Leadership Track Record**
- How long has current management been in place?
- Track record of capital allocation
- History of shareholder returns
- Promoter shareholding (skin in the game)

**Corporate Governance**
- Any major red flags or controversies?
- Board independence and diversity
- Compensation structure (aligned with performance)
- Audit findings and compliance

### 4. **Competitive Position** (Weight: 15%)

**Market Position**
- Is company #1, #2, or #3 in its segment?
- Market share trend
- Brand recognition vs competitors
- Pricing vs competitors

**Moat Strength** (Link to moat analysis prompt)
- Economic moat rating
- Moat durability
- Threat from disruption

---

## Quality Score Calculation

### **Scoring Table** (0-10 scale for each category)

| Metric | Score 9-10 | Score 7-8 | Score 5-6 | Score 3-4 | Score 1-2 |
|--------|-----------|----------|----------|----------|-----------|
| **Profitability** | Exceptional & stable margins | Strong margins, stable | Adequate margins, volatile | Declining margins | Losses/very low margins |
| **Cash Flow** | FCF > NI consistently | FCF ≈ NI | FCF < NI | Negative FCF | Severe cash burn |
| **Growth** | 15%+ CAGR, sustainable | 10-15% CAGR | 5-10% CAGR | 0-5% CAGR | Declining |
| **Management** | Proven track record, aligned | Good track record | Adequate | Questions raised | Red flags |
| **Moat** | Very strong (5 star) | Strong (4 star) | Moderate (3 star) | Weak (2 star) | No moat (1 star) |

---

## Final Quality Score

**Overall Quality Score = (Profitability × 0.30) + (Business Quality × 0.30) + (Management × 0.25) + (Competitive Position × 0.15)**

### Interpretation:
- **8.5-10**: Exceptional Quality - Worth premium valuation
- **7-8.4**: High Quality - Preferred by Munger
- **5.5-6.9**: Average Quality - Requires fair price
- **4-5.4**: Below Average - Needs deep discount
- **Below 4**: Poor Quality - Avoid

---

## Investment Decision Framework

**Quality Score 8.5+ at fair/discount valuation** = STRONG BUY candidate for Munger-style investor

---

## Usage Notes
- Works on: All AI models
- Data needed: Last 5 years annual reports, quarterly results
- Time: 30-45 minutes per company
- Review annually for quality degradation
