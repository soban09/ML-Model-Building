# ML Model Building

### About the dataset
The dataset for this Machine Learning competition consists of profiles from 2000 users on a matrimony website. Each profile can be assigned one of three labels: "approved," "deleted," or "pending," based on whether it meets certain criteria set by the company.

Each profile in the dataset can be described by a set of features, such as the user's age, occupation, location, interests, and other relevant attributes. These features can be used as input to Machine Learning algorithms to build a model that can accurately predict the profile's class label.

### Goal
The goal of this competition is to build a model that can accurately predict the class label of new, unseen profiles with a high degree of accuracy.

### Preprocessing
* Checking NULL values
* Label encoding
* Standard Scaling

### Models used and their accuracy
* Logistic Regression : 0.6558
* Random Forest Classifier : 0.6911
* SVM Classifier : 0.6647
* Graident Boosting : 0.7176
* XgBoost : 0.6588
* Voting Classifier : {Logistic, RandomForest, SVM} : 0.6764

### Result
The model was able to predict with a accuracy of 67% in average cases when applied on testing datasets.  
