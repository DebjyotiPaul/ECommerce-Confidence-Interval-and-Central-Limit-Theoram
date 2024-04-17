# Walmart-Confidence-Interval-and-Central-Limit-Theoram
Walmart's management aims to scrutinize customer purchase behavior, particularly spending disparities between genders, like whether women outspend men on Black Friday, among 100 million customers.

# About Walmart
Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

# Business Problem
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).

# Dataset
The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:
* User_ID:	User ID
* Product_ID:	Product ID
* Gender:	Sex of User
* Age:	Age in bins
* Occupation:	Occupation(Masked)
* City_Category:	Category of the City (A,B,C)
* StayInCurrentCityYears:	Number of years stay in current city
* Marital_Status:	Marital Status
* ProductCategory:	Product Category (Masked)
* Purchase:	Purchase Amount

# Procedural menthodology

## Defining Problem Statement and Analyzing basic metrics

### Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), statistical summary
- The dataset consists of [insert number] entries and [insert number] attributes.
- Data types of attributes include [insert data types].
- Categorical attributes have been converted to 'category' data type.
- Statistical summary:
  - Mean, median, min, max, and standard deviation for continuous variables.
  - Value counts and unique attributes for categorical variables.

## Non-Graphical Analysis
- Value counts and unique attributes for each categorical variable.
- Summary statistics for each continuous variable.

## Visual Analysis - Univariate & Bivariate

### For continuous variable(s):
- Distplot, countplot, histogram for univariate analysis.
- Boxplot for bivariate analysis.

### For categorical variable(s):
- Boxplot for categorical variables.

### For correlation:
- Heatmaps and Pairplots for identifying correlations.

## Missing Value & Outlier Detection
- Identify missing values and handle them appropriately.
- Detect outliers using statistical methods.

## Business Insights based on Non-Graphical and Visual Analysis
- Range of attributes: [Comments on the range of attributes].
- Distribution of variables: [Comments on the distribution of the variables and relationship between them].
- Comments on univariate and bivariate plots: [Comments for each univariate and bivariate plot].

## Answering questions

### Are women spending more money per transaction than men? Why or Why not?
- Explanation based on analysis results.

### Confidence intervals and distribution of the mean of the expenses by female and male customers
- Analysis of confidence intervals and distribution.

### Are confidence intervals of average male and female spending overlapping? How can Walmart leverage this conclusion to make changes or improvements?
- Discussion on leveraging the conclusion.

### Results when the same activity is performed for Married vs Unmarried
- Insights on spending behavior based on marital status.

### Results when the same activity is performed for Age
- Insights on spending behavior based on age.

## Final Insights
- Comments on the distribution of the variables and relationship between them.
- Comments for each univariate and bivariate plots.
- Comments on different variables when generalizing it for Population.

## Recommendations 
- Actionable items for business based on insights.




