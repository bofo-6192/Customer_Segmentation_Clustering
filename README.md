# Customer Segmentation Clustering

An unsupervised machine learning project that groups customers into meaningful segments based on their age, annual income, and spending behavior using clustering techniques for business decision support.

## Dataset
- **Source:** Mall Customers Dataset  
- **Format:** CSV  
- **Features:** Customer ID, Gender, Age, Annual Income (k$), Spending Score (1–100)  
- **Target:** No labeled target (Unsupervised Learning)

## Model Used
- **Algorithm:** Hierarchical Clustering (Agglomerative)  
- **Distance Metric:** Euclidean  
- **Linkage Method:** Ward  
- **Scaler:** StandardScaler for feature normalization  
- **Dimensionality Reduction:** PCA (2D & 3D), t-SNE  

## Model Performance
| Metric                   | Score   |
|--------------------------|---------|
| Silhouette Score         | 0.3098  |
| Davies–Bouldin Index     | 1.0070  |

## Business Interpretation
The clustering model identified clear customer segments such as:
- High-income, high-spending customers (VIP)
- High-income, low-spending customers (Potential growth)
- Low-income, high-spending customers (Risky segment)
- Low-income, low-spending customers (Low-value customers)

These insights can be used for targeted marketing, personalized offers, and customer retention strategies.

## Dependencies
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- scipy  
