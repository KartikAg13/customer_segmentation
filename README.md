# Mall Customer Segmentation using K-Means

## Overview
This repository contains an implementation of K-Means clustering using manually assigned initial centroids. The algorithm clusters customer data based on their **Annual Income (k$)** and **Spending Score (1-100)**.

## Files
- **main.ipynb**: Jupyter Notebook containing the full implementation of K-Means clustering.
- **README.md**: Documentation explaining the project and usage.

## Features
- Reads customer data from [Mall_Customers.csv](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).
- Initializes centroids manually for better clustering control.
- Implements K-Means clustering from scratch using NumPy.
- Visualizes clusters before and after training using Matplotlib.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/KartikAg13/customer_segmentation.git
   cd customer_segmentation
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
4. Run all cells in `main.ipynb` to execute the clustering process.

## Algorithm Explanation
### Steps in K-Means:
1. **Initialize Centroids**: Five manually chosen centroids.
2. **Assign Clusters**: Each point is assigned to the nearest centroid.
3. **Update Centroids**: Compute new centroids based on the mean of cluster points.
4. **Repeat Until Convergence**: Stop when centroid movement is below a set tolerance.

## Visualizations
- **Before Training**: Displays initial centroids on the dataset.
- **After Training**: Shows final clusters after running K-Means.

## Output Example
![Clustering Output](https://github.com/user-attachments/assets/b256cc15-a03a-4362-a299-a161d176dc30)
