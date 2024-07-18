## Adbot Ad Engagement Forecasting Challenge Fourth Position Solution

### Overview and Objectives of the Challenge
- The objective of this challenge is to accurately predict the number of clicks a client’s ad receives, one and two weeks into the future (in digital marketing, clicks refer to when someone views the advert and follows one of the hyperlinks in that advert). Winning solutions will further be required to submit a description of the variables that had the most significant impact on engagement (number of clicks). It is therefore important that the models you build are not only accurate, but also interpretable.

- `segregated_df.csv` was formed from `SampleSubmission.csv` just to streamline the submission generation pipeline.

- Use `LightGBM_Modeling_With_Feature_Importance` notebook to walk through the entire process of data preprocessing, modeling, feature importance analysis (Sensitivity report analysis) and submission generation.


### Data modeling

- The data was modeled using a time series approach. The data was split into timesplits. The data was split into 3 timesplits: 1. Train, 2. Validation and 3. Test. The train data was used to train the model, the validation data was used to validate the model and the test data was used to test the model. LightGBM was used to model the data.


### Feature Engineering using Lagged Features and Rolling Window Features

- Feature engineering was performed on the data. The data was lagged and rolling window features were created. The lagged features were created by shifting the data by a certain number of time periods. The rolling window features were created by taking the mean, median, sum, min and max of the data over 15 time periods. The lagged and rolling window features were used to train the model.


### LightGBM Modeling

- LightGBM was used to model the data. LightGBM is a gradient boosting framework that uses tree based learning algorithms. LightGBM was used to model the data because it is fast, efficient and accurate. LightGBM was used to model the data because it is able to handle large datasets with a large number of features. LightGBM was used to model the data because it is able to handle missing values and categorical features. LightGBM was used to model the data because it is able to handle imbalanced datasets. LightGBM was used to model the data because it is able to handle large datasets with a large number of features. LightGBM was used to model the data because it is able to handle missing values and categorical features. LightGBM was used to model the data because it is able to handle imbalanced datasets.


### Feature Importance Analysis

- The feature importance analysis was done using the SHAP library. The SHAP library was used to generate a summary plot of the feature importance. The summary plot was used to identify the most important features in the model.


### Sensitivity Report Analysis

- The sensitivity report analysis was done using the SHAP library. The SHAP library was used to generate a summary plot of the feature importance


### Submission Generation

- The submission was generated using the LightGBM model. The LightGBM model was used to predict the number of clicks a client’s ad receives, one and two weeks into the future. The submission was generated using the LightGBM model. The LightGBM model was used to predict the number of clicks a client’s ad receives, one and two weeks into the future.




