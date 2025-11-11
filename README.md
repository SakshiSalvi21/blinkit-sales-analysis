# Blinkit Sales Dashboard (Power BI)

An interactive **Power BI** dashboard to analyze Blinkit's sales performance, outlet trends, and product contribution. 
Built using **Power Query**, **DAX**, and clean **UX** practices. Inspired by the community tutorial referenced below.

## 🔗 Demo Reference
- Tutorial used for inspiration: https://www.youtube.com/watch?v=mmxVCFceQgU

## ✨ Features
- KPI cards for **Total Sales, Orders, Rating**
- Interactivity via **slicers** (Location, Outlet Size, Item Type) and **visual/page/report-level filters**
- Category and outlet performance with drill-through to detail views
- Consistent color theme and layout for business-friendly presentation
- Ready for publishing to **Power BI Service**

## 🧰 Tech Stack
- Power BI Desktop
- Power Query (M)
- DAX

## 🧱 Data Model (at a glance)
- Star-schema style model with **Fact** table (sales/orders) and **Dimensions** (product, outlet, location)
- DAX measures for KPIs, and averages
- Slicer-driven navigation and drill-through

## 📁 Repository Structure
```
blinkit-powerbi-dashboard/
├─ pbix/
│  └─ Blinkit Sales Dashboard.pbix
├─ LICENSE
└─ README.md
```

## 📊 KPIs & Measures (examples)
- `Total Sales`
- `Average Sales`
- `No. of Items`
- `Average Rating`

## 📝 Attribution
This dashboard was created for learning and portfolio use. Tutorial credit: the YouTube video linked above.

---

**Author:** Sakshi Salvi  
**License:** MIT
