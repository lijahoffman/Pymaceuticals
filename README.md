# Pymaceuticals

Dataset containing the treatment regimen and tumor development of 249 mice over the course of 45 days. The following script prepares the data, generates summary statistics, calculates quartiles and outliers, and visualizes results. 

## Preparing the Data 
1. Imports and merges mouse_medata.csv and study_results.csv (both located in Resources) into a single dataframe. 
2. Displays the number of unique mouse IDs in the data.
3. Creates a new dataframe with any duplicate data removed. 


## Analysis
1. Generates the mean, median, variance, standard deviation, and SEM of tumor volume during each drug regimen. 
2. Calculates the final tumor volume of each mouse across the following treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
3. Calculates the quartiles and IQR for each of the above regimens to determine if there are any potential outliers. 
4. Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume of the Capomulin regimen (plot on top of the scatter plot generated in Visualizations step 5). 

## Visualization
1. Generate a barplot showing the total number of timepoints for all mice tested for each drug regimen throughout the course of the study. 
2. Generate a pie plot that shows the distribpution of male and female mice in the study. 
3. Generates a bocplot of the final tumor volume for the following treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Highlights any potential outliers. 
4. Generates a line plot of tumor volume vs time point for a specific mouse treated with Capomulin. 
5. Creates a scatter plot of tumor volume versus mouse weight for the Capomulin regimen (plots correlation coefficient and linear regression model calculated in Analysis step 4). 


## Conclusions
1. There is a moderate positive correlation (r = 0.53) between Mouse Weight (g) and Tumor Volume (mm3).
2. On average, mice treated with Capomulin or Ramicane displayed a smaller final Tumor Volume (mm3) than those treated with Infubinol or Ceftamin.
3. Mouse s185 displayed an overall decrease in Tumor Volume (mm3) after treatment with Capomulin.



## Technology
• Python
• Pandas
• Matplotlib 
° Jupyter Notebooks 