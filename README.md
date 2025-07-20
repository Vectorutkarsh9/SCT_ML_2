# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to segment mall customers into groups based on their **Age**, **Annual Income**, **Spending Score**, and **Gender**. These segments can be used to develop effective marketing strategies and understand customer behavior better.

## 📊 Dataset
- **Source**: [Kaggle - Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features**:
  - `CustomerID`: Unique identifier
  - `Gender`: Categorical (Male/Female)
  - `Age`: Customer age
  - `Annual Income (k$)`: Income in thousands of dollars
  - `Spending Score (1-100)`: Score assigned by the mall based on behavior

## 🧠 Techniques Used
- Unsupervised Learning
- K-Means Clustering
- Elbow Method to determine optimal clusters
- Data Encoding and Normalization
- Data Visualization (Scatterplots, Pairplots)

## 🛠️ Tools & Libraries
- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- Jupyter Notebook

## 🔁 Workflow
1. Load and explore the dataset
2. Encode categorical variables (`Gender`)
3. Normalize and select relevant features
4. Use the **Elbow Method** to find the optimal value of `k`
5. Apply **K-Means Clustering**
6. Visualize customer segments
7. Save the model and draw insights from each cluster

## 📸 Sample Visualization

```python
sns.scatterplot(x='Annual Income (k$)', y='Spending Score (1-100)', hue='Cluster', data=df, palette='Set2')

---

Let me know if you want me to generate:
- ✅ `requirements.txt` file  
- ✅ Jupyter Notebook sample  
- ✅ Sample `.pkl` save/load code  
- ✅ Streamlit UI for live demo

Just say *"ek aur do"* 😄
