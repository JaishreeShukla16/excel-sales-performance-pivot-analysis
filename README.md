# Sales Performance Analysis: Excel Pivot Tables

An Excel practice project that analyses the 5-day sales performance of 141 sales executives across 8 regions, using **pivot tables, charts and a slicer** to find top performers, weak spots and target gaps.

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot_Tables-217346?style=flat-square)
![Status](https://img.shields.io/badge/Status-Practice_Project-blue?style=flat-square)

---

## Objective
To practise turning raw sales data into a clear performance summary, answering questions such as:
- Who are the best and worst performing sales executives?
- Which regions sell the most?
- How far is each executive from their target?
- Which day of the week has the strongest sales?

## Files

| File | Description |
|------|-------------|
| [`Pivot_Table_Practice.xlsm`](./Pivot_Table_Practice.xlsm) | Excel workbook with raw data, pivot tables, charts and a slicer |

**Sheets inside the workbook**

| Sheet | Contents |
|-------|----------|
| `Raw Data` | Source data: 141 rows, 12 columns |
| `Dashboard` | 4 pivot tables, 3 charts and a Region slicer |

## Dataset

| Column | Description |
|--------|-------------|
| `Emp Code` | Unique employee ID |
| `Sales Executive` | Name of the executive |
| `Region` | Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi or Surat |
| `Day1` to `Day5` | Units sold on each day |
| `Total Sales` | Sum of Day1 to Day5 |
| `Target` | Sales target (500 for every executive) |
| `Target Hit %` | Total Sales ÷ Target |
| `Away From Target %` | Gap remaining to reach the target |

> Note: This is a practice dataset, not real company data.

## What I Built
- **Top 5 sales executives** by total sales
- **Bottom 5 sales executives** by total sales
- **Target Hit % ranking** of the top performers
- **Away From Target %** for the lowest performers
- **Bar, pie and line charts** to visualise the summaries
- **Region slicer** to filter the whole dashboard with one click

## Key Insights
- Total sales across all executives: **38,945 units**, with an average target achievement of **about 55%**.
- **No executive reached the 500 target.** The best performer (Jagdish Chandra, Surat) reached 389 units, or 77.8%.
- **Nagpur** led all regions with 5,248 units, followed closely by Mumbai. **Ranchi** was lowest at 4,296.
- **Day 4** was the strongest sales day (8,323 units) and **Day 5** the weakest (7,352).
- The lowest performers sold under 170 units, which is less than a third of the target.

## Skills Practised
- Creating and formatting **PivotTables**
- Sorting and filtering **Top N / Bottom N** values
- Calculated percentage columns (Target Hit %)
- Building **bar, pie and line charts** from pivot data
- Adding **slicers** for interactive filtering
- Structuring raw data in a clean tabular format

## How to Use
1. Download or clone this repository.
2. Open `Pivot_Table_Practice.xlsm` in Microsoft Excel.
3. If prompted, click **Enable Content** (the file is macro-enabled; it contains no macros that change your data).
4. Open `dashboard` and use the **Region slicer** to filter the pivot tables and charts.

## Next Steps
- [ ] Add a Region-wise pivot table and a Day-wise trend chart
- [ ] Recreate this analysis in Python (Pandas + Seaborn)
- [ ] Build an interactive Power BI dashboard from the same data

---

## Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jaishree_Shukla-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jaishree-shukla-948496289)
