# Airline Delay Analysis

An exploratory data analysis of U.S. domestic flights using Python, Pandas, and Matplotlib to investigate flight delays and identify patterns across airlines, airports, and departure times.

## Project Objectives

- Explore how departure delays vary by time of day and day of the week.
- Compare delay patterns across airlines and origin airports.
- Examine the relationship between flight distance and delays.
- Investigate recorded delay causes among severely delayed flights.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis Process

The project includes data quality checks, filtering, feature creation, grouping and aggregation, and visualization. Cancelled flights were excluded from the main departure-delay analysis.

Departure delays were classified using these thresholds:
- **Delayed:** departure delay of at least 15 minutes.
- **Severely delayed:** departure delay of at least 60 minutes.

## Key Findings

- Evening flights had a higher departure-delay rate than morning flights in the analyzed sample.
- Late-aircraft delays were recorded more frequently later in the day.
- The increase in delay rates from morning to evening varied across airlines.
- Mean and median delays sometimes differed substantially, highlighting the influence of unusually long delays.

These findings describe patterns in the analyzed sample and do not establish causation.

## View the Analysis

[Open the full Jupyter Notebook](Flight_Analysis_2024.ipynb) to explore the code, charts, and detailed conclusions.

## Author

Shelli Bandilovski
