# Data-Driven Dental Clinic Performance Optimization

# Data-Driven Dental Clinic Performance Optimization Using Predictive Modeling and Market Segmentation

## Overview
This project focuses on analyzing and optimizing the performance of a private dental clinic chain in France using data-driven methodologies. The objective is to identify key factors influencing revenue, assess the impact of competition, and provide strategic recommendations based on predictive modeling and clustering techniques.

## Objectives
- Understand the key factors that drive dental center performance.
- Differentiate the impact of **internal factors** (e.g., staffing, customer engagement, operational efficiency) versus **external factors** (e.g., demographics, economic conditions, competition).
- Use **supervised machine learning models** to explain revenue drivers.
- Perform **clustering analysis** to segment dental centers based on performance and market conditions.
- **Incorporate competition data** to assess its influence on revenue and customer acquisition.
- Provide actionable recommendations for business strategy and network expansion.

## Data
The project is built on two main datasets:
1. **Client Data:** Information on 71 dental centers, including operational metrics and catchment area characteristics.
2. **Competition Data:** A dataset containing geo-coordinates of all medical institutions in France, filtered to identify direct competitors.

The datasets have been cleaned, transformed, and enriched to ensure accurate analysis.

## Methodology
The project follows a structured data science approach:

### 1. Exploratory Data Analysis (EDA)
- Data inspection, missing value treatment, and outlier detection.
- Correlation analysis between internal and external factors.
- Geospatial visualization of dental centers and competitors.

### 2. Data Cleaning & Transformation
- Standardizing and filtering data to ensure consistency.
- Reprojecting coordinates to **EPSG:4326** for accurate geospatial analysis.
- Extracting relevant competition data for further analysis.

### 3. Feature Importance & Performance Explainability
- Building **linear (Regression, Ridge, Lasso)** and **non-linear models (Random Forest, Gradient Boosting)** to identify revenue drivers.
- Evaluating model performance using **R-squared, MSE, and feature importance plots**.

### 4. Client Segmentation (Clustering)
- Using **K-Means clustering** to group dental centers into meaningful segments.
- Applying **Principal Component Analysis (PCA)** for visualization.
- Extracting business insights from cluster characteristics.

### 5. Competition Analysis
- Identifying direct competitors within a **500m catchment area** for each client center.
- Assessing **competitive intensity** and its impact on revenue.
- Visualizing competition zones using **folium maps**.

### 6. Reevaluation with Competition Data
- Revisiting feature importance and clustering with competition as an additional factor.
- Analyzing how **competition density influences performance**.
- Extracting insights on the optimal competitive landscape for revenue maximization.

### 7. Business Recommendations
- Strategic insights on **optimal location selection** for new centers.
- Marketing and **customer acquisition strategies** based on data-driven segmentation.
- Actionable plans to **leverage competitive presence for growth** while avoiding oversaturation.


## Technologies Used
- **Python** (pandas, numpy, scikit-learn, seaborn, matplotlib)
- **Geospatial Analysis** (geopandas, shapely, pyproj, folium)
- **Machine Learning** (Linear Regression, Random Forest, Gradient Boosting, K-Means Clustering)
- **Visualization** (Matplotlib, Seaborn, Folium, PCA projections)

## Installation & Usage
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/DATA-DRIVEN-DENTAL-CLINIC-PERFORMANCE.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook 2023_DS_exercise.ipynb
   ```
4. Open and interact with the HTML maps for visual analysis.

## Key Findings
- **Internal factors** (staffing, customer reviews) have the most significant impact on revenue.
- **External factors**, particularly demographics, play a role but are secondary.
- **Competition has a nuanced effect** – moderate competition increases revenue, while excessive competition can reduce it.
- **Cluster analysis** reveals that the best-performing centers are in areas with balanced competition and strong internal operations.

## Business Recommendations
- **Expand strategically** in areas with moderate competitive intensity.
- **Leverage online reputation** by increasing customer reviews and engagement.
- **Optimize staffing levels** to maximize operational efficiency.
- **Differentiate services** in highly competitive areas to gain market share.

## License
This project is for educational and analytical purposes. Feel free to use and modify the code, but please credit the original work.