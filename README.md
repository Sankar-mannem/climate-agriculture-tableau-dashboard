# Climate Balance & Agricultural Impact Dashboard using Tableau

## Project Overview

This project presents an interactive Tableau dashboard designed to analyse climate balance and agricultural risk across countries. The dashboard focuses on the relationship between temperature and precipitation and identifies regions where high heat and low rainfall may create pressure on agriculture, water availability, and crop productivity.

The main aim of this project is to convert climate data into clear visual insights that can support decision-making for climate adaptation, agricultural planning, and food security analysis.

## Business Problem

Climate change is one of the major challenges affecting global agriculture. Rising temperatures, irregular rainfall, drought conditions, and water stress can directly impact crop productivity and farming livelihoods.

Agricultural planners, policymakers, and researchers need a simple way to identify countries that may be more vulnerable to climate imbalance. This dashboard helps answer questions such as:

- Which countries show the highest imbalance between temperature and rainfall?
- Are hotter countries always receiving less rainfall?
- Which regions are more exposed to warm and dry climate conditions?
- Which countries may need more attention for irrigation, drought-resistant crops, and climate adaptation planning?

## Tools Used

- Tableau
- Data visualisation
- Dashboard design
- Interactive filters and tooltips
- Climate and agriculture data analysis

## Dataset

The project uses a climate change and agriculture-related dataset containing country-level climate indicators.

Key variables used in the dashboard include:

- Country name
- Average annual temperature
- Annual precipitation
- Temperature-to-precipitation ratio
- Country/location information

## Dashboard Preview

![Dashboard Overview](screenshots/dashboard_overview.png)

## Dashboard Visualisations and Analysis

### 1. Climate Imbalance Indicator - Heat vs Rainfall by Country

![Climate Imbalance Bar Chart](screenshots/climate_imbalance_bar_chart.png)

This horizontal bar chart ranks countries based on a temperature-to-precipitation ratio. The purpose of this chart is to identify countries where heat levels are high compared with rainfall availability.

A higher value may indicate stronger climate stress, especially for countries that depend heavily on rain-fed agriculture. These countries may face higher risk of drought, irrigation demand, crop stress, and reduced agricultural productivity.

Why this visual is useful:

- It provides a clear country-level ranking.
- It helps identify high-risk countries quickly.
- Horizontal bars make country names easier to read.
- Colour intensity supports quick interpretation of climate imbalance.

Recruiter-focused insight:

This chart shows how a simple calculated indicator can be used to turn raw climate variables into an actionable risk-ranking metric. Instead of only showing temperature and rainfall separately, the dashboard combines them into a practical measure that supports faster decision-making.

### 2. Temperature vs Precipitation Scatter Plot

![Temperature vs Precipitation Scatter Plot](screenshots/temperature_precipitation_scatter.png)

This scatter plot compares average annual temperature with annual precipitation for each country. It helps show whether hotter countries also receive more or less rainfall.

The scatter plot is important because agricultural risk cannot be understood from temperature alone. Some countries may be warm and dry, while others may be warm and wet. These two groups face different agricultural challenges.

For example:

- Warm and dry countries may face drought, irrigation demand, and crop yield pressure.
- Warm and wet countries may face flooding, pests, disease, or drainage-related challenges.

Why this visual is useful:

- It shows the relationship between two key climate variables.
- It helps identify clusters and outliers.
- It separates warm-dry and warm-wet country patterns.
- It supports deeper analysis beyond basic ranking.

Recruiter-focused insight:

This visual demonstrates analytical thinking by comparing two variables together instead of viewing them separately. It helps identify that temperature alone is not enough to explain agricultural risk; rainfall context is also necessary.

### 3. Temperature and Precipitation Map

![Climate Map](screenshots/climate_map.png)

The map visualisation shows climate patterns geographically. It helps identify regional clusters where high temperature and low rainfall may overlap.

This view is especially useful because climate risk is strongly connected to location. A map allows users to quickly identify whether climate stress is concentrated in certain regions such as North Africa, the Middle East, or the Sahel.

Why this visual is useful:

- It adds geographical context to the analysis.
- It helps identify regional climate-risk hotspots.
- It supports policy and agricultural planning decisions.
- It makes the dashboard easier for non-technical users to understand.

Recruiter-focused insight:

The map improves storytelling by showing where climate risks are located, not just which countries have high values. This makes the dashboard more useful for decision-makers who need to prioritise resources by region.

### 4. Top 10 Countries with Highest Temperature

![Highest Temperature Treemap](screenshots/highest_temperature_treemap.png)

