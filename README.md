# Fitness-Tracker-Analysis ⌚🏃🚴
This is Challenge Project from **DataDNA** Fitness Tracker Dataset Challenge from Pomerol Partners! 💪🏻

## About 🛈
* This is a fitness tracker product dataset consisting of different products from various brands with their specifications, ratings and reviews for the Indian market. 
* The data has been collected from e-commerce websites namely Flipkart and Amazon using web scraping technique.
* This dataset contains 451 samples with 16 attributes. There are some missing values in this dataset.

## Objective 🎯
* Is there a significant demand for fitness trackers in the Indian market?
* Information on the top 5 brands for fitness bands and smart watches
* Is there a correlation between the prices and product specifications, ratings, etc.
* Different types of fitness trackers, their price segments for different users

## Dataset Columns and Descriptions 📝

| Column Name           | Description                                          |
|------------------------|------------------------------------------------------|
| **Index**             | The row index number. *(Integer)*                    |
| **Brand**             | The fitness tracker brand. *(String)*                |
| **Current Price**     | The price at the time of scraping. *(Integer)*        |
| **Original Price**    | The price at the time of launch. *(Integer)*          |
| **Discount Percentage** | The discount as of now. *(Integer)*                |
| **Rating**            | The product rating. *(String)*                       |
| **Number of Ratings** | The number of ratings given by the customers. *(Integer)* |
| **Model Name**        | The model name under the brand. *(String)*           |
| **Dial Shape**        | The dial shape of the product. *(String)*            |
| **Strap Color**       | The strap color of the product. *(String)*           |

## Insights 💡🧐🤔

### Report 1: Is there a significant demand for fitness trackers in the Indian market?

1. Total Sale Price by Brand:

* Brands like Noise, Samsung, and Pebble lead in total sales, indicating strong demand.
* Premium brands like Garmin and Fossil contribute less to sales due to higher pricing.

2. Average Ratings Across Brands:

* Top-rated brands include Garmin (4.44) and Apple (4.55), showing customer satisfaction.
* Lower ratings for budget brands like Fire-Boltt and Hammer suggest compromises on quality.

3. Total Ratings:

* Brands like Noise and Pebble have high customer engagement (ratings), showing popularity in the budget segment.


### Report 2: Information on the top brands for fitness trackers

1. Brand Analysis:

* Apple, Garmin, and Samsung have high ratings (4.2+), appealing to premium customers.
* Noise dominates the budget segment with the highest number of ratings, suggesting affordability drives sales.

2. Discount Trends:

* High discounts on brands like Noise and Pebble make them attractive to price-sensitive customers.
* Premium brands like Garmin have minimal discounts, targeting niche markets.

3. Price vs. Rating Comparison:

* Ratings remain consistent across price ranges, implying customers prioritize quality over cost in certain segments.


### Report 3: Correlation between prices, product specifications, and ratings

1. Price vs. Ratings:

* Premium brands like Garmin maintain high ratings despite high prices, indicating perceived value.
* Budget brands show mixed ratings, highlighting variability in quality.

2. Number of Ratings vs. Price:

* Budget-friendly brands such as Noise and Pebble garner significantly higher engagement.

3. Current Price Segmentation:

* Clear segmentation shows three distinct groups: High (>₹20K), Mid (₹10K-₹20K), and Low (<₹10K), catering to diverse audiences.


### Report 4: Different types of fitness trackers and price segmentation

1. Price Segment Distribution:

* Low-segment trackers dominate the market, driven by brands like Noise and Boat.
* Mid and high-segment trackers, led by Samsung and Garmin, cater to fitness enthusiasts and premium buyers.

2. Brand-Specific Pricing:

* Premium brands have higher average prices, e.g., Garmin (₹25K), reflecting advanced features and build quality.
* Budget brands, like Zebronics, keep prices around ₹3K-₹5K, appealing to the mass market.

3. Sale Price vs. Ratings:

* Higher-priced trackers generally maintain better ratings, showcasing a price-quality relationship.
