# 🛍️ Mall Customer Segmentation using K-Means Clustering  

## 📌 Project Overview  
This project demonstrates customer segmentation using the **K-Means clustering algorithm**.  
The dataset contains information about mall customers, and the goal is to group customers into different clusters based on their **purchasing behavior**.  

👉 Customer segmentation helps businesses understand their customer base better and design targeted marketing strategies.  

---

## 🛠️ Technologies Used  
- 🐍 Python  
- 📊 Pandas → Data manipulation  
- 🔢 NumPy → Numerical operations  
- 🎨 Matplotlib / Seaborn → Data visualization  
- 🤖 Scikit-learn (sklearn) → Machine learning (K-Means, Silhouette Score, Elbow Method)  

---

## 📂 Dataset  
The dataset includes details of mall customers such as:  
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

---

## 🔑 Steps Involved  

### 1️⃣ Data Loading & Exploration  
- Loaded the dataset using **pandas**  
- Performed initial exploration with `.head()`, `.info()`, `.describe()`  

### 2️⃣ Data Visualization  
- Plotted histograms & countplots for **Gender, Age, Income, Spending Score**  
- Created scatter plots to study relationships between features  

### 3️⃣ Feature Selection  
- Selected **Annual Income & Spending Score** for clustering  

### 4️⃣ Finding Optimal Clusters  
- **Elbow Method** → To find the best number of clusters (K)  
- **Silhouette Score** → To evaluate cluster quality  

### 5️⃣ Model Training (K-Means)  
- Applied **K-Means clustering** on the dataset  
- Predicted cluster labels for each customer  

### 6️⃣ Visualization of Clusters  
- Scatter plots showing different customer groups with distinct colors  
- Highlighted **cluster centroids**  

---

## 📊 Results & Insights  
- Customers were divided into **meaningful groups** (e.g., *High income–high spenders*, *Low income–low spenders*, etc.)  
- Helps mall management & marketing teams to:  
  - Identify potential **high-value customers**  
  - Offer **personalized promotions**  
  - Improve **customer retention**  

---

## 🚀 How to Run  

### Clone this repository:  
```bash
git clone https://github.com/your-username/Mall-Customer-Segmentation.git
cd Mall-Customer-Segmentation

✨ Author
    Aman Mani Tripathi
📍 Data Science Enthusiast | Machine Learning
