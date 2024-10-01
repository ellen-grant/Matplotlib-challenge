# Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. This is the top-level summary of the study results.



## 1. Data Cleaning and Preparation
The initial steps involved merging mouse metadata with study results to create a comprehensive dataset. Duplicate entries based on "Mouse ID" and "Timepoint" were identified and removed, resulting in a clean dataset. The total number of unique mice in the study after cleaning was recalculated to ensure data integrity.

## 2. Summary Statistics
A summary statistics table was generated to provide insights into the mean, median, variance, standard deviation, and standard error of the mean (SEM) of the tumor volume for each treatment regimen. This statistical overview is crucial to understand the variability and central tendency of tumor volumes under different treatments.

## 3. Bar and Pie Charts
### Bar Chart: 
A bar chart visualized the total number of observations (Mouse ID/Timepoints) for each drug regimen, highlighting the frequency of data points collected for each treatment. This provides an idea of the distribution and sample size across regimens.
### Pie Chart: 
Another visualization showed the distribution of female versus male mice in the study, offering insights into the gender balance of the experimental subjects.

## 4. Quartiles, Outliers, and Boxplots
The final tumor volume for each mouse was analyzed across four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Boxplots illustrated the distribution of tumor volumes, highlighting medians, quartiles, and potential outliers. This analysis allows a comparison of treatment efficacy by showcasing how tumor volumes differ across regimens.

## 5. Line and Scatter Plots
### Line Plot:
A line plot displayed the change in tumor volume over time for a specific mouse treated with Capomulin. This visualization helps track the efficacy of Capomulin on an individual level and shows how the tumor responds to the treatment over time.
### Scatter Plot:
A scatter plot was created to show the relationship between mouse weight and average tumor volume for the Capomulin regimen. This provides insights into whether there is a correlation between a mouse's weight and the effectiveness of the treatment.

## 6. Correlation and Regression Analysis
A correlation coefficient was calculated, and a linear regression model was applied to the relationship between mouse weight and average tumor volume for the Capomulin regimen. This analysis assessed the strength and direction of the association, with the scatter plot showing a regression line indicating the trend.

# Analysis

## 1. Effectiveness of Treatment Regimens
The treatments evaluated, particularly Capomulin and Ramicane, showed promising results in reducing tumor volume compared to other regimens. The boxplot analysis revealed that these two treatments had lower median tumor volumes, suggesting they might be more effective in controlling tumor growth in mice with squamous cell carcinoma (SCC). Additionally, fewer outliers and tighter quartile ranges for Capomulin and Ramicane indicate more consistent results among the treated mice.

## 2. Gender Distribution and Representation
The pie chart showed that the study had a fairly balanced distribution of male and female mice. This balance ensures that the results are not biased toward a particular gender, making the findings more generalizable. It also suggests that any observed treatment effects are likely applicable to both male and female subjects.

## 3. Tumor Volume Progression with Capomulin
A closer examination of an individual mouse treated with Capomulin demonstrated a noticeable decrease in tumor volume over time. This suggests that Capomulin is effective in inhibiting tumor growth on a case-by-case basis. Tracking the change over multiple timepoints helps in understanding the dynamic impact of the drug over the course of treatment.

## 4. Correlation Between Mouse Weight and Tumor Volume
The scatter plot and subsequent regression analysis highlighted a positive correlation between mouse weight and average tumor volume for mice treated with Capomulin. This implies that heavier mice tended to have larger tumors. The correlation coefficient and regression model suggest that weight might be a factor to consider when assessing tumor growth or the effectiveness of treatment, although further investigation would be needed to understand the underlying reasons for this relationship.

## 5. Data Integrity and Sample Size
The bar chart analysis showed the number of observations for each drug regimen, with some treatments having significantly more data points than others. This variation in sample size suggests that some treatments were more extensively tested, which could affect the reliability and robustness of the conclusions drawn about those regimens. Nevertheless, Capomulin and Ramicane, having a substantial number of observations, add confidence to the conclusion of their effectiveness.

## Overall Conclusion
Capomulin and Ramicane emerged as the most effective treatment options based on the data analyzed, demonstrating significant reductions in tumor volumes and consistent results. The study’s balanced gender representation and comprehensive data analysis provide a strong foundation for these conclusions. However, given the observed correlation between mouse weight and tumor size, future studies should consider stratifying results by weight to further refine the understanding of treatment efficacy. Additionally, expanding sample sizes for other treatment regimens could offer a more complete comparison across all potential therapies.

## These conclusions suggest that Capomulin and Ramicane may be promising candidates for further investigation and potential clinical application in anti-cancer treatment strategies.
