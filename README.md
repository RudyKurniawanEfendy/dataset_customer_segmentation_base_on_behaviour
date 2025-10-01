# A Comparative Analysis of K-Means++ and DBSCAN Clustering Algorithms for Customer Segmentation base on behaviour in Indonesian E-commerce
This repository contains raw datasets that used in this study for customer segmentation base on behaviour in Indonesian E-commerce. The dataset collected from an online survey to respondents who use the e-commerce platform as primary data and web scraping data collected from e-commerce websites as secondary data.  

## 📁Dataset Files
  - `customer_segmentation_dataset.csv`:
      - Raw dataset from online survey distributed to Indonesian customer.
  -  Content: Includes customer's demographic and shopping behavior information.  

## 🛠️Preprocessing Steps

The dataset has been processed through the following pipeline:

  - Checking missing values, noisy data, and other inconsistencies
  - Encoding categorical attributes into numerical attributes (Label and One-Hot encoding)
  - Standardize the ranges values of attributes (Z-score Normalization)
  - Applying Principal Component Analysis (PCA) to reduce dimensionality
  - Applying clustering algorithms (K-Means++ and DBSCAN)

## 🔗Citation
If you use this dataset for your research, please cite the following work:
```text
J. N. Saputra, R. K. Efendy, F. H. A. Hadad, & K. Purwandari. (2025). A Comparative Analysis of K-Means++ and DBSCAN Clustering Algorithms for Customer Segmentation base on behaviour in Indonesian E-commerce.
```
## 📜License
This dataset is provided for research and academic use only.
