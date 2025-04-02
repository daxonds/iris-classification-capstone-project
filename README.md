# Iris Classification Capstone Project

This project demonstrates a complete machine learning workflow for classifying iris flower species using the Iris dataset. It covers data loading, preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and logging for traceability. This notebook was developed as a university capstone project and is intended to showcase a clear and reproducible pipeline.

## Dataset

- **Source**: [Kaggle - Iris Dataset](https://www.kaggle.com/datasets/uciml/iris?resource=download)
- The dataset includes 150 samples with the following features:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
  - Species (target variable)

## Technologies Used

- Python (Google Colab environment)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Python logging module

## Project Workflow

1. **Data Loading**  
   Load the Iris dataset and configure logging for monitoring the pipeline execution.

2. **Data Cleaning and Feature Engineering**  
   - Drop the ID column
   - Rename columns for consistency
   - Create a new feature (`petal_area`) by multiplying petal length and width

3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics and correlation analysis
   - Visualizations including pair plots, box plots, and distribution plots

4. **Preprocessing**  
   - Encode the categorical target variable
   - Scale numeric features using `StandardScaler`
   - Split the dataset into training and testing sets

5. **Model Training and Evaluation**  
   - Train and compare multiple classification models (e.g., Logistic Regression, KNN, Decision Tree)
   - Evaluate using accuracy, confusion matrices, and classification reports

6. **Logging**  
   - Operational steps are logged to `application.log` for transparency

## Files Included

- `Iris_Classification_ML_Model_Capstone.ipynb` – Main Jupyter Notebook
- `Iris.csv` – Dataset file (must be in the same directory as the notebook)
- `application.log` – Log file generated during notebook execution

## How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Ensure `Iris.csv` is in the same directory.
4. Run all cells sequentially.
5. Check `application.log` for logging output (optional).
