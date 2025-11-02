# 💰 Global Billionaires Dashboard (1997-2024)

An interactive Excel dashboard analyzing global billionaires’ data from **1997 to 2024**, highlighting trends in **net worth, countries, and industries** over time.

---

## 📊 Project Overview

This project visualizes historical billionaire data to uncover:
- Yearly trends in total global net worth
- Top billionaires and their industries
- Country-wise wealth distribution
- Changes in billionaire demographics over time

The dashboard is built entirely in **Microsoft Excel**, using **PivotTables, PivotCharts, Slicers, and Timelines** for interactivity.

---

## 🗂️ Dataset

**File:** `all_billionaires_1997_2024.csv`

**Source Columns (examples):**
- `person` — Name of billionaire  
- `country` — Country or citizenship  
- `industry` — Industry / source of wealth  
- `net_worth` — Net worth (USD billions)  
- `year` — Year of listing (1997-2024)

---

## ⚙️ Dashboard Build Process

### 1. Data Cleaning
- Imported raw CSV into Excel / Python (`pandas`)
- Removed duplicates and formatted headers
- Converted `net_worth` to numeric (USD billions)
- Extracted key columns: `person`, `country`, `industry`, `year`, `net_worth`

### 2. Excel Data Model
- Converted cleaned data into an Excel **Table** (`tblBillionaires`)
- Created **PivotTables** for:
  - Top 10 Billionaires (by Net Worth)
  - Net Worth by Country
  - Net Worth by Industry
  - Year-wise Total Net Worth

### 3. Visualization
- Added **PivotCharts**:
  - Line Chart → Total Net Worth by Year
  - Column Chart → Top Countries by Total Net Worth
  - Bar Chart → Top Industries
- Applied custom formatting and color themes

### 4. Interactivity
- Added **Slicers** for `Country` and `Industry`
- Added **Timeline** for `Year`
- Connected all visuals via Report Connections for dynamic filtering

---

## 📈 Key Insights
- Total global billionaire net worth grew **exponentially after 2010**
- The **Technology** and **Finance** sectors dominate overall wealth
- The **United States** and **China** lead in total net worth contribution
- Emerging markets show significant increases post-2015

---

## 📘 Files Included

| File Name | Description |
|------------|-------------|
| `billionaires_dashboard.xlsx` | Interactive Excel dashboard |
| `all_billionaires_1997_2024.csv` | Cleaned dataset |
| `billionaires_dashboard_sample.xlsx` | Auto-generated version (from Python cleaning) |

---

## 🧭 How to Use

1. Download and open `billionaires_dashboard.xlsx`
2. Enable editing (if prompted)
3. Use slicers/timeline to filter by:
   - Country
   - Industry
   - Year
4. Hover over charts to explore dynamic tooltips and insights
5. Click **Refresh All** (Data tab) when updating the dataset

---

## 🧰 Tools Used

| Tool | Purpose |
|------|----------|
| **Microsoft Excel** | Dashboard, pivot tables, charts |
| **Python (pandas, xlsxwriter)** | Data cleaning & export |
| **Power Query (optional)** | Advanced data import and transformation |

---

## 🚀 Future Enhancements
- Integrate live billionaire data via web scraping or API
- Add **Power BI** or **Tableau** version for advanced analytics
- Include KPI cards (e.g., median net worth, YoY growth)
- Automate data refresh with Power Query or VBA

---

## 📄 License
This project is released under the MIT License.  
Feel free to use, modify, and share with attribution.

---

## 👤 Author
**Yatish Raj**  
*Project: Billionaires Dashboard (Excel Analytics)*  
📧 Contact / Contributions welcome!
