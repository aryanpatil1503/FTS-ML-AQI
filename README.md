# 28-05-21
Harshit Gaur - i have done cleaning,expolatory analysis,data manupulation, removed local outliers from training dataset.                                                                

Anjali Singh - I have done preprocessing of the data.on both of the dataset cities_by_day and cities_by_hour .I looked for the null values using using visualiztion with the help of heatmap  present in both the dataset and handled those NAN values using mean function in cities_by_day and with median in cities_by_hours i.e. NAN values are replaced with the mean and median of that respective columns.Then i removed the columns having maximum number of NAN values  and then I did some visualization part for both dataset.Also found the correlations and finally after that I visualized outliers using boxplot and in whatever columns i found large number of outliers ,in both of the dataset ,i handled them using Z score method , and finally i found my cleaned data.

After my cleaned , normalized dataset i trained the model using multiple regression and splitted my dataset into 80:20 ratio for training and testing part .
when i completed my model training and testing , i checked using R square that whether my model fits the best or not ..and i found 0.85 r square value in my city by datr and 0.56 value in my city by hour dataset. more close the value is to 1 more perfect is our model

After I completed my training for AQI , i used logistic regression to predict my categorical variable AQI Bucket 

Aryan Patil- performed cleaning of dataset using different functions and performed some feature engineering on the same.Found correlation of different features on AQI,performed basic visualisation and found outliers using IQR and Zscore and managed them. Trained the data on ML models. Used regression(accuracy 0.85) to predict AQI and normalised the data for the same. Used classification (svm) to predict AQI_BUCKET(accuracy 0.99)

Harsh Agarwal - Cleaned Data and applied some stats

Pihu Jain  - I have cleaned dataset by removing null values and removed the null values of category data by most frequent ones and removed outliers and done some data visualization.
 

