### 🧮 EMI Calculator & Amortization Schedule (`EMI Calculator.xlsx`)

An interactive loan installment calculator and multi-frequency amortization workbook built with **7 core Excel functions**, dynamic date logic, and a loan-tenure comparison matrix.

#### ✨ Key Features & Workbook Structure
* **`EMI Calculator` Tab:**
  * Calculates periodic installments dynamically using **`PMT`** based on **Downpayment**, **Loan Amount**, **Annual Interest Rate**, **Tenure (Years)**, and **EMI Frequency** (`Monthly` = 12 installments/year via **`VLOOKUP`**).
  * Computes **Total Repayment** and **Total Interest** automatically as inputs change.
  * Includes an **EMI Chart / Sensitivity Table** comparing installment amounts across loan sizes (`3,00,000` to `70,00,000`) and tenures (`1` to `12` periods).
* **`Payment Schedule` Tab:**
  * Generates installment dates dynamically using **`EDATE`** (for monthly/multi-month intervals) or day-interval stepping with **`ROUND`** and **`IF`** (for shorter payment frequencies), leaving rows blank past the final installment.
  * Breaks down each installment into **Amount**, **Principal** (**`PPMT`**), and **Interest** (**`IPMT`**), with summary totals for **Total Repayment** and **Total Interest** (with a schedule-length check up to 808 rows).
* **`Functions Used` Tab:**
  * Documents all 7 functions (`VLOOKUP`, `PMT`, `IPMT`, `PPMT`, `IF`, `ROUND`, `EDATE`) along with absolute cell locking (`$`) and frequency dropdown/comparison design.
* **`Raw Information` Tab:**
  * Stores the frequency-to-installments lookup table (`Monthly` = 12, `Every 15 days` = 24, `Fortnightly` = 26, `BI-Monthly` = 6, `Half-Yearly` = 2, `Annually` = 1, `Weekly` = 52, `Quarterly` = 4).

#### 📌 Sample Output (Default Inputs)
* **Inputs:** `0` Downpayment | `5,00,000` Loan Amount | `10%` Annual Interest | `2` Years | `Monthly` (24 installments)
* **Installment Amount:** **`23,072.46`**
* **Total Interest:** **`53,739.12`**
* **Total Repayment:** **`5,53,739.12`**
