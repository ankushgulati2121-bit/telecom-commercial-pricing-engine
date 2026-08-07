# Enterprise Telecom Commercial Pricing & SOW Risk Engine

An institutional-grade B2B Deal Pricing, Margin Optimization, and Commercial Risk Model engineered for telecommunications commercial analyst functions.

## Executive Summary
This engine automates the financial evaluation of multi-tier enterprise telecommunications proposals (300+ mobile connections and regional fixed fiber broadband links) against standard benchmark rate cards.

### Key Financial & Governance Outputs (Base Case)
* **Total Contract Value (TCV):** $420,600.00 NZD (24-Month Term)
* **Rate Card Variance:** -14.51% ($2,975.00/mo discount vs. list price)
* **Gross Profit Margin:** 71.30% (Surpasses minimum 45.0% target)
* **Net Profit Margin (Post-HW Fund):** 65.35% ($274,880.00 net profit)
* **Hardware Fund Payback:** Month 3 breakeven on $25,000 device credit
* **SOW Risk Score:** 20 / 100 (Low Risk Tier - Approved)

---

## Model Visualizations

### 1. B2B Deal Margin Waterfall
![Deal Waterfall](waterfall.png)

### 2. Hardware Credit Recovery Trajectory
![Payback Curve](payback.png)

---

## Technical & Financial Features
* **Dynamic Rate Card Matrix:** Compares custom sales discounts against baseline list rates and direct network COGS.
* **Hardware Credit Amortization:** Tracks monthly cash-flow recovery for client equipment allowances.
* **Scenario Stress-Testing:** Simulates profit resilience against international roaming cost surges (+30%) and aggressive discounting (25%).
* **Automated SOW Risk Assessment:** Programmatically audits SLA penalty caps, CPI indexation, and early exit clawbacks.
* **C-Suite Model Export:** Automatically generates formatted, multi-tab Excel workbooks (`openpyxl`) and interactive Plotly visual decks.

---

## Repository Files
* `telecom-commercial-pricing-engine.ipynb` — Executable Python Notebook
* `Telecom_Enterprise_Deal_Model.xlsx` — Auto-generated Excel Model
