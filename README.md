# Authorship Attribution Application

## Overview

This project developed an **Authorship Attribution Application** for a machine learning project. The goal was to classify tweets from five distinct Twitter accounts: `BBCBreaking`, `Caradelevingne`, `justinbieber`, `ImRaina`, and `shahidkapoor`. Tweets were obtained using the Twitter API, cleaned using regular expressions, and then represented using a Bag of Words (BoW) model. 

The data was shuffled and split into training and testing sets. Various machine learning models were used for authorship attribution, including **k-Nearest Neighbors (k-NN)**, **Neural Networks (NNs)**, and ensemble methods like **Random Forest Classifier**. Among all models, the **Random Forest Classifier** achieved the highest accuracy, reaching approximately **85%**.

## Libraries and Technologies Used

- `numpy`
- `pandas`
- `sklearn` (for machine learning models and metrics)
  - `RandomForestClassifier`, `LogisticRegression`, `SVC`, `MLPClassifier`, `KNeighborsClassifier`
  - `GradientBoostingClassifier`, `VotingClassifier`
  - `train_test_split`, `GridSearchCV`, `validation_curve`
  - `classification_report`, `accuracy_score`, `confusion_matrix`
- `matplotlib` and `seaborn` (for visualizing results)

## Workflow

1. **Data Collection**: Tweets were collected using the Twitter API from five distinct Twitter accounts.
2. **Data Pre-processing**: The tweets were cleaned using regular expressions, removing unwanted characters, punctuation, and URLs.
3. **Feature Extraction**: A Bag of Words representation was created for each tweet.
4. **Modeling**: The data was split into training and test sets. Various machine learning models were trained and tested on the data:
   - **k-NN**, **Neural Networks**, **Random Forest Classifier**, and other ensemble methods.
5. **Evaluation**: The models were evaluated using accuracy and confusion matrix visualizations, with **Random Forest Classifier** providing the best performance (~85%).

## Results

- **Highest Accuracy**: Random Forest Classifier (~85% accuracy)
- **Visualizations**: Confusion matrix and classification reports for model performance.

---

Feel free to explore the code and models to dive deeper into the project. Contributions and improvements are always welcome!
