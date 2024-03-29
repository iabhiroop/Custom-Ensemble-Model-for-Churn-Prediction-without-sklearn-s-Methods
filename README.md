# Custom Ensemble Model for Churn Prediction without sklearn's Methods

This repository is an example of a custom ensmeble model done with the given dataset for churn prediction without the use of sklearn's in-built ensemble methods. A total of 6 models are part of the ensemble.

### Implementation Details
- **Data Preprocessing:** The dataset is preprocessed to handle any missing values, perform feature scaling, and encode categorical variables as needed.
- **Train-Test Split:** The dataset is split into a training set and a test set.
- **Individual Model Training:** Six different machine learning models are selected for the ensemble: Logistic Regression, Decision Tree, Support Vector Classifier, Naive Bayes, k-Nearest Neighbors, and Random Forest Classifier. Each model is trained independently on the training data.
- **Bagging:** Bags of the training data are created for each individual model to introduce randomness and diversity during training.
- **Ensemble Model Training:** The bags created for each model are used to train the ensemble. The trained ensemble model combines the predictions of individual models to make the final prediction.
- **Ensemble Model Evaluation:** The trained ensemble model is evaluated on the test data to assess its performance in churn prediction.

### Requirements
  - Python 3.x   

### Libraries:
  - numpy
  - pandas
  - scikit-learn (sklearn)

### How to Use the Repository
- **Clone the Repository:** Clone this repository to your local machine using the following command:
```
git clone [https://github.com/your_username/repo_name.git](https://github.com/iabhiroop/Ensemble-model-with-sklearn.git)
```
- **Install Dependencies:** Ensure you have Python 3.x installed and the required libraries by running-
```
pip install numpy pandas scikit-learn
```
- **Data Preparation:** Load the dataset or a new dataset in a format suitable for training the ensemble model.
- **Run the Code:** Execute the code that trains the ensemble model and evaluates its performance on the test data.
- **Analyze Results:** Examine the evaluation metrics and predictions generated by the ensemble model to gain insights into its performance.

### Contribution
Contributions to this repository are welcome! If you have suggestions for improvement, find any issues, or want to add additional features or models to the ensemble, please feel free to open an issue or submit a pull request. Together, let's enhance the churn prediction ensemble model and make it more effective.
