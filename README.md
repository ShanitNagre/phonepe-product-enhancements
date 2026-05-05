# 📱 PhonePe Product Analysis — Spend Intelligence Feature

> A full product analysis of PhonePe including teardown, competitive landscape, PRD for a new AI feature, and an interactive prototype. Built as a PM portfolio exercise.

**Author:** Shanit Nagre — AI Product Manager  
**Portfolio:** [shanitnagre.github.io](https://shanitnagre.github.io)

---

## What's Inside

| File | Type | Description |
|------|------|-------------|
| `01-product-teardown.md` | Research | Full teardown — strengths, gaps, opportunities |
| `02-PRD-spend-intelligence.md` | PRD | Complete PRD for AI spending intelligence layer |
| `03-competitive-analysis.md` | Analysis | PhonePe vs GPay, Paytm, CRED, Fi, Jupiter |
| `04-spend-intelligence-prototype.html` | Prototype | Fully interactive mobile UI prototype |

---

## The Core Insight

PhonePe has 500M users' complete transaction histories and processes 48% of all UPI transactions in India. It uses this data almost exclusively for fraud detection.

CRED and Fi — with 1–5% of PhonePe's user base — are winning the premium segment by turning transaction data into personalized financial intelligence.

**The opportunity:** Build a Spend Intelligence layer that converts PhonePe's data advantage into a revenue advantage through better financial product conversion.

---

## The Feature: Spend Intelligence

Five components:
1. **Spend Pulse** — weekly digest of spending vs personal baseline
2. **Payday Intelligence** — salary-credit moment with forward-looking breakdown
3. **Anomaly Alerts** — real-time flags when spending deviates significantly
4. **Financial Moment Detection** — life event signals mapped to relevant products
5. **Pre-Month Planning** — predicted fixed expenses before the month starts

**Target metric:** Financial product conversion rate 2% → 8% for nudge-engaged users.

---

## Interactive Prototype

Open `04-spend-intelligence-prototype.html` in any browser.

Features working in the prototype:
- 3 screens: Home, Insights, Upcoming Bills
- Payday card with salary breakdown
- AI insight nudge with anomaly alert
- Spend Pulse with category breakdown and trend chart
- Upcoming bills predictor
- SIP start modal with amount selection
- Toast notifications on interactions

---

## PM Approach

This analysis follows the framework I use for all product work:

**Teardown first.** Understand what exists before proposing what should. Too many PM case studies jump to solutions without earning the right to propose them.

**Find the data advantage.** PhonePe's moat isn't UPI — that's commoditized. The moat is behavioral data at scale. The feature should exploit that, not ignore it.

**Metric clarity before features.** The PRD starts with the North Star metric (financial product conversion) and works backwards to features. Features without metrics are art projects.

**Prototype to think, not just to present.** The prototype forced decisions I wouldn't have made in a doc — what does the payday moment actually look like? How do you surface anomaly alerts without feeling surveillance-y? Building the UI answers questions writing can't.

---

*Part of Shanit Nagre's AI PM portfolio — [shanitnagre.github.io](https://shanitnagre.github.io)*
