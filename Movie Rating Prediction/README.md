# Movie Rating Prediction

This project is my submission for Task 2 of the CODSOFT Data Science Internship. The goal is to predict movie ratings using features from the IMDb India Movies dataset.

### Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Google Colab

### Dataset
- IMDb Movies India from Kaggle
- [Link to dataset](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)

### What I Did
- **Data Cleaning**: Loaded the dataset, handled encoding issues, and dropped rows with missing values in key columns.
- **Feature Engineering**:
    - Used `LabelEncoder` for the 'Genre' and 'Director' columns.
    - Applied one-hot encoding (using `pd.get_dummies`) to the top 10 most frequent actors from the 'Actor 1' column to create better features.
- **Modeling**:
    - Initially trained a `RandomForestRegressor` which yielded a low R² score of ~0.076.
    - To improve, I trained a `GradientBoostingRegressor` on the engineered features.
- **Evaluation**: The new model showed improvement, achieving an R² score of **0.106**.

### Final Model Performance
- **Mean Squared Error (MSE)**: 1.72
- **R² Score**: 0.106

### Visualization
A scatter plot was created to visualize the model's predicted ratings versus the actual ratings, showing a slight positive correlation.

### Hashtags
#codsoft #internship #machinelearning #regression #datascience
