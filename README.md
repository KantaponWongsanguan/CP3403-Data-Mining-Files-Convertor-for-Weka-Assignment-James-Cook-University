# Online Retail Data Analysis Project

This repository contains the code and data for analyzing and categorizing an online retail dataset. The project involves several stages of data preprocessing, categorization, and analysis using Python.

## Project Structure

- **Excel Files:**
  - `online_retail_II.xlsx`: The original dataset containing transaction records from an online retail store.

- **Python Scripts:**
  - `cleanonlineretail.py`: Script for cleaning the retail dataset. This script handles missing values, removes duplicates, filters out invalid transactions, and performs feature engineering.
  - `categorize.py`: Script that assigns categories to products based on keywords found in the product descriptions.
  - `xceltocsv.py`: Script to convert the original Excel file into a CSV format.
  - `wordcount.py`: Script to count the frequency of words in product descriptions, providing insights into common terms and potential product categories.
  - `tartocsv.py`: Script to extract data from a `.tar` archive and combine multiple `.gz` files into a single CSV.
  - `ap.py`: Script that creates a one-hot encoded matrix from categorized items, grouping transactions by invoice.

## Key Features

- **Data Cleaning:**
  - Handled missing values by filling numeric fields with the median and categorical fields with the mode.
  - Removed duplicate records and filtered out transactions with negative quantities or prices.
  - Performed feature engineering by adding `Year`, `Month`, and `TotalPrice` columns.

- **Product Categorization:**
  - Developed a custom categorization function that assigns product categories based on keywords in the product descriptions.
  - Categories include "Bags & Accessories", "Home Decor", "Stationery", "Kitchenware", "Christmas", "Jewelry & Accessories", "Color Themes", and "Others".

- **Data Transformation and Analysis:**
  - Converted the cleaned Excel data to CSV for easier handling and processing.
  - Counted word frequencies in product descriptions to identify common themes and terms.
  - Extracted data from compressed files and combined them into a single dataset for analysis.
  - Created a one-hot encoded matrix to analyze transactions by invoice and product category.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/online-retail-analysis.git
.

### Dataset
https://archive.ics.uci.edu/dataset/502/online+retail+ii

* Chen,Daqing. (2019). Online Retail II. UCI Machine Learning Repository. https://doi.org/10.24432/C5CG6D.
