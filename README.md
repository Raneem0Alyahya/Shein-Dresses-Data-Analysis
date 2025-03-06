# Shein Dresses Data Analysis Project

## Overview
This project focuses on analyzing data related to the top-rated dresses from the popular online shop, Shein. The primary goal is to gather, clean, and analyze data to derive meaningful insights about the dresses, including their ratings, prices, discounts, materials, colors, and more. The data was collected using web scraping techniques with Selenium, and the analysis was performed using Python libraries such as Pandas, Seaborn, and Scikit-learn.

## Project Structure
The project is organized into several sections, each corresponding to a different stage of the data analysis process:

1. **Data Collection**: The data was collected from the Shein website using Selenium. The process involved navigating through the website, extracting URLs of the top-rated dresses, and then scraping detailed information from each product page.

2. **Data Cleaning and Preprocessing**: The raw data was cleaned and preprocessed to handle missing values, remove duplicates, and convert categorical data into numerical formats. This step also involved feature engineering and handling outliers.

3. **Exploratory Data Analysis (EDA)**: The cleaned data was analyzed to uncover patterns and trends. Visualizations were created using Seaborn to better understand the relationships between different variables.

4. **Machine Learning Models**: Various machine learning models were trained and evaluated to predict dress ratings based on other features. Models used include Linear Regression, Ridge Regression, and Gradient Boosting Regressor.

5. **Conclusion**: The final section summarizes the findings from the analysis and provides insights into the factors that influence dress ratings on Shein.

## Data Overview
The dataset contains information on 1215 top-rated dresses from Shein. Each dress is described by the following features:
- **Rating**: The average rating of the dress.
- **Final Price**: The final price of the dress after discounts.
- **Discount**: The discount percentage applied to the dress.
- **Number of Reviews**: The number of reviews the dress has received.
- **Material**: The material of the dress.
- **Color**: The color of the dress.
- **Brand**: The brand of the dress.

## Key Findings
- **Rating Distribution**: The majority of dresses have high ratings, with most ratings clustered around 4.9 to 5.0.
- **Price and Discount**: There is a weak negative correlation between the final price and the discount percentage. Higher discounts are often associated with lower final prices.
- **Material and Color**: The most common material is fabric, and the most common color is multicolor.
- **Brand Popularity**: The brand "SHEIN VCAY" has the highest number of dresses in the dataset.

## Machine Learning Models
Several machine learning models were trained to predict dress ratings:
- **Linear Regression**: Achieved an R² score of 0.02, indicating a poor fit.
- **Ridge Regression**: Slightly improved the R² score to 0.03.
- **Gradient Boosting Regressor**: Provided the best performance with an R² score of 0.08.

## Conclusion
The analysis revealed that while high ratings are common, there is no strong correlation between the rating and other features like price, discount, or material. The machine learning models did not perform well in predicting ratings, suggesting that other factors not included in the dataset may influence dress ratings.

## Future Work
- **Feature Engineering**: Explore additional features that could improve model performance, such as dress style or customer demographics.
- **Advanced Models**: Experiment with more advanced machine learning models or deep learning techniques.
- **Real-time Data**: Implement a system to collect and analyze real-time data from Shein to keep the insights up-to-date.

## Acknowledgments
- **Shein**: For providing the data.
- **Selenium**: For enabling web scraping.
- **Pandas, Seaborn, Scikit-learn**: For data analysis and machine learning.

---

Feel free to contribute to this project by submitting issues or pull requests. Your feedback and contributions are highly appreciated!
