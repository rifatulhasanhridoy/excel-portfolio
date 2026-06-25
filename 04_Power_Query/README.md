# 📊 Excel Power Query Portfolio

A hands-on collection of Excel Power Query projects covering data import, cleaning, transformation, and advanced grouping techniques. Each chapter focuses on a specific skill set with real-world practice files.

---

## 📁 Project Structure

```
04_Power_Query/
├── Chapter-1-Data Cleaning/
│   ├── Medical History Data Cleaning.xlsx
│   └── Medical History Raw Data.xlsx
│
├── Chapter-2-Importing Data from Various Sources/
│   ├── Appending Data From Multiple Sheets - .xlsx
│   ├── Import From PDF.xlsx
│   ├── Import From Web.xlsx
│   ├── Pivot - Unpivot Column.xlsx
│   ├── Table data in PDF file.pdf
│   └── Table in Image format.png
│
├── Chapter-4-Appending Data From Multiple Workbooks/
│   ├── AppendFromMultipleWorkbooks.xlsx
│   ├── Year 2014.xlsx
│   ├── Year 2015.xlsx
│   ├── Year 2016.xlsx
│   ├── Year 2017.xlsx
│   └── Year 2018.xlsx
│
├── Chapter-5-Appending CSV Files/
│   ├── AppendFromMultipleCSV.xlsx
│   ├── Central.csv
│   ├── North.csv
│   ├── South.csv
│   └── West.csv
│
└── Chapter-6-Advance Grouping/
    ├── Grouping.xlsx
    ├── Product List.xlsx
    └── Software Names and Versions.xlsx
```

---

## 📚 Chapter Overview

### Chapter 1 — Data Cleaning
Learn how to clean messy, real-world data using Power Query. This chapter uses a medical history dataset to practice removing duplicates, fixing data types, trimming whitespace, handling nulls, and standardizing column formats.

### Chapter 2 — Importing Data from Various Sources
Explores how Power Query can pull data from multiple file types and locations:
- **Import From PDF** — extract tables directly from PDF files
- **Import From Web** — connect to live web data sources
- **Multiple Sheets** — append data across sheets in a single workbook
- **Pivot & Unpivot** — reshape data between wide and long formats
- Also includes practice source files: a PDF with tabular data and a PNG image of a table

### Chapter 4 — Appending Data from Multiple Workbooks
Combines annual sales/data files (2014–2018) into a single unified table using Power Query's folder connector. Great for automating multi-file consolidation workflows.

### Chapter 5 — Appending CSV Files
Demonstrates how to merge multiple regional CSV files (Central, North, South, West) into one dataset automatically using Power Query — no manual copy-paste required.

### Chapter 6 — Advanced Grouping
Covers advanced `Group By` operations in Power Query including multi-column grouping, custom aggregations, and working with product and software version data.

---

## 🛠️ Tools & Requirements

- **Microsoft Excel** (2016 or later recommended) — Power Query is built in
- **Power Query Editor** — accessed via `Data → Get & Transform Data`
- No additional software or plugins required

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open the `.xlsx` file for the chapter you want to explore
3. Go to **Data → Queries & Connections** to view existing queries
4. Open the **Power Query Editor** to inspect or modify the transformation steps



## 📌 Notes

- Chapter 3 is intentionally skipped in this folder structure — content is too large(More Than 25 MB)
- Source data files (PDFs, CSVs, raw Excel files) are included alongside each workbook so queries can be refreshed locally.
