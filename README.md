# Credit_Risk_Analysis
## Analysis Overview
Using machine learning we will try to solve a real-world problem, credit card risk analysis. Credit risk is inherently an unbalance classification problem. In this analysis we will used a balance and unbalance score to solve weather a client is a low risk or high risk for credit default.  In addition, we will used six (6) models for comparison such as the Random Oversampling, SMOTE Oversampling, Cluster Centroids Undersampling, Combination Sampling, Random Forest Sampling, and Easy Ensemble Sampling.
## Results

1. Random Oversampling (Naive Random)
Balance Score 
![Random_Forest_Sampling_Balance_Score](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Random_Forest_Sampling_balance_score.PNG)

Precision and Recall Scores
![Random_Forest_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Random_Forest_Sampling.PNG)

2. SMOTE Oversampling
Balance Score 
![SMOTE_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/SMOT_random_Sampling_balance_score.PNG)

Precision and Recall Scores
![SMOTE_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/SMOT_random_Sampling.PNG)

3. Cluster Centroids Undersampling

Balance Score 
![Cluster_C_Sampling_Balance_Score](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Cluster_C_Sampling_balance_score.PNG)

Precision and Recall Scores
![Cluster_C_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Cluster_C_Sampling.PNG)

4. Combination Sampling 
Balance Score 
![Combination_Sampling_Balance_Score](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Combination_Sampling_balance_score.PNG)

Precision and Recall Scores
![Combination_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Combination_Sampling.PNG)

5. Random Forest Sampling 

Balance Score 
![Random_Forest_Balance_Score](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Random_Forest_Sampling_balance_score.PNG)

Precision and Recall Scores
![Random_Forest_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Random_Forest_Sampling.PNG)

6. Easy Ensemble Sampling 
Balance Score 
![Easy_Esem_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Easy_Ensem_Sampling_balance_score.PNG)

Precision and Recall Scores
![Easy_Esem_Sampling](https://github.com/rick2stack/Credit_Risk_Analysis/blob/main/Resources/Easy_Ensem_Sampling.PNG)

## Summary 
The purpose of this Machine Learning analysis is to determine if the client will be low risk or high risk to default on their credit.  First to note is that no sampling technique prove to be 100% correct in any of the 3 scores, balance score/precision score/recall score. However, if we decide that the main purpose is to accept as many customers as possible into a credit plan then we should focus on precision score. This will allow us to accept most low risk clients, even though we will risk of accepting some high-risk people.  The Easy Ensemble sampling model had a precision for low risk of 100% and over 90% on recall rates for both low and high risk.  Where the Easy Ensemble model fails is the precision for high risk, but that is okay if our main goal is to maximize all the low-risk credit customers.  


