# 📈 Price Elasticity & Revenue Sensitivity Analysis  
*A QuantShift-Lab Applied Economics Project*  

---

## 🧠 Overview  
This project investigates **price elasticity of demand** and its downstream effect on **revenue and profit sensitivity** using real-world transactional or simulated retail data.  
The goal is to build a transparent, data-driven framework that quantifies how price changes influence total revenue, enabling more informed pricing strategies and market modeling.  

The current phase focuses on exploratory data analysis, elasticity estimation, and visualization of demand curves using Python-based econometric methods.  

---

## 🧩 Repository Structure (Anticipated)  
```bash
Elasticity-Analysis/
│
├── notebooks/               # Core Jupyter notebooks for exploration and modeling
├── data/                    # Raw and processed datasets (excluded in .gitignore)
├── docs/                    # Research notes and visual summaries
├── environment.yml          # Conda environment for reproducibility
├── elasticity_model.ipynb   # Main notebook for EDA, modeling, and visualization
├── LICENSE                  # MIT License
└── README.md                # Project documentation
```

---

## 🔄 Current Progress & Beyond

### 🧹 **Phase 1: Data Exploration & Cleaning (In Progress)**
- Imported and profiled product-level sales dataset.  
- Verified numerical consistency between price, quantity, and revenue fields.  
- Cleaned and standardized column names; corrected outliers and data entry anomalies.  
- Conducted exploratory data analysis (EDA) to visualize demand trends and relationships.  
- Computed descriptive statistics for price, volume, and total revenue.  
- Confirmed expected inverse price–quantity relationship through scatter and log–log plots.  
- Generated initial visualizations showing demand sensitivity and revenue concentration zones.

**Key Early Findings:**  
- Quantity demanded exhibits clear negative elasticity with respect to price.  
- Revenue peaks in the mid-price range, suggesting the presence of an optimal pricing window.  
- Outliers correspond to promotional periods or bulk purchase behavior, which will need segmentation.

---

### 🧮 **Phase 2: Elasticity Modeling (Next Phase)**
- Implement baseline elasticity estimation using log-log regression (`ln(Q) = a + b·ln(P)`).  
- Interpret regression coefficient `b` as point elasticity of demand.  
- Experiment with polynomial and piecewise regressions to capture nonlinear elasticity.  
- Segment dataset by product or time period to compare elasticity across groups.  
- Validate model assumptions (normality, homoscedasticity, multicollinearity).  
- Benchmark results using R², RMSE, and adjusted R² for fit quality.

**Deliverables:**  
- Elasticity estimation notebook.  
- Comparison of model performance across methods.  
- Summary report (`/docs/elasticity_results.md`).  

---

### ⚙️ **Phase 3: Revenue Sensitivity & Optimization (Planned)**
- Simulate revenue responses to incremental price changes (±5%, ±10%, ±20%).  
- Compute marginal revenue and profit-maximizing price points.  
- Introduce variable cost estimates to model contribution margin.  
- Develop elasticity–revenue surface plots for scenario analysis.  
- Quantify total revenue impact under varying elasticity assumptions.  
- Document results for visualization in dashboard phase.

**Objective:**  
Identify data-driven pricing zones that maximize revenue while maintaining realistic demand levels.

---

### 📊 **Phase 4: Visualization & Dashboard Development (Future Work)**
- Build Streamlit dashboard for interactive elasticity exploration.  
- Integrate sliders for price adjustment and elasticity coefficients.  
- Plot real-time demand curves, marginal revenue, and profit projections.  
- Display heatmaps of elasticity across products or regions.  
- Export dashboard analytics as static HTML or PDF reports.

**Technical Focus:**  
Combine analytical transparency with visual interpretability to support managerial decision-making.

---

### 🧭 **Phase 5: Quantitative Extensions & Research Expansion (Long-Term)**
- Extend framework to cross-price elasticity analysis for complementary and substitute goods.  
- Incorporate macroeconomic factors (e.g., income, inflation) to study contextual elasticity.  
- Explore causal inference methods (Difference-in-Differences, Instrumental Variables) for promotions.  
- Integrate time-series elasticity tracking to observe behavioral drift.  
- Develop `elasticity_toolkit` module for reusable QuantShift-Lab econometric workflows.  

**Research Vision:**  
Evolve this notebook into a reproducible, open-source elasticity modeling framework that bridges economics, data science, and applied quantitative research.

---

## ✉️ Contact

**Brice A. Nelson**  
Founder, **QuantShift-Lab**  
Python Backend Engineer | Applied Quantitative Researcher  

🌐 [devbybrice.com](https://www.devbybrice.com)  
📧 brice@devbybrice.com  
🔗 [LinkedIn](https://www.linkedin.com/in/brice-a-nelson-p-e-mba-36b28b15/) • [GitHub](https://github.com/QuantShift-Lab)  

---

> _QuantShift-Lab: advancing reproducible, quantitative research in economics, finance, and data science._
