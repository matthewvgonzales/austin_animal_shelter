# austin_animal_shelter
# Data Cleaning and Basic EDA Project
This project demonstrates my ability to clean and manipulate data, as well as perform exploratory data analysis. The dataset comes from the Austin Animal Center, a no-kill animal shelter in Austin, Texas, covering records from 2013 to February 2025.

# Project Objectives
Import and preprocess data

Perform data cleaning and wrangling

Conduct exploratory data analysis (EDA)

Visualize key insights

## Technologies Used
Python 3.11.11

Pandas 2.2.2

NumPy 1.26.4

Matplotlib 3.10.1

## Data Cleaning & Wrangling
Removed redundant columns (e.g., MonthYear was dropped in favor of DateTime)

Dropped Outcome_Subtype due to substantial missing values

Processed age_upon_outcome to ensure consistent formatting and usability

Converted relevant columns (e.g., Animal_Type, Animal_ID) to categorical data to optimize memory usage

Converted date-related columns to datetime format

Please see additional csv file for long outputs for "breed" and "color" columns. Separated for improved readability.

## Exploratory Data Analysis (EDA)
Analyzed trends in animal outcomes over time

Identified patterns in animal types, breeds, and ages

Visualized outcome distributions to understand adoption trends

## Acknowledgments
This project serves as a demonstration of my data analysis skills. While substantial cleaning and EDA were performed, additional analysis could be conducted to further explore insights from the data. The depth of this anaylsis could be
deepened by using statical tests and further analysis to explore the relationships between animal types in relation to each other versus their outcome types.

## How to Run
Clone this repository
Install required libraries manually using pip install pandas numpy matplotlib
Open the Jupyter Notebook and run the cells sequentially

## Contact
For any questions, feel free to reach out!
