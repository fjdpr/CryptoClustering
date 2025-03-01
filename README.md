# Crypto Clustering

## Summary
This project involves the analysis and clustering of cryptocurrency market data using K-Means and Principal Component Analysis (PCA). The goal is to identify distinct clusters of cryptocurrencies based on their market performance.

## Objectives
- Use K-Means to cluster cryptocurrencies.
- Use PCA to reduce the dimensionality of the data.
- Compare clustering results with and without PCA.
- Visualize the clusters using hvPlot.

## Data Description
The dataset includes:
- **Cryptocurrency Market Data**: CSV data for various cryptocurrencies, including price changes over different time periods.

## Included Scripts
1. **Crypto_Clustering.ipynb**:
   - Loads and preprocesses the data.
   - Uses StandardScaler to normalize the data.
   - Applies K-Means clustering to the scaled data.
   - Uses PCA to reduce the data to three principal components.
   - Applies K-Means clustering to the PCA-reduced data.
   - Visualizes the clusters using hvPlot.

## Requirements
- pandas
- hvplot
- scikit-learn

## Instructions

### Getting Started
1. Ensure you have the required libraries installed:
   ```bash
   pip install pandas hvplot scikit-learn
   ```
2. Open `Crypto_Clustering.ipynb` in Jupyter Notebook or JupyterLab.

## Features
- **Data Normalization**: Normalize the cryptocurrency market data using StandardScaler.
- **K-Means Clustering**: Apply K-Means clustering to the normalized data.
- **PCA**: Reduce the dimensionality of the data using PCA.
- **Cluster Visualization**: Visualize the clusters using hvPlot.

## Deployment
The Jupyter Notebook can be run locally on your machine. Ensure you have Jupyter Notebook or JupyterLab installed.

## References
- [scikit-learn documentation](https://scikit-learn.org/stable/documentation.html)
- [hvPlot documentation](https://hvplot.holoviz.org/)

## Contributions
Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
