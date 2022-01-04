# Heart-Disease-Classification
This repo contains a notebook that looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes. 

See Jupyter Notebook for details

## Conclusion:
Through modelling and experimentation, we concluded that LogisticRegression is the best model for our problem. 

#### Hyperparameters
- C = 0.20433597178569418
- solver = liblinear

#### ROC Curve and AUC score

![image](https://user-images.githubusercontent.com/59708469/148119321-a55e6982-0f20-4dc7-b4c1-a2ea5c631b5b.png)

#### Confusion Matrix

![image](https://user-images.githubusercontent.com/59708469/148119405-ca284cdd-db51-4a82-875d-86e5839df077.png)


#### Cross-Validated Classification Metrics
- 'accuracy': 0.8446994535519124
- 'precision': 0.8207936507936507
- 'recall': 0.9212121212121213
- 'f1': 0.8673007976269721

![image](https://user-images.githubusercontent.com/59708469/148119470-30f77f11-e111-4db3-b262-66487c0e2116.png)

#### Feature Importance for future improvements

- 'age': 0.0031672721856887734
- 'sex': -0.860445816920919
- 'cp': 0.6606707303492849
- 'trestbps': -0.011569930902919925
- 'chol': -0.001663741604035976
- 'fbs': 0.04386130751482091
- 'restecg': 0.3127578715206996
- 'thalach': 0.02459360818122666
- 'exang': -0.6041303799858143
- 'oldpeak': -0.5686285194546157
- 'slope': 0.4505161679452401
- 'ca': -0.6360986316921434
- 'thal': -0.6766337521354281

![image](https://user-images.githubusercontent.com/59708469/148119716-ab2ae314-78c0-4453-8f86-4ace66654c25.png)




