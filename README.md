# Heart-Disease-Prediction

This is a binary classification problem and depending on several features the target value is either disease or healthy.
All the labels are cleaned and EDA stuff has been done. Then, Random Forest, Decision Tree and KNN algorithms applied to the 
data. Best accuracy was with Random Forest Classifier as it seems in accuracy score and confusion matrix.

Attribute Informations:
age (in years), 
sex (0=female, 1=male), 
cp : chest pain type (4 values),
trestbps : resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital)), 
chol : serum cholestoral in mg/dl,
fbs : fasting blood sugar > 120 mg/dl (1=true, 0=false),
restecg : resting electrocardiographic results (values 0,1,2), 
thalach : maximum heart rate achieved, 
exang : exercise induced angina (1=yes, 0=no), 
oldpeak : ST depression induced by exercise relative to rest,
slope = the slope of the peak exercise ST segment, 
ca = number of major vessels (0-3) colored by fluorosopy <br />
thal: 0 = normal; 1 = fixed defect; 2 = reversable defect <br />
target : 1 = heart disease ; 0 = no heart disease <br />

Needed Librares
------
* Pandas, numpy, matplotlib, seaborn, sklearn
