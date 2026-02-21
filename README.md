# Customer-segmentation-using-Clustering-algorithm
# Customer Segmentation using Clustering Algorithms

## 📌 Project Overview
This project focuses on grouping customers into distinct segments based on their purchasing behavior and demographics. By identifying these clusters, businesses can create targeted marketing strategies and improve customer retention.

## 🚀 Key Features
* **Data Preprocessing:** Handled missing values, scaling, and feature engineering.
* **Exploratory Data Analysis (EDA):** Visualized distributions and correlations using Seaborn and Matplotlib.
* **Clustering Algorithms:** Implemented **K-Means**, **Hierarchical Clustering**, or **DBSCAN**.
* **Optimal Cluster Selection:** Used the **Elbow Method** and **Silhouette Scores** to find the best $K$ value.



## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook, Git

## 🧪 Technical Implementation
This project implements a complete pipeline to segment 2,138 customers based on 15 psychographic variables (e.g., brand loyalty, health consciousness, and tech-savviness).

### Key Workflow:
* **Mock Data Generation:** Simulated customer personas (Traditionalist, Modern Spender, Value Seeker, and Skeptic) with Gaussian noise to mimic real-world survey data.
* **Dimensionality Reduction:** Utilized **PCA (Principal Component Analysis)** to project 15D data into 2D for cluster visualization.
* **Clustering:** Applied **K-Means Clustering** with `StandardScaler` to ensure feature parity.
* **Statistical Validation:** Replicated research-grade validation using **One-Way ANOVA** to rank variables by their "F-Statistic" (identifying which features most effectively separate the segments).

### Visualization Dashboard:
The script generates a three-part diagnostic dashboard:
1. **PCA Scatter Plot:** Visualizes the spatial separation of clusters.
2. **ANOVA Bar Chart:** Ranks features by statistical significance.
3. **Profile Plot:** Compares the mean ratings (1-5) across clusters to define "Archetypes."



## 📊 Results
The model successfully identified [Number] distinct customer segments, such as "High-Spenders" and "Budget-Conscious" customers.

## 📂 How to Run
1. Clone the repo: `git clone https://github.com/your-fayiz77/customer-segmentation.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook`
