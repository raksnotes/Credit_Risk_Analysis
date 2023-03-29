# Credit_Risk_Analysis

## Purpose: 
The purpose of this analysis was to create and compare multiple Machine Learning Models to predict Credit Risk and ultimately make a recommendation as to whether or not these ML models are useful. 

## Results: 

-The Ensemble Classifiers had the highest accuracy scores 
-The EasyEnsemble Classifier had the maximum accuracy score at 0.93. 
-The Undersampling Model had the minimum accuracy score at 0.54. 

### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/116187123/228410733-86235da0-e636-49ca-97c1-7c8c892c4769.png)

### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/116187123/228410815-1fdfea5d-98e5-494b-aa2d-20646d8f3caf.png)

### Undersampling
![image](https://user-images.githubusercontent.com/116187123/228410874-ed479a8c-7e2e-4584-9665-564b4a724052.png)

### Combination (Over and Under) Sampling
![image](https://user-images.githubusercontent.com/116187123/228410924-06cbf074-485c-429b-ab84-d47f857a5b68.png)

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/116187123/228410997-96029e53-34e5-4835-b654-4ae7c39c19ce.png)

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/116187123/228411048-1867c740-2003-45e5-bc0f-922ae30cbb29.png)


## Summary: 

I would recommend the Easy Ensemble AdaBoost Classifier Model due to the fact that it has the highest accuracy score. The second highest was also in the Ensemble Classifier Group, so I think that Ensemble Classifiers are useful in predicting credit risk. 

## Challenges: 
One challenge that I'd run into while compiling the code, is that the code was not running when I had initially checked the balance of target counts. 
As shown below, I had a continual error that 'y was not defined' or a KeyError at 'loan_status', however, once I removed that variable, I was able to run it
successfully, as shown in the following screenshot. In the previous line of code, when initializing the target, y is the dataframe that contains loan_status. 
![image](https://user-images.githubusercontent.com/116187123/228414544-0992f717-830a-4658-91f7-9d33a6b768b2.png)
![image](https://user-images.githubusercontent.com/116187123/228414992-e8d4094b-d964-492a-a338-8a2427ee95cf.png)


