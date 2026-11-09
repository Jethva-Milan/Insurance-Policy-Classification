# Insurance Policy Classification Using Machine Learning

## Project Overview

This project uses machine learning classification algorithms to predict whether a customer has taken an insurance policy. It includes data preprocessing, exploratory data analysis, model training, and performance comparison.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithms

The project compares six classification algorithms:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Support Vector Machine (SVM)
6. Gaussian Naive Bayes

## Project Workflow

- Load and inspect the insurance dataset.
- Check missing values and duplicate records.
- Remove duplicate records and the `Policy_Status` column.
- Encode categorical variables.
- Split data into training (80%) and testing (20%) sets.
- Apply feature scaling where used by the models.
- Train and evaluate six classification algorithms.
- Compare accuracy, precision, recall, and F1-score.
- Visualize customer data and model performance.

## Model Results

| Algorithm           | Accuracy | F1-score |
| ------------------- | -------: | -------: |
| Logistic Regression |   78.92% |   88.22% |
| Decision Tree       |   69.91% |   80.51% |
| Random Forest       |   82.78% |   90.16% |
| KNN                 |   77.85% |   87.05% |
| SVM                 |   78.92% |   88.22% |
| Naive Bayes         |   80.29% |   88.80% |

Random Forest achieved the highest accuracy (82.78%) and F1-score (90.16%) among the tested models in this recorded experiment.

## Dataset

The code expects a CSV file named `insurance_40000_clean.csv`. Add the dataset to the repository if you have permission to share it.

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Place the dataset in the expected project location.
4. Run `insurance_2.py` or open `Insurance_2.ipynb` in Google Colab.
5. Execute the cells or script to train and evaluate the models.

## Project Type

Academic Machine Learning Classification Project.
