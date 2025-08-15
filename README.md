# 🧠 Customer Segmentation using Clustering

## 📌 Project Overview
This project focuses on **customer segmentation** using clustering techniques. The goal is to group customers based on their **demographics** and **spending behavior**, allowing businesses to tailor their marketing strategies and improve customer engagement.  

We apply **K-Means** and **Hierarchical Clustering** on the **Mall Customer Dataset** and visualize the resulting clusters.

---

## 🎯 Objectives
- Segment customers based on purchasing behavior and income.  
- Identify high-value customer groups for targeted marketing.  
- Compare results of K-Means and Hierarchical Clustering.  

---

## 📂 Dataset
**Mall Customer Dataset** (from Kaggle)  

| Column               | Description                               |
|-----------------------|-------------------------------------------|
| CustomerID            | Unique customer ID (not used in clustering) |
| Gender                | Male / Female                            |
| Age                   | Age of customer                          |
| Annual Income (k$)    | Annual income in thousand dollars         |
| Spending Score (1-100)| Spending behavior score assigned by mall  |

---

## 🛠️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (sklearn)  
- Scipy (for hierarchical clustering)  

---

## 📊 Project Workflow
1. **Data Preprocessing**  
   - Convert categorical data (`Gender`) to numeric  
   - Scale features using `StandardScaler`  

2. **Clustering Techniques**  
   - **K-Means Clustering**  
     - Used the **Elbow Method** to find optimal clusters  
     - Segmented customers into 5 groups  
   - **Hierarchical Clustering**  
     - Built dendrogram to determine clusters  

3. **Visualization**  
   - Scatter plots of clusters based on **Annual Income** vs **Spending Score**  
   - Pair plots for feature comparisons  

---

## 📈 Insights
- **High Income + High Spending** → Target with premium offers  
- **High Income + Low Spending** → Encourage engagement with loyalty programs  
- **Low Income + High Spending** → Focus on discounts & retention  
- **Moderate Groups** → Standard marketing campaigns  

---

## 📦 Folder Structure




---

## 🚀 Future Improvements
- Try **DBSCAN** and **Gaussian Mixture Models (GMM)**  
- Use **E-commerce dataset** with purchase history  
- Deploy interactive segmentation app using **Streamlit/Flask**  

---

## 📄 Conclusion
This project demonstrates how clustering techniques can uncover hidden patterns in customer data, enabling businesses to personalize marketing strategies, increase sales, and improve customer satisfaction.

---
