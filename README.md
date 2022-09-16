# Iswaryaah Balakrishnan's Portfolio
Here are the assignments and projects that I have worked on... 

![](https://github.com/iswaryaah/portfolio/blob/main/images/Py%20Portfolio.png)

# ![Project 1 - SQL](../blob/main/project%20files/Assignment%201%20SQL.docx)
* Created a database in SQLite Studio.
* Applied basic data querying techniques to create datasets from database tables.

### How is SQL used in Data Science? 
* Structured Query Language (SQL) is a standard language for accessing and manipulating databases. 
* It is used to update/create/delete databases, execute queries, and manage data access permissions.
* Many organizations store data in relational databases thus a data scientist should know how to use SQL in order to retrieve and manipulate data.
* Data can be retrieved from a database using SQL and can then be further analyzed using R, Python, or other tools.

### Basic SQL Syntax
• SELECT
• DISTINCT
• WHERE
• INSERT
• ORDER BY
• GROUP BY
• Joins
• Unions
• Sub-queries

# ![Project 2 - Basic Python](../blob/main/project%20files/Assignment%202.ipynb)
* I installed Anaconda and programmed in Jupyter. 
* Anaconda allows us to create multiple environments, manage Python packages in various versions (when working on
multiple projects) and provides access to multiple IDEs.
* Wrote simple Python functions
* Worked with strings and dictionaries

# ![Project 3 - Data Analysis using Python](../blob/main/project%20files/Assignment%203.ipynb)
* In this project, I analyzed data of the passengers aboard the titanic.
* My approach:
  * I imported the titanic dataset and then I used .info() to get a summary of the dataframe. 
  * The .info function lists all the columns along with their data types.
  * I can also interpret which columns have missing data. 
  * I then used the .head() function to see what the dataset looks like. 
  * To analyse data, I used the groupby() function to categorize my data.
  * I used the groupby function to specify the columns to group on and then the columns to aggregate.
  * Throughout the analysis, I anchored to the key question of who would be more likely to survive.
  * I used functions such as...
    * pandas.cut() to categorise age
    * .median() to find the median fare paid by passengers 
    * .mean() to find the average age of passengers

# ![Project 4 - Data Cleaning and Exploration](../blob/main/project%20files/Assignment%201.ipynb)
* I created a dataframe based on a provided csv file with data on various types of cereal and the corresponding customer ratings
* Based on the analysis conducted, I came to the following conclusions:
  * There appears to be a strong negative relationship between calories and ratings where the higher in calories the cereal is, the lower the rating
  * For this dataset we defined a healthy cereal as one which has the following characteristics:
low calories (<100), low sodium (<150), low sugar (<9) high fiber (>3), and high protein (>2)
  * Both the highest rated cereal as well as the lowest rated cereal are healthy (according to our definition)
  
# ![Project 5 - Time Series Analysis on Financial Data](../blob/main/project%20files/Assignment2.ipynb)
* Set up my environment, importing the Yahoo Finance library which allowed me to download the stocks of Amazon, Facebook, IBM and MMM over the last 60 months.
* Applied inferential statistical methods to draw insights from time-series data.

# ![Project 6 - Linear Regression](../blob/main/project%20files/Assignment%203.ipynb)
* Built a linear regression model to understand the drivers which influence car prices. 

### Common Algorithms
* Linear Regression
  * Used to estimate real values based on continuous variables (e.g. sales, house prices)
* Logistic Regression
  * Used to predict a binary outcome, usually for discrete data (e.g. winning a game vs. not, successful sale vs. not)
* Decision Tree
  * Used in classification problems (e.g. photos, bio samples)
* SVM (Support Vector Machine)
  * Used in classification problems where a point belongs to one group or another (e.g. height vs. hair length)
* Naive Bayes
  * Classification technique which assumes independence between predictors (e.g. probability of color, weight and shape predictors of fruit would be considered independently)
* kNN (k-nearest neighbour)
  * Classification mechanism which classifies data points based on majority votes of k neighbours
* K-Means
  * Classify a data set through clustering (e.g. types of clients)
* Random Forest
  * An ensemble of decision trees for classification problems
* Dimensionality Reduction Algorithms
  * Identifies the variables more significant to the analysis
* Gradient Boosting algorithms: 
  * GBM
  * XGBoost
  * LightGBM
  * CatBoost
