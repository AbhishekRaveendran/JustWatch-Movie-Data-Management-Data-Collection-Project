# Airbnb Bookings Analysis | NYC Listings EDA

## Project Type
Exploratory Data Analysis (EDA)

## Author
**Abhishek Raveendran c t**

---

## Project Summary

### Objective
To leverage data analysis of approximately 49,000 Airbnb listings in New York City to optimize host performance and enhance customer satisfaction, thereby increasing overall platform revenue and market competitiveness.

### Dataset
The dataset contains 49,000 listings with 16 columns, including:
- Numeric variables: `price`, `minimum_nights`, `number_of_reviews`, `reviews_per_month`, `availability_365`, `calculated_host_listings_count`
- Categorical variables: `neighbourhood_group`, `neighbourhood`, `room_type`, `last_review`

### Approach
- Conducted **Exploratory Data Analysis** using 15+ visualizations, including bar charts, scatter plots, heatmaps, and pair plots.
- Explored relationships between key variables like price, location, room type, reviews, and availability.

---

## Key Insights
- Manhattan listings have the highest average prices (~$200/night), while Queens and Bronx are cheaper (~$80/night).
- Entire homes are the priciest and most popular room type.
- Brooklyn and Manhattan (especially Williamsburg) dominate listings; Staten Island is underserved.
- Higher-priced listings tend to have fewer reviews and higher availability, indicating possible overpricing or low demand.
- Seasonal trends show peak reviews during summer months.
- Listings with longer minimum stays generally have lower prices.

---

## Business Solutions & Impact

- **Dynamic Pricing Tools:** Suggest optimal rates by location and room type to maximize earnings.
- **Review Enhancement:** Encourage guest reviews to improve listing trustworthiness.
- **Targeted Marketing:** Promote high-demand neighborhoods and incentivize hosts in underserved areas.
- **Availability Optimization:** Adjust pricing and minimum stay policies to reduce vacancies.
- **Personalized Recommendations:** Improve guest experience with tailored suggestions.
- **Seasonal/Niche Offerings:** Introduce bundles and budget options to capture new market segments.

These solutions aim to:
- Empower hosts to increase revenue and occupancy.
- Enhance guest satisfaction and loyalty.
- Boost Airbnb’s competitiveness and market reach in NYC.

---

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Problem Statement
Since 2008, Airbnb has revolutionized travel with unique, personalized stays worldwide. Analyzing Airbnb’s extensive NYC dataset (~49,000 listings) helps understand customer and host behavior, improve platform security, and guide business and marketing strategies. This project explores and analyzes this dataset to extract actionable insights.

---

## General Guidelines Followed
- Well-structured, clean, and commented code.
- Exception handling and production-grade code practices.
- Deployment-ready notebook executable without errors.
- Each visualization is accompanied by:
  - Reason for chart choice
  - Insights found
  - Business impact and implications (positive or negative)
- Created 20+ logical and meaningful charts following the **UBM rule**:
  - **U**nivariate Analysis
  - **B**ivariate Analysis (Numerical-Categorical, Numerical-Numerical, Categorical-Categorical)
  - **M**ultivariate Analysis

---
