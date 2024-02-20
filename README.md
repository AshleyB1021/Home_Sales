## Home Sales Data Analysis with SparkSQL

### Overview

In this project, SparkSQL is used to analyze home sales data to determine key metrics. The analysis includes creating temporary views, partitioning the data, caching and uncaching a temporary table, and verifying that the table has been uncached.

### Questions Answered

* Average Price for a Four-Bedroom House: Calculates the average price for a four-bedroom house sold for each year.
  
* Average Price of a Home for Each Year Built: Determines the average price of a home for each year it was built that has three bedrooms and three bathrooms.
  
* Average Price of a Home for Each Year with Specific Criteria: Calculates the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet.

* "View" Rating for Homes Over $350,000: Determines the "view" rating for homes costing more than or equal to $350,000, along with the run time for this query.

### Instructions

* Clone the repository to your local machine.
* Ensure you have Apache Spark installed and set up.
* Run the provided SparkSQL queries against the home sales data to get the required metrics.
* Review the results and analysis in the notebook.

### Dataset

The dataset used for this analysis contains information about home sales, including the number of bedrooms, bathrooms, floors, square footage, year built, view rating, and price.
