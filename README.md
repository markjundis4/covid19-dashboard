# Global COVID-19 Dashboard (Tableau)

> Interactive Tableau dashboard analyzing COVID-19 global trends with KPIs, trend analysis, country comparisons, and a choropleth map.

**Live dashboard:** [View on Tableau Public](https://public.tableau.com/shared/44FNCB5GP?:display_count=n&:origin=viz_share_link)  
**Data source:** Our World in Data (OWID) – COVID-19 dataset

---

## Preview
![Dashboard preview](https://github.com/user-attachments/assets/fd1a8830-a2bf-492e-bd4a-c03d4599e424)

---

## What’s inside
- **KPIs:** Total Cases, Total Deaths, Total Vaccinations (latest available)
- **Trends:** Cases over time
- **Comparisons:** Top 10 countries by total cases
- **Map:** Total cases by country (latest)
- **Filters:** Country (continents/World excluded)

---

## How it works
- Uses MAX aggregations and FIXED LOD to capture **latest values per country**
- Country dropdown drives all views (applied to all worksheets)
- Built with **containers** for a responsive layout

---

## Files
- `Global_COVID19_Dashboard.twbx` – packaged Tableau workbook
- `screenshots/` – images for preview
- [OWID COVID-19 Data Source](https://ourworldindata.org/covid-deaths) – official dataset page
- `data/` (optional) – sample data or instructions

---

## Reproduce / Edit
1. Download `Global_COVID19_Dashboard.twbx`
2. Open in Tableau Desktop or Tableau Public
3. Replace data source with the latest OWID CSV if needed:
   - OWID catalog CSV (compact): *link above*
4. Refresh extracts → Save

---

## Notes
- This project is for educational/portfolio purposes.
- Credit: Our World in Data (OWID) for the dataset.
