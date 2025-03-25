Airline Flights Status  Dashboard - Power BI Project
This project presents a comprehensive Power BI dashboard that visualizes key insights into U.S. airlines flight operations, focusing on flight status, delays, and cancellations, airpoarts. The goal was to transform raw flight data into meaningful and interactive visualizations that facilitate quick and informed decision-making.

📁 Dataset Overview
The main dataset (flights.csv) contains over 2 million flight records, making it a large-scale real-world dataset suitable for building a robust and insightful dashboard. The data covers commercial flights across the United States, including details such as:

Flight date and number 
Airline code (Carrier)
Origin and destination airport codes
Scheduled and actual departure/arrival times
Arrival and departure delays (in minutes)
Cancellation indicator and reason
Air time, distance, and more

Supporting Datasets:
airlines.csv – Maps airline codes to their full names.
airports.csv – Provides geographic and identifying information about U.S. airports.
cancellation_codes.csv – Explains the codes for flight cancellations (e.g., weather, security, carrier-related).

Project Highlights
1- Data Size:
Processed and analyzed over 2 million observations from the flight dataset to uncover meaningful trends and KPIs.

2- Data Cleaning & Preparation:

Addressed missing values and filtered irrelevant rows and columns.

Selected key variables to ensure consistency and relevance.

Removed duplicates and ensured data types were appropriately set.

3- Feature Engineering:

Created a new Flight Status column to categorize flights as:

On-Time

Delayed

Cancelled

Built custom metrics and KPIs using DAX:

% of Flights Delayed

% of Flights Cancelled

% of On-Time Flights

4- Data Modeling:

Linked the three data tables through Power BI’s data model:

Joined flights.csv with airlines.csv using the Carrier field

Mapped Origin and Dest to airports.csv for geographical insights

Enriched cancellation data using cancellation_codes.csv

5- Dashboard Development:

Developed an interactive Power BI dashboard with:

KPIs and card visuals

Bar charts, maps, and slicers for filtering by airline, airport, and date

Visual summaries of flight delays and cancellation reasons

🧰 Tools & Technologies
Power BI Desktop

Data Modeling & DAX

Interactive Visualizations

Custom Measures and Calculated Columns

✅ Key Takeaways
This project demonstrates the follwing  skills:

Clean and process large datasets

Engineer features and KPIs for analysis

Build interactive and insightful dashboards

Use DAX for advanced calculations

Apply sound data modeling principles in Power BI

