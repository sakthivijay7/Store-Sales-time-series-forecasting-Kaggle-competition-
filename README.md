# Store-Sales-time-series-forecasting-Kaggle-competition-
Kaggle competition page: https://www.kaggle.com/competitions/store-sales-time-series-forecasting

Data collection:
Data collect from kaggle compatition page.Datasets oil,holiday_events,train,test,stores,transactions in csv format.

Data handle:
pandas to read all the files and check null values.

Null values:
"dcoilwtico" fill with forwardfill & backwardfill,"transactions fill with 0.

Combine files:
Extract the holiday_event files values by National,Regional,Local types and all files merge with "date","store_nbr".

Encoding:
OrdinalEncoder to encoding the categorical values.

Date Extraction:
Extract the date values by day,month,year,weekday,weekofyear,is_weekend.

Features:
selected the importent features in training data.

Target:
"Sales"

Split data:
Data split by date "2017-01-01" before and after.

Model:
Trainning a model with XGBRegressor algorithm.

Validation:
Model predicted root_mean_squared_error  327.03.

Submission:
Submit the dataframe value of test_id:"id", predicted:"sales" in csv format.

Result:
Got error score 2.30706  ,leaderboard 721.


