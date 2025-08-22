# 🛒 Customer Segmentation with Clustering

## 📌 Project Overview
This project segments customers into groups based on purchasing behavior and demographics.  
The goal is to help businesses **understand customer groups**, enabling better marketing strategies and personalized services.  

We apply **K-Means Clustering** to the dataset, and evaluate cluster quality using the **Elbow Method** and **Silhouette Score**.  

---

## 🚀 Key Highlights
- **Goal:** Group customers into meaningful clusters.  
- **Dataset:** Customer data (Age, Annual Income, Spending Score, etc.).  
- **Techniques Used:**  
  - K-Means Clustering.  
  - Elbow Method (for choosing optimal k).  
  - Silhouette Score (for cluster validation).  
- **Visualization:**  
  - Scatter plots of clusters.  
  - Distribution of features across clusters.  

---

## 📊 Results
- Optimal number of clusters found using **Elbow Method** and **Silhouette Score**.  
- Clear segmentation observed, separating customers by income and spending behavior.  

Example clusters:  
1. **High Income, High Spending** → Potential premium customers.  
2. **High Income, Low Spending** → Customers needing targeted engagement.  
3. **Low Income, High Spending** → Impulsive buyers.  
4. **Low Income, Low Spending** → Budget-constrained customers.  

✅ Clustering provides actionable insights for marketing and product recommendations.  

---

## 🛠 Tools & Libraries
- **Python**  
- **NumPy, Pandas**  
- **Scikit-learn** (KMeans, metrics for clustering)  
- **Matplotlib, Seaborn** (visualizations for EDA and clusters)  

---

## 📈 Workflow
1. **Data Preprocessing:**  
   - Handled missing values.  
   - Scaled numerical features with **StandardScaler**.  
2. **EDA (Exploratory Data Analysis):**  
   - Feature distributions.  
   - Correlation heatmaps.  
3. **Model Training:**  
   - Applied **K-Means clustering** with different k values.  
   - Used **Elbow Method** to identify optimal k.  
4. **Model Evaluation:**  
   - Validated results with **Silhouette Score**.  
   - Visualized clusters.  

---

## 🧩 How to Run
1. Clone the repository:

    git clone https://github.com/Hussein-alali/Customer-Segmentation-Clustering.git

2. Install dependencies:

    pip install -r requirements.txt

3. Run The Notebook:

    jupyter notebook Customer_Segmentation_with_Clustering.ipynb

---

## 📘 License
This project is licensed for educational and personal use.

---

## 🙋 Author
**Hussein Abdalrhman Alali Alhlal**  
Computer Engineer | Data & AI Enthusiast

---
