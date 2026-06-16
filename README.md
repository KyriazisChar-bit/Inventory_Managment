
# Inventory Management & Operational Cost Optimization

## Overview

This project investigates inventory control strategies for a manufacturing company operating under both deterministic and stochastic demand conditions. The objective was to minimize total operating costs while maintaining high service levels through forecasting, inventory policy design, and supplier cost analysis.

The study evaluates multiple inventory management approaches and develops data-driven recommendations that balance inventory holding costs, stockout risks, and procurement savings.

---

## Problem Statement

The company faced several operational challenges:

* Determining the most accurate demand forecasting method.
* Evaluating whether supplier quantity discounts were financially beneficial.
* Comparing alternative service-level policies proposed by management.
* Selecting the most cost-effective inventory review system.
* Optimizing inventory decisions under uncertain demand.

---

## Methodology

### Demand Forecasting

* Historical demand analysis
* Moving Average forecasting
* Exponential Smoothing
* Forecast accuracy evaluation using:

  * Mean Squared Error (MSE)
  * Mean Absolute Deviation (MAD)
  * Mean Absolute Percentage Error (MAPE)

### Inventory Management

* Economic Order Quantity (EOQ)
* Continuous Review System (Q, R)
* Periodic Review System (R, S)
* Safety Stock calculations

### Service-Level Analysis

* Cycle Service Level (P1)
* Fill Rate (P2)

### Cost Analysis

* Inventory holding costs
* Ordering costs
* Stockout costs
* Quantity discount evaluation

---

## Key Results

### Forecasting Performance

Exponential Smoothing with **α = 0.20** achieved the lowest forecasting errors across all evaluation metrics, producing a demand forecast of **190 units per month**.

### Supplier Discount Evaluation

The proposed quantity discount options were rejected after analysis showed that the reduction in purchase price was outweighed by the increase in annual inventory holding costs.

### Service-Level Policy Comparison

A **95% Fill Rate (P2)** policy significantly outperformed a **95% Cycle Service Level (P1)** policy.

Key findings:

* Required safety stock under P1: **93 units**
* Required safety stock under P2: **2 units**
* Estimated savings: **€1,036 over 18 months**

### Recommended Inventory Policy

The optimal solution was a **Periodic Review System** with:

* Review period: **4 weeks**
* Order-up-to level: **960 units**

This policy achieved:

* **99.1% Fill Rate**
* **3% supplier purchase discount**
* Approximately **€17,000 annual procurement savings**

---

## Repository Contents

### `Inventory_management.pdf`

Comprehensive engineering report containing:

* Problem formulation
* Mathematical derivations
* Forecasting analysis
* Inventory policy design
* Cost comparisons
* Final recommendations

[View Final Engineering Report (PDF)](./Inventory_managment.pdf)

### `ERGASIA_EN.xlsx`

Interactive spreadsheet model containing:

* Automated calculations
* Forecasting models
* Inventory optimization logic
* Cost analysis framework
* Scenario evaluation tools

[Download Formula-Driven Excel Model (.xlsx)](./ERGASIA_EN.xlsx)

---

## Skills Demonstrated

* Inventory Management
* Operations Research
* Supply Chain Analytics
* Demand Forecasting
* Service-Level Analysis
* Cost Optimization
* Quantitative Decision Making
* Microsoft Excel Modeling

---

## Key Takeaway

The analysis demonstrates how data-driven inventory management can significantly reduce operating costs while maintaining high customer service levels. By combining forecasting techniques, inventory optimization models, and supplier cost analysis, the project identifies practical strategies that improve both operational efficiency and financial performance.
