Data Preprocessing:

Loaded the dataset and checked for missing values.
Converted categorical variables with binary values ('yes'/'no') to numerical format (1/0).

Exploratory Data Analysis (EDA):

Checked the distribution of the target variable 'price' and other numerical features using box plots.
Visualized the correlation between numerical features using a heatmap.
Plotted distributions of 'bedrooms', 'bathrooms', and 'stories' using a density plot.

Model Building:

Split the data into training and testing sets.
Applied standard scaling to the numerical features.
Built a Linear Regression model and a K-Nearest Neighbors Regression model.
Evaluated the models using the R-squared score.

Predicting with Furnishing Status:

Processed the 'furnishingstatus' column to use it in the prediction.
Created dummy variables for the 'furnishingstatus' column.
Modified the dataset to include these dummy variables.
Built and evaluated the model again considering 'furnishingstatus' as a feature.

Conclusion:

Both models (with and without considering furnishing status) resulted in the same R-squared score, suggesting that adding 'furnishingstatus' didn't improve the model's performance in this case.
