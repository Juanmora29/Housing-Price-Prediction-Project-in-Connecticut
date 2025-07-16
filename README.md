# Dataset Description

The selected dataset is "Real Estate Sales 2001–2022 GL".

* Link to download the CSV file: https://catalog.data.gov/dataset/real-estate-sales-2001-2018

* Link to download the Connecticut .geojson file (under "Download", then "GeoJSON"): https://deepmaps.ct.gov/datasets/CTDEEP::connecticut-state/explore?layer=1&location=41.484333%2C-72.649122%2C9.42

The Office of Policy and Management maintains a comprehensive record of all real estate transactions with a sale price of $2,000 or more occurring between October 1st and September 30th of each fiscal year. For each sales record, the dataset includes the following attributes: municipality, property address, sale date, property type (residential, apartment, commercial, industrial, or vacant land), sale price, and assessed property value.

The data is collected in accordance with the Connecticut General Statutes, Sections 10-261a and 10-261b:
https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261a
https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261b

This dataset is of particular interest as it enables the analysis of the real estate landscape in the State of Connecticut, serving as a reflection of broader trends in the United States during the first two decades of the 21st century.

## Variable Descriptions

* List Year: The year the property was listed.
* Date Recorded: The official date the property sale was recorded.
* Town: Municipality in which the property is located.
* Address: Street address of the property.
* Assessed Value: The value assigned to the property by the local government for taxation purposes.
* Sale Amount: Final sale price of the property.
* Sales Ratio: The percentage ratio between the assessed value and the final sale price.
* Property Type: Category of the property (e.g., residential, commercial, etc.).
* Residential Type: Indicates whether the property is a single-family or multi-family residence.
* Longitude: Geographic longitude coordinate of the property.
* Latitude: Geographic latitude coordinate of the property.
* Sale Year: Year in which the property sale was completed.
* Years on Market: Number of years the property remained listed before sale.

# Objectives

* Conduct an in-depth exploratory data analysis (EDA) to examine the behavior and dynamics of the real estate sector in the State of Connecticut over the 2001–2022 period.
* Develop a linear regression model to estimate property sale prices within Connecticut, using the variables Assessed Value, Sales Ratio, and Residential Type as predictors.
