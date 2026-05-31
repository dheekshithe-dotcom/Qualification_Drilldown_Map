# Qualification_Drilldown_Map
 Project Overview

This project is an interactive Tableau map visualization that displays job postings across African countries based on specific qualification, salary, company size, and recruitment criteria. The dashboard uses latitude and longitude coordinates to map job locations and allows users to explore hiring opportunities geographically.


Objective

To create a map-based visualization showing job postings that meet specific hiring conditions and provide location-level insights using drilldown functionality.


 Filters Applied

* Qualification = B.Tech, M.Tech, PhD
* Work Type = Full-Time
* Job Title starts with the letter "D"
* Preference = Male
* Company Size > 80,000
* Salary > 20,000
* Contact Person name starts with "A"
* Job Portal = Indeed
* African countries only
* Time-based visibility between 3 PM and 6 PM IST, When published to Tableau Public, time-based calculations may behave differently due to server time zone settings and UTC-based processing.


 Visualization

Chart Type: Symbol Map

Mapping Fields

* Latitude
* Longitude

 Marks Used

* Color: Country
* Detail: Location
* Tooltip: Job Title, Salary, Company Size, Country, Latitude, Longitude



 Drilldown Functionality

The visualization enables users to explore exact job locations by interacting with map points. Hovering over a location displays detailed information including job title, salary, company size, and geographic coordinates.


 Tools Used

* Tableau Public
* CSV Dataset
* Geographic Mapping
* Calculated Fields
* Filters and Aggregations


Key Insights

* Large organizations with more than 80,000 employees dominate hiring activity.
* Data-related and technology-focused job roles are widely distributed across African countries.
* Salary and company size filters help identify high-value employment opportunities.
* Geographic visualization makes it easier to compare hiring activity across multiple regions.


Dataset Source

The dataset used in this project is a self-created CSV dataset prepared for educational and analytical purposes.


Project Purpose

The purpose of this project is to demonstrate geographic data visualization, filtering techniques, drilldown functionality, and map-based analysis using Tableau.


Author

Dheekshith Eggidi
