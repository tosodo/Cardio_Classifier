 ### Cardio_Classifier
### Name :  Thomas Osodo 
 ### Predicting (CVD) Using Machine Learning(ML).

  

 
### Predicting (CVD) Using Machine Learning(ML).

Machine learning has demonstrated truly life-impacting potential in healthcare – particularly in the area of medical diagnosis. 

One in four deaths in Britain is caused by CVD and has a very high human and Economic cost.

Figures released by the Centre for Economic and Business Research shows the total cost of CVD in the UK is set to rise by over £3billion in the next six years, from around £15billion in 2014 to over £18billion in 2020.

I used dataset from https://www.kaggle.com/sulianova/cardiovascular-disease-dataset .
I used mainly information from several sources with facts and figures from 
https://www.bhf.org.uk/what-we-do/our-research/heart-statistics/heart-statistics-publications/cardiovascular-disease-statistics-2019.

https://www.england.nhs.uk/ourwork/clinical-policy/cvd/.

You can also link to 
* [Your Email](osodot@icloud.com)
* [Your Linked In](https://www.linkedin.com/in/thomas-osodo-6961041a/)
* [Your Twitter?]()



 ### Executive Summary

7 Million people have a (CVD)condition in the entire country and plenty of resources used to manage and treat (CVD). Early intervention and prediction can add value to person(s) at risk of (CVD).Saving the tax payer,Lives and the economy interms of productivity . 

Applying Machine learning Models by analysing data using different classifier algorithms to predict the risk of (CVD) i found an accuracy prediction of 73% .

Automated diagnosis is less time consuming and an effective tool a secong pair of eyes for the clinician.

Solving a problem with machine learning often involves many iterative experiments to find the best model for solving the problem by further tuning the model.

### Analyze and perform EDA on the Dataset
### Applying knowledge of CRISP-DM methodology.


I used data from kaggle [https://www.kaggle.com/sulianova/cardiovascular-disease-dataset] 


After experimenting with different algorithms, the mean F1 scores, in cross-validation, gained by each classifier is presented below. Given that accuracy is considered the most intuitive measure, it has also been plotted on the graph.

As you can see from the graph, the classifiers are showing pretty good results in terms of being able to better distinguish patients who have cvd versus those who are healthy by reaching 0.73% F1 scores.

The best value for F1 is 1, and the worst value is 0. In order to gain higher scores.

The goal of this project was to create a classification model that was able to predict cardiovascular diseases.

 1. 1 in 4 deaths in the UK is Cardiovascular related,using modern machine learning algorithms can improve the chances of early prediction .
 2. Automating the diagnostic process will save clinical time and save lives . This will also reduce the number of misdiagnosed cases , which account for 1 in 3 cases .
 
 


### More Information

Machine learning in a cvd context is digital diagnosis. ML can detect patterns of cvd within a patient electronic healthcare records and inform clinicians of any anomalies .

As machine learning and data science are starting to be adopted as a tool in healthcare applications, the industry is slowly pushing the boundaries on what it can do.

In order to get started modeling, the data set was split into two parts:

Train set (75%), for choosing and validating models, and
Test set (25%), hold out data on which I will see how well models are able to generalize on unseen data.

Based on these numbers I define the metrics as follows:

-Accuracy – ratio of correctly classified patients to the total number of patients (Accuracy = (TP+TN)/(TP+FP+FN+TN)).

-Precision – ratio of correctly classified patients with cvd to the total patients classified as having cvd. The intuition behind precision is how many patients classified as having cvd truly have the cvd . (Precision = TP/TP+FP).

Recall – ratio of correctly classified cvd patients to patients who have the cvd. The intuition  behind recall is how many patients who have cvd classified as having the cvd. (Recall = TP/TP+FN).

The potential of machine learning within the medical industry is revealed through this in-depth example of how the technology can be applied to provide a medical diagnosis in this case, the prediction and diagnosis of cardiovascular disease. 

Evaluating Output Quality Through Receiver Operating Curves(ROC).

### Model Scores.
Training AUC: 74.38%
Test AUC:     73.77%


<p align="center">
  <img width="700" height="600" src="https://github.com/tosodo/Cardio_Classifier/blob/master/Images/Screenshot%202020-04-28%20at%2017.14.32.png">
</p>
<p align="center">
  <img width="700" height="600" src="https://github.com/tosodo/Cardio_Classifier/blob/master/Images/Screenshot%202020-04-28%20at%2017.12.59.png">
</p>




