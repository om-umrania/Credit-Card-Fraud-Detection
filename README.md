# Credit-Card-Fraud-Detection

This repository contains various machine learning models implemented to detect credit card fraud using the Credit Card Fraud Detection dataset.

## Dataset

The dataset used for this project can be found on Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

Additionally, the dataset is stored in Google Drive. You can download it from the following link:
[Download creditcard.csv](https://drive.google.com/file/d/178YzJ_VMbmQfvcUZn85WcNTJ5BlcFIMF/view?usp=sharing)

## Project Structure

│
├── data/
│ ├── creditcard.csv # Original dataset
│
├── notebooks/
│ ├── Logistic_Regression.ipynb
│ ├── Decision_Tree.ipynb
│ ├── Random_Forest_Classifier.ipynb
│ ├── Gradient_Boosting_Classifier.ipynb
│ ├── XGBoost_Classifier.ipynb
│
├── images/
│ ├── confusion_matrix_logistic_regression.png
│ ├── confusion_matrix_decision_tree.png
│ ├── confusion_matrix_random_forest.png
│ ├── confusion_matrix_gradient_boosting.png
│ ├── confusion_matrix_xgboost.png
│
├── requirements.txt
├── README.md
└── .gitignore

## Models and Results

The following models have been implemented and evaluated:

- **Logistic Regression** - Accuracy: 0.988
- **Decision Tree** - Accuracy: 1.0
- **Random Forest Classifier** - Accuracy: 0.997
- **Gradient Boosting Classifier** - Accuracy: 0.998
- **XGBoost Classifier** - Accuracy: 0.999
- **Random Forest Classifier** - Accuracy: 0.998
- **SVM_Classifier** - Accuracy: 0.997

## How to Run

1. Clone the repository:

```sh
   git clone https://github.com/your_username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
```
2. Install the dependencies:

```sh
Copy code
pip install -r requirements.txt
```

3. Download the dataset from Google Drive and place it in the data folder.

4. Run the notebooks or scripts:
- Notebooks: Open and run the Jupyter notebooks in the notebooks folder.
- Scripts: Execute the Python scripts in the scripts folder.

## Visualization
Confusion matrices and other visualizations are saved in the images folder.

## Contributing
Feel free to fork this repository and contribute by submitting a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgements
The dataset is provided by the Machine Learning Group at ULB.