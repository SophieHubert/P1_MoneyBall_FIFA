# P1_MoneyBall_FIFA
Objective and hypothesis

To work on this database i used jupiter and mysql.

I answered to the following questions:
 - Rank players by market value.
 - best value for italian or english players taking penalties (10)
 - Best value for goalkeeping players


First I imported in jupyter notebook all the libraries needed to work on this database.
Then I loaded the data from MySQL. I choose mySQL as i used it to answer to my three questions.
 
 Data Cleaning:
  -For the data cleaning , I used functions as some columns needed to be converted in numerical data. 
  Also nan and null data had to be replaced and few columns have been dropped (33 columns).

Processing Data:
    - Dealing with outliers
    - Normalization
    - Encoding Categorical Data
    - Splitting into train set and test set

Model Validation
    - R2
    - MSE
    - RMSE
    - MAE

(My r2 is to low as all the data weren't loaded)