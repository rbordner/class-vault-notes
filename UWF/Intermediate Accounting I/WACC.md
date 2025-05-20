---
tags:
  - "#WACC_Finance"
  - "#Finance"
---
## What is WACC?

**WACC** stands for **Weighted Average Cost of Capital**.

- Imagine Tesla Power Co. is a bakery and needs ingredients (money) to bake cakes (run projects).
- Some money comes from loans (debt), some from selling part of the bakery (equity), and some from special shares (preferred).
- Each “ingredient” costs a different price: interest on loans, expected returns to investors, etc.
- **WACC** is the average price the bakery pays for _all_ its ingredients, weighted by how much of each it uses.

> If your cake ingredients cost less than WACC, you lose money.  
> If you bake cakes that earn more than WACC, you make money.

---

## Step 1: Find our ingredients and how much we have

| Ingredient         | Details                                           | Market Value      |
|--------------------|----------------------------------------------------|-------------------|
| **Debt** (bonds)   | 15,000 bonds, \$1,000 par, selling at 105% of par   | \$15,750,000      |
| **Equity**         | 650,000 shares @ \$84 each                         | \$54,600,000      |
| **Preferred stock**| 30,000 shares @ \$103 each                         | \$3,090,000       |
| **Total (V)**      |                                                    | **\$73,440,000**  |

**Weights** (slice of each “ingredient”):  
- w<sub>D</sub> = 15.75 M ÷ 73.44 M ≈ **0.2146** (21.5%)  
- w<sub>E</sub> = 54.60 M ÷ 73.44 M ≈ **0.7435** (74.4%)  
- w<sub>P</sub> = 3.09 M ÷ 73.44 M ≈ **0.0421** (4.2%)  

> **Memory trick:** D–E–P for Debt, Equity, Preferred.

---

## Step 2: Find the cost (price) of each “ingredient”

1. **Debt (loans):**  
   - Bonds pay a 5.8% coupon, but trade at \$1,050, giving a yield ≈ 5.43% per year.  
   - After 21% tax: 5.43% × (1 – 0.21) = **4.29%**.

2. **Equity (common shares):**  
   - **CAPM** formula:  
     \[
       R_E = R_f + \beta\,(R_M - R_f)
           = 4.9\% + 0.88 \times 6\%
           = \mathbf{10.18\%}
     \]

3. **Preferred stock:**  
   - Pays \$5.25 annually (\$100 × 5.25%).  
   - Cost = 5.25 ÷ 103 = **5.10%**.

---

## Step 3: Mix (multiply) and add ’em up

**WACC formula**  

WACC = w_E·R_E + w_P·R_P + w_D·R_D·(1–T_C)


| Component               | Calculation         | Contribution |
|-------------------------|---------------------|-------------:|
| Equity slice            | 0.7435 × 10.18%     | 7.57%        |
| Preferred slice         | 0.0421 × 5.10%      | 0.21%        |
| Debt slice (after tax)  | 0.2146 × 4.29%      | 0.92%        |
| **Total WACC**          | _Sum of above_      | **8.70%**    |

So, Tesla Power Co.’s overall cost of capital ≈ **8.70%**.

---

## How to Remember

- **Recipe** = Weights (share of each) × Costs (price of each) → add up  
- **D–E–P** reminds you: Debt, Equity, Preferred.  
- **CAPM** = Risk-Free + Beta × Market Premium.  
- **Tax on debt** = Multiply by (1 – tax rate).  

Whenever you see a WACC problem, just:  
1. **Weigh** your ingredients (market values).  
2. **Price** each ingredient (costs).  
3. **Blend** (multiply + sum).  

Practice this “recipe” a few times, and you’ll master WACC! 🎂  
