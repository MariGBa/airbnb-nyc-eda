# Airbnb NYC Pricing Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on 47,660 Airbnb listings in New York City to understand pricing patterns, location influence, and host behavior.

The objective is to extract actionable insights that influence listing price and availability.

---

## Dataset

- **Source:** AB_NYC_2019 dataset  
- **Records analyzed:** 47,660 listings  
- **Features used after cleaning:** 12  

### Key Columns

- neighbourhood_group  
- neighbourhood  
- room_type  
- price  
- minimum_nights  
- number_of_reviews  
- reviews_per_month  
- calculated_host_listings_count  
- availability_365  

---

## Data Cleaning Steps

- Handled missing values in `reviews_per_month`  
- Removed unnecessary columns (`id`, `name`, `host_name`, `last_review`)  
- Verified data types and summary statistics  
- Checked for outliers in `price`  

---

## Key Insights

- Manhattan listings are significantly more expensive compared to other boroughs  
- Entire homes/apartments are priced substantially higher than private rooms  
- The price distribution is right-skewed with extreme high-value outliers  
- Weak correlation between price and number of reviews  
- Slight negative correlation between longitude and price (~ -0.3)  

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## Visualizations

- Price distribution histogram  
- Price vs Room Type analysis  
- Price vs Neighbourhood Group comparison  
- Correlation heatmap  
- Price vs Number of Reviews scatter plot  

---

## Conclusion

Location and room type are the strongest drivers of Airbnb pricing in NYC. Review count and host listing count have minimal direct impact on price.
