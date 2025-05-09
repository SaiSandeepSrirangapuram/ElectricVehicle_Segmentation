#  Electric Vehicle Segmentation: A Data Science Approach

##  Project Overview

This project analyzes electric vehicle (EV) adoption trends in India using advanced **data science techniques**. By employing clustering algorithms and geospatial analysis, it identifies key income and geographic segments, offering actionable insights for targeted EV marketing strategies.

---

##  Data Science Methodologies Employed

### 1. **Data Preprocessing & Feature Engineering**
- **Handling Missing Values**: Implemented strategies to manage incomplete data entries.
- **Normalization**: Applied scaling techniques to ensure uniformity across features.
- **Feature Creation**: Derived new variables to enhance model performance.

### 2. **Clustering Algorithms**
- **K-Means Clustering**: Segmented households based on income levels to identify potential EV adopters.
- **Gaussian Mixture Models (GMM)**: Captured the probabilistic distribution of income segments, allowing for overlapping clusters.
- **Hierarchical Clustering**: Analyzed geographic data to uncover regional adoption patterns.

### 3. **Dimensionality Reduction**
- **Principal Component Analysis (PCA)**: Reduced data dimensionality while preserving variance, facilitating more efficient clustering.

### 4. **Model Evaluation Metrics**
- **Silhouette Score**: Assessed the cohesion and separation of clusters.
- **Elbow Method**: Determined the optimal number of clusters by analyzing within-cluster sum of squares.
- **Log-Likelihood**: Evaluated the fit of the GMM model to the data.

### 5. **Data Visualization**
- **Scatter Plots**: Visualized clustering results and centroids.
- **Heatmaps**: Displayed correlations between features.
- **Geospatial Maps**: Illustrated regional EV adoption trends.

---

##  Repository Structure

- `EV_Income_segmentation.ipynb`: Notebook detailing income-based clustering using K-Means and GMM.
- `Geographic_variable.ipynb`: Notebook focusing on geographic segmentation through hierarchical clustering.
- `DocumentsAndConclusion/EV Segmentation (IncomeGroup).docx`: Comprehensive report linking data insights to strategic business recommendations.
- `DataSets/India Household Spending raw_file.xlsx`: Raw dataset utilized for analysis.

---

##  Technologies & Libraries

- **Programming Language**: Python
- **Data Manipulation**: pandas, NumPy
- **Machine Learning**: scikit-learn
- **Visualization**: matplotlib, seaborn
- **Geospatial Analysis**: geopandas, folium

---

##  Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/SaiSandeepSrirangapuram/ElectricVehicle_Segmentation.git
```
### 2. Navigate to the Project Directory
```bash
ElectricVehicle_Segmentation
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```
