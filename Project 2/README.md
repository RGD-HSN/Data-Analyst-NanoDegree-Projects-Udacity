# Google Play Store Data Wrangling & Sentiment Analysis

## Overview

This project focuses on applying real-world data wrangling techniques to analyze data from the Google Play Store. The main objective is to clean, transform, and merge datasets to explore the relationship between user sentiment, app ratings, and pricing.

## Datasets

Two datasets were used in this project:

* **Google Play Store Dataset**: Contains information about apps such as rating, category, number of installs, price, and more.
* **User Reviews Dataset**: Contains user reviews along with sentiment labels and numerical sentiment scores (polarity and subjectivity).

## Process

The project follows a complete data wrangling pipeline:

1. **Data Gathering**

   * Data was manually downloaded from Kaggle.

2. **Data Assessment**

   * The datasets were inspected both visually and programmatically.
   * Identified issues included missing values, incorrect data types, duplicate records, and structural inconsistencies.

3. **Data Cleaning**

   * Handled missing values by removing or filling them where appropriate.
   * Converted columns to correct data types (e.g., numeric values).
   * Removed duplicate records.
   * Restructured columns (e.g., splitting multiple genres into separate rows).

4. **Data Integration**

   * Merged both datasets using the common column **App**.

5. **Data Analysis & Visualization**

   * Created visualizations to explore relationships between:

     * App rating and user sentiment
     * App price and user sentiment

## Research Question

Is there a relationship between user sentiment and app rating or price?

---

This project demonstrates practical skills in data wrangling, data cleaning, and exploratory data analysis using real-world datasets.
