# Project Customer Segmentation

**Dataset:** [Customers.csv](https://github.com/MMosayebi/Work-samples/tree/0d745a0da31faa9f9e3b1554880abf9bcf9d052e/Customer%20Segmentation/Dataset),The data is collected from a retail store.

**File:** [Customer Segmentation.ipynb](https://github.com/MMosayebi/Work-samples/blob/0d745a0da31faa9f9e3b1554880abf9bcf9d052e/Customer%20Segmentation/Customer%20Segmentation.ipynb)

## Goal
Segment customers into different groups to provide better services, focusing on **customer income** and **spending score**.

## Libraries Used
- `pandas`, `numpy` – data processing  
- `matplotlib`, `seaborn` – visualization  
- `scikit-learn` – K‑Means clustering & `silhouette_score`

## Clustering Quality Metric
**Silhouette Score** measures how close each point is to its own cluster versus others.  
Range: –1 to +1 (closer to +1 → better clustering).

## Results
- Number of clusters selected: **5**, based on elbow method & silhouette score (see cell 8)
- Visual segmentation is available in the notebook (see cell 14)  
- Average income & spending score per cluster (see cell 15 and 17)

### Analytical Insights
1. **Class A** (clusters 0 & 1) – Avg income & spending score ≥ 40  
2. **Class B** (cluster 2) – Avg income ≥ 40, spending score < 40  
3. **Class C** (cluster 4) – Avg income < 40, spending score ≥ 40  
4. **Class D** (cluster 3) – Avg income & spending score < 40
