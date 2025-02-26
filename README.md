# Coupon Acceptance Analysis

## Project Overview

This project explores the factors that influence whether drivers accept coupons delivered to their cell phones while driving. We analyzed survey data from the UCI Machine Learning repository, which includes various attributes such as user demographics, contextual factors (weather, time, destination), and coupon characteristics. 

This analysis is focused on distinguishing between drivers who accepted coupons and those who did not, with a special focus on specific coupon types.

## Problem Statement

**What factors determine coupon acceptance among drivers, and how do these factors differ for bar coupons compared to other types?**  
This analysis specifically investigates whether frequent bar-goers (especially those over 25) are more likely to accept bar coupons, and explores how additional factors such as passenger type, time of day, and weather conditions influence acceptance.

## Key Analyses

### 1. Overall Coupon Acceptance
- **Descriptive Statistics:** Calculated the overall coupon acceptance rate.
- **Visualization:** A bar plot was used to visualize the proportion of accepted versus rejected coupons.

### 2. Analysis of Bar Coupons
- **Focused Investigation:** Filtered the data to focus exclusively on bar coupons.
- **Comparative Analysis:** Acceptance rates were compared between drivers who visit bars frequently (more than 3 times per month) versus less frequently.
- Further analysis compared the acceptance rate for drivers over 25 who visit bars more than once a month against all other drivers.
- **Findings:** The results indicate that frequent bar-goers—especially those over 25—are more likely to accept bar coupons.
- **Actionable Recommendation:** Focus promotional efforts for bar coupons on drivers over 25 and frequent bar-goers.

### 3. Comparative Analysis Across Coupon Types
Using the bar coupon analysis as a model, we extended our investigation to other coupon groups such as Coffee House, Carry Out & Take Away, and Restaurant coupons.

For each coupon type, we explored:
### Passenger Type
- **Insight:** Visualizations reveal that customers traveling with a friend are significantly more inclined to accept a coupon.

### Time of Day
- **Insight:**  
  - **Restaurant ($20 - $50) and Coffee House Coupons:** More likely to be accepted earlier in the day, with acceptance rates tapering off late at night.
  - **Bar Coupons:** Tend to be accepted predominantly after 6 PM.
  - **Carry Out and Take Out Coupons:** See higher acceptance rates during the afternoon.

### Weather Conditions
- **Insight:** Although coupon acceptance is generally highest on sunny days, coffee house coupons display an opposite pattern with significantly higher acceptance on rainy days.


### Actionable Recommendation
- **Optimized Timing:**  
  Schedule coupon deliveries in alignment with the peak acceptance times—morning for Restaurant and Coffee House, afternoon for Carry Out/Take Away, and after 6 PM for Bar coupons.
- **Contextual Personalization:**  
  Use weather and passenger data to personalize coupon offers, such as promoting coffee house coupons on rainy days.

## Next Steps

- **Predictive Modeling:**  
  Develop machine learning models to forecast coupon acceptance based on user and contextual data.

## Conclusions

Our findings suggest that factors such as passenger type, age, and contextual conditions (time and weather) significantly impact coupon acceptance across different coupon groups.

## Repository Structure

- **`coupon_analysis.ipynb`**: The Jupyter Notebook containing the full exploratory data analysis, visualizations, and code.
- **`README.md`**: This file summarizing the project, key findings, and recommendations.

## How to Access the Notebook

You can view the complete analysis in the Jupyter Notebook available at the following link:  
[View the Jupyter Notebook on GitHub](https://github.com/AriAlas/ml-ai-coupon-data-analysis/blob/main/coupon_analysis.ipynb)
