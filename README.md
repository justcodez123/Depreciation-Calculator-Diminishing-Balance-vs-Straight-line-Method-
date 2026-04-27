# 📊 Depreciation Calculator: Straight-Line vs. Diminishing Balance

##  Project Overview
This project is a comprehensive financial modeling tool developed to compare two fundamental methods of asset depreciation: **Straight-Line (SL)** and **Diminishing Balance (DB)**. It provides a dynamic Excel-based engine to help businesses and individuals understand how different accounting methods impact asset valuation and expense distribution over time.

---

##  Key Objectives
* **Automated Modeling:** Create a dynamic system where updating a single input (e.g., Asset Cost) refreshes the entire 10-year depreciation schedule.
* **Methodological Comparison:** Directly contrast the linear decay of the Straight-Line method with the accelerated decay of the Diminishing Balance method.
* **Financial Visualization:** Use dashboards and charts to visualize Book Value trends and annual depreciation expenses.
* **Actionable Insights:** Provide recommendations on which method suits specific asset types (e.g., technology vs. furniture).

---

##  Methodologies & Formulas

### 1. Straight-Line Method (SL)
Best for assets that provide consistent utility over their entire lifespan.
* **Formula:** `Depreciation per Year = (Asset Price - Scrap Value) / Estimated Life Span`
* **Result:** A constant annual expense, resulting in a linear decrease in book value.

### 2. Diminishing Balance Method (DB)
Ideal for assets that lose value rapidly in their early years (e.g., vehicles, computers).
* **Formula:** `Depreciation per Year = Book Value at Beginning of Year × Depreciation Rate`
* **Result:** Higher expenses in the initial years, reflecting the accelerated usage or obsolescence of the asset.

---

##  Tools & Technologies
* **Microsoft Excel:** Core financial engine using recursive formulas, absolute referencing, and data validation.
* **Data Visualization:** Comparative line and column charts for financial analysis.
* **Documentation:** Technical reports and executive presentations (PDF/PPTX).

---

##  Project Structure
* `Project-1(Depreciation-Calculator-Excel).xlsx`: The primary automated financial model.
* `Stimulation Model/`: Contains additional data sets and comparative analysis files.
* `Project-1(Documentation).pdf`: Detailed breakdown of terminologies and problem statements.
* `Depreciation-Calculator.pptx`: Executive summary and visual presentation of findings.

---

##  Key Findings & Recommendations
| Feature | Straight-Line Method | Diminishing Balance Method |
| :--- | :--- | :--- |
| **Expense Pattern** | Constant/Uniform | Front-loaded (Higher in early years) |
| **Best For** | Stable assets (Furniture, Buildings) | Tech assets (Machinery, Computers) |
| **Complexity** | Simple | More complex (Recursive) |

**Recommendation:** Use **Straight-Line** for assets with steady utility and **Diminishing Balance** for high-tech infrastructure to better align expenses with the asset's actual economic contribution.
