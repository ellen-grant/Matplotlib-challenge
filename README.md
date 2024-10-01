# 1. Data Cleaning and Preparation
The initial steps involved merging mouse metadata with study results to create a comprehensive dataset. Duplicate entries based on "Mouse ID" and "Timepoint" were identified and removed, resulting in a clean dataset. The total number of unique mice in the study after cleaning was recalculated to ensure data integrity.
# 2. Summary Statistics
A summary statistics table was generated to provide insights into the mean, median, variance, standard deviation, and standard error of the mean (SEM) of the tumor volume for each treatment regimen. This statistical overview is crucial to understand the variability and central tendency of tumor volumes under different treatments.
# 3. Bar and Pie Charts
Bar Chart: A bar chart visualized the total number of observations (Mouse ID/Timepoints) for each drug regimen, highlighting the frequency of data points collected for each treatment. This provides an idea of the distribution and sample size across regimens.
Pie Chart: Another visualization showed the distribution of female versus male mice in the study, offering insights into the gender balance of the experimental subjects.
# 4. Quartiles, Outliers, and Boxplots
The final tumor volume for each mouse was analyzed across four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Boxplots illustrated the distribution of tumor volumes, highlighting medians, quartiles, and potential outliers. This analysis allows a comparison of treatment efficacy by showcasing how tumor volumes differ across regimens.
# 5. Line and Scatter Plots
Line Plot: A line plot displayed the change in tumor volume over time for a specific mouse treated with Capomulin. This visualization helps track the efficacy of Capomulin on an individual level and shows how the tumor responds to the treatment over time.
Scatter Plot: A scatter plot was created to show the relationship between mouse weight and average tumor volume for the Capomulin regimen. This provides insights into whether there is a correlation between a mouse's weight and the effectiveness of the treatment.
# 6. Correlation and Regression Analysis
A correlation coefficient was calculated, and a linear regression model was applied to the relationship between mouse weight and average tumor volume for the Capomulin regimen. This analysis assessed the strength and direction of the association, with the scatter plot showing a regression line indicating the trend.
