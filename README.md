# Module_17_Credit_Risk_Analysis
UNC Bootcamp - Module 17 Challenge

## OVERVIEW
The goal of this project was to determine which, if any, of six modeling processes for machine learning would provide a better prediction of high-risk credit card consumers.  The data was supplied from LendingClub in a csv format.  The data was oversampled with RandomOverSampler and SMOTE algorithms, undersampled with the ClusterCentroids algorithm, and a combination of the two with the SMOTEENN algorithm.  Two machine learning models, BalanceRandomForestClassifier and EasyEmsembleClassifer, were also applied to the data.

## RESULTS
The following results were derived from the testing.  Below are images of the sampling results for all six models.  <br><br>
•	The Balanced Accuracy Scores for each model were: <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Naive Random Oversampling:  65% <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	SMOTE Oversampling:  63% <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Undersampling: 52% <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Combination (Over and Under) Sampling:  64% <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Balanced Random Forest Classifier :  79% <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Easy Ensemble AdaBoost Classifier: 93% <br><br>

•	The Precision Scores for high-risk for each model were:<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Naive Random Oversampling:  1%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	SMOTE Oversampling:  1%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Undersampling: 1%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Combination (Over and Under) Sampling:  1%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Balanced Random Forest Classifier :  4%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Easy Ensemble AdaBoost Classifier: 7%<br><br>

•	The Recall Scores for high-risk for each model were:<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Naive Random Oversampling:  63%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	SMOTE Oversampling:  60%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Undersampling: 60%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Combination (Over and Under) Sampling:  69%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Balanced Random Forest Classifier :  67%<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Easy Ensemble AdaBoost Classifier: 91%<br><br>

## Summary






## <i><b>Naive Random Oversampling </i></b>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/NRO11.png" width="85%" heigth="600"> 
</br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/NRO12.png" width="85%" heigth="600"> 
</br></br>


## <i><b>SMOTE Oversampling </i></b>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/SMOTE21.png" width="85%" heigth="600"> 
</br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/SMOTE22.png" width="85%" heigth="600"> 
</br></br>

## <i><b>Undersampling </i></b>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/US31.png" width="85%" heigth="600"> 
</br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/US32.png" width="85%" heigth="600"> 
</br></br>


## <i><b>Combination (Over and Under) Sampling   </i></b>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/COU41.png" width="85%" heigth="600"> 
</br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/COU42.png" width="85%" heigth="600"> 
</br></br>

## <i><b>Balanced Random Forest Classifier </i></b>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/BRFC51.png" width="85%" heigth="600"> 
</br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/BRFC52.png" width="85%" heigth="600"> 
</br></br>


## <i><b>Easy Ensemble AdaBoost Classifier   </i></b>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/EEAC61.png" width="85%" heigth="600"> 
</br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <img src="Static/Images/EEAC62.png" width="85%" heigth="600"> 
</br></br>
