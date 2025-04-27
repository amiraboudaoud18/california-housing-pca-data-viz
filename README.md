# California Housing Dataset - PCA Analysis for Data visualization

## 📖 Introduction
In this project, we perform Principal Component Analysis (PCA) on the California Housing Dataset from the 1990 US Census. The goal is to reduce the dimensionality of the dataset while retaining as much information as possible, and to identify key features influencing housing prices.

Through PCA, we aim to:
- Visualize patterns and relationships between features in a lower-dimensional space.
- Identify the most influential factors affecting median house values.
- Explore how variables like location, income, and population contribute to housing price variations.

Dimensionality reduction techniques like PCA help simplify complex datasets, improve model performance, and reduce computational costs.

## 📚 Dataset Description
- **Source**: [Kaggle - California Housing Prices (Extra Features)](https://www.kaggle.com/datasets/fedesoriano/california-housing-prices-data-extra-features/data)
- The dataset describes demographic and geographic features of California block groups from the 1990 US Census.
- **Features include**:
  - Median House Value (target)
  - Median Income
  - Median Age
  - Total Rooms
  - Total Bedrooms
  - Population
  - Households
  - Latitude
  - Longitude
  - Distance to Coast
  - Distance to Los Angeles
  - Distance to San Diego
  - Distance to San Jose
  - Distance to San Francisco

## 🛠️ Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- altair
- scikit-learn
- prince (for PCA)

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn altair scikit-learn prince
3. Open and run the Jupyter Notebook (notebook.ipynb) to perform the full analysis and view visualizations.

## 📂 Files Included
california_housing_pca_data_viz.ipynb — Main Jupyter Notebook containing data preprocessing, PCA analysis, and visualizations.

## 📈 Key Results
- PCA helped reduce feature dimensionality while preserving most of the variance.
- Key factors influencing house prices include median income, proximity to coastlines, and population density.
- Visualization of principal components revealed clear patterns linked to geographic and demographic variables.

## 📄 License
This project is licensed under the MIT License.

## ✨ Acknowledgments
Kaggle for providing the dataset.
