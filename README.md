# house-price-prediction
Estimating future house prices by combining a number of different machine learning models

After conducting feature engineering, data preprocessing, and building various regression models, we obtained the following results:

While comparing the individual models, ElasticNet regression achieved the best performance on the House Prices dataset, with a root-mean-squared-error (RMSE) of 0.1229438 on the test set.

The other regression models, including Support Vector Regressor, XGBoost Regressor, and the LGBMRegressor also achieved relatively good performance on the dataset, with RMSEs 0.1235645, 0.1257572 and 0.1327230 respectively on the test set.

The blended model, which combined the predictions of the five regression models, achieved an even lower RMSE of 0.0656923 on the test set.

Therefore, in this analysis, the Elastic Net and SVR models perform better than the XGBoost and LightGBM models in predicting house prices. However, blended model takes the strengths and weaknesses of each model and produces the lowest RMSE of 0.0656923

