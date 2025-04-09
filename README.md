# Apr2025_data_week22
Data Bootcamp Week Twenty Two Big Data
This project performs SQL queries on a home sales dataset using Apache Spark. The queries analyze average home prices based on various criteria such as the number of bedrooms, bathrooms, and view ratings.

Queries
Average Price per Year for 4-Bedroom Homes

Calculates the average price of 4-bedroom homes, grouped by year.

Average Price per Year for 3-Bedroom, 3-Bathroom Homes

Calculates the average price for 3-bedroom, 3-bathroom homes, grouped by the year the home was built.

Average Price for Large 3-Bedroom Homes

Calculates the average price for 3-bedroom, 3-bathroom homes with at least 2000 sqft and two floors.

Average Price per "View" Rating

Calculates the average price of homes based on the "view" rating, with a filter for homes priced above $350,000.

Performance Benchmarks
Uncached Query: Runs the query on the dataset without caching for comparison.

Cached Query: Caches the data to speed up the query on repeated runs.

Parquet Query: Reads the data from a Parquet file and performs the same analysis.