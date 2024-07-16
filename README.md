# Housing Price Data Analysis

## Project Overview

This project focuses on analyzing housing price data, particularly resale flat transactions in Singapore. It combines data analysis, visualization, and machine learning techniques to extract insights from the dataset and explore factors influencing resale prices.

## Objectives

- Understand and analyze the dataset with a data scientist's mindset
- Design and implement computational logic and routines in Python
- Perform data extraction, loading, and transformation operations using Python and Pandas
- Structure code using appropriate methods, loops, and conditions
- Conduct meaningful data visualizations
- Utilize database ORM and SQLite methods for data operations

## Libraries and Technologies Used

This project leverages several Python libraries for data manipulation, analysis, visualization, and machine learning:

- Pandas (for data manipulation and analysis)
- Matplotlib (for data visualization)
- Geopandas and Contextily (for geographical data handling and visualization)
- Scikit-learn (for machine learning tasks)
  - KMeans clustering
  - StandardScaler
  - haversine_distances
- SQLite3 and SQLAlchemy (for database operations)
- Geopy - GoogleV3 (for geocoding)

## Key Features

1. Data Loading and Preprocessing
   - Merging multiple CSV files
   - Handling null values and data type conversions

2. Exploratory Data Analysis
   - Time series analysis of transaction dates
   - Analysis of storey levels and floor areas
   - Standardization of flat models and types

3. Price Analysis
   - Distribution analysis of resale prices
   - Identification of factors influencing resale prices

4. Geographical Visualizations & Analysis
   - Visualization of MRT exits using Geopandas
   - Clustering of MRT exits using KMeans
   - Mapping MRT exits to Singapore regions

5. Distance Calculations
   - Geocoding of flat addresses
   - Calculation of distances to nearest MRT exits
   - Analysis of relationship between price and distance to CBD

6. Advanced Visualizations
   - Scatter plots incorporating multiple dimensions (price, distance, year, region)

7. Database Operations
   - Use of SQLite and SQLAlchemy for data querying and analysis

## Data Sources

- Resale flat transaction data
- MRT exit location data (from Singapore's open data portal)
- Address and region mapping data

## How to Use

1. Ensure all required libraries are installed
2. Download the project files and datasets
3. Run the Jupyter Notebook to execute the analyses

## Key Insights

1. Transaction Trends:
   - Sharp increase in resale flat transactions from 1990 to 1998, followed by a decline until 2013.
   - Increase in transactions from 2013 to 2023.
   - Possible influence of market recessions in 1998 and 2008 on transaction volumes.
   - Unexpected spike in transactions around 2010-2011, possibly due to large-scale real estate corporation activities.

2. Resale Price Trends:
   - Overall increase in resale prices over the years, attributed to housing market appreciation and inflation.
   - Positive correlation between resale price and floor size, reflecting the per square foot/meter pricing model.
   - Higher resale prices for properties with more recent lease commencement dates, due to longer remaining tenure.
   - Positive correlation between resale price and storey level, with buyers valuing higher floors for various reasons (air quality, noise, etc.).
   - Seasonal trends: Highest prices in May, lowest in February, possibly influenced by factors like bonuses, weather, and school schedules.

3. Geographical and Temporal Analysis:
   - Properties closer to the Central Business District (CBD) generally command higher prices due to prime amenities and workplace proximity.
   - 2023 shows the highest selling prices, while 2020 exhibits the widest price range.
   - 2015 prices fall within a smaller range compared to 2020, possibly due to cooling measures introduced in 2013.
   - North-East region properties, despite being further from CBD than East region, often sell for higher prices, possibly due to attractive amenities.
   - Interestingly, some properties 15km from CBD (e.g., in Punggol) sell for higher prices than those 10km away (e.g., Hougang, Ang Mo Kio), likely due to newer developments and advanced amenities in areas like Punggol.

These insights reveal complex interplays between location, time, government policies, and amenities in determining resale flat prices in Singapore. They highlight the importance of considering multiple factors when analyzing housing market trends.
