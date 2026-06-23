# Real Estate Housing Market & Sales Performance Analytics

A comprehensive Business Intelligence solution built in Power BI designed to analyze real estate metrics, transaction volumes, pricing structures, and macroeconomic factors across multiple regions.

## 🔗 Live Interactive Dashboard
[View Interactive Power BI Dashboard](https://app.powerbi.com/groups/43b68cad-8070-45f8-83cf-7c2c69d7dc27/reports/595dae3c-72f2-4102-ab8b-a9f5db54f42e/7d13a9ca6e1072e00040?experience=power-bi)

---

## 📌 Project Overview
The housing market produces high-velocity transactional data influenced heavily by geography, economic rates, and property configurations. This project aggregates real estate historical records to provide an analytical tool evaluating sales volume velocity, pricing influences, and property specific size/value ratios. 

### Key Analytics Focus Areas:
* **Market Volume Velocity:** Tracking year-over-year adjustments, unit velocity, and gross revenue distributions across core territories.
* **Pricing Structural Influences:** Utilizing AI-driven root cause analysis to identify key drivers moving transaction values.
* **Asset Configuration Analysis:** Breaking down performance profiles across property types (Farms, Villas, Apartments, Townhouses, Summerhouses).

---

## 📊 Dashboard Architecture & Views

### 1. House Market Overview (Macro View)
Focuses on general market health, total sales volumes, and time-based shifts.
* **Key Metrics:** Features core telemetry cards displaying **453 units sold** in the latest period and a total **12-month sales volume of 11bn**.
* **Visual Elements:** Includes cross-regional sales price adjustments and Year-Over-Year sales growth trends filtered across distinct sales types (auction vs. regular vs. family sale).
* *Recommended Repo Image Placement:* `![House Market Overview Screenshot](your_uploaded_screenshot_name_1.png)` (Referencing image_182fbf.png)

### 2. Sales Performance Analysis (Operational View)
Breaks down financial transaction volumes and regional value densities.
* **Key Metrics:** Highlights top revenue generating territories led by **Zealand (95bn)** and **Jutland (81bn)**.
* **Visual Elements:** Features structured time-series ledgers mapping historic transactional dates alongside Key Influencers visual assets capturing localized price modifiers.
* *Recommended Repo Image Placement:* `![Sales Performance Screenshot](your_uploaded_screenshot_name_2.png)` (Referencing image_182fbc.png)

### 3. House Type Deep-Dive (Granular View)
An analytical perspective cross-examining building profiles against operational yields and financial costs.
* **Key Metrics:** Identifies Farm properties as leading baseline acquisition values at an average **2.7M Offer/Purchase price** paired with maximum asset spacing (**196.32 Avg SQM**).
* **Visual Elements:** Side-by-side matrices comparing inflation-to-yield scales next to SQM/SQM price density pairings.
* *Recommended Repo Image Placement:* `![House Type Analysis Screenshot](your_uploaded_screenshot_name_3.png)` (Referencing image_182fba.png)

---

## 🛠️ Data Model & Technical Stack
* **BI Architecture Platform:** Power BI Desktop
* **Modeling & Language Engine:** DAX (Data Analysis Expressions) for complex statistical calculations (YOY growth distributions, running totals, and conditional aggregations).
* **Advanced Visual Analytics:** Native Key Influencers Machine Learning integration.

### Core Fields and Schema Elements (See image_182fbf.png):
* **Measures Workspace:** `Average Price SQM`, `Median Sales Price Change`, `Offer to SQM Ration`, `Total YOY Sales`, `YOY_Sales_Growth`
* **Housing Data Architecture:** `area`, `city`, `date`, `house_type`, `no_rooms`, `Offer Price`, `Purchase Price`, `dk_ann_infl_rate%`, `nom_interest_rate%`

---

## 🚀 Local Deployment Instructions
1. Clone this repository locally.
2. Ensure you have the latest version of **Power BI Desktop** installed.
3. Download the repository `.pbix` file.
4. Open the workspace file to interactively parse the core semantic model and structural canvas.
