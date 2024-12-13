# Car Resale Data Analysis

## Project Overview
This project focuses on analyzing and visualizing car resale data to uncover meaningful patterns and insights. The dataset contains information about car make, model, year, body type, odometer readings, selling price, and more. The goal was to clean the data, explore its structure, and create visualizations to support key insights.

## Dataset Description

The dataset used in this project contains the following columns:

- **year**: The manufacturing year of the car.  
- **make**: The brand of the car (e.g., Toyota, Ford).  
- **model**: The specific model of the car.  
- **trim**: The variant of the model (e.g., Sport, Luxury).  
- **body**: The body style of the car (e.g., Sedan, SUV, Coupe).  
- **transmission**: The type of transmission (e.g., Automatic, Manual).  
- **vin**: The Vehicle Identification Number, a unique identifier for the car.  
- **state**: The state where the car is being sold.  
- **condition**: The overall condition of the car.  
- **odometer**: The number of miles the car has been driven.  
- **color**: The color of the car.  
- **interior**: The color and type of the car's interior.  
- **seller**: The name or type of the seller (e.g., Dealer, Private).  
- **mmr**: The Manheim Market Report price, which is an industry standard for the estimated wholesale price of the car.  
- **sellingprice**: The price at which the car was sold.  
- **saledate**: The date when the car was sold.

## Features and Analysis
1. **Data Cleaning:**
   - Removed special characters from seller names.
   - Replaced missing values with appropriate defaults (e.g., median for numerical data and "Unknown" for text-based columns).
   - Standardized car makes by consolidating similar or alternative names (e.g., "VW" to "VOLKSWAGEN").

2. **Key Visualizations:**
   - **Year-wise Distribution:**
     - Line chart to display the number of cars manufactured each year.
   - **Top 10 Car Brands:**
     - Bar chart showcasing the top 10 most frequent car brands in the dataset.
   - **Price Distribution:**
     - Histogram to illustrate the distribution of selling prices, capped at $50,000.
   - **Maximum Prices by Brand:**
     - Bar chart showing the highest selling price for each car brand.
   - **Body Type Distribution:**
     - Bar chart visualizing the frequency of different car body types.
   - **Correlation Between Odometer and Selling Price:**
     - Scatter plot highlighting the relationship between odometer readings and selling prices.
   - **Top 10 Sellers:**
     - Pie chart displaying the percentage share of top 10 sellers in the dataset.
   - **Box Plot for Selling Price:**
     - Box plot representing the distribution of selling prices for a sample of 1,000 cars.
   - **Correlation Heatmap:**
     - Heatmap to explore correlations among numerical variables, such as year, odometer, condition, and selling price.

## Tools and Technologies
- **Python Libraries:**
  - `pandas` for data manipulation and cleaning.
  - `matplotlib` for data visualization.
- **Development Environment:** Google Colab.



## Insights Gained
- Identified the most popular car brands and body types.
- Explored the selling price trends and their relationship with other factors like odometer readings and car condition.
- Visualized the market share of top sellers in the dataset.

## Future Improvements
- Enhance the dataset with additional features such as location and demand to improve analysis depth.
- Implement machine learning models to predict car resale prices.
- Automate reporting and visualization using dashboards.


