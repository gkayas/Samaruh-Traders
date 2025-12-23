# Amazon FBA Jute Product Research

This repository contains **conservative, data-driven research outputs** for Amazon FBA products, with a focus on **jute / natural / sustainable products** manufactured in Bangladesh and sold on Amazon US.

The goal is to **evaluate demand, revenue potential, and unit economics** using **free, reproducible tools only**, avoiding inflated or speculative estimates.

---

## 📁 Repository Structure

```
.
├── reports/
│   ├── ASIN_<ASIN>_Conservative_Report.md
│   └── ...
├── data/
│   ├── ASIN_<ASIN>_Research_Data.csv
│   └── master_research.csv   (optional, user-maintained)
└── README.md
```

---

## 🔍 Methodology (Strict & Conservative)

### Data Sources (Free Only)
- Helium 10 Chrome Extension (Free tier)
- Jungle Scout Free Sales Estimator (BSR-based)
- Amazon public product pages (BSR, price)
- Keepa (free tier, qualitative trend checks)

No paid tools or private Amazon metrics are used.

---

## 📊 Sales Estimation Rules

1. Helium 10 Free estimates are the **primary anchor**
2. All estimates are cross-checked with at least one other free source
3. When estimates differ, the **lower (more conservative)** value is used
4. Results are expressed as **ranges**, not exact numbers
5. Confidence levels are explicitly stated

Expected uncertainty: ±20–30%

---

## 💰 Unit Economics Model

Each product includes:
- Amazon referral fee (~15%)
- FBA fulfillment fee
- PPC & promotions buffer
- Returns buffer
- International + domestic logistics
- Target net margin (25–30%)

Key outputs:
- Ideal manufacturer cost (FOB Bangladesh)
- Maximum safe manufacturer cost
- Estimated net profit per unit

---

## 🧾 CSV Schema (Standardized)

Each CSV includes:
- ASIN
- Product name
- Marketplace
- Estimated monthly units (low / high / anchor)
- Average selling price
- Monthly gross revenue
- Monthly net revenue
- Amazon fees per unit
- PPC & returns buffer
- Logistics cost per unit
- Ideal manufacturer cost
- Maximum manufacturer cost
- Profit per unit
- Confidence level
- Sources

---

## ⚠️ Disclaimer

All figures are **estimates**, not guarantees.  
They are intended for **early-stage validation and comparison only**.

Final decisions should be validated with:
- Supplier quotes
- Freight forwarders
- Amazon FBA fee calculator
- Test orders

---

## ✨ Philosophy

**Boring, conservative numbers beat exciting, wrong numbers.**
