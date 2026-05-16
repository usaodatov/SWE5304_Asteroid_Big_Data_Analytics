# SWE5304 Asteroid Big Data Analytics Project

## Project Description

The purpose of this project is to perform an analysis of a NASA/Kaggle asteroid dataset and to gain insights into factors that contribute to Potentially Hazardous Asteroids (PHAs) through the application of Python Big Data Analytics tools and techniques for the cleaning, visualisation, and classification of the asteroid data set.

---

## Topic

### Asteroid Classification for Planetary Defence Using Big Data Analytics

The reason for this project topic was because of the need for asteroid detection in regards to planetary science and safety. The topic is also a good application of Big Data Analytics in a context where a large dataset is available, and the information provided in the data set is complex and contains numerous numerical features that contribute to the classification of a given asteroid.

---

## Dataset

The dataset to be used in this project is the NASA/Kaggle Asteroid Dataset.

Dataset source: https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset

The dataset consists of several features, including:

- Asteroid name
- Near-Earth Object
- Potentially Hazardous Asteroid
- Magnitude
- Diameter
- Orbital characteristics

---

## Tooling & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

---

## Project Description

This project is a complete Big Data analysis performed in 12 steps:

1. Load and inspect the asteroid dataset
2. Identify number of rows, columns, and data types
3. Perform Data Cleaning to handle missing values and duplicated records
4. Clean the target column of the dataset
5. Select appropriate features for classification
6. Generate Descriptive Statistics
7. Create visualisations
8. Visualise potential outliers and examine correlations
9. Split data and prepare for ML
10. Train a Random Forest Classifier ML Model
11. Evaluate the trained model using several metrics, including Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
12. Final conclusion, summary, and further potential research

---

## Random Forest Classifier

This project uses a Random Forest Classifier for a two-class classification (Potentially Hazardous Asteroid and Not Potentially Hazardous Asteroid).

The choice to use a Random Forest Classifier model was because it is known to perform well with large datasets as it can capture complex relationships between features, reduces risk of overfitting, and produces feature importance results.

---

## Key Findings

- It is notable that the dataset is severely imbalanced in regards to the number of asteroids classified as potentially hazardous as compared to non-hazardous asteroids.

- Due to the imbalanced nature of the dataset, it was deemed necessary to also examine additional metrics to evaluate the Random Forest Classifier as using only Accuracy as a measure of performance was insufficient. Additional metrics such as Precision, Recall, F1-Score, and Confusion Matrix provided deeper insight into how well the model classified potentially hazardous asteroids.

- Both Absolute Magnitude and various Orbital features play key roles in the classification of an asteroid.

- The model performed well overall, however it still had a few misses, highlighting the necessity for improvement.

---

## Project Files

- Asteroid_Big_Data_Analytics.ipynb is a Jupyter Notebook for full project analysis
- Asteroid_Big_Data_Analytics.pdf is a PDF version of the Jupyter Notebook
- README.md is a project summary and documentation

---

## Potential Next Steps/Further Research

Additional work that could be performed in the future includes:

- Exploring other ML models
- Using techniques such as SMOTE or oversampling in order to resolve the class imbalance problem
- Further Feature Engineering
- Utilising NASA data API for real time updates
- Evaluating ML model performance across different algorithms for comparison purposes
