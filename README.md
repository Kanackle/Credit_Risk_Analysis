# Credit_Risk_Analysis

##Purpose
The purpose of this analysis was to train various machine learning models on a sample database of credit card loans.
The models were to predict if the loan was low risk or high risk based on the data given.

##Results
0 -> high risk loans
1 -> low risk loans
Naive Random Oversampling:
<li>Accuracy: .645
![image](https://user-images.githubusercontent.com/33528884/212809937-ed40b5a3-e816-463d-9668-3c731d8f0a5d.png)
SMOTE Oversampling:
<li>Accuracy: .631
![image](https://user-images.githubusercontent.com/33528884/212810005-33b817ab-8aec-4385-9bfc-653d12ad3e05.png)
Cluster Centroids Undersampling:
<li>Accuracy: .580
![image](https://user-images.githubusercontent.com/33528884/212810058-17f35d98-291c-4218-bc68-285ebe3e3e82.png)
SMOTEENN:
<li>Accuracy: .580
![image](https://user-images.githubusercontent.com/33528884/212810274-2c8a99a7-7f91-483d-b859-9af46f0b02b0.png)
Balanced Random Forest:
<li>Accuracy: .885
![image](https://user-images.githubusercontent.com/33528884/212810632-1a6d0986-4fa1-4381-a261-b16eddc3cf1d.png)
Easy Ensemble:
<li>Accuracy: .553
![image](https://user-images.githubusercontent.com/33528884/212810662-922e64a6-5224-4058-a6f7-4c490a9d4f14.png)
