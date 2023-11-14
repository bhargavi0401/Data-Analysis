# Covid-19 Data Analysis and Pima Indians Diabetes Database

## Overview
This repository contains Python scripts for analyzing two datasets: daily COVID-19 cases in India and the Pima Indians Diabetes Database. The code includes data visualization, statistical analysis, and modeling.

## Covid-19 Data Analysis
### Autoregression (AR) Model
1. **Line Plot with Lagged Values:**
   - Created a line plot representing the daily COVID-19 cases in India, identifying distinct waves in August 2020 and May 2021.

2. **Autocorrelation Coefficient Calculation:**
   - Computed the Pearson correlation coefficient between the given time sequence and a one-day lagged sequence.

3. **Scatter Plot and Correlation Analysis:**
   - Generated a scatter plot between the given time sequence and the one-day lagged sequence, providing visual insights into the correlation.
   - Explored correlation coefficients between the given time sequence and sequences with various lag values.

4. **Correlogram (Auto Correlation Function):**
   - Plotted a correlogram using the 'plot_acf' function to observe trends in correlation with increasing lag values.

## Pima Indians Diabetes Database Analysis
### Descriptive Statistics and Visualization
1. **Statistical Metrics:**
   - Calculated mean, median, mode, minimum, maximum, and standard deviation for attributes (excluding 'class').

2. **Scatter Plots:**
   - Generated scatter plots for 'Age' against each attribute and 'BMI' against each attribute (excluding 'class').

3. **Correlation Coefficients:**
   - Determined correlation coefficients between 'Age' and all other attributes, as well as between 'BMI' and all other attributes (excluding 'class').

4. **Histograms:**
   - Plotted histograms for attributes 'preg' and 'skin', and separately for 'preg' for each of the 2 classes.

5. **Boxplots:**
   - Created boxplots for all attributes (excluding 'class') to visualize data distribution.

## How to Use
1. Ensure you have Python and the required libraries installed.
2. Download the datasets: 'daily_covid_cases.csv' and 'pima-indians-diabetes.csv'.
3. Run the Python scripts to perform the analyses and visualize the results.

Feel free to explore and modify the code to suit your specific requirements.
