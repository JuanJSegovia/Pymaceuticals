# Pymaceuticals

This project involves analyzing tumor volume data from an animal study to evaluate the effectiveness of various drug regimens in treating squamous cell carcinoma (SCC) in mice.

## Project Structure
Data Preparation:

Merged mouse_metadata and study_results DataFrames to create a single comprehensive dataset.
Cleaned the dataset by identifying and removing duplicate entries based on Mouse ID and timepoints.
Summary Statistics:

Generated a summary table that includes the mean, median, variance, standard deviation, and SEM of tumor volumes for each drug regimen.
Data Visualization:

Bar Charts: Visualized the total number of timepoints for each drug regimen using both Pandas and Matplotlib.
Pie Charts: Showcased the distribution of male and female mice in the study using both Pandas and Matplotlib.
Quartile and Outlier Analysis:

Identified the final tumor volume for each mouse in the top four drug regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
Calculated the interquartile range (IQR) for each regimen and identified any potential outliers.
Created a box plot displaying the distribution of final tumor volumes for each regimen, with outliers highlighted.
Line Plot and Scatter Plot:

Line Plot: Tracked the tumor volume over time for a specific mouse treated with Capomulin.
Scatter Plot: Examined the relationship between mouse weight and average tumor volume for the Capomulin regimen.
Correlation and Regression Analysis:

Calculated the correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen.
Plotted a linear regression model on the scatter plot to visualize the correlation.

## Deliverables
Jupyter Notebook 'pymaceuticals.ipynb': Contains all the analysis, calculations, and visualizations.
This project highlights the effectiveness of Capomulin compared to other treatments, the relationship between mouse weight and tumor volume, and identifies potential outliers in the dataset. These insights are crucial for making informed decisions on the development of anti-cancer treatments.

