#  Automotive Data Analysis

A data science project analyzing the Car Features dataset using Python.

##  About
This project focuses on analyzing a dataset containing detailed information 
about car models including specifications, fuel efficiency, and performance.

##  Libraries Used
- Pandas : data manipulation and analysis
- NumPy : numerical operations and statistics
- Matplotlib : data visualization
- Seaborn : statistical plots and heatmaps

##  Data Wrangling
- Checked and handled missing values using mean/mode imputation per column
- Removed duplicate entries
- Filtered out unrealistic values (0-cylinder engines, unknown transmission types)

##  Analysis Performed
- Descriptive statistics (mean, median, min, max, standard deviation)
- Distribution of numerical features using histograms
- Outlier detection using the IQR method
- Correlation analysis via heatmap and pairplot

##  Questions Answered
- What are the statistical characteristics of numerical car features?
- How are key numerical variables distributed?
- Are there outliers present in key numerical features?
- What is the Average City MPG by Vehicle Size?
- Does car size have an effect on car price?
- Do cars with more engine cylinders gravitate towards having more engine horsepower?
- What are the percentages of cars by transmission type?
- Is there a relationship between city MPG and highway MPG?
- How are engine specifications related to efficiency and price?
- Which cars are most popular?
- Which year has the most cars?
- What's the correlation of numeric features ?
- Which car brands are the most expensive on average?
- How does engine power affect car price?
- Are newer cars always more expensive?
- Which fuel type provides the best fuel efficiency?

##  Key Findings
- City and highway MPG are strongly positively correlated
- Compact cars have the highest fuel efficiency
- More cylinders = more horsepower
- Higher horsepower generally means higher price
- Newer year does not always mean higher price
- Electric vehicles lead in fuel efficiency
- Automatic transmission accounts for ~70% of the dataset
- 2016 had the highest number of car models in the dataset
- High-end brands like Bugatti and Maybach are the most expensive on average
- Ford is the most popular brand

##  Files
- `Automotive.ipynb` — the main analysis notebook
- `Car Features.csv` — the dataset
