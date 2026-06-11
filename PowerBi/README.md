# US States Population Analysis Dashboard

## Project Overview

This Power BI project analyzes historical population data across the United States from 1950 to 2015. The dashboard enables users to explore population distribution, census region breakdowns, 
census division insights, and long-term population growth trends through interactive visualizations and dynamic filtering capabilities.
The report is designed to support regional and state-level population analysis while demonstrating advanced Power BI features such as 
DAX measures, report page tooltips, dynamic tables, and cross-filtering interactions.
---
## Dataset

The dataset contains historical population information for U.S. states from 1950 through 2015 and includes the following attributes:
- State Name  
- State Abbreviation  
- Census Region  
- Census Division  
- Population  
- Year  
---
## Dashboard Components
### 1. Overview Dashboard

The Overview page provides a high-level summary of population distribution across the United States.

#### Features
- Interactive U.S. map visual displaying states grouped by Census Region  
- State count analysis by Census Region  
- Detailed population table containing:
  - Census Division  
  - Census Region  
  - State Name  
  - State Abbreviation  
  - Population Metrics  
- Cross-filtering between all report visuals  
- Interactive exploration of regional population statistics  

#### Visualizations
- Filled Map  
- Bar Chart  
- Detailed Data Table  
- Interactive Filters  
---
### 2. Custom Report Page Tooltips
The dashboard includes advanced report page tooltips that provide additional insights without requiring users to navigate away from the main report.
#### Census Division Population Breakdown Tooltip
When users hover over a Census Division, a tooltip displays:
- Population distribution by Census Division  
- Percentage contribution of each division  
- Comparative population analysis  

#### Historical Population Trend Tooltip
When users hover over a state, a tooltip displays:
- Historical population trend from 1950 to 2015  
- Population growth visualization  
- Long-term demographic changes  

**Example:**
- Kansas Population Trend (1950–2015)  
- Interactive line chart showing population growth over time  
---
### 3. Dynamic Population Growth Analysis

A dedicated analysis section allows users to explore population growth trends across states and regions.

#### Dynamic Population Growth Table
The table dynamically displays:
- State Name  
- State Abbreviation  
- Minimum Year Population (1950)  
- Maximum Year Population (2015)  
- Population Growth Analysis  

#### Interactive Year Range Slicer
Users can select any year range between:
- 1950  
- 2015  

The table dynamically updates based on the selected period, allowing flexible historical analysis.
---
### Interactive Census Region Filter

Users can filter the analysis using a multi-select Census Region slicer:

- Midwest  
- Northeast  
- South  
- West  

The dynamic table updates automatically to display only the selected region's population data.
---
## User Interactions
Users can:
- Hover over visuals to view detailed report page tooltips  
- Select Census Regions directly from visuals or slicers  
- Filter population data using year ranges  
- Compare population growth across states  
- Explore Census Region and Census Division relationships  
- Perform regional population trend analysis  
- Drill into state-level demographic information  
---
## Power BI Features Demonstrated

### Data Modeling
- Star-schema style relationships  
- Dimension and fact table design  

### Power Query
- Data cleansing  
- Data transformation  
- Query optimization  

### DAX
- Calculated Measures  
- Dynamic Measures  
- Aggregations  
- Population Growth Calculations  

### Interactive Reporting
- Report Page Tooltips  
- Cross Filtering  
- Dynamic Tables  
- Interactive Slicers  
- Responsive Visual Interactions  

### Visualizations
- Filled Maps  
- Bar Charts  
- Pie Charts  
- Line Charts  
- KPI Analysis Tables  
---
## Business Insights
The dashboard helps answer questions such as:
- Which Census Region contains the largest number of states?  
- How is the U.S. population distributed across Census Divisions?
- Which states experienced the highest population growth between 1950 and 2015?  
- How have population trends evolved over time?  
- How do population patterns differ across regions?  
- What regional demographic changes can be observed over multiple decades?
---
<img width="1225" height="714" alt="image" src="https://github.com/user-attachments/assets/e49bba97-f432-42b8-8495-c8865a6bf2bb" /><img width="597" height="356" alt="image" src="https://github.com/user-attachments/assets/122e9117-c0d2-4d19-9ac9-97ae8250b95b" /> <img width="947" height="641" alt="image" src="https://github.com/user-attachments/assets/b9ce56e3-9e22-447e-8429-d127f8031283" />



## Population Tooltip by Years & by Census_region

<img width="403" height="250" alt="image" src="https://github.com/user-attachments/assets/bc89dcf2-12c7-45da-b3ba-45b8873cdb59" /> , <img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/8152ce89-5df3-438c-b00a-3698c5cd8f51" />






