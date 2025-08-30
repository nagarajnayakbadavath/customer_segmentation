#  Customer Segmentation using Machine Learning

This project applies unsupervised machine learning techniques to identify distinct customer segments based on their purchasing behavior and demographic features. The goal is to help businesses understand their customers better and enable targeted marketing strategies.

##  Project Overview

Customer segmentation is the process of dividing a customer base into groups of individuals with similar characteristics. In this project, I used clustering algorithms, specifically **K-Means**, to group customers based on key features such as age, income, spending score, etc.

##  Dataset

- **Source:** [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python) (Kaggle)
- **Features Used:**
  - Customer ID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

> The dataset is included in the `data/` directory.

##  Technologies Used

- **Language:** Python 3.x
- **Libraries:**
  - `pandas` – data manipulation
  - `matplotlib`, `seaborn` – visualization
  - `scikit-learn` – machine learning (KMeans, PCA, etc.)
 



##  Clustering with K-Means

- Used the **Elbow Method** to determine the optimal number of clusters.
- Applied **K-Means clustering** algorithm.
- Visualized customer clusters in 2D plot.
- Labeled each customer segment with intuitive names like:
  - High Spenders
  - Budget Shoppers
  - Young Adults
  - Loyal Customers

##  Results

- Identified **5 unique customer segments**.
- Presented cluster insights and marketing recommendations.
- Achieved clear visual distinction between different segments using both 2D plot.





