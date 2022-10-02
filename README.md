# Credit_Risk_Analysis

### Projec Overview 

The goal of the project is to create insight in using Machine Learning statistical algorithms to make predictions relying on data style available. In this challenge there’s more focus on Supervised Learning using a free data set to access and predict credit risk. It is called Supervised Learning because the data includes labeled outcome. 

In order to successful complete the analysis, we use different Machine Learning techniques to train and evaluate the data. The data we use has an unbalanced classification issue which stems from the number of good loans outweighing the amount of risky loans. For more reasonable prediction and improve the accuracy score Machine Learning algorithms were needed to be implemented and utilized to resample the data. These algorithms include RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifer, and EasyEnsembleClassifier

### Resources 
* Dataset from : [LoanStats_2019Q1]()

#### Deliverable 1: Resampling to Predict Credit Risk

Oversampling

<img width="406" alt="Screen Shot 2022-10-02 at 4 53 08 PM" src="https://user-images.githubusercontent.com/106555873/193475789-d46977f1-5ee3-407c-a361-0dae4401fc37.png">

The high risk precision rate was only 1% with the recall at 66% with an F1 score of 2%
Low risk had a precision rate of 100% and recall at 62%

<img width="736" alt="predicted_high_risk" src="https://user-images.githubusercontent.com/106555873/193475830-4efd070a-39b0-447c-a74a-9940486432f4.png">

Undersampling 

<img width="341" alt="undersampling_balance" src="https://user-images.githubusercontent.com/106555873/193475842-8469f95f-ec75-4f3c-beb4-78e3023a795f.png">

The high risk precision rate again was only at 1% with the recall at 69% with at F1 score of 1%
Low risk had a precision rate of 100% and with a lower recall at 40% compared to the oversampling models 

<img width="590" alt="predicted_undersasampling" src="https://user-images.githubusercontent.com/106555873/193475861-27787eda-a2c7-4ac3-b124-421910326871.png">

#### Deliverable 2. SMOTEENN algorithm to Predict Credit Risk

<img width="490" alt="Screen Shot 2022-10-02 at 2 23 38 PM" src="https://user-images.githubusercontent.com/106555873/193475874-ce0d24b6-5a16-4177-963a-5bc1dc682add.png">

<img width="585" alt="Screen Shot 2022-10-02 at 2 24 12 PM" src="https://user-images.githubusercontent.com/106555873/193475887-34cf6dcb-88cc-454e-8205-a93476f9aee1.png">

#### Deliverable 3

<img width="459" alt="balance_accuracy" src="https://user-images.githubusercontent.com/106555873/193475918-ea1d46ab-7312-41d9-b952-c84e4359448d.png">
<img width="349" alt="predict_high_risk" src="https://user-images.githubusercontent.com/106555873/193475932-a2ba8a2d-3134-4b28-bea6-ad7803de3a8a.png">
<img width="531" alt="features" src="https://user-images.githubusercontent.com/106555873/193475942-039eed0b-f2b6-4fc5-861c-dfba698f0044.png">
<img width="686" alt="Screen Shot 2022-10-02 at 4 59 50 PM" src="https://user-images.githubusercontent.com/106555873/193476075-aaa42399-4971-42cc-91a5-f066088ec2c4.png">
