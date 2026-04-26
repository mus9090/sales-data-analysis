Manufacturer Sales Analysis Dashboard 📊

An interactive Power BI dashboard analyzing VanArsdel Ltd.'s sales performance against 4 competitors across 7 countries from 2014 to 2021.

📌 Objective

To build a multi-page interactive dashboard that tracks manufacturer revenue, compares competitor performance, visualizes year-over-year growth trends, and enables geographic and category-level analysis.

📂 Dataset

- **Source:** Microsoft Power BI Dashboard in a Day (DiAD) training dataset
- **Description:** Manufacturer sales data covering VanArsdel Ltd. and competitors (Fabrikam Inc., Nod Publishers, Tailwind Traders, Wide World Importers) across 7 countries and 2 product categories (Urban, Rural) from 2014–2021.

📸 Dashboard Preview

![Dashboard Preview](screenshots/dashboard.png)

<img width="1997" height="1157" alt="image" src="https://github.com/user-attachments/assets/57c7cfa9-09dd-4119-b84f-ed50d0829fd7" />


 ✨ Features

- **KPI Gauge** — Tracks current vs. prior year (PY) revenue with target comparison
- **Revenue by Country** — Bar chart showing sales across USA, Australia, Japan, Germany, Nigeria, Mexico, Canada
- **Revenue & % Growth by Year** — Combo chart tracking revenue alongside growth rate trend (2014–2021)
- **Category Breakdown Table** — Urban vs. Rural revenue with %GT Revenue, % Growth, and PY Sales columns
- **AI-Generated Insights** — Auto-generated narrative highlights key trends
- **Manufacturer Slicer** — Filter entire dashboard by competitor
- **Year Play-Axis** — Animated year-by-year progression of revenue data
- **Bookmarks** — Initial State, USA Revenue, Australia Revenue views

 🔍 Key Insights

- **USA** was the top market with Rs. 67.05Cr in total revenue
- **Revenue grew 154.39%** between 2014 and 2021, though growth rate declined 52.70% over the same period
- **% Growth peaked around 2017–2018** before entering a steep decline through 2021
- **Urban category** accounted for 99.95% of total revenue vs. Rural at 0.05%
- **VanArsdel Ltd.** met its revenue target of Rs. 67,05,94,889.37

 🛠️ Tools & Features Used

- Power BI Desktop
- DAX measures (% Growth, PY Sales, %GT Revenue)
- KPI Gauge & Cards
- Combo Charts (Bar + Line)
- Drill-Down Matrix
- Manufacturer & Year Slicers
- Play Axis Animation
- AI Insights (Smart Narrative)
- Bookmarks

 📁 Project Structure

manufacturer-sales-dashboard/
│
├── ManufacturerAnalysis.pbix   # Power BI file
├── screenshots/
│   └── dashboard.png           # Dashboard preview
└── README.md
🚀 How to Run

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Open `ManufacturerAnalysis.pbix`
3. Use the manufacturer slicer to compare competitors
4. Use the year play-axis to animate revenue progression