This treemap highlights the countries with the highest average temperatures. These countries may face stronger heat stress, higher evaporation, increased water demand, and greater pressure on temperature-sensitive crops.

Why this visual is useful:

- It quickly highlights high-temperature countries.
- It gives a compact view of top climate-risk areas.
- Colour helps communicate heat intensity.
- It complements the climate imbalance ranking and map.

Recruiter-focused insight:

This visual helps identify countries where heat exposure may be a major agricultural concern. When combined with rainfall analysis, it supports better understanding of drought and crop vulnerability risk.

### 5. Top 10 Countries with Lowest Temperature

![Lowest Temperature Treemap](screenshots/lowest_temperature_treemap.png)

This treemap shows countries with the lowest average temperatures. Cold-climate countries may face different agricultural challenges, such as shorter growing seasons, frost risk, and the need for cold-resistant crop varieties.

Why this visual is useful:

- It shows the opposite side of climate risk.
- It helps compare hot and cold climate countries.
- It supports a more balanced climate analysis.
- It shows that agricultural risk is not only caused by heat but also by extreme cold conditions.

Recruiter-focused insight:

Including both highest and lowest temperature countries makes the analysis more complete. It shows that the dashboard considers different types of agricultural climate risk rather than focusing only on heat.

## Key Insights

Based on the dashboard analysis, the following insights were identified:

1. Countries in arid and semi-arid regions show stronger climate imbalance because they experience high temperatures with relatively low rainfall.

2. Temperature alone does not fully explain agricultural risk. Some warm countries receive high rainfall, while others receive very little rainfall. This means precipitation must be analysed together with temperature.

3. Warm-dry regions are more likely to face drought stress, irrigation demand, soil moisture loss, and crop productivity challenges.

4. Warm-wet regions may face different risks, such as flooding, pest growth, crop disease, and drainage problems.

5. Cold-climate countries may experience shorter growing seasons and may require crop varieties that can tolerate lower temperatures.

6. Country-level climate indicators are useful for high-level screening, but more detailed regional and seasonal data would improve the accuracy of agricultural planning.

## Recommendations

Based on the dashboard findings, the following recommendations can support climate adaptation and agricultural planning:

- Prioritise irrigation investment in warm-dry regions.
- Promote drought-resistant crop varieties in countries with high climate imbalance.
- Improve water-harvesting and soil-moisture conservation practices.
- Use regional and seasonal climate data for more detailed planning.
- Combine climate indicators with crop yield, land use, and socio-economic data for stronger food-security risk analysis.
- Monitor high-risk countries regularly to identify changes in climate stress over time.

## Business / Policy Value

This dashboard can support:

- Policymakers identifying climate-risk hotspots
- Agricultural planners prioritising irrigation and adaptation strategies
- Researchers studying the relationship between climate and agriculture
- NGOs or development organisations planning food security interventions
- Data analysts demonstrating how visual analytics can support real-world decision-making

The project shows how Tableau can be used not only for reporting but also for analytical storytelling and decision support.

## Limitations

This dashboard uses country-level climate data, which may hide important differences within large countries. For example, one part of a country may be dry while another part may receive high rainfall.

Other limitations include:

- Annual averages may hide seasonal climate patterns.
- Country-level data may not capture local agricultural conditions.
- The temperature-to-precipitation ratio is a useful screening measure but does not fully represent crop-specific risk.
- Crop yield, soil type, irrigation access, and socio-economic indicators were not included in the current version.

## Future Improvements

Future improvements could include:

- Adding subnational or regional climate data
- Including seasonal temperature and rainfall patterns
- Adding crop-specific vulnerability indicators
- Integrating crop yield and food production data
- Creating multi-year climate trend analysis
- Adding interactive filters for region, income group, or crop type
- Publishing the dashboard on Tableau Public for easier online access

## Project Files

- `Climate_Agriculture_Tableau_Dashboard.twbx` - Tableau packaged workbook
- `Climate_Agriculture_Tableau_Report.pdf` - project report
- `screenshots/` - dashboard preview images

## How to View the Dashboard

To view the dashboard:

1. Download the `.twbx` file from this repository.
2. Open it using Tableau Desktop or Tableau Reader.
3. Explore the dashboard using filters, tooltips, and interactive visuals.

## Skills Demonstrated

- Tableau dashboard development
- Data visualisation and storytelling
- Climate data analysis
- Analytical thinking
- Dashboard layout design
- Insight generation
- Business and policy-oriented reporting
- Communication of technical findings to non-technical users

## Author

Sankar Mannem  
MSc Data Analytics  
Dublin, Ireland
