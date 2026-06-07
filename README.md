# 📊 Customer Behavior Analytics — Power BI Dashboard

> **Business Question:** How can a company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

---

## 🗂️ Project Overview

This project presents an end-to-end data analysis pipeline built on a retail consumer dataset of **3,900 customers**. It covers data cleaning in Python, data modeling in Power BI, and interactive dashboard design across three analytical dimensions: revenue performance, customer segmentation, and product feedback.

| Metric | Value |
|---|---|
| Total Customers | 3,900 |
| Total Revenue | $233,081 |
| Subscription Rate | 27% |
| Avg. Purchase Amount | $59.76 |
| Avg. Review Rating | 3.75 / 5 |

---

## 📁 Repository Structure

```
Customer-Behavior-Analytics-PowerBI/
│
├── README.md                        # Project overview and documentation
├── LICENSE                          # MIT License
├── .gitignore                       # Files excluded from version control
│
├── reports/
│   └── Dashboard_Report.pdf         # Exported Power BI dashboard (all pages)
│
├── notebooks/
│   └── DataCleaning.ipynb           # Python data cleaning pipeline (pandas/numpy)
│
└── docs/
    └── insights_summary.md          # Detailed written analysis and recommendations
```

---

## 📈 Dashboard Pages

### Page 1 — Executive Summary
High-level KPIs and revenue breakdowns to give stakeholders a quick business pulse.

- **Revenue by Category:** Clothing leads at $104K (45% of total revenue)
- **Revenue by Age Group:** Young Adults are the highest-spending segment ($62K)
- **Top Locations:** Montana, Illinois, and California lead by revenue
- **Gender Split:** Male customers average $60.25 vs. Female at $59.54

### Page 2 — Customer Segmentation & Engagement Analysis
Deep dive into gender-based differences in discount usage and subscription participation.

- **Male Discount Rate:** 43% — **Female Discount Rate:** 0%
- **Subscription:** 39.71% of male customers subscribed vs. 0% of female customers
- Revenue is consistently higher for male customers across all product categories
- Significant gender gap in promotional and loyalty program engagement

### Page 3 — Product Performance & Customer Feedback Analysis
Review sentiment and category-level product performance to guide quality improvement.

- **Good + Excellent Reviews:** 37.26% of all reviews
- **Poor Reviews:** Only 1.69% — low negative sentiment overall
- **Footwear** receives the highest proportion of Excellent reviews
- **40.1% of reviews are Fair** — the largest single sentiment bucket, signaling room for improvement
- **Clothing** has the highest Fair review concentration despite being the top revenue category

---

## 💡 Key Recommendations

| # | Recommendation |
|---|---|
| 1 | **Expand promotional reach** — Investigate why female customers have 0% discount engagement and close the loyalty gap |
| 2 | **Replicate Footwear success** — Study what drives Footwear's high Excellent review rate and apply those practices elsewhere |
| 3 | **Improve Clothing quality** — Highest revenue category but highest Fair review concentration; prioritize quality feedback loops |
| 4 | **Grow subscription program** — At 27%, there is significant room to grow loyalty membership, especially among female customers |
| 5 | **Leverage review insights** — Use the high Fair review volume as a structured source for product improvement sprints |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python (pandas, numpy)** | Data cleaning and preprocessing |
| **Jupyter Notebook** | Exploratory data analysis and cleaning pipeline |
| **Power BI Desktop** | Data modeling, DAX measures, dashboard design |
| **DAX** | Custom KPI calculations and segmentation logic |
| **GitHub** | Version control and project documentation |

---

## 🚀 How to Use This Project

### View the Dashboard Report
Open `reports/Dashboard_Report.pdf` to explore all three dashboard pages with full visuals and key insights.

### Run the Data Cleaning Notebook
```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/Customer-Behavior-Analytics-PowerBI.git
cd Customer-Behavior-Analytics-PowerBI

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook notebooks/DataCleaning.ipynb
```

### Open the Power BI File *(if shared)*
Open the `.pbix` file in **Power BI Desktop** (free download from Microsoft). All visuals, DAX measures, and data model are included.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Anis**
- 📧 *[your email]*
- 💼 [LinkedIn](https://linkedin.com/in/YOUR_PROFILE)
- 🐙 [GitHub](https://github.com/YOUR_USERNAME)

---

*Built as part of a personal data analytics portfolio. Dataset used is publicly available consumer shopping data.*
