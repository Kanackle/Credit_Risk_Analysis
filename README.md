# Credit_Risk_Analysis

##Purpose
The purpose of this analysis was to train various machine learning models on a sample database of credit card loans.
The models were to predict if the loan was low risk or high risk based on the data given.

##Results
0 -> high risk loans
1 -> low risk loans
Naive Random Oversampling:
<li>Accuracy: .645 </br>
![image](https://user-images.githubusercontent.com/33528884/212809937-ed40b5a3-e816-463d-9668-3c731d8f0a5d.png) </br>
SMOTE Oversampling:
<li>Accuracy: .631 </br>
![image](https://user-images.githubusercontent.com/33528884/212810005-33b817ab-8aec-4385-9bfc-653d12ad3e05.png) </br>
Cluster Centroids Undersampling:
<li>Accuracy: .580 </br>
![image](https://user-images.githubusercontent.com/33528884/212810058-17f35d98-291c-4218-bc68-285ebe3e3e82.png) </br>
SMOTEENN: 
<li>Accuracy: .580 </br>
![image](https://user-images.githubusercontent.com/33528884/212810274-2c8a99a7-7f91-483d-b859-9af46f0b02b0.png) </br>
Balanced Random Forest:
<li>Accuracy: .885 </br>
![image](https://user-images.githubusercontent.com/33528884/212810632-1a6d0986-4fa1-4381-a261-b16eddc3cf1d.png) </br>
Easy Ensemble:
<li>Accuracy: .553 </br>
![image](https://user-images.githubusercontent.com/33528884/212810662-922e64a6-5224-4058-a6f7-4c490a9d4f14.png) </br>

##Summary
As can be shown from all the images, the precision score is less reliable than the recall score. The most accurate model is the Balanced Random Score. It has an accuracy score of .885 which triumphs all other accuracy scores of other models. It also has high sensitivity scores for both low risk and high risk loans. This means the majority of low and high risk loans were predicted correctly. 
