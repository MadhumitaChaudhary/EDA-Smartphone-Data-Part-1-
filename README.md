# Samsung Mobiles Data Analysis

This repository contains the code and notebooks for analyzing the Samsung Mobiles Latest Dataset. The dataset provides valuable insights into Samsung's cutting-edge range of mobile devices, including specifications, ratings, and prices. 

**Source:** https://www.kaggle.com/datasets/gyanprakashkushwaha/samsung-mobiles-latest-dataset

## Dataset Overview

The dataset comprises key columns that shed light on Samsung mobiles' essential attributes, such as:

- `name`: Names of various Samsung smartphone models.
- `ratings`: User ratings and reviews.
- `price`: Prices of the Samsung mobiles.
- `storage_ram`: Storage capacity and RAM configuration.
- `os_processor`: Operating system and processor details.
- `camera`: Camera specifications.
- `display`: Display-related specifications.
- `battery`: Battery-related specifications.

## Part 1: Data Cleaning and Preprocessing

### Loading the Data

The data was loaded from a CSV file using pandas.

### Identifying Missing Data, Duplicates, and Typos

- Checked for missing values and duplicates.
- Removed duplicates to ensure the quality of the data.

### Feature Extraction

- Extracted features from the 'name' column to create new columns like 'Brand', 'Model', 'Color', 'Storage', and 'Network'.
- Used regular expressions to extract features from other columns like 'storage_ram', 'os_processor', 'camera', 'display', 'network', and 'battery'.

### Handling Missing Data

- Checked for missing data again after feature extraction.
- Decided to handle missing values later in the preprocessing stage.

### Renaming Columns

- Renamed columns to more descriptive names for better readability.

### Converting Data Types

- Converted some columns to appropriate data types, such as removing the rupee sign from the 'Price' column and converting it to float.

### Saving the Processed Data

- Saved the processed data to a new CSV file, ready for further analysis or modeling.



