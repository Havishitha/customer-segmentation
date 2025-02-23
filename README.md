# customer-segmentation
---

### **📌 Customer Segmentation using K-Means Clustering**
🚀 This project segments customers based on transactional behavior using **K-Means Clustering**. **Principal Component Analysis (PCA)** is applied for dimensionality reduction to improve model interpretability.  

---

## **📝 Problem Statement**
Businesses collect large amounts of customer transaction data, but without proper analysis, this data remains underutilized. Identifying **high-value customer groups** enables companies to create **targeted marketing strategies, enhance customer engagement, and improve revenue generation**.  

This project aims to:  
✅ Segment customers using **K-Means Clustering** based on their transactional behavior.  
✅ Apply **PCA** for dimensionality reduction, improving model performance and interpretability.  
✅ Visualize **customer segments** using Python libraries (**Seaborn, Matplotlib**).  

---

## **💾 Dataset Information**
The dataset used for this project contains the following attributes:  
| Column Name  | Description |
|-------------|------------|
| **InvoiceNo** | Unique invoice number for a transaction |
| **StockCode** | Unique product code |
| **Description** | Product description |
| **Quantity** | Number of units purchased |
| **InvoiceDate** | Date and time of purchase |
| **UnitPrice** | Price per unit of product |
| **CustomerID** | Unique customer identifier |
| **Country** | Customer’s country |

DataSet : https://www.kaggle.com/datasets/vijayuv/onlineretail?resource=download
---

## **📊 Techniques Used**
1️⃣ **Data Cleaning & Preprocessing**  
- Handled missing values and duplicates.  
- Removed outliers using IQR method.  
- Created **RFM (Recency, Frequency, Monetary) features** for better segmentation.  

2️⃣ **Feature Engineering & Dimensionality Reduction**  
- Applied **Principal Component Analysis (PCA)** to reduce dimensionality.  

3️⃣ **Clustering Using K-Means**  
- Determined the **optimal K value** using **Elbow Method & Silhouette Score**.  
- Applied **K-Means Clustering** to segment customers.  

4️⃣ **Visualization & Insights**  
- Used **Seaborn & Matplotlib** to visualize customer clusters.  
- Analyzed characteristics of high-value customer groups.  

---

## **📈 Results & Insights**
- **Customer groups were identified** based on purchase frequency and spending patterns.  
- **High-value customers** were differentiated from low-value customers.  
- **Business Impact**: These insights can help businesses create **targeted marketing campaigns** and **personalized offers**.  

---

## **📜 License**
This project is open-source and available under the **MIT License**.
