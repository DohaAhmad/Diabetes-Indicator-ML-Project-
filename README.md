# Diabetes-Indicator-Machine-Learning-Project
Diabetes-Indicator-Machine-Learning-Project
Machine Learning project name: Diabetes Binary Health Indicators Our project (Diabetes Binary Health Indicators) is used to determine whether a person is suffering from diabetes or not based on some data. This project uses supervised learning, using classification methods.

Firstly, we made data preprocessing includes the following:

1. Data cleaning (removing nulls if they exist, removing duplicates)

2. Splitting data into Features (x) and Target (y)

3. Saving preprocessed dataset into files to make it easy to recall data and processes the code easily

4. Balancing data using over-sampling & under-sampling as the data wasn’t balanced

5. Applying standard scaling on X-features to make processing easier

Secondly, we applied Algorithms before feature selection:

1. Splitting data into Test data (30%) & Train data (70%)

2. Applying Logistic regression with: accuracy = 73%, precision= 72%, F1-score = 73% and confusion matrix = [(41463 16886 14439 43839)]

3. Applying Random Forest with: accuracy = 93%, precision = 89%, F1-score = 93% and confusion matrix = [(51352 6997 719 57559)]

4. Applying Decision Tree with: accuracy = 90%, precision = 85%, F1-score = 91% and confusion matrix = ⌊(48297 10052 860 57418)⌋

5. Applying Svm (with under-sampling) with: accuracy = 73%, precision = 71%, F1-score = 74% and confusion matrix = ⌊(7180 3288 2405 8186)⌋

Thirdly, we applied Algorithms After Feature selection using the correlation method, dropping columns with a correlation less than 0.1 with the target column (Diabetes binary) Taking 10 features:

1. Visualising the correlation of all data in a diagram

2. Splitting data into Test data (30%) & Train data (70%)

3. Applying Logistic regression with: accuracy = 72.7%, precision= 71.8%, F1-score = 73% and confusion matrix = ⌊(41297 17052 14761 43517)⌋

4. Applying Random Forest with: accuracy = 84%, precision = 80%, F1-score = 85% and confusion matrix = (45951 12398 5992 52286)⌋

5. Applying Decision Tree with: accuracy = 83%, precision = 80%, F1-score = 84% and confusion matrix = ⌊(45708 12641 6587 51691)⌋

6. Applying SVM (with under-sampling) with: accuracy = 72.4%, precision = 70.8%, F1-score = 73.6% and confusion matrix = ⌊(7129 3339 2468 8123)⌋

## Screenshots
![data set](https://user-images.githubusercontent.com/103465018/177391962-6f286d3f-1d7c-4069-b26e-02cfb759481d.PNG)

 - Data Set Visualization 
 
![describtion](https://user-images.githubusercontent.com/103465018/177391982-64f53610-4dc4-4761-b253-3a882fb277f8.PNG)

 - Data Set Decsribtion
 
![de](https://user-images.githubusercontent.com/103465018/177391994-ab82841e-b112-47ac-850b-06e477913bc1.PNG)

 - Correlation Graph Plot
 
![logistic](https://user-images.githubusercontent.com/103465018/177392010-f6cccedb-d332-4c73-b66d-bc5452267453.PNG)

 - Logistic Regression Algorithm
 
![decision tree](https://user-images.githubusercontent.com/103465018/177392023-c2ce7e4e-cad9-43d7-bff4-5abd8affd835.PNG)

 - Decision Tree Algorithm
 
![random forest](https://user-images.githubusercontent.com/103465018/177392034-5ba586de-6fa6-4c6b-9a07-29c5c4c4260b.PNG)

 - Random Forest Algorithm
 
![svm](https://user-images.githubusercontent.com/103465018/177392047-21361ec6-584d-42d4-8538-d2dd661b20d1.PNG)

 - SVM Algorithm







