## 📈 Project: Marketing Analysis and Expense Optimization (Y.Afisha)

The user wants me to translate and reformat the key details of the "Y.Afisha" marketing analysis project, based on the provided Jupyter Notebook content, into the standard GitHub project summary template.

---

### **Objective**

Optimize the Y.Afisha ridesharing company's marketing expenditure by performing a deep analysis of **customer behavior**, **user journey**, and **Lifetime Value (LTV)**. The core goal was to determine the **Return on Investment (ROI)** and the **payback period** for various marketing channels to guide future investment strategy.

---

### **Results**

* **Investment Recommendations (ROI-Based):** The analysis strongly recommends focusing investments on **Source ID 1** (highest ROI, above 1.2, making it the most profitable channel) and **Source ID 9** (low CAC and positive ROI, making it highly efficient).
* **Channels to Avoid (Negative ROI):** Channels such as **Source 3 and 10** generated a negative ROI and should be avoided, even if their Customer Acquisition Cost (CAC) was moderate or low.
* **User Value (LTV/ROMI):** The majority of financial return (ROMI) is heavily **concentrated in the first month** after customer acquisition.
* **Repurchase Rate:** The **LTV does not grow significantly** over time, and most customers make **only one purchase**, indicating a low repurchase rate.
* **Device Preference:** **Desktop users generate more revenue** than mobile users, which is a critical factor for segmentation and targeting.
* **Marketing Spend Peaks:** Most marketing expenditure occurred between **October and December 2017**.

---

### **Tools**

* **Python**
* **Pandas** (Data manipulation, cleaning, aggregation, and Cohort analysis)
* **Matplotlib & Seaborn** (Data visualization, specifically used for **ROMI Heatmaps**)
* **NumPy** (Numerical operations)

---

### **Skills Learned**

* **Data Preprocessing and Cleaning:** Standardizing column names (snake\_case) and converting date columns to the appropriate datetime format across multiple datasets (visits, orders, costs).
* **Exploratory Data Analysis (EDA):** Calculating user metrics like **DAU, WAU, and MAU**, session duration, and the average time between consecutive visits.
* **Financial Metric Calculation (AARRR):** Computing and analyzing key marketing performance indicators, including **Customer Acquisition Cost (CAC)**, **Lifetime Value (LTV)**, **Return on Marketing Investment (ROMI)**, and **Payback Period**.
* **Cohort Analysis:** Structuring and analyzing customer cohorts based on their first purchase month to track accumulated revenue and LTV over time.
* **Strategic Recommendation:** Translating complex financial and behavioral metrics (ROI, CAC, LTV) into clear, actionable investment and retention strategies.

---

### **Improvements / Future Work**

* **Retention Strategy:** Implement **loyalty and retention initiatives** to address the low repurchase rate and increase LTV.
* **Device Segmentation:** Leverage the finding that desktop users generate higher revenue to influence **targeting and segmentation decisions**.
* **Optimization Focus:** Repurpose or eliminate channels (like Source 3 and 10) that yield a negative ROI and **increase investment in proven, profitable channels** (Source 1 and 9).
