# Operational Demand & Resource Planning Analysis

**Tool:** Python (Pandas, NumPy, Matplotlib) | **Domain:** Business Operations & Resource Planning  
**Context:** The Timeless Pictures — Jamshedpur, India (2025)

---

## Business Problem

As the founder of The Timeless Pictures, I needed to make data-driven decisions about:
- **When** demand peaks so team members can be pre-booked in advance
- **Which project types** drive the most revenue and profit
- **How to allocate** a 3-person team across 14 projects efficiently
- **Where the operational gaps** are in the booking calendar

This analysis uses real invoice data from 14 client projects (Jan–Dec 2025) to surface actionable insights.

---

## What the Analysis Does

### 1. Business Overview
Summarizes total revenue, profit, cost, average margins, and highest/lowest value projects from raw invoice data.

### 2. Monthly Demand Analysis
Breaks down bookings and revenue month-by-month to identify peak seasons and zero-booking gaps — critical for advance resource planning.

### 3. Project Type Analysis
Ranks project types by total revenue, average value, and revenue share — informing pricing strategy and sales focus.

### 4. Team Resource Allocation
Analyzes each team member's project load, revenue contribution, profit, and margin — identifying workload imbalances and top performers.

### 5. Key Insights & Recommendations
Five data-driven operational recommendations with specific numbers and actions.

### 6. Charts (4-panel visualization)
- Monthly revenue bar chart (highlights peak and zero months)
- Revenue by project type (horizontal bar)
- Team performance — revenue vs profit (grouped bar)
- Profit margin % by project (with average line)

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total Projects | 14 |
| Total Revenue Billed | ₹7,53,000 |
| Total Profit | ₹98,720 |
| Avg Profit Margin | 12.1% |
| Peak Revenue Month | October |
| Zero Booking Months | Jun & Jul |
| Top Project Type | Cinematic Wedding (76% of revenue) |
| Highest Value Project | Nishant Singh — ₹1,45,000 |

---

## Operational Recommendations

1. **Fill Jun–Jul gap** — Launch advance booking discounts in Apr–May to convert the zero-booking months into at least 1–2 bookings each.
2. **Focus on Cinematic Weddings** — At 76% revenue share and 13–15% margins, this is the highest-ROI service to prioritize.
3. **Pre-book a 4th freelancer for Oct–Dec** — Peak season load warrants capacity buffer to avoid delivery risk.
4. **Upsell Post-Wedding packages** — As done for Vicky Nayak (₹25,000 add-on), 3 upsells/year = ₹60,000+ additional revenue.
5. **Rebalance team load** — Sanjeet manages 51% of revenue with only 4 projects; consider moving one high-value project to Alex Soy.

---

## Technical Skills Demonstrated

- **Pandas** — data loading, groupby aggregations, merge operations
- **NumPy** — margin calculations and numerical operations
- **Matplotlib** — 4-panel subplot visualization with custom styling
- **Data storytelling** — translating raw numbers into business recommendations
- **Operational analytics** — seasonality detection, resource utilization, revenue mix analysis

---

## How to Run

```bash
# Clone the repo
git clone https://github.com/anjanbawa/operational-demand-analysis.git
cd operational-demand-analysis

# Install dependencies
pip install pandas numpy matplotlib

# Run the analysis
python demand_analysis.py
```

Output: Console report + `demand_analysis_charts.png`

---

## Files

```
├── demand_analysis.py          # Main analysis script
├── demand_analysis_charts.png  # 4-panel chart output
└── README.md                   # This file
```

---

*Built as part of an operations analytics portfolio to demonstrate real-world data analysis, resource planning, and Python-based business intelligence skills.*
