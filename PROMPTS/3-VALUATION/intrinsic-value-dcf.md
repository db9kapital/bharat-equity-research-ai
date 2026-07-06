# Intrinsic Value Estimation (DCF) Prompt

**Charlie Munger's Approach**: "If you know a business intimately, you can estimate its intrinsic value within a range."

## Prompt for AI Models

---

I want to calculate the **intrinsic value** of **[COMPANY NAME]** (NSE/BSE: [TICKER]) using the Discounted Cash Flow (DCF) method.

Please help me build a DCF valuation model. Here's what I'll provide:

### **Data I'll Supply:**
- Last 3 years Free Cash Flow (FCF): INR [X] Cr, [Y] Cr, [Z] Cr
- Current Revenue: INR [A] Cr
- Expected growth rate for next 5 years: [B]%
- Terminal growth rate (beyond 5 years): [C]% (typically 2-3% for India)
- Weighted Average Cost of Capital (WACC): [D]% 
- Current shares outstanding: [E] Cr shares
- Net debt: INR [F] Cr (or cash)

### **DCF Model Steps:**

**Step 1: Project Free Cash Flows (Next 5 years)**
- Year 1-5 FCF projections based on growth rate
- Show declining growth if company matures
- Consider cyclicality if applicable

**Step 2: Calculate Terminal Value**
- Terminal Value = Final Year FCF × (1 + Terminal Growth Rate) / (WACC - Terminal Growth Rate)
- This captures value beyond 5-year projection

**Step 3: Discount to Present Value**
- Discount all projected FCFs and terminal value using WACC
- PV = FCF / (1 + WACC)^n

**Step 4: Calculate Enterprise Value**
- Sum of PV of all FCFs + PV of Terminal Value

**Step 5: Calculate Equity Value**
- Equity Value = Enterprise Value - Net Debt

**Step 6: Per-Share Intrinsic Value**
- Intrinsic Value per Share = Equity Value / Shares Outstanding

**Step 7: Create Valuation Range**
- **Bull Case** (optimistic): Higher growth, lower WACC
- **Base Case** (realistic): Mid-range assumptions
- **Bear Case** (conservative): Lower growth, higher WACC

---

## Sensitivity Analysis

Please create a sensitivity table showing how intrinsic value changes with:
- Growth rate variations (±2%)
- WACC variations (±1%)

Example format:
```
                WACC = 8%    WACC = 9%    WACC = 10%
Growth 12%      INR 2500     INR 2200     INR 1950
Growth 13%      INR 2700     INR 2400     INR 2100
Growth 14%      INR 2900     INR 2600     INR 2300
```

---

## Investment Decision Framework

**Compare Intrinsic Value with Current Market Price:**

- **Current Price < Bear Case Value** = STRONG BUY (50%+ margin of safety)
- **Current Price < Base Case Value** = BUY (Margin of safety exists)
- **Current Price ≈ Base Case Value** = FAIR VALUE (No margin of safety)
- **Current Price > Base Case Value** = AVOID (Overvalued)
- **Current Price > Bull Case Value** = DEFINITELY AVOID

---

## Munger's Margin of Safety Principle

"It's far better to buy a wonderful company at a fair price than a fair company at a wonderful price."

**Recommended Margin of Safety**: 30-50% discount to base case DCF value

---

## Important Assumptions to Document

- Why did you choose this growth rate?
- What WACC assumptions are you using and why?
- What could change your projections?
- What are the biggest risks to your valuation?

---

## Usage Notes
- Works on: ChatGPT, Claude, DeepSeek, Qwen
- Data needed: Last 3 years P&L, Cash flow statements
- Time: 30-40 minutes
- Update annually or after major company developments
