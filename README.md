
# 📊 Public Distribution System (PDS) Efficiency Analysis – India 🇮🇳

## 🔍 Project Overview

This project presents a **comprehensive data science case study** analyzing the **allocation and distribution efficiency** of wheat and rice under India's **Public Distribution System (PDS)**. The goal is to identify operational inefficiencies, regional disparities, and predictive trends using statistical analysis, machine learning, and interactive dashboards.

---

## 🧠 Key Insights

- 📈 **Rice distribution** has strong alignment with allocations (R² = 0.85), while wheat shows inefficiencies (R² = 0.46).
- 🧪 **Statistical tests (t-test & ANOVA)** reveal significant differences in efficiency across states and commodities.
- 🔍 **Clustering (K-Means)** highlights underperforming districts and flags an outlier with extreme rice efficiency.
- 📆 **Monthly efficiency trends** indicate seasonal operational stress (e.g., during COVID lockdowns).
- 📊 **Power BI dashboard** allows real-time filtering by state, district, and time for actionable insights.

---

## 🛠️ Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Power BI
- Excel
- GitHub

---

## 🖼️ Power BI Dashboard Views

### 🔹 Overview View
> Summary of allocation vs distribution, key KPIs, state-wise totals, and overall trends.

![Overview View](images/overview_view.png)

---

### 🔹 Location View
> State- and district-wise allocation vs distribution comparison with a monthly slicer.

![Location View](images/location_view.png)

---

### 🔹 Time View
> Quarterly efficiency of rice and wheat with filters by state and district.

![Time View](images/time_view.png)

> 📌 *Upload your screenshots to the `images/` folder and ensure the paths match above.*

---

## 📁 Repository Structure

```

📂 PDS-Efficiency-Analysis
├── 📊 PDS\_India.ipynb                  # Main Jupyter Notebook (Data Cleaning, EDA, Modeling)
├── 📈 PDS\_data\_with\_efficiency.xlsx     # Cleaned dataset with efficiency metrics
├── 🧾 PDS District Wise Monthly Wheat and Rice\_Sample\_Data.csv  # Raw sample dataset
├── 📘 Public Distribution System India\_Analysis.pdf   # Full Business Analytics Report (PDF)
├── 📊 BI Project.pdf                   # Power BI dashboard screenshots
├── 📂 images/
│   ├── overview\_view\.png              # Screenshot of Overview View
│   ├── location\_view\.png              # Screenshot of Location View
│   └── time\_view\.png                  # Screenshot of Time View
├── 📄 README.md                        # Project documentation (this file)

````

---

## 🧪 How to Use

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/PDS-Efficiency-Analysis.git
   cd PDS-Efficiency-Analysis
````

2. **Open the Jupyter Notebook**:
   Use any Python IDE (like JupyterLab or VSCode) to explore the analysis step-by-step.

3. **Explore the Power BI Dashboard**:
   Refer to the `BI Project.pdf` file or the image previews above.

4. **Read the PDF Report**:
   Go through `Public Distribution System India_Analysis.pdf` for the complete business analytics documentation.

---
