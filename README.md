# Electric Vehicles Analysis Dashboard

## Introduction

The **Electric Vehicles Analysis Dashboard** is an interactive Microsoft Excel-based tool designed to analyze trends in electric vehicle (EV) adoption. It provides insights into:

- Total number of electric vehicles.
- Distribution of EVs across different states.
- Vehicle model-wise distribution.
- Growth trends over the years.
- Clean Alternative Fuel Vehicle (CAFV) eligibility.

Leveraging Excel's **PivotTables**, **PivotCharts**, **slicers**, and **conditional formatting**, this dashboard allows real-time data filtering and interactive exploration.

---

## Objective

The primary goals of this dashboard are to:

- **Provide a comprehensive view** of electric vehicle adoption trends.
- **Enable interactive filtering** to analyze data by city, electric utility, and vehicle type.
- **Offer insightful visualizations** for understanding EV distribution, model popularity, and CAFV eligibility.
- **Facilitate data-driven decision-making** for businesses, policymakers, and researchers.

---

## Data Source

The dataset contains information about electric vehicle models, manufacturers, states, CAFV eligibility, and battery range. The data is structured and processed using Excel formulas, PivotTables, and dynamic filtering for smooth interactivity.

---

## Dashboard Overview

The dashboard consists of multiple interactive sections, each focusing on different insights:

### 1. Key Performance Indicators (KPIs) Section

Located on the left side of the dashboard, this section displays summary metrics:
- **Total Vehicles**: Total count of electric vehicles.
- **Average Electric Range**: Mean range (in miles) for all EVs.
- **BEV & PHEV Distribution**: Pie charts displaying the proportion of Battery Electric Vehicles (BEV) vs. Plug-in Hybrid Electric Vehicles (PHEV).

### 2. Interactive Filter Panel

Positioned at the top, this panel allows users to filter data dynamically by:
- **Electric Utility Provider**: Filter by electricity provider (e.g., Avista Corp).
- **City**: Select a city (e.g., Aberdeen).
- **Electric Vehicle Type**: Filter by BEV or PHEV.

👉 **Note**: When a filter is applied, all charts and graphs update in real-time.

### 3. Total Vehicles by Model Year (Line Chart)

This chart shows the growth trend of EVs from 2010 onwards, illustrating:
- EV adoption over the years.
- Peaks and dips in adoption, highlighting significant years.

**Use case**: Helps analysts identify years with spikes or dips in EV sales.

### 4. Total Vehicles by State (Geographical Map)

This U.S. map visualizes the state-wise distribution of EVs using different shades of green to represent varying adoption levels.

**Use case**: Aids policymakers in understanding which states are leading in EV adoption and where infrastructure may need improvement.

### 5. Total Vehicles by Model Name (Bar Chart)

This horizontal bar chart displays the most popular EV manufacturers. Tesla leads, followed by Nissan, Chevrolet, Ford, and BMW.

**Use case**: Helps identify the most popular EV manufacturers in the dataset.

### 6. Total Vehicles by CAFV Eligibility (Donut Chart)

Categorizes vehicles based on their eligibility for the Clean Alternative Fuel Vehicle (CAFV) program:
- **Eligible for CAFV Program**: 37%
- **Eligibility Unknown**: 11%
- **Not Eligible (Low battery range)**: 52%

**Use case**: Highlights the percentage of EVs that qualify for alternative fuel programs.

### 7. Total Vehicles by Model (Treemap Visualization)

A treemap chart displays various EV models (e.g., Tesla Model 3, Nissan Leaf). The size of each box represents the number of vehicles of that model.

**Use case**: Helps users compare the popularity and sales volume of different EV models.

---

## How the Dashboard Was Built

### 1. Data Preparation & Cleaning
- Raw data was cleaned and formatted using Excel formulas.
- Unnecessary columns were removed, and missing values were handled.
- The data was structured in a PivotTable-friendly format.

### 2. PivotTables & PivotCharts
- PivotTables were used for data aggregation and analysis.
- PivotCharts were created to visualize the insights dynamically.
- Slicers were added to allow real-time filtering.

### 3. Data Visualization Enhancements
- Conditional formatting was applied to highlight key trends.
- Custom color themes were used for a visually appealing design.
- Excel’s map chart feature was used for geographical mapping.

---

## How to Use the Dashboard

1. **Open the Excel file** containing the dashboard.
2. Use the **filter panel** to refine the analysis based on utility provider, city, and vehicle type.
3. Review the **KPIs** (Total Vehicles, Avg. Electric Range, BEV/PHEV distribution).
4. Analyze the charts for insights on EV growth, model distribution, and state-wise adoption.
5. **Hover** over charts for additional details.
6. Modify the dataset to update the dashboard automatically.

---

## Key Insights from the Dashboard

- **Tesla** dominates the EV market, leading in vehicle count.
- EV adoption has **increased significantly** over the years, with recent years showing a peak.
- Certain states have **higher EV adoption**, indicating better infrastructure support.
- A large percentage of EVs are **not CAFV eligible**, highlighting potential areas for improvement.

---

## Future Enhancements

- **Advanced Filtering Options**: Add filters for battery capacity, charging time, and energy efficiency.
- **Predictive Analytics**: Implement forecasting models to predict future EV adoption trends.
- **Expanded Data Sources**: Integrate government and industry datasets for deeper insights.
- **Automated Data Updates**: Link to external databases for real-time data refresh.

---

## Conclusion

The **Electric Vehicles Analysis Dashboard** in Excel provides a powerful and interactive tool for analyzing EV adoption trends. With dynamic filtering, clear visual insights, and user-friendly navigation, the dashboard serves as a valuable resource for:
- **Businesses** looking to understand EV market trends.
- **Policymakers** planning EV infrastructure.
- **Researchers & Analysts** studying EV adoption patterns.

---

### License

Include your license here (e.g., MIT License, GPL License, etc.).

