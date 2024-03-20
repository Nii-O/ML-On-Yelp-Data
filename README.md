# Yelp Review Analysis

## Introduction
Welcome to our Yelp Review Analysis project! In this analysis, we delve deep into the vast world of Yelp reviews to extract valuable insights and patterns. Led by Group 3 - Jackson Hett, Immanuel Odarteifio, and Shreyas Subhash Tekawade - our objective is to uncover meaningful insights from the diverse tapestry of user-generated content on Yelp. The project was divide into two parts. The first part using user coments to predict review stars and the second using numerical data including customer and reviewer ratings to predict the final stars rating.

## Data Preparation
We meticulously prepared our data using the R programming language, leveraging essential libraries like tidyverse and jsonlite. Our process involved sampling, integration, sorting, and selection to curate a refined dataset ready for analysis. This data was then migrated to a python notebook 

## Exploratory Data Analysis
Our journey began with exploring collinearity, correlations, and trends within the dataset. Through insightful visualizations, we gained valuable insights into user sentiments and business attributes.

## Model Selection
We employed Support Vector Machines (SVM), decision tree models, and Multi-Class Ordinal Logistic Regression (MCOLR) to predict business stars accurately. Each model was meticulously tuned and evaluated to ensure robust performance.

## Results
Our SVM model achieved an accuracy of 60.6%, closely followed by decision tree and random forest models. The MCOLR model, tailored for ordinal data, provided valuable insights into the ordinal nature of review stars.

## Quantitative Feature Analysis
We conducted in-depth quantitative feature analysis, exploring the impact of various variables on review ratings. Through meticulous modeling and grid search optimization, we achieved significant improvements in model accuracy.

## Limitations
Despite our rigorous analysis, we acknowledge several limitations, including the ordinal nature of review stars and inherent biases in human-generated data. We also address challenges related to imbalanced data and evolving review sentiments over time.

## Conclusion
Our Yelp Review Analysis project offers a comprehensive exploration of user sentiments and business dynamics on Yelp. By leveraging advanced analytical techniques, we aim to empower businesses with actionable insights for strategic decision-making. Dive into our findings and discover the intricate world of Yelp reviews!

For a more detailed exploration, check out our project report. Let's unravel the mysteries of Yelp together!

GitHub Repository: Yelp Review Analysis

This project was completed as part of the IST 707 course at Syracuse University, School of Information Studies.

