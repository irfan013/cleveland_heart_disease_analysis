# Machine learning to Cleveland heart disease dataset

Dataset source: https://archive.ics.uci.edu/ml/datasets/heart+disease

## Descriptions of the dataset
### Dependent variable
- hd: diagnosis of heart disease (angiographic disease status), the predicted attribute

### Independent variables (features)
- age: age in years
- sex: sex (1 = male; 0 = female)
- cp: chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 4 = asymptomatic)
- trestbps: resting blood pressure (in mm Hg on admission to the hospital)
- chol: serum cholestoral in mg/dl
- fbs: (fasting blood sugar > 120 mg/dl)  (1 = true; 0 = false)
- restecg: resting electrocardiographic results (0 = normal; 1 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV); 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
- thalach: maximum heart rate achieved
- exang: exercise induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment (1 = upsloping; 2 = flat; 3 = downsloping)
- ca: number of major vessels (0-3) colored by flourosopy
- thal: Thalium heart scan (3 = normal; 6 = fixed defect; 7 = reversable defect)

### Analysis performed (Classification tree)
 - Importing the dataset
 - Explaining the features and target variable
 - Dealing with the missing values
 - Performing One-hot Encoding
 - Spliting the original dataset into the train set (80%) and the test set (20%) with addition of random state and stratification
 - Performing the training with Decision Tree Classifier
 - Producing a tree diagram of the Decision Tree
 - Finding the Confusion Matrix, Classification report, and ROC-AUC
