## **Exploratory Data Analysis (EDA)**

Exploratory Data Analysis (EDA) is an essential approach for analyzing datasets, with the aim of summarizing their primary characteristics. This process typically involves employing statistical graphics and various data visualization techniques. EDA often serves as the initial step in the data analysis journey. However, mastering the art of effectively utilizing EDA in data analysis requires experience.    
When faced with a dataset and the need to gain profound insights, make informed decisions, and establish a sound strategy for further experimentation, consider the following key aspects:    
### First and formost, what `strategy` do you intend to use for EDA?   
Before embarking on data analysis, it's crucial to gather relevant information. Engage with stakeholders and domain experts to acquire insights into the data. Subsequently, explore the dataset to ascertain its dimensions, understanding the number of rows and variables it contains. An initial examination of the first few rows of data can help you identify the types of variables present. Pay special attention to unique variables and address missing values by deciding whether to remove variables with missing data or impute reasonable values.    
Explore the basic statistical characteristics of your sample and its features. The choice of appropriate visualizations and statistical methods should align with the variable types. You can use plots and charts to visualize the dataset. Calculating the mean and variance of each variable provides insights into their stability or variability. Variables with extremely low or high variances may warrant further investigation. Investigate correlations between variables and seek to understand the reasons behind these correlations. Lastly, be vigilant in identifying outliers within the dataset.    
Throughout the above steps, maintain detailed notes for each variable, as these will be invaluable in summarizing your findings. After completing your EDA, consider presenting a summary of your discoveries to project stakeholders and relevant teams.    

### In addition to employing the right approach, it's essential to establish a clear overarching `goal` when conducting EDA.   
The primary purpose of EDA is to explore the data without making premature assumptions. It aids in identifying errors, understanding data patterns, detecting outliers, and revealing interesting relationships among variables.    
### In the realm of EDA, there are four primary `methods` you can employ to explore your dataset:  
+ Univariate Non-Graphical: This method involves examining single variables to gain insights into their properties and patterns within the dataset.  
+ Univariate Graphical: Visualize variables using various techniques, such as stem-and-leaf plots, histograms, and box plots. These methods provide information about distribution shape, variable frequencies, and key statistics.  
+ Multivariate Non-Graphical: This method explores relationships between two or more variables through cross-tabulation and statistics.  
+ Multivariate Graphical: Employ techniques like grouped bar plots, scatter plots, bubble charts, or heat maps to visualize relationships among multiple variables.  
Commonly used tools for EDA include **Python** and **R**.  
### Finally, you can compile a comprehensive report to present your `findings`, including:   
  - Basic dataset descriptions  
  - Standard deviations  
  - Analysis of categorical variables  
  - Confidence intervals  
  - Identified patterns in the data  
  - Detection of anomalies  
  - Hypothesis testing  
  - Verification of assumptions  
This report enhances your understanding of dataset variables and their interrelationships. It also aids in determining the suitability of statistical techniques for further data analysis. EDA helps ensure that stakeholders are asking the right questions. Once EDA is completed and insights are extracted, the features of the dataset can be harnessed for more advanced data analysis or modeling, including machine learning.  

**References:** 
- https://shopify.engineering/conducting-exploratory-data-analysis  
- https://www.ibm.com/cloud/learn/exploratory-data-analysis  
- https://en.wikipedia.org/wiki/Exploratory_data_analysis  
- https://www.itl.nist.gov/div898/handbook/eda/section1/eda11.htm

 ```tsql
 SELECT *
 FROM sys.tables
 WHERE [name] = 'SomeTable'
 ```
