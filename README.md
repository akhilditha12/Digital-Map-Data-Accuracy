Improving Digital Map Data Accuracy using OpenStreetMap and Python

Objective:
Enhance the accuracy of digital maps by comparing official hospital location data with OpenStreetMap data to identify missing or inconsistent entries.

Tools Used:

Python
Pandas
GeoPandas
Folium (for map visualization)
OpenStreetMap (data source)

Workflow:

Extracted hospital data from OpenStreetMap for a selected city

Created a small official dataset for comparison

Verified and matched hospitals between datasets

Identified missing or inconsistent map entries

Visualized all hospitals on an interactive map

Results:

Matched Hospitals: Found in both datasets

Unmatched Hospitals: Missing in OSM → flagged for improvement

Interactive visualization available in map.html

Files in This Repository

File	Description
map.html	Interactive map showing hospital locations
report.md	Summary of findings
matches.csv	Verified matched hospitals
unmatched_official.csv	Missing or inconsistent hospitals

Author:
Akhilditha Bachala
Data Analyst | Python | SQL | Data Visualization
