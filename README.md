# Mall-Customers-Segmentation
KMeans clustering with EDA on Mall Customer dataset

This project performs **customer segmentation** on a mall dataset using **KMeans clustering**. It helps businesses understand customer groups based on **income, and spending behavior**.

---

## 📊 Dataset Features Used

- **Annual Income (k$)**: Annual income in thousands of dollars
- **Spending Score (1-100)**: Customer's spending score (higher means higher spenders)

---

## 🚀 Methods Applied

- Clustering using **KMeans (k=5)**
- Summary statistics and insights per cluster
- 
## 📈 Outputs and Visuals

### 📋 Cluster Summary Table
| Cluster | Avg Annual Income (k$) | Avg Spending Score |
|---------|-------------------------|---------------------|
| 0       | Medium                  | Medium              |
| 1       | High                    | High                |
| 2       | High                    | Low                 |
| 3       | Low                     | Low                 |
| 4       | Low                     | High                |

---

## 💡 Business Insights

- **Cluster 0**: Average customers. Good for general offers or occasional promotions.
- **Cluster 1**: Best customers – likely VIPs. Should be targeted with exclusive deals or premium services.
- **Cluster 2**: These people can afford to spend, but don’t. Target with customized marketing or value-based offers to increase spending.
- **Cluster 3**: Low-value customers. If targeted, use low-cost promotions or bundled offers.
- **Cluster 4**: Surprising group — spends a lot despite low income. Good for budget-friendly products, EMIs, or installment offers.

---
---

## 🛠️ Tools Used

- Python, Pandas
- Scikit-learn (KMeans)
- Seaborn, Matplotlib

---

## 📂 Files

- `Mall_Customers_Segmentation.ipynb` — Main Jupyter notebook
- `Mall_Customers.csv`
- `cluster_plot.png`
