# Bank_Marketing
Preprocessing data, analysis, find insights and create best model for prediction.

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

Original Source: UCI Machine Learning RepositorySource 
Link: [Bank_Marketing_Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing).

### Models Used
- Random Forest Classifier
- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

Model performance was optimized by tuning hyperparameters using both Grid Search and Randomized Search strategies.

### Best Model: 
- Random Forest ClassifierOutcome(Random Search Random Forest): 
  The Random Forest model achieved the absolute highest F1-Score (0.919987) and a near-perfect ROC-AUC (0.970911). This confirms it is highly effective identifying successful term deposit subscribers without creating excessive false positives.

### Deployment: 
This winning architecture was saved as a unified pipeline asset named bank_marketing_production_model.pkl and is fully ready to generate predictions on future raw marketing data.

## Model Download

The production model is available in the [Releases](https://github.com/NamithaDaney/Bank_Marketing/releases) section.

Download the latest version:
- [Bank Marketing Model v1.0.0](https://github.com/NamithaDaney/Bank_Marketing/releases/download/v1.0.0/your_file.bin)
