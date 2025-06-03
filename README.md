Airbnb Market Analysis Dashboard – Price & Revenue Trends
This repository showcases a Tableau dashboard that analyzes Airbnb listing data to uncover pricing patterns and revenue trends across ZIP codes and bedroom counts.

Project Objective
To build an interactive dashboard in Tableau Public that helps users visualize:

Average prices by number of bedrooms

Price distribution across ZIP codes

Annual revenue trends over time

Listings by distinct count of bedrooms

Dataset Used
listings.csv: Contains property-level information such as ID, name, bedroom count, price, location (ZIP code), etc.

calendar.csv: Contains daily price data and availability for each listing, used for calculating revenue.

Dashboard Overview
1. Price Per Bedroom
Visual: Bar chart

Description: Shows average price for properties with 1 to 6 bedrooms.

2. Listings by Number of Bedrooms
Visual: Text table

Description: Displays count of listings per bedroom type.

3. Price Per ZIP Code
Visuals: Choropleth map and bar chart

Description: Price variation based on ZIP code.

4. Annual Revenue Trend
Visual: Line graph

Description: Estimated total revenue over time using calendar data.

Step-by-Step Process
🔹 Step 1: Data Collection & Preparation
Downloaded listings.csv and calendar.csv.

Cleaned data in Excel (removed nulls, reformatted dates and prices).

🔹 Step 2: Importing Data into Tableau
Connected both CSV files as data sources.

Created a join between listings and calendar based on listing ID in the logical layer of data modelling section.

🔹 Step 3: Data Modeling
Extracted ZIP codes, price, date, and bedroom count.

🔹 Step 4: Dashboard Creation
Built sheets:

Price by Bedrooms

Listings by Bedrooms

Map of Price by ZIP Code

Revenue over Time

Combined them into a single dashboard layout.

🔹 Step 5: Formatting & Publishing
Added interactive filters and tooltips.

Formatted fonts, labels, and layout for better UX.

Published to Tableau Public .



