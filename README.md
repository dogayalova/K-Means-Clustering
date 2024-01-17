# K-Means Clustering in Gene Expression Data Analysis

## Project Overview
This project applies the K-Means clustering algorithm to a gene expression dataset comprising 2000 genes from 62 individuals. The dataset includes samples from both colon cancer patients and healthy individuals. The objective is to explore clustering patterns and potentially infer the health status of the unknown sample (62nd patient).
Assignment for the Bioinformatics Course (CMPE549) at Bogazici University.
## Problem Breakdown

### Data Loading and Preprocessing
- **Data Source**: The dataset is sourced from `gene_expression_matrix.txt`, featuring gene expression levels.
- **Matrix Structure**: Upon loading, the data forms a 62 x 2000 matrix, representing 62 individuals and 2000 gene expression levels.
- **Preprocessing**: Standardization of the data is performed for each gene expression dimension.

### K-Means Clustering Implementation
- **Algorithm**: Custom implementation of the K-Means clustering algorithm.
- **Feature**: Utilizes cosine similarity as the distance/similarity metric.
- **Objective**: Cluster 62 patients into two groups representing cancer and non-cancer patients.

### Analysis and Iterations
- **Multiple Runs**: The algorithm is run 5 times with different initial centroids.
- **Error Calculation**: Squared error distortion is calculated for each run to evaluate clustering performance.

### Results Interpretation
- **Cancer Patient Distribution**: Analysis of the distribution of cancer patients across the clusters.
- **Patient 62 Analysis**: The cluster assignment of the 62nd patient, whose health status is unknown, is determined.
- **Discussion**: A brief discussion on the findings and their implications on determining the health status of the 62nd patient.

## Instructions for Running the Code
- Clone this repository.
- Ensure all dependencies (as listed in `requirements.txt`) are installed.
- Run the Jupyter Notebook to execute the analysis.
- View the outputs for each section within the notebook for insights and results.

## Contributing
Your contributions to enhance or extend the analysis are welcome. Please feel free to fork this repository and submit your changes via pull requests.

## Contact
For any queries related to this project, please reach out to me at [dogayalova@gmail.com](mailto:dogayalova@gmail.com).
