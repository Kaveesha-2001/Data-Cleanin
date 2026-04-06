# Data Cleaning and Visualization Project

## Project Overview
This project is a beginner-friendly tutorial on how to clean and visualize a dataset using Python.

## Dataset
The dataset used in this project was downloaded from Kaggle. It contains health-related data such as age, sex, and cholesterol levels.

## Steps Involved

### 1. Importing Libraries
I used the following Python libraries for this project:
* **Pandas:** For data manipulation and reading the CSV file.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For creating charts and data visualization.

### 2. Data Cleaning
* **Removed Unused Columns:** I dropped irrelevant columns like `cp`, `fbs`, and `thalach` to focus on the important data.
* **Renamed Columns:** I changed confusing column names to more readable names (e.g., `trestbps` to `Resting_BP`).
* **Replaced Values:** I changed the values in the `S1234567ex` column from `1` and `0` to `Male` and `Female` to make the data more understandable for everyone.

### 3. Data Visualization and Findings
I created 3 charts to understand the data better:

* **Gender Distribution Chart:** This chart shows the number of males and females in our dataset. We can see that there are more male records compared to females.
* **Age vs Cholesterol Plot:** This scatter plot shows the relationship between age and cholesterol. Generally, as age increases, cholesterol levels also tend to rise for many individuals.
* **Age Distribution Histogram:** This chart shows that most of the people in this study are between the ages of 50 and 60. The data is mostly concentrated in middle-aged groups.

## Conclusion
This project helped me understand the basics of Data Science. Even though this was a small tutorial, it was a good way to get my hands dirty with real data!
