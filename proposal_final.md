### 1) Find out number of observatoins and columns

9134 rows and 24 columns

### 2) Column data types

Customer                          object
State                             object
Customer Lifetime Value          float64
Response                          object
Coverage                          object
Education                         object
Effective To Date                 object
EmploymentStatus                  object
Gender                            object
Income                             int64
Location Code                     object
Marital Status                    object
Monthly Premium Auto               int64
Months Since Last Claim            int64
Months Since Policy Inception      int64
Number of Open Complaints          int64
Number of Policies                 int64
Policy Type                       object
Policy                            object
Renew Offer Type                  object
Sales Channel                     object
Total Claim Amount               float64
Vehicle Class                     object
Vehicle Size                      object
dtype: object


### 3) Check for number of unique categories for categorical variables

13 unique categorical variables


### 4) Check for missing values

There are zero missing values


### 5) Identify potential features for machine learning (some columns may not have predictive power)

Employment Status, customer, and Effective to Date are three features that are considered noise and do not add any value for predictve power.


### 6) Identify the target column 

All of these columns will be utilized as a target in order to complete clustering algorithem. For further analysis I can use the response column to analyze using Logistic Regression.

### 7) Look at the distribution of the target columns. for categorical type, find out if it is imblanced. For numeric type, see how it is distributed  (summary statistics, boxplot, histogram).



