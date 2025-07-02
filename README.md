# 🏡 Housing Prices Analysis — California, 1990

This project explores California housing data from the 1990 U.S. Census using both Python and Power BI. It combines data wrangling, statistical analysis, and geospatial visualization to uncover patterns in home prices, income brackets, affordability, and location.

---

## 📊 Dashboard & Notebook

- 📍 **Power BI Dashboard**:  
  Explore interactive insights on housing value by city, income bracket, and ocean proximity.  
  👉 [Power BI Report](https://github.com/Daiaa-K/Housing-Prices-Analysis)

- 🐍 **Jupyter Notebook**:  
  Python-based data cleaning, feature engineering, and visualization.  
  File: [`notebook.ipynb`](./notebook.ipynb)

---

## 🧠 Project Highlights

### 🔹 Data Source
- **California Housing Dataset** (1990 U.S. Census)
- Features: `median_house_value`, `income_bracket`, `total_rooms`, `latitude`, `longitude`, `ocean_proximity`, etc.

### 🔹 Key Questions Answered
- Which cities have the highest and lowest median house values?
- How does income level affect housing affordability?
- How do location features (like ocean proximity) influence price?
- What qualifies as “affordable” or “premium” housing in 1990?

### 🔹 Power BI Features
- Interactive map of housing prices by income bracket
- Conditional formatting by affordability
- Matrix drill-downs from city → ocean proximity
- Grouped visualizations of bedroom/room averages by region

---

## 📁 File Structure

| File | Description |
|------|-------------|
| `notebook.ipynb` | Full Python data analysis with visualizations |
| `Housing_Analysis.pbix` | Power BI report (open with Power BI Desktop) |
| `requirements.txt` | Python packages used with versioning |
| `README.md` | Project overview and documentation |

---

## 🛠️ Requirements

Install Python dependencies using:

```bash
pip install -r requirements.txt
