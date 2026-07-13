# Indian Aviation to Rail Transition Analysis

## About This Project
This Power BI dashboard analyzes domestic aviation traffic across India to identify strategic opportunities for launching new railway services. By evaluating flight routes (Origin-Destination pairs) and passenger volumes, the dashboard calculates an **Opportunity Score** to rank flight routes and show exactly where a train service alternative makes the most sense.

[Link to Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZThjNjA5YWEtYzZkYS00YTVjLTg3OGQtMjY1ZjNkZWMwYWM2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Key Performance Indicators (KPIs)
* **Total Air Passengers:** 371.94M
* **Passengers Under 500 KM:** 77.10M
* **Share Within Rail Range:** 20.73%
* **Analyzed OD Pairs:** 2.327K
* **Average Distance:** 899.61 KM

## Visual Insights Included
* **Geographical Passenger Distribution:** An interactive bubble map visualizing total air passengers originating from various Indian cities.
* **Distance Slab Analysis:** A bar chart breaking down passenger volumes by specific distance intervals (e.g., 0-100km, 101-200km) to highlight the dominance of short-haul flights.
* **Route Opportunity Ranking:** A detailed matrix evaluating specific routes (like Mumbai-Delhi or Bengaluru-Delhi) based on distance, average monthly passengers, and the custom Opportunity Score.
* **Cumulative Growth Trends:** A line chart tracking cumulative air passenger growth by month across 2024, 2025, and 2026.

## Tools & Data
* **Platform:** Microsoft Power BI
* **Data Sources:** Custom relational data models including `Aviation_Data` and `aviation_distance_data`, spanning from January 2024 to March 2026. 

## How to View the Dashboard
GitHub does not natively render `.pbix` files in the browser. To interact with this dashboard:
1. Download the `aviation.pbix` file from this repository.
2. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Free).
3. Open the downloaded file using Power BI Desktop.

## Author
**Tanvi Umang Patil**
