# Chapter 6: Time Value of Money (TVM)

---

## Overview

The **Time Value of Money (TVM)** is a fundamental financial concept stating that a dollar today is worth more than a dollar in the future due to its **earning potential**.  
Accounting applications include valuation of **bonds**, **leases**, **pensions**, **long-term notes**, and **installment sales**.

---

## Key Concepts

### 🔹 Present Value (PV)
The current worth of future cash flows discounted at an appropriate interest rate.

### 🔹 Future Value (FV)
The amount a sum will grow to over time with compound interest.

---

## Core TVM Formulas

### 1. **Future Value of a Single Sum**
$$
FV = PV \times (1 + i)^n
$$

### 2. **Present Value of a Single Sum**
$$
PV = \frac{FV}{(1 + i)^n}
$$

Where:
- \( i \) = interest rate per period  
- \( n \) = number of periods

---

## Annuities

An **annuity** is a series of equal payments at regular intervals.

### Types:
| Type           | Description                                     |
|----------------|-------------------------------------------------|
| Ordinary Annuity | Payments at end of each period                |
| Annuity Due      | Payments at beginning of each period          |
| Deferred Annuity | First payment delayed beyond 1 period         |

---

### 3. **Future Value of an Ordinary Annuity**
$$
FV_{oa} = PMT \times \left[ \frac{(1 + i)^n - 1}{i} \right]
$$

### 4. **Present Value of an Ordinary Annuity**
$$
PV_{oa} = PMT \times \left[ \frac{1 - (1 + i)^{-n}}{i} \right]
$$

### 5. **Future Value of an Annuity Due**
$$
FV_{ad} = FV_{oa} \times (1 + i)
$$

### 6. **Present Value of an Annuity Due**
$$
PV_{ad} = PV_{oa} \times (1 + i)
$$

---

## Compounding and Discounting

- **Annual**, **semiannual**, **quarterly**, **monthly**, or **daily** compounding changes both \( i \) and \( n \).

### Adjusted for compounding:
- \( i = \frac{\text{Annual Rate}}{\text{Periods per Year}} \)  
- \( n = \text{Years} \times \text{Periods per Year} \)

---

## Deferred Annuities

Annuities that **begin after a delay** (e.g., start in year 4).  
Calculate PV as of **first payment date**, then **discount back** to present.

---

## Applications in Accounting

### 1. **Notes Receivable/Payable**
Discount long-term notes using present value of future cash flows.

**Example:**
```
Loan: $10,000 to be repaid in 5 years at 5%
PV = $10,000 / (1.05)^5 ≈ $7,835
```

---

### 2. **Leases**
- Right-of-use asset and lease liability are measured at PV of lease payments.

---

### 3. **Pensions**
- PV of future retirement benefits based on actuarial assumptions.

---

### 4. **Bonds**
Use **present value of annuity + single sum** to price bonds.

**Example – Bond Valuation:**
```
Bond face: $100,000  
Coupon: 5% annual, paid semiannually  
Market rate: 6% annual (3% semiannual)  
Term: 10 years (20 periods)  
Coupon PMT: $2,500

Price = PV of 20 payments of $2,500 + PV of $100,000 lump sum
```

---

## Effective Interest Rate

Used to calculate **interest expense or revenue** using the **carrying value** of the financial instrument.

**Formula:**
$$
\text{Interest} = \text{Carrying Amount} \times \text{Effective Rate per Period}
$$

---

## Time Value of Money Tables

Most problems can use:
- PV/FV of $1
- PV/FV of annuity
- Present value table for annuity due (multiply ordinary annuity by \( (1 + i) \))

---

## Timeline Diagrams

| Single Sum | Ordinary Annuity | Annuity Due |
|------------|------------------|-------------|
| One cash flow at end | Even payments at end | Even payments at start |

---

## Journal Entry Example

**Issue a note payable with present value of $7,835 for a $10,000 payment in 5 years at 5%:**

```
Dr. Cash ............................... 7,835  
Dr. Discount on Notes Payable ......... 2,165  
   Cr. Notes Payable ......................... 10,000
```

---

## Summary

- Time value of money tools are foundational for accounting decisions involving future and past cash flows.
- Annuity types, interest compounding, and deferred payments must be understood and applied.
- The correct interest rate and time frame are essential for precision in accounting measurements.

> **Tip for Mastery:** On exams, draw timelines to visualize cash flows — especially for bonds, leases, and deferred annuities.