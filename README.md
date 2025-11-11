# Blinkit Sales Dashboard (Power BI)

An interactive **Power BI** dashboard to analyze Blinkit's sales performance, outlet trends, and product contribution. 
Built using **Power Query**, **DAX**, and clean **UX** practices. Inspired by the community tutorial referenced below.

## 🔗 Demo Reference
- Tutorial used for inspiration: https://www.youtube.com/watch?v=mmxVCFceQgU

## ✨ Features
- KPI cards for **Total Sales, Orders, Profit Margin, Avg. Delivery Time**
- Interactivity via **slicers** (Region, Outlet Type, Year) and **visual/page/report-level filters**
- Category and outlet performance with drill-through to detail views
- Consistent color theme and layout for business-friendly presentation
- Ready for publishing to **Power BI Service**

## 🧰 Tech Stack
- Power BI Desktop
- Power Query (M)
- DAX
- (Optional) Excel/CSV as data source

## 🧱 Data Model (at a glance)
- Star-schema style model with **Fact** table (sales/orders) and **Dimensions** (date, product, outlet, region)
- DAX measures for KPIs, YoY, and averages
- Slicer-driven navigation and drill-through

## 📁 Repository Structure
```
blinkit-powerbi-dashboard/
├─ pbix/
│  └─ Blinkit Sales Dashboard.pbix
├─ data/                 # Place source CSV/Excel files here (if applicable)
├─ docs/
│  └─ screenshots/       # Add screenshots for README/LinkedIn
├─ sql/                  # Optional: SQL used for data prep (if any)
├─ assets/               # Logos, thumbnails
├─ .gitignore
├─ LICENSE
└─ README.md
```

## 🚀 Getting Started
1. Open `pbix/Blinkit Sales Dashboard.pbix` in **Power BI Desktop**.
2. Update data source paths if prompted (File → Options & settings → Data source settings).
3. Refresh the model.
4. Export screenshots from the report (File → Export → PDF or use Snipping Tool) and add them in `docs/screenshots`.
5. Publish to **Power BI Service** when ready.

## 📊 KPIs & Measures (examples)
- `Total Sales`
- `Total Orders`
- `Average Delivery Time`
- `Profit Margin %`
- Time series trend with Year slicer

> To keep it tidy, create a `Measures` table to organize all DAX.

## 🌐 Power BI Service (optional)
- Publish report to a workspace
- Configure scheduled refresh (if you connect to live files/DB)
- Share as an App for stakeholders

## 📸 Screenshots (add yours)
- `docs/screenshots/overview.png`
- `docs/screenshots/category_breakdown.png`
- `docs/screenshots/outlet_performance.png`

## 📝 Attribution
This dashboard was created for learning and portfolio use. Tutorial credit: the YouTube video linked above.

---

**Author:** Your Name  
**License:** MIT