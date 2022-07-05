# DohaAhmad-Diabetes-Indicator-Machine-Learning-Project-
Machine Learning project
Project Name: Diabetes Binary Health Indicators
Our project (Diabetes Binary Health Indicators) used to determine whether the person is suffering from diabetes or not based on some data.
This project uses supervised learning, using classification methods.
Firstly, we made data preprocessing includes: 
	Data cleaning (removing nulls if exist, removing duplicates)
	Splitting data into Features (x) and Target (y)
	Saving preprocessed dataset into files to make it easy to recall data and processes the code easily 
	Balancing data using over-sampling & under-sampling as the data wasn’t balanced 
	(Bonus)Appling standard-scaling on X-features to make processing easier 

Secondly, we applied Algorithms before Feature selection:
	Splitting data into Test data (30%) & Train data (70%)
	Appling Logistic regression with: accuracy = 73%, precision= 72%, F1-score = 73% and confusion matrix = [(41463 16886 14439 43839)]
	(bonus)Appling Random Forest with: accuracy = 93%, precision = 89%, F1-score = 93% andconfusion matrix = [(51352 6997 719 57559)] 
	Appling Decision Tree with: accuracy = 90%, precision = 85%, F1-score = 91% and confusion matrix = ⌊(48297&10052@860&57418)⌋
	Appling Svm (with under-sampling) with: accuracy = 73%, precision = 71%, F1-score = 74% andconfusion matrix = ⌊(7180&3288@2405&8186)⌋
Thirdly, we applied Algorithms After Feature selection
Using correlation method, dropping columns with correlation less than 0.1 with target column (Diabetes binary) Taking 10 features:
	(bonus)Visualizing correlation of all data in a diagram 
	Splitting data into Test data (30%) & Train data (70%)
	Appling Logistic regression with: accuracy = 72.7%, precision= 71.8%, F1-score = 73% and confusion matrix = ⌊(41297 17052 14761 43517)⌋
	(bonus)Appling Random Forest with: accuracy = 84%, precision = 80%, F1-score = 85% and confusion matrix = (45951 12398 5992 52286)⌋    
	Appling Decision Tree with: accuracy = 83%, precision = 80%, F1-score = 84% and confusion matrix = ⌊(45708 12641 6587 51691)⌋  
	Appling Svm (with under-sampling) with: accuracy = 72.4%, precision = 70.8%, F1-score = 73.6% and confusion matrix = ⌊(7129 3339 2468 8123)⌋









