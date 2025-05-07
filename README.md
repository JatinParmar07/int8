# int8
# Mall Customer Segmentation using K-Means Clustering

In this project, I performed customer segmentation on a mall dataset using **K-Means clustering**. The goal was to group customers based on their **annual income** and **spending score**, so the business can better target marketing strategies.

## What I Did

1. **Loaded and explored** the Mall Customer dataset.
2. Selected relevant features: `Annual Income (k$)` and `Spending Score (1-100)`.
3. Plotted a basic **scatter plot** to visualize the distribution.
4. Used the **Elbow Method** to determine the optimal number of clusters (K).
5. Applied **K-Means Clustering** to assign each customer to a cluster.
6. **Visualized** the final clusters with color coding.
7. Evaluated the clustering performance using the **Silhouette Score** (I got **0.554**, which is pretty solid!).

## Key Results

- The optimal number of clusters (K) was determined to be **5** using the Elbow Method.
- Visualizations showed **distinct customer segments**, such as high income + low spenders, low income + high spenders, etc.
- The Silhouette Score of **0.554** indicated a meaningful clustering.

## Dataset

The dataset I used is the **Mall_Customers.csv**, which contains the following columns:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

You can download it from [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial).
