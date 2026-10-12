# Smart Cart Clustering System

## 📌 About the Project

This project implements a **customer segmentation system using machine learning clustering algorithms** to identify groups of customers based on shopping behavior and purchasing patterns. It applies data preprocessing, One-Hot Encoding, StandardScaler, PCA, and clustering techniques to discover meaningful customer segments and generate cluster summaries.


## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🧠 Machine Learning Workflow

1. **Data Loading:** Import the smart cart dataset.
2. **Data Preprocessing:** Handle missing values, clean data, and prepare relevant features.
3. **One-Hot Encoding:** Transform categorical variables into numerical features.
4. **Feature Scaling:** Standardize features using `StandardScaler`.
5. **PCA:** Reduce dimensionality to simplify analysis and support visualization.
6. **K-Value Analysis:** Evaluate candidate cluster counts using the Elbow Method and Silhouette Score.
7. **Clustering:** Apply K-Means and Agglomerative Clustering.
8. **Cluster Analysis:** Generate cluster summaries to understand the characteristics of each group.

## 📊 Clustering Techniques

### 1. K-Means Clustering

K-Means partitions the dataset into a specified number of clusters by minimizing the within-cluster sum of squared distances.

### 2. Agglomerative Clustering

Agglomerative Clustering uses a hierarchical approach, initially treating each observation as its own cluster and progressively merging similar groups.

### 3. Optimal Number of Clusters

Two evaluation techniques are used to identify an appropriate number of clusters:

- **Elbow Method:** Examines the within-cluster sum of squares (inertia) to identify where additional clusters provide diminishing returns.
- **Silhouette Score:** Measures how well observations fit within their assigned clusters compared with neighboring clusters. Higher scores generally indicate better-separated clusters.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Swapnil833/SmartCart-Clustering-System
cd SmartCart-Clustering-System
```

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## ▶️ Usage

1. Open the project notebook or Python script.
2. Load the smart cart dataset.
3. Execute the preprocessing and feature engineering steps.
4. Analyze cluster counts using the Elbow Method and Silhouette Score.
5. Train the K-Means and Agglomerative Clustering models.
6. Review the generated cluster summaries and visualizations.

To launch Jupyter Notebook:

```bash
jupyter notebook
```

## 📈 Results and Analysis

The system groups similar shopping profiles into clusters and summarizes their characteristics for interpretation. Depending on the features in the dataset, these clusters may reveal differences in purchasing behavior, spending patterns, or product preferences.

Cluster quality can be assessed using silhouette scores and visual analysis. The most useful clustering model depends on the dataset and the resulting cluster structure.

