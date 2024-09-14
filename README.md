# DMRC-Analysis
Metro Network &amp; Geospatial Analysis

Project Overview
This project is focused on the geospatial and network analysis of the Delhi Metro system. We utilized DMRC Static Data from the Open Transit Data platform to analyze metro routes, stops, trips, and schedules. The primary goal was to visualize geographical paths, analyze trip patterns, and provide insights into route efficiency based on spatial data.

Data Sources
The project is based on General Transit Feed Specification (GTFS) data, provided by the Delhi Metro Rail Corporation (DMRC) via the Open Transit Data platform. The key datasets used include:

- Agency
- Calendar
- Routes
- Shapes
- Stop times
- Stops
- Trips

Tools & Libraries
Python (Pandas, Matplotlib, Seaborn, Plotly, Folium)
Google Colab

Key Accomplishments
Geographical Path Analysis: We plotted the geographical distribution of Delhi Metro routes using latitude and longitude data from the shapes file. This provided a clear visualization of different routes and their spatial spread.

Stop Distribution Visualization: Using scatter plots, we showcased the spatial distribution of metro stops. This helped in understanding the density of stops in different areas of Delhi.

Route Efficiency Analysis: We calculated the number of unique routes passing through each stop and plotted the number of routes per metro stop. Stops with a higher number of routes indicate critical transfer points in the network.

Trip Frequency Analysis: By analyzing the stop_times and trips data, we calculated the intervals between trips at each stop and determined peak times for the metro service.

Adjusted Trip Frequencies: Based on hypothetical adjustments, we modeled different peak and off-peak hour scenarios to analyze how changes in frequency would affect the number of trips at different times of the day.

Quantitative Results
- Route Distribution: We identified key transfer stops where multiple routes intersect.
- Average Trip Interval: On average, trips during peak hours have intervals of X minutes, while non-peak hours saw intervals of Y minutes.
- Hypothetical Scenario: After adjusting for peak hours (20% increase in trips during peak hours and 10% decrease in off-peak hours), we observed a Z% improvement in passenger throughput during peak hours.

Visualizations
- Geographical Distribution of Delhi Metro Routes: A scatter plot that visualizes the geographical paths based on the shapes data.
- Number of Trips per Time Interval: A bar plot comparing original and adjusted trip counts for different times of the day.
- Number of Routes per Metro Stop: A scatter plot showing stops with varying numbers of intersecting routes.

Discoveries
- Peak Hour Demand: The analysis revealed that the morning and evening peak hours have significantly more trips than other times, indicating potential overcrowding during those periods.
- Spatial Distribution: Some areas have a higher concentration of metro stops and routes, which might indicate better connectivity. However, certain regions with fewer routes could benefit from better service coverage.
- Efficiency Gains: Adjusting trip frequencies during peak hours showed that increasing services by 20% during peak hours could significantly reduce waiting times and crowding.

License
This project is licensed under the MIT License - see the LICENSE section for details.
