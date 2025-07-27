# Titanic Survival Prediction

This is my submission for Task 1 of the CODSOFT Data Science Internship. The goal was to use the Titanic dataset to build a model that predicts whether a passenger on the Titanic survived or not.

### Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab

### Dataset
Kaggle Titanic Dataset
https://www.kaggle.com/datasets/yasserh/titanic-dataset

### What I Did
- Cleaned the dataset by handling missing values (filling 'Age' and dropping 'Cabin').
- Encoded categorical variables ('Sex', 'Embarked') into numerical form using `LabelEncoder`.
- Split the data into training and test sets.
- Trained a `LogisticRegression` model.
- Evaluated model performance using accuracy, a confusion matrix, and a classification report.
- Plotted the survival rate by gender to visualize the results.

### Accuracy
The model achieved an accuracy of **78%** on the test data.

### Hashtags
#codsoft #internship #machinelearning #titanic #datascience
