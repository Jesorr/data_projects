# Advanced Spreadsheets: Vacation Rental Market Analysis

## Project Overview
This project involved analyzing the vacation rental market in Manhattan, New York City, to assist a client in making informed investment decisions. Using data from Airbnb listings, the objective was to identify the most promising types of properties for investment by analyzing rental activity, neighborhood popularity, property sizes, and estimated revenue.

## Goals and Objectives
- **Explore and Filter Data**: Understand the dataset, identify and clean relevant data.
- **Target Property Types**: Analyze neighborhoods and property sizes to recommend optimal investment properties.
- **Calculate Occupancy**: Determine average occupancy rates to estimate rental activity.
- **Estimate Revenue**: Calculate potential annual revenue for recommended investment properties.

## Skills Demonstrated
- **Data Cleaning and Preparation**: Ensured data accuracy by handling inconsistencies and missing values.
- **Data Analysis**: Used pivot tables and other advanced spreadsheet techniques to derive insights.
- **Data Visualization**: Created charts to visualize occupancy rates and other key metrics.
- **Documentation**: Maintained a detailed log of data cleaning steps and assumptions.

## Project Steps

### Part 1: Explore and Filter the Data
1. **Data Review**:
   - Downloaded and familiarized with the dataset: `data_dictionary`, `listings`, and `calendar` sheets.
2. **Data Preparation**:
   - Added documentation tabs for data cleaning history.
   - Organized the spreadsheet by freezing rows/columns, resizing columns, wrapping text, and adding filters.
3. **Data Filtering**:
   - Created a reference copy of raw data.
   - Filtered out listings not relevant to vacation rentals (e.g., minimum night requirement over 7 days, inactive listings).

### Part 2: Target Property Types
1. **Rental Activity Estimation**:
   - Used `number_of_reviews_ltm` as a proxy for rental frequency.
2. **Neighborhood Analysis**:
   - Cleaned neighborhood data and created a `neighborhood_clean` column.
   - Built pivot tables to identify top 10 neighborhoods by reviews.
3. **Property Size Analysis**:
   - Cleaned `bedrooms` data, substituting empty cells with zeros.
   - Built pivot tables to determine popular property sizes and neighborhood preferences.

### Part 3: Calculate Occupancy
1. **Data Preparation for Occupancy**:
   - Converted `available` column to a numeric `occupied` column.
   - Added a `day_of_week` column using the `WEEKDAY()` function.
2. **Occupancy Calculation**:
   - Created pivot tables to calculate average occupancy rates for each listing.
   - Analyzed occupancy by day of the week and visualized the data with bar charts.

### Part 4: Estimate Revenue for Investment Properties
1. **Filtering Representative Properties**:
   - Focused on high-review, actively rented properties.
2. **Adding Occupancy Rates**:
   - Used `VLOOKUP()` to add average occupancy rates to the listings sheet.
3. **Revenue Calculation**:
   - Built pivot tables to determine average price and occupancy for selected neighborhoods and property sizes.
   - Estimated annual revenue using the formula: `Annual Revenue = 365 days * Average Price * Occupancy Rate`.

## Key Accomplishments
- Successfully cleaned and organized a large dataset for analysis.
- Identified top neighborhoods and property sizes for vacation rental investment.
- Calculated occupancy rates and estimated potential revenue for recommended properties.
- Demonstrated proficiency in advanced spreadsheet techniques and data analysis.

## Conclusion
This project showcases my ability to handle complex data analysis tasks, from data cleaning and preparation to detailed analysis and visualization. The insights derived from this project can guide investors in making informed decisions about vacation rental properties in Manhattan.

Feel free to explore the project files and reach out if you have any questions!

#### Links to project files
- [Project Spreadsheet](https://docs.google.com/spreadsheets/d/1biYIxQTHJh9wqWgubNoor4HyoP3f3hOuyf0909XH2As/edit?usp=sharing)
- [Executive Summary](./Project1/Executive Summary.pdf)

