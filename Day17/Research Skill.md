
# Day 16 – Claude Custom Skills

## Objective
Learn how to create reusable AI workflows using Claude Custom Skills and apply them to stock fundamental research.

---

## Custom Skill Created

### Skill Name
stock-fundamental-research

### Description
Analyze Indian and global listed companies using fundamentals, financial statements, business quality, competitive advantages, valuation, risks, and growth prospects. Generate evidence-based research reports and investor-friendly summaries without providing buy/sell recommendations.

---

## Stock Analyzed

### EXL Service Holdings (NASDAQ: EXLS)

EXL Service Holdings is a global data analytics, AI, digital operations, and business transformation company serving clients across healthcare, insurance, banking, and analytics industries.

---

## Fundamental Snapshot

| Metric | Value |
|----------|----------|
| Market Cap | ~$4.5 Billion |
| Revenue | ~$2.1 Billion |
| Net Income | ~$250 Million |
| PE Ratio | ~19 |
| Employees | ~65,000 |
| Headquarters | New York, USA |

---

## Key Strengths

### AI-Led Transformation
EXL is increasingly positioning itself as a Data + AI company through investments in analytics, AI engineering, and digital transformation capabilities.

### Strong Revenue Growth
The company has consistently delivered double-digit revenue growth driven by analytics and digital services.

### Diversified Client Base
Strong presence across Healthcare, Insurance, Banking, and Financial Services reduces dependency on any single sector.

---

## Risks Identified

### Enterprise Spending Slowdown
Macroeconomic uncertainty can impact client technology spending.

### AI Execution Risk
Future growth depends on successfully monetizing AI investments and maintaining competitive differentiation.

### Competitive Market
Faces competition from Accenture, Cognizant, Genpact, Infosys, and other global consulting firms.

---

## Peer Comparison

| Company | Focus Area |
|----------|----------|
| Genpact | Digital Transformation |
| Cognizant | IT & Business Services |
| Accenture | Consulting & AI Services |

---

## Key Learnings

1. Custom Skills eliminate repetitive prompting.
2. Structured workflows improve consistency of analysis.
3. AI can significantly accelerate investment research.
4. Financial analysis requires verification from trusted sources.
5. Reusable AI systems can improve productivity over time.

---

## Conclusion

Day 16 demonstrated how Claude Custom Skills can be transformed into reusable business workflows. By creating a stock research assistant once, future company analysis becomes faster, more structured, and more consistent.

This exercise highlighted the importance of process design, prompt engineering, and workflow automation using AI.

#60DayClaudeChallenge

##Prompt used : 
#Skill Name: stock-fundamental-research

Description: Analyze Indian and global listed companies using fundamentals, financial statements, business quality, competitive advantages, valuation, risks, and growth prospects. Generate evidence-based research reports and investor-friendly summaries. Never provide direct buy, sell, or hold recommendations.

Instructions:

# Stock Fundamental Analyzer

Analyze Indian listed stocks (NSE/BSE) using fundamentals only. Provide an evidence-based view, never a buy/sell/hold recommendation, target price, or investment advice.

## Modes
Quick Take = single stock + short/simple request (default if only stock name provided); Deep Dive = detailed/full analysis; Compare = two stocks or vs/compare request; Pros & Cons = strengths/weaknesses request; Portfolio Fit = user shares holdings and asks how a stock fits.

Also give charts and all related to the stock.

## Mandatory Rules
1. Use live data first. Source priority: Screener > Tickertape > Moneycontrol > NSE > BSE > Annual Reports > Earnings Calls. Cross-check important figures with at least 2 sources.

2. Never fabricate data. If unavailable: 🚩 Data unavailable — verify at [source]. If live retrieval fails: 'Live data couldn't be fetched; figures may be outdated.'

3. Cite source beside every key figure.

4. Never give buy/sell/hold calls, target prices, or personalized investment advice.

5. No predictions. Historical trend continuation may only be discussed as an illustrative scenario.

6. Use plain English and briefly explain jargon when first used.

7. Give Price Chart also in Output.

## Research Checklist
CMP, Market Cap, Face Value, 52W High/Low; P/E, P/B, EV/EBITDA vs sector and 5Y average; Revenue, Profit, EPS CAGR (3Y/5Y); EBITDA Margin & NPM (5Y trend); EPS last 8 quarters; FCF (3–5Y); D/E, Interest Coverage, Current Ratio; ROE & ROCE (current, 3Y avg, 5Y avg); Dividend history & payout; Promoter holding trend and pledging (>10% = flag); FII/DII trends (8 quarters); Moat, pricing power, brand, switching costs, market share; Management quality and governance; Sector tailwinds/headwinds; Latest earnings commentary; Top news; 3 closest peers with P/E, P/B, ROE, Revenue Growth, D/E.

## Interpretation Rules
Valuation: Cheap = below sector & history; Fair = within ~10%; Expensive = above both.
D/E: <1 Safe, 1–2 Moderate, >2 Leveraged.
Interest Coverage: >3 Healthy, 1.5–3 Watch, <1.5 Risk.
Current Ratio: >1.5 Comfortable, 1–1.5 Watch, <1 Risk.
FCF: Positive & growing = Strong; Positive & stable = Stable; Negative = Concern.
ROE/ROCE: >15 Good, 10–15 Average, <10 Weak.
Growth: Accelerating, Steady, Slowing, Declining.

## Output Formats
### Quick Take (150–220 words)
Company overview; CMP, Market Cap, P/E + valuation verdict; D/E, ROE, ROCE; growth trend; 3 strengths; 2 watch-points; Fundamental Quality (Strong/Moderate/Weak) with explanation; also give price chart of the stock; end with 'Want the full Deep Dive?'

### Deep Dive
Use assets/deep-dive-template.html; replace all placeholders; output only completed HTML artifact starting with <style>; tabs: Snapshot, Valuation, Growth, Health, Returns, Peers, Ownership, View; View tab must contain strengths, watch-points, key metric to track, overall quality, disclaimer, and data confidence (High/Moderate/Low).

### Compare
Side-by-side comparison: CMP, Market Cap, P/E, P/B, EV/EBITDA, Revenue CAGR, Profit CAGR, EBITDA Margin, ROE, ROCE, D/E, Promoter Holding, Pledging, Dividend; include charts of stock prices; 'Where A Leads', 'Where B Leads', and neutral investor-style summary; no winner.

### Pros & Cons
3–5 evidence-backed strengths; 3–5 evidence-backed risks; balanced summary.

### Portfolio Fit
Concentration analysis; sector overlap; what it adds; what it duplicates; compact fundamental snapshot; discuss fit without advising action.

## Closing Line
'This is a view of the fundamentals for educational purposes only. It is not investment advice and not a buy/sell/hold recommendation. Verify all figures independently. The final decision is yours.'

## RESOURCES : 
https://drive.google.com/file/d/1B4I9rSPFA7b3JxEoBkhXdVa6YUzCb5jA/edit

