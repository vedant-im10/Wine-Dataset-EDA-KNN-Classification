# 🍷 Wine Dataset EDA & K-Nearest Neighbors Classification

This project explores the Wine dataset through visualizations and classification using K-Nearest Neighbors (KNN) to analyze bias-variance trade-offs. The dataset contains attributes for three different wine classes, and this project uses these attributes to predict the class using KNN.

## 📁 Project Structure

- **EDA (Exploratory Data Analysis)**: 
  - Box plots and scatter plots are used to visualize relationships between key attributes and target classes.
  - Principal Component Analysis (PCA) is applied to project the data into two dimensions and visually inspect class separability.
  
- **K-Nearest Neighbors (KNN) Classification**: 
  - KNN classification is applied to the Wine dataset.
  - Hyperparameter `k` is tuned, and errors are analyzed with respect to training and testing sets.
  - Decision boundaries are plotted for varying values of `k`.

## 🔍 Exploratory Data Analysis
1. **Descriptive Statistics**: Provides a summary of the wine dataset including the count, mean, standard deviation, and quantiles for all features.
2. **Visualizations**:
   - Box plots of selected attributes (`alcohol`, `malic_acid`, `ash`, `alcalinity_of_ash`).
   - Scatter plots to explore pairwise attribute relationships.
3. **Principal Component Analysis (PCA)**: Projects the 13-dimensional data into 2D to highlight class separation.

## 🧠 K-Nearest Neighbors Classification
1. **Model Setup**: Used `KNeighborsClassifier` from Scikit-Learn.
2. **Tuning Hyperparameter k**: Trained KNN models for different `k` values and analyzed training vs testing error.
3. **Decision Boundaries**: Visualized decision boundaries for different values of `k` using the first two features of the dataset.

## 🛠️ Tools & Libraries
- **Python**
- **Scikit-Learn**
- **Matplotlib**
- **Seaborn**
- **Pandas**
- **NumPy**
