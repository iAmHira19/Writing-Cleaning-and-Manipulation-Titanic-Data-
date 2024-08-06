# Titanic Data Cleaning and Manipulation
This repository contains a Python script for cleaning and manipulating the Titanic dataset. The script demonstrates various data processing techniques, including filtering, sorting, creating new columns, and aggregating data. The cleaned and manipulated data is saved to a new CSV file for further analysis.

# Repository Structure
titanic_data_cleaning.py: Python script for downloading, cleaning, manipulating, and saving the Titanic dataset.
kaggle.json: (Upload manually) Your Kaggle API credentials file needed for data download.
Installation and Setup
# Install Dependencies:
Ensure you have pandas and kaggle installed. You can install these using pip:

bash
Copy code
pip install pandas kaggle
# Kaggle API Setup:

Create a Kaggle API token from your Kaggle account settings.
Save the token as kaggle.json.
# Upload Kaggle API Token:

Upload the kaggle.json file manually if using Google Colab or ensure it is available in your local environment.
Usage
# Download and Extract the Dataset:
The script will handle the download of the Titanic dataset from Kaggle and unzip it for use.

# Run the Script:
Execute the script to load the dataset, perform data cleaning and manipulation, and save the results to a new CSV file.

bash
Copy code
python titanic_data_cleaning.py
# Review Output:
# The script will output:

Initial DataFrame preview.
Basic dataset information and summary statistics.
Details of missing values and unique values in each column.
Filtered, sorted, and aggregated data.
The manipulated DataFrame saved as manipulated_train.csv.
E# xample Output
Initial DataFrame: Displays the first few rows of the dataset.
Basic Information: Shows data types, non-null counts, and memory usage.
Summary Statistics: Provides statistical summary of numerical columns.
Missing Values: Lists missing values for each column.
Unique Values: Shows unique values for categorical columns.
Filtered Data: Data of passengers who survived and those who did not.
Sorted Data: DataFrame sorted by age.
New Columns: Added FamilySize column.
Grouped Data: Mean age by passenger class.
Aggregated Data: Mean fare and age by passenger class.
# License
This project is licensed under the MIT License - see the LICENSE file for details.
