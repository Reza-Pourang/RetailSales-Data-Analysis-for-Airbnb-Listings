# Advanced-Data-Analysis-and-Visualization-for-Airbnb-Listings

### Overview  
This project focuses on analyzing and visualizing Airbnb data from Boston and Seattle. It processes combined datasets to clean inconsistencies, perform exploratory data analysis (EDA), detect trends, and apply dimensionality reduction techniques like PCA.  

### Key Objectives  
- Combine and clean datasets from multiple sources.  
- Perform exploratory data analysis (EDA), including descriptive statistics and trend identification.  
- Apply dimensionality reduction (PCA) to visualize data variability.  
- Visualize key insights into room types, prices, and listing patterns.  

### Methodology  

#### Data Cleaning and Preprocessing:  
- Combined Boston and Seattle Airbnb datasets.  
- Handled missing values, outliers, and inconsistent formats.  
- Converted columns to appropriate data types for further analysis.  
- Derived new features for temporal and trend analysis.  

#### Exploratory Data Analysis (EDA):  
- Summarized room types, cancellation policies, and instant booking statistics.  
- Identified correlations between key variables, such as price and review scores.  
- Detected trends over time, including anomalies like a sharp price peak in 2009.  

#### Dimensionality Reduction:  
- Applied PCA for 2D visualization of Airbnb listings.  
- Identified clusters and outliers in the dataset.  

### Key Results  
- Most listings were entire homes/apartments (63%).  
- The strict cancellation policy was the most common (41%).  
- PCA revealed price variations and unique outliers in the data.  

### Scalability and Future Improvements  
- For larger datasets, frameworks like Dask or PySpark can enhance performance.  
- Integrating Tableau or Plotly can provide interactive visualizations for stakeholders.  
- Advanced anomaly detection methods can further improve analysis accuracy.  

### Datasets  
- Boston and Seattle Airbnb datasets from Kaggle.  

### Requirements  
- Python 3.x  
- Libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`  

### How to Run  
1. Download the datasets from Kaggle and upload them to Google Colab or your local environment.  
2. Load the datasets into the provided Google Colab notebook.  
3. Follow the steps outlined to process, analyze, and visualize the data.  

