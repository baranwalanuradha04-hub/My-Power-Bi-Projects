# My-Power-Bi-Projects
Repository containing Power BI development files (.pbix), data transformation steps, and interactive dashboards designed to solve complex business problems.

# 📊 Power BI Data Analytics Project

## Data Transformation, DAX, and Interactive Reporting — Data Technician Bootcamp

This project showcases my end-to-end Power BI skills developed during the Data Technician Bootcamp, including data cleaning, modelling, DAX calculations, and interactive report design. The work was completed through hands-on labs aligned with the **PL-300: Power BI Data Analyst** curriculum, using a retail and sales dataset.

---

## 🛠️ Skills Demonstrated

### Data Transformation & Cleaning (Power Query)
- Cleaning, shaping, and transforming raw data before loading it into a Power BI data model
- Handling inconsistent, missing, or incorrectly formatted data ahead of analysis
- Loading cleaned data into Power BI to build a reliable foundation for reporting

### DAX Calculations
- Creating calculated columns to derive new fields from existing data
- Building DAX measures to calculate dynamic values (e.g. totals, averages, growth rates) that respond to report filters and slicers
- Working within a semantic model, configuring relationships between tables to support accurate calculations

### Interactive Report Design
- Adding slicers and filters to allow users to interactively explore the data (e.g. by category, region, or time period)
- Designing report layouts for clarity, ensuring visuals are easy to interpret at a glance
- Structuring reports so that filters apply consistently across multiple visuals on the same page

### Data Visualisation
Building a variety of visualisations to represent different types of insight:
- 📊 **Bar charts** – comparing values across categories
- 📈 **Line charts** – tracking trends and changes over time
- 🥧 **Pie charts** – showing proportional breakdowns
- 🗺️ **Maps** – visualising geographic or regional data

### Data Storytelling
- Combining multiple visuals into a single, cohesive report that tells a clear story with the data
- Using visuals and interactivity together to highlight key trends, patterns, and outliers relevant to retail and sales performance
- Focusing on turning raw numbers into insights a business audience can act on

---
### 🔗 Building the Data Model

With clean data in hand, I moved on to shaping it into a proper semantic model:

- Designed a star-schema layout, separating fact tables (transactions) from dimension tables (products, regions, dates, etc.)
- Set up table relationships with the correct cardinality and cross-filter direction
- Built a Date hierarchy (Year → Month → Day) to support time-based drill-down
- Configured formatting, summarisation, and data categories at the model level so visuals behave correctly by default

<!-- 📸 Add your star-schema diagram screenshot here -->
<!-- ![Data Model Diagram](images/data-model-diagram.png) -->


---
### 🧮 DAX: Calculated Columns & Measures

This is where the model came to life. I wrote DAX to answer specific business questions rather than just display raw numbers.

**Calculated columns** for things like category flags, date breakdowns, and custom classification logic.

**Measures** covering:
- Core aggregations (SUM, AVERAGE, COUNT)
- Time intelligence — Year-to-Date, Month-over-Month growth
- Percentage of Total
- KPI-style measures for tracking performance against targets
---

## 📁 Project Files

### 1️⃣ `03-Starter-Sales_Analysis.pbix` — Configuring the Semantic Model

Built the underlying data model for the sales analysis report — establishing table relationships and preparing a reliable foundation for accurate DAX calculations and reporting.

**Skills applied:** Data modelling, relationships between tables, semantic model configuration

<!-- 📸 Add your screenshot here -->
<!-- ![Semantic Model Screenshot](images/03-semantic-model.png) -->

<img width="572" height="276" alt="image" src="https://github.com/user-attachments/assets/ecb6d163-00f4-4fef-929b-9b0b17e913b7" />


<img width="527" height="212" alt="image" src="https://github.com/user-attachments/assets/885a8882-3373-4af9-a996-4bd40da02f5b" />


---


### 2️⃣ `04-Starter-Sales_Analysis.pbix` — Creating DAX Calculations

Extended the sales analysis model with calculated columns and measures, enabling dynamic, filter-responsive metrics such as totals and averages.

**Skills applied:** DAX calculated columns, DAX measures, working within a semantic model

<!-- 📸 Add your screenshot here -->
<!-- ![DAX Calculations Screenshot](images/04-dax-calculations.png) -->

<img width="562" height="206" alt="image" src="https://github.com/user-attachments/assets/771ddef2-da37-43a1-a7ab-1d284a550595" />
<img width="507" height="207" alt="image" src="https://github.com/user-attachments/assets/cb032506-90ce-433b-a559-d73e498ef0c9" />
<img width="561" height="247" alt="image" src="https://github.com/user-attachments/assets/900c4f5c-4b40-4e30-9798-8563cf7b9e0b" />


---

### 3️⃣ `08-Starter-Sales_Analysis.pbix` — Designing Interactive Power BI Reports

Brought the model together into a polished, interactive sales report — combining KPI cards, bar charts, and line charts, with slicers and filters for user-driven exploration.

**Skills applied:** Interactive report design, slicers & filters, bar/line chart visualisations, data storytelling

<!-- 📸 Add your screenshot here -->
<!-- ![Sales Report Screenshot](images/08-sales-report.png) -->
<img width="562" height="307" alt="image" src="https://github.com/user-attachments/assets/005f2d9f-b2d5-45fd-852d-a046ae2c0f4b" />
<img width="556" height="365" alt="image" src="https://github.com/user-attachments/assets/be5e3a10-b066-4c91-bebe-02da185a9e13" />



---

### 4️⃣ `DAX_calculations.pbix` — DAX Practice & Calculations

A focused workbook dedicated to practicing and applying DAX — building calculated columns and measures to strengthen core DAX skills independent of the main sales report.

**Skills applied:** DAX calculated columns, DAX measures, formula logic and filter context

<!-- 📸 Add your screenshot here -->
<!-- ![DAX Practice Screenshot](images/dax-calculations.png) -->
<img width="572" height="376" alt="image" src="https://github.com/user-attachments/assets/5a9f75c6-8c43-4360-b29c-c60d9b85d536" />



---

## 🎯 Purpose

This project strengthened my understanding of the end-to-end Power BI workflow — from cleaning and shaping data in Power Query, through building DAX calculations, to designing interactive, visually clear reports. These are core skills for a Data Technician role, particularly when it comes to communicating retail and sales insights to a non-technical audience.











