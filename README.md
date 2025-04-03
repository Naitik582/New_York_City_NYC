<h1>NYC Airbnb Data Cleaning & Preprocessing</h1>

**Overview**

This project involves cleaning and preprocessing the AB_NYC_2019.csv dataset using Google Colab. The dataset contains listings of Airbnb properties in New York City with details such as price, room type, location, host details, and reviews.

**Steps Performed**

**1. Data Loading & Exploration**

• Uploaded AB_NYC_2019.csv to Google Colab.

• Displayed the first few rows to understand the dataset.


**2. Handling Missing Values**

• Replaced missing values in name and host_name with "Unknown".

• Filled missing values in last_review with "No Review".

• Replaced missing values in reviews_per_month with the median.

• Removed rows where last_review was missing.


**3. Removing Duplicates & Standardizing Column Names**

• Removed duplicate entries.

• Standardized column names to lowercase and replaced spaces with underscores.


**4. Handling Outliers**

• Used Interquartile Range (IQR) to remove extreme price outliers.


**5. Saving the Cleaned Dataset**

• Exported the cleaned dataset as AB_NYC_2019_cleaned.csv.

• Made the file available for download.


**Tools Used**

• Google Colab for execution

• Pandas for data manipulation

• Matplotlib for visualization

• NumPy for numerical operations
