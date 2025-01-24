# New York Airbnb Listings EDA (2024)
## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of New York Airbnb data to identify trends and patterns in rental listings. Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, we cleaned, visualized, and analyzed the dataset to uncover actionable insights.

## Objective
The primary goals of this project include:
* Analyzing room types, prices, and availability across different neighborhoods.
* Understanding host behavior and listing patterns.
* Detecting outliers in price data.
* Providing actionable recommendations for both guests and hosts.

## Dataset Details
The dataset consists of 20,765 entries and 22 features, including:
* id: Unique identifier for each listing.
* name: Title of the Airbnb listing.
* host_name: Name of the host.
* neighborhood_group: Borough where the listing is located.
* latitude/longitude: Geolocation of the listing.
* price: Nightly rental price.
* room_type: Type of accommodation (e.g., entire home, private room).
* reviews_per_month: Average monthly reviews for the listing.
* availability_365: Number of available days in the year.

## Workflow and Steps

### Data Cleaning
* Handled missing values in price, neighborhood, and beds columns.
* Converted last_review to a datetime object for accurate analysis.
* Capped outlier prices above $1,000 to improve visualization and analysis.

### Exploratory Data Analysis (EDA)
* Room Type Distribution: Visualized room type counts and identified that Entire home/apt is the most common.
* Neighborhood Insights: Analyzed price variations by borough, with Manhattan having the highest average prices.
* Availability Trends: Explored correlations among price, availability_365, and reviews.
* Price Distribution: Highlighted most listings priced between $50 and $300.
* Host Listings: Examined host behavior, especially those managing multiple listings.
* Review Behavior: Analyzed relationships between reviews, availability, and price.

### Data Visualization
* Heatmaps: To explore correlations between numerical features.
* Histograms & Boxplots: To study price distribution and detect outliers.
* Bar Charts: For room type and neighborhood distributions.
* Pairplots: To visualize relationships among key variables.

## Key Findings and Insights

### Price Trends:
* Manhattan has the most expensive listings, while Brooklyn offers more budget-friendly options.
* Entire homes/apartments are significantly pricier compared to private or shared rooms.

### Room Type Distribution:
* Entire homes/apartments dominate the market, though private rooms provide affordable alternatives.
  
### Availability Patterns:
* Listings with high availability often have lower prices and better reviews.

### Host Behavior:
* Some hosts manage multiple listings, showcasing the rise of professional hosting.

## Recommendations

### For Guests:
* Choose listings with high availability and positive reviews for a better experience.
* Consider private rooms in Brooklyn for affordable stays compared to Manhattan.

### For Hosts:
* Improve availability and responsiveness to attract more bookings.
* Optimize pricing to remain competitive within the local market.





  
