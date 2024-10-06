# Showtime OTT Viewership Prediction

## Project Overview

This is a data science project aimed at building a predictive model for first-day content viewership on an Over-The-Top (OTT) platform, ShowTime. Conducted as part of my Predictive Modeling module in the Postgraduate Program in Data Science and Business Analytics at the University of Texas at Austin, this project explores various factors influencing content viewership, including trailer views, major sports events, and seasonal trends.

## Objective

The objective of this project is to identify the key driver variables that impact first-day content viewership. With the increasing competition in the OTT space, understanding these factors will help Showtime improve audience engagement and optimize its content release strategies. 

Key considerations include:
- Visitor trends to the platform
- Marketing spend on advertising campaigns
- Timing of content releases, including potential clashes with major events
- Day of the week and seasonal influences on viewership

## Data Description

The dataset used for analysis contains the following columns:

| **Column Name**         | **Description**                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------------|
| **visitors**            | Average number of visitors (in millions) to the platform in the past week.                       |
| **ad_impressions**      | Number of ad impressions (in millions) across all ad campaigns for the content (both running and completed). |
| **major_sports_event**  | Indicator of any major sports event occurring on the release day.                                 |
| **genre**               | Genre of the content (e.g., drama, comedy, action).                                              |
| **dayofweek**          | Day of the week on which the content is released.                                                |
| **season**              | Season during which the content is released (e.g., Spring, Summer, Fall, Winter).                |
| **views_trailer**       | Number of views (in millions) of the content's trailer.                                          |
| **views_content**       | Number of first-day views (in millions) for the content.                                         |

## Methodology

1. **Data Preprocessing**: The dataset was cleaned and prepared for analysis, including handling missing values, detecting and handling the outliers and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Key relationships between variables were visualized and analyzed to understand their impact on content viewership.
3. **Model Building**: A linear regression model was constructed to predict first-day content viewership based on the identified factors.
4. **Model Evaluation**: Various metrics were used to assess the model's performance, including R-squared and p-values for coefficients.

## Results

The analysis provides actionable insights that can help Showtime enhance its content strategies and marketing efforts. By understanding the factors affecting viewership, the platform can optimize content release timings and improve audience engagement.
