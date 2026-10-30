# Power BI Dashboards

Power BI reports and practice workbooks covering visuals, Power Query, and DAX functions.

| File | What it shows |
|---|---|
| `Report Full.pbix` | Complete end-to-end report |
| `Animated Bar,Drill down, Word Cloud, Sankey Chart.pbix` | Animated bar chart race, drill-down, word cloud and Sankey visuals |
| `Gantt and Pareto Chart.pbix` | Gantt chart and Pareto (80/20) analysis |
| `Merge,Power Querry.pbix` | Merging queries in Power Query |
| `Modulo,roundup,is odd,iss even.pbix` | DAX math functions: MOD, ROUNDUP, ISODD, ISEVEN |
| `Copy of Sample - Superstore.xlsx` | Source data for the reports |
| `11. Power Query - Text Functions.xlsx` | Power Query text function practice data |
| `13. Power Query - Number Functions.xlsx` | Power Query number function practice data |
| `Transform Merge columns full name.xlsx` | Practice data for merging columns into a full name |

## How to open (step by step)

**1. Install Power BI Desktop** (free, Windows only)
- From the Microsoft Store: search "Power BI Desktop", or
- Download it from https://www.microsoft.com/power-bi/desktop

**2. Download this repository**

On GitHub, click **Code → Download ZIP** and unzip it. Or run:

```bash
git clone https://github.com/amitmohanty022/PowerBI.git
```

**3. Open a report**

Double-click any `.pbix` file, or in Power BI Desktop choose **File → Open report → Browse reports**.

**4. If visuals show "Couldn't load data"**

The report still points to the Excel file's location on the original computer.
1. Go to **Home → Transform data → Data source settings**.
2. Select the source, click **Change Source…**, and browse to `Copy of Sample - Superstore.xlsx` (or the matching `.xlsx`) in this folder.
3. Click **Close**, then **Apply changes** and **Refresh**.

**5. Custom visuals**

Word Cloud, Sankey, Gantt and animated bar charts are AppSource visuals. If one shows a warning, click it and choose **Enable**, or add it with **Visualizations → … → Get more visuals**.

> On a Mac or Linux, you can upload `.pbix` files to the Power BI web service at https://app.powerbi.com (free Microsoft account) to view them.
