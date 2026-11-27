# FinTech-Credit-Risk-Dashboard-Excel
Interactive Credit Risk and Loan Default Analytics Dashboard built in Microsoft Excel analyzing 32,581 retail loans ($312.4M portfolio).

![Dashboard Preview](dashboard_preview.png.png)

## 🎯 Business Problem
Lenders and FinTech platforms face significant revenue loss from Non-Performing Assets (NPAs). This dashboard helps risk managers answer:
* What is the overall default rate across the loan portfolio?
* Which borrower demographics (age, home ownership) and credit grades carry the highest risk?
* Which loan purposes generate the highest default volume vs. highest average ticket size?

## 🔍 Key Insights
* **21.82% Overall Default Rate:** Out of 32,581 total applications, **7,108 loans defaulted** while **25,473 were repaid safely (78.18%)**.
* **Home Ownership Risk:** Borrowers living on **Rent** accounted for **5,192 defaults**—more than **3x higher** than mortgage holders (1,690).
* **Loan Purpose Trends:** **Medical** (1,621) and **Debt Consolidation** (1,490) carry the highest default counts, while **Home Improvement** leads in average loan size (~$10,360).
* **Age Demand:** The **23–26 age bracket** drives the highest volume of loan applications.

## 💡 Recommendations
1. **Tighten Underwriting for Renters:** Enforce stricter Debt-to-Income (DTI) checks for Grade D–G applicants living on rent.
2. **Risk-Based Pricing:** Apply calibrated interest rate buffers on Medical and Debt Consolidation segments to offset expected credit losses.
3. **Retention Offers:** Extend pre-approved top-up loans to Grade A & B borrowers with zero prior defaults.

## 🛠️ Excel Skills & Techniques Used
* Structured Data Modeling with **Excel Tables** (`Ctrl + T`)
* **7 Multi-Dimensional Pivot Tables** for dynamic aggregation
* **Live KPI Cards** linked via dynamic cell references
* **Combo Chart (Secondary Axis)** comparing Total Loan Volume vs. Average Ticket Size
* **Interactive Slicers** (`loan_grade` & `person_home_ownership`) connected via **Report Connections**
*
