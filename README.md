# Restaurant Cost Analysis and Visualization

## Project Overview
This project analyzes restaurant data to uncover patterns and insights related to approximate costs, ratings, and types of restaurants. The analysis uses Python for data manipulation, cleaning, and visualization to identify trends and correlations in restaurant pricing and performance.

The goal of this project is to present actionable insights about restaurant cost structures and rating trends, enabling better business and operational decisions in the restaurant industry.

---

## Features
- **Data Cleaning and Preprocessing**:
  - Removal of outliers.
  - Handling non-numeric values and missing data.
  - Conversion of data types for analysis.

- **Statistical Analysis**:
  - Calculation of measures like Interquartile Range (IQR), outlier thresholds, and summary statistics.
  - Insights into cost and rating trends by restaurant type.

- **Data Visualization**:
  - Boxplots for cost distributions by restaurant type (using Seaborn and Matplotlib).
  - Scatter plots for relationships between cost and rating (using Bokeh).
  - Donut charts for categorical data distributions.

---

## Tools and Libraries
- **Python Libraries**:
  - `pandas` for data manipulation and cleaning.
  - `matplotlib` and `seaborn` for traditional data visualization.
  - `bokeh` for interactive and detailed visualizations.
  - `numpy` for numerical operations.

---

## Steps in the Analysis
1. **Data Loading**:
   - The dataset is loaded from a CSV file into a Pandas DataFrame.

2. **Data Cleaning**:
   - Non-numeric characters in cost columns are removed.
   - Missing values in key columns like `rate` and `approx_cost(for two people)` are dropped.

3. **Exploratory Data Analysis**:
   - Summary statistics and distribution of data.
   - Identification of outliers using IQR and removal to improve data quality.

4. **Visualization**:
   - **Boxplot**: Shows cost distribution by restaurant type.
   - **Scatter Plot**: Highlights the relationship between approximate cost and rating.
   - **Donut Chart**: Visualizes the proportion of restaurant types.

---

## Key Insights
1. **Restaurant Type and Cost**:
   - Casual dining tends to have higher average costs compared to cafes and quick-service restaurants.
   - Fine dining establishments exhibit significant cost variation.
   
2. **Cost vs. Rating**:
   - Higher-rated restaurants often correlate with mid-to-high costs, but there are exceptions, showing cost is not the sole determinant of quality.

3. **Interactive Insights**:
   - Using Bokeh, users can explore restaurant types, their ratings, and costs interactively.

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn bokeh
   ```
3. Load the dataset into your environment (ensure the CSV file is in the correct location).
4. Execute the Jupyter Notebook or Python script:
   - Open the Jupyter Notebook (`Data_Analysis.ipynb`) and run all cells.
   - Alternatively, run the script using Python.

---

## Visualizations
### 1. Boxplot
- Shows cost variation across restaurant types.
- Helps identify expensive and affordable restaurant categories.

### 2. Scatter Plot (Bokeh)
- Interactive visualization showing how cost correlates with ratings.
- Hover over points to explore restaurant types and specific costs.

### 3. Donut Chart
- Visualizes the proportion of restaurant types in the dataset.

---

## Conclusion
This project provides valuable insights into the restaurant industry by analyzing cost patterns, ratings, and categories. The combination of statistical analysis and interactive visualizations ensures a comprehensive understanding of the data, supporting strategic business decisions.

---

## Future Enhancements
- Incorporate location-based analysis for regional trends.
- Add time-series analysis to observe cost/rating changes over time.
- Include machine learning models to predict ratings or costs.

---
