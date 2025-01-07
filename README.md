# Market Segmentation Analysis Code Conversion

This project contains the conversion of R code from the book ***Market Segmentation Analysis: Understanding It, Doing It, and Making It Useful*** by **Sara Dolnicar**, **Bettina Grün**, and **Friedrich Leisch** to Python.

## Overview

The book provides comprehensive insights into Market Segmentation Analysis. This repository aims to replicate those analysis using Python, allowing users to benefit from Python's vast ecosystem and tools.

## Dataset 

The dataset used in this project is the McDonald's dataset, which includes various attributes related to customer preferences and demographics. The dataset consists of columns such as customer ratings (e.g., `yummy`, `convenient`, `spicy`), demographic information (e.g., `Age`, `Gender`), and behavioral data (e.g., `VisitFrequency`)

## Conversion Details

### Data Preparation
- **Null Value Check:** Checked for null values using the .isnull() method.
- **Summary Statistics:**  Generated summary statistics using the .describe() method.
- **Encoding Categorical Variables:**  Converted categorical variables into numerical formats using LabelEncoder.

### Clustering
- **K-Means Clustering**: Implemented K-Means clustering to identify market segments.
- **Mixture Models**: Used Gaussian Mixture Models to perform latent class analysis for identifying segments with binary distributions.

### Visualization
- **Mosaic Plots**: Created mosaic plots to visualize the association between segment membership and categorical variables such as `Like` and `Gender`.
- **Box-and-Whisker Plots**: Generated parallel box plots to compare the distribution of age across different segments.
- **Bar Plots**: Visualized the mean visit frequency and other descriptor variables for each segment.

### Advanced Analysis
- **Conditional Inference Trees**: Fitted decision trees to predict segment membership based on descriptor variables.
- **Principal Component Analysis (PCA)**: Performed PCA for dimensionality reduction and visualized the principal components.

### Acknowledgments
This project is based on the book Market Segmentation Analysis: Understanding It, Doing It, and Making It Useful by Sara Dolnicar, Bettina Grün, and Friedrich Leisch. All credit for the original analysis and methodology goes to the authors.
#### *Thank you!*
