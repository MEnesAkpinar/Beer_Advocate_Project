Description

This repository contains my solution for the technical assignment. The task involves analyzing a large CSV dataset, focusing on establishing connections within the data, exploring its intricacies, and making various predictions and analyses.

This project showcases my ability to tackle real-world data challenges and deliver actionable insights through efficient data processing and visualization techniques. It reflects my skills in data exploration, predictive analytics, and presenting findings in a clear, understandable format.

Table of Contents

1. Introduction
2. Importing Related Libraries
3. Data Load and Review
4. Questions and Analysis

Features

Data Loading: Efficiently reads and imports the dataset for analysis.
Exploratory Data Analysis (EDA): Conducts thorough exploration and manipulation of the data to uncover patterns and trends.
Data Visualization: Utilizes visualization techniques to understand relationships between different variables and enhance interpretability.
Insight Generation: Provides in-depth insights and answers to key analytical questions, facilitating informed decision-making.


Technologies

- Python
- Pandas 
- NumPy 
- Matplotlib 
- Seaborn


Data Description

This dataset(about 1.5 million rows/ 13 columns) contains information related to beer reviews and breweries, comprising the following columns:


1. brewery_id (int64): A unique identifier for each brewery.
2. brewery_name (object): The name of the brewery.
3. review_time (int64): The timestamp of when the review was submitted.
4. review_overall (float64): The overall rating given by the reviewer, typically on a scale from 0 to 5.
5. review_aroma (float64): The rating for the aroma of the beer, usually on a scale from 1 to 5.
6. review_appearance (float64): The rating for the appearance of the beer, often on a scale from 0 to 5.
7. review_profilename (object): The name of the reviewer or profile from which the review originated.
8. beer_style (object): The style of the beer (e.g., IPA, Lager, Stout).
9. review_palate (float64): The rating for the palate of the beer, typically on a scale from 1 to 5.
10. review_taste (float64): The rating for the taste of the beer, generally on a scale from 1 to 5.
11. beer_name (object): The name of the beer being reviewed.
12. beer_abv (float64): The Alcohol by Volume (ABV) percentage of the beer.
13. beer_beerid (int64): A unique identifier for each beer.


Data Overview

Data Type: The dataset is primarily composed of numerical and categorical data types. The numerical fields (e.g., int64, float64) are used for ratings and identifiers, while categorical fields (e.g., object) represent text-based information such as names and styles.