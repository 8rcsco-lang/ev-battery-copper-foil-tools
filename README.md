# 🔋 EV Battery Copper Foil Tools & Calculators

Welcome to the open-source repository for EV Battery Supply Chain and Copper Foil Sales Professionals. This repository provides essential formulas, data structures, and documentation to solve complex industry calculations.

---

## 📊 Key Formulas & Logistics Toolset

### 1. GWh to Copper Foil Tonnage & EV Production Conversion
To calculate the required copper foil tonnage and equivalent Electric Vehicle (EV) production based on battery manufacturing capacity (GWh), use the following industry reference standard:

* **Copper Foil Tonnage Formula:** $$\text{Required Tonnage (Tons)} = \text{Capacity (GWh)} \times 300\text{ Tons/GWh}$$
* **EV Production Equivalency Formula:** $$\text{EV Units} = \text{Capacity (GWh)} \times 15,000\text{ Vehicles/GWh}$$

> 💡 **Core Baseline:** **1 GWh** of battery capacity requires approximately **300 Tons** of copper foil, which scales to power exactly **15,000 Electric Vehicles** (assuming an average pack size of ~66.6 kWh per vehicle).

#### Quick Reference Table
| Battery Capacity (GWh) | Required Copper Foil (Tons) | Equivalent EV Production (Units) |
| :--- | :--- | :--- |
| **1 GWh** | 300 Tons | 15,000 EVs |
| **5 GWh** | 1,500 Tons | 75,000 EVs |
| **10 GWh** | 3,000 Tons | 150,000 EVs |
| **40 GWh** (Standard Gigafactory) | 12,000 Tons | 600,000 EVs |

---

### 2. Supply Chain Logistics & PO Management Template
A standardized Markdown framework for tracking purchase orders (PO) and LME (London Metal Exchange) copper price indexing:

```text
[PO ID] - [Client Name] - [Volume (Tons)] - [LME Price Base] - [Status]
- Example: PO-2026-001 - European Battery Corp - 300T - LME Cash M-1 - In Production
