### 1) Find out number of observatoins and columns

9134 rows and 24 columns

### 2) Column data types

- Customer                          object
- State                             object
- Customer Lifetime Value          float
- Response                          object
- Coverage                          object
- Education                         object
- Effective To Date                 object
- EmploymentStatus                  object
- Gender                            object
- Income                             integer
- Location Code                     object
- Marital Status                    object
- Monthly Premium Auto               integer
- Months Since Last Claim            integer
- Months Since Policy Inception      integer
- Number of Open Complaints          integer
- Number of Policies                 integer
- Policy Type                       object
- Policy                            object
- Renew Offer Type                  object
- Sales Channel                     object
- Total Claim Amount               float
- Vehicle Class                     object
- Vehicle Size                      object


### 3) Check for number of unique categories for categorical variables

13 unique categorical variables


### 4) Check for missing values

There are zero missing values


### 5) Identify potential features for machine learning (some columns may not have predictive power)

Employment Status, customer, and Effective to Date are three features that are considered noise and do not add any value for predictve power.


### 6) Identify the target column 

All of these columns will be utilized as a target in order to complete clustering algorithem. For further analysis I can use the response column to analyze using Logistic Regression.

### 7) Look at the distribution of the target columns. for categorical type, find out if it is imblanced. For numeric type, see how it is distributed  (summary statistics, boxplot, histogram).

Monthly Premium Auto is heavily skewed as one of the columns. This feature contains many upper bound outliers and will have to be scaled in order for it to be included in the dataset. As of now I am aware that a number 3 standard deviations above or below the mean is considered an outlier. Therefore I will remove those above the mean of this feature which is 93.219291
