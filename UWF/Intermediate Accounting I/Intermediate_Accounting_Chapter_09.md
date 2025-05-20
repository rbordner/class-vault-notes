# Chapter 9: Inventories – Additional Issues

---

## Overview

This chapter explores **advanced inventory valuation issues**, including accounting for **declines in value**, **inventory estimation methods**, **errors**, and **disclosures**.  
These considerations ensure proper application of the **conservatism principle** and compliance with **GAAP/IFRS**.

---

## 🔻 Lower of Cost or Net Realizable Value (LCNRV)

Used for companies applying **FIFO**, **average cost**, or **specific identification**.

### Formula:
$$
LCNRV = \min(\text{Cost}, \text{Net Realizable Value})
$$

### Where:
- Net Realizable Value (NRV) = Estimated selling price - costs to complete/sell

**Example:**
- Cost = $50  
- Selling price = $60  
- Selling cost = $15  
- NRV = $45 → Inventory is reported at **$45**

---

## 🛒 Lower of Cost or Market (LCM)

Used only under **LIFO** or **retail method** (GAAP only).

### Steps:
1. Determine **market** value:
   - Replacement cost
   - Ceiling = NRV
   - Floor = NRV - normal profit margin

2. Then:
$$
LCM = \min(\max(\text{NRV} - \text{Profit Margin}, \text{Replacement Cost}), \text{NRV})
$$

---

## 🧾 Journal Entry – Write-Down to NRV

If material, write-down is reported as a separate loss:

```
Dr. Loss on Inventory Write-down ......... XX  
   Cr. Inventory ..................................... XX
```

---

## 🔁 Reversals of Write-Downs (IFRS only)

- Allowed **only under IFRS**
- Limited to amount of original write-down

---

## 📉 Inventory Estimation Methods

Used when **physical count is impractical**, e.g., interim reporting, loss from disaster.

---

### 1. **Gross Profit Method**

Estimates ending inventory using historical gross profit margin.

#### Formula:
$$
\text{COGS} = \text{Sales} \times (1 - \text{Gross Profit %}) \\
\text{Ending Inventory} = \text{Goods Available for Sale} - \text{COGS}
$$

---

### 2. **Retail Inventory Method**

Used by retailers. Compares **cost** and **retail price** of goods available.

#### Steps:
1. Compute cost-to-retail ratio:
$$
CTR = \frac{\text{Cost of GAFS}}{\text{Retail of GAFS}}
$$

2. Estimate ending inventory at retail

3. Convert retail ending inventory to cost using CTR

---

## 🧮 Retail Method Variants

| Variant            | Includes Markups | Includes Markdowns | Conservative? |
|--------------------|------------------|---------------------|----------------|
| Average Cost       | Yes              | Yes                 | No             |
| Conventional (LCM)| Yes              | No                  | Yes            |
| FIFO               | Yes              | Yes                 | No             |
| LIFO Retail        | Special treatment per layer  | Yes | Varies          |

---

## 📊 Example – Retail Inventory (Conventional Method)

| Item                        | Cost  | Retail |
|----------------------------|-------|--------|
| Beginning Inventory        | 1000  | 1300   |
| Net Purchases              | 3000  | 4200   |
| Net Markups                |       | 200    |
| Net Markdowns              |       | 400    |
| Sales                      |       | 3700   |

**Step 1:**  
CTR = (1000 + 3000) / (1300 + 4200 + 200) = 4000 / 5700 = 70.18%

**Step 2:**  
Ending Inventory @ Retail = GAFS Retail – Sales – Markdowns = 5700 – 3700 – 400 = 1600

**Step 3:**  
Ending Inventory @ Cost = 1600 × 70.18% ≈ $1123

---

## 📉 Purchase Commitments

Non-cancellable agreements to buy inventory in the future at a fixed price.

- Record **loss** if market price drops below commitment price.

**Journal Entry:**
```
Dr. Unrealized Holding Loss ........... XX  
   Cr. Estimated Liability on Purchase Commitment ... XX
```

---

## 🛠️ Inventory Errors

### Ending Inventory Error → affects two periods

#### Overstatement:
- Current: COGS ↓, Net Income ↑
- Next: COGS ↑, Net Income ↓

### Correction:
- Prior-period adjustment (if discovered later)
- Restate comparative financials

---

## 📄 Disclosures

Required under GAAP:
- Inventory cost flow method (FIFO, LIFO, etc.)
- LIFO reserve (if applicable)
- Write-downs and reversals (IFRS)
- Significant estimates and judgments

---

## Summary

- Inventory must be stated at the **lower of cost or NRV** (LCNRV) or **LCM** under LIFO
- **Gross profit and retail methods** provide reliable estimates in interim or emergency cases
- **Errors in inventory** affect income and must be corrected via restatement
- GAAP and IFRS differ on **reversals** and **market definitions**

> **Tip for Mastery:** Practice applying LCM and LCNRV — many exam problems test the **ceiling/floor logic** and the **retail method variations**.