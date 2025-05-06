# Task-8-Clustering-with-K-Means
📊 Mall Customer Segmentation using K-Means
This project performs unsupervised customer segmentation using the K-Means clustering algorithm. It includes dimensionality reduction, optimal cluster selection using the Elbow Method, visualization of clusters, and evaluation using the Silhouette Score.

📁 Dataset
Filename: Mall_Customers.csv
Columns:

CustomerID: Unique identifier for each customer

Gender: Male or Female

Age: Age of the customer

Annual Income (k$): Annual income in thousand dollars

Spending Score (1-100): Score assigned based on customer behavior and spending

🧪 Project Steps
Load and Preprocess Dataset

Encode the categorical Gender column using Label Encoding.

Select relevant features: Age, Annual Income (k$), Spending Score, and Gender.

Optional PCA for Visualization

Apply PCA to reduce the dataset to 2D for easier visualization.

Elbow Method

Iterate over K values from 1 to 10.

Plot the inertia to find the "elbow point", indicating the optimal number of clusters.

K-Means Clustering

Fit the model with the optimal number of clusters (typically k=5).

Assign and store cluster labels.

Visualization

Plot the PCA-reduced data, color-coded by cluster labels.

Evaluation

Use Silhouette Score to assess the cohesion and separation of clusters.

📈 Example Output
Elbow curve showing optimal k.

PCA scatter plot showing colored clusters.

Silhouette Score (e.g., 0.55) indicating clustering quality.

🛠️ Requirements
Install necessary libraries using:

bash
Copy
Edit
pip install pandas scikit-learn matplotlib seaborn
▶️ Run the Notebook
Run the Python script or Jupyter Notebook step-by-step to see visualizations and cluster segmentation.

