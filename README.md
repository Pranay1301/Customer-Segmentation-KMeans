# Customer Segmentation using K-Means Clustering 🛍️

## Project Overview

This project uses unsupervised machine learning to segment customers based on their shopping behavior. By applying the **K-Means clustering algorithm** to a dataset of mall customers, we can identify distinct groups and better understand their profiles. This kind of analysis is crucial for targeted marketing and business strategy.

## Dataset

The dataset used is the "Mall Customer Segmentation Data" from Kaggle, which contains basic information about customers, including their age, gender, annual income, and spending score.

-   **Source:** [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## Methodology

1.  **Data Exploration:** Loaded the dataset and performed an initial exploratory data analysis (EDA) to understand its structure and features.
2.  **Feature Selection:** Selected 'Annual Income' and 'Spending Score' as the key features for clustering.
3.  **Finding Optimal K:** Used the **Elbow Method** to determine the optimal number of clusters (K) for the K-Means algorithm. The "elbow" point in the plot indicated that **K=5** was the best choice.
4.  **Clustering:** Trained a K-Means model with K=5 to segment the customers into five distinct groups.
5.  **Visualization:** Plotted the clusters on a scatter plot to visualize the different customer segments and their centroids.

## Results: Customer Segments Identified

The analysis revealed five distinct customer segments:
-   **High Income, Low Spenders (Careful):** Earn a lot but spend little.
-   **High Income, High Spenders (Targets):** The prime target for marketing.
-   **Mid Income, Mid Spenders (Standard):** A large, average group.
-   **Low Income, Low Spenders (Sensible):** Spend cautiously.
-   **Low Income, High Spenders (Careless):** Potential for credit offerings but high risk.

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/Customer-Segmentation-KMeans.git](https://github.com/YourUsername/Customer-Segmentation-KMeans.git)
2. Install the required libraries from `requirements.txt`.
3. Run the Jupyter Notebook `customer_segmentation.ipynb`.
