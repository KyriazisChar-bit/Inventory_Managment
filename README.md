# 📦 Inventory Management & Operational Cost Optimization

A data-driven inventory control study for a manufacturing company operating under
deterministic and stochastic demand — forecasting, policy design, and supplier
cost analysis to minimize total operating costs while maintaining high service levels.

**Institution:** Aristotle University of Thessaloniki (AUTh)  
**School:** Polytechnic School — Department of Mechanical Engineering  
**Course:** Inventory Management  
**Instructor:** Tagaras George  
**Author:** Charitopoulos Kyriazis 
**Semester:** 7th Semester  

---

## ⚙️ Tech Stack

- **Microsoft Excel** — forecasting models, inventory optimization, cost analysis
- **Operations Research** — EOQ, (Q,R), (R,S) inventory policies
- **Statistical Forecasting** — Moving Average, Exponential Smoothing, MSE/MAD/MAPE
- **Service-Level Theory** — Cycle Service Level (P1), Fill Rate (P2)

---

## 🏗️ Methodology

**Demand Forecasting** — historical demand was analysed using Moving Average and
Exponential Smoothing. Forecast accuracy was evaluated with MSE, MAD, and MAPE.
Exponential Smoothing with α = 0.20 achieved the lowest errors across all metrics,
producing a forecast of **190 units/month**.

**Inventory Policy Design** — three systems were evaluated:
- Economic Order Quantity (EOQ) as the baseline
- Continuous Review System (Q, R) with safety stock calibration
- Periodic Review System (R, S) with a 4-week review period

**Service-Level Analysis** — two management proposals were compared:
- 95% Cycle Service Level (P1) → required safety stock: **93 units**
- 95% Fill Rate (P2) → required safety stock: **2 units**

P2 significantly outperformed P1, with estimated savings of **€1,036 over 18 months**.

**Supplier Discount Evaluation** — proposed quantity discount options were rejected
after analysis showed that the reduction in purchase price was outweighed by the
increase in annual inventory holding costs.

---

## 📁 Key Files

| File | Description |
|------|-------------|
| `ERGASIA_EN.xlsx` | Formula-driven Excel model: forecasting, EOQ, (Q,R), (R,S), cost analysis |
| `Inventory_Management.pdf` | Full engineering report with derivations and recommendations |

---

## 📊 Key Results

| Metric | Value |
|--------|-------|
| Best forecasting method | Exponential Smoothing, α = 0.20 |
| Demand forecast | 190 units / month |
| Recommended system | Periodic Review (R, S) |
| Review period | 4 weeks |
| Order-up-to level | 960 units |
| Achieved fill rate | 99.1% |
| Supplier discount secured | 3% |
| Annual procurement savings | ~€17,000 |

---

## 🔑 Key Takeaways

**Fill Rate beats Cycle Service Level** — under identical 95% service targets, P2
required only 2 units of safety stock versus 93 under P1, a dramatic reduction in
tied-up capital with better actual coverage.

**Quantity discounts are not always beneficial** — the supplier's discount offers
were financially unattractive once holding cost increases were factored in.

**Periodic review unlocked the discount tier** — consolidating orders into a
4-week cycle naturally pushed order quantities into the 3% discount bracket,
delivering ~€17,000 in annual savings without sacrificing service level.

---

## 👥 Author

| Field | Detail |
|-------|--------|
| Name | Charitopoulos Kyriazis |
| University | Aristotle University of Thessaloniki |
| Department | Mechanical Engineering |

---

*Academic coursework — Aristotle University of Thessaloniki. Not for resubmission
in other academic contexts.*
