# Big_Mart-sales
This Kernel predicts the Item_sales by using various Item and Store/ Outlet Parameters. 
The cleaned data is encoded to create dummy variables for categorical features, feature scaled to normalize data.
K- fold Validation technique is used on data to create 5 sets of validation and training samples.
The prediction uses attributes such as Item_Visibility, Item_MRP, Outlet_location_Type, and Outlet_Size. 
The feature engineering was applied to data to modify certain columns into the desired format, Impute the missing values using Groupby means, mode and correct the errors.   
The sample sets are trained using Multivariate Linear regression, Decision Tree, Random Forests, Gradient Boosting algorithm and evaluated using multiple model evaluation techniques.
