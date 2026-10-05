# Customer-segmentation-analysis
# Customer Segmentation Analysis Using K-Means Clustering

## 📌 Project Overview

This project focuses on **customer segmentation using K-Means clustering**, an unsupervised machine learning technique used to group customers based on their purchasing behaviour.

The analysis uses **Annual Income** and **Spending Score** to identify distinct customer segments. These segments can help businesses understand customer behaviour and develop more targeted marketing strategies.

---

## 🎯 Project Objective

The primary objective of this project is to segment customers into meaningful groups based on their income and spending behaviour using the **K-Means Clustering algorithm**.

The resulting customer segments can support businesses in:

* Identifying valuable customer groups
* Developing targeted marketing strategies
* Creating personalized offers
* Improving customer engagement
* Supporting data-driven marketing decisions

---

## 📊 Dataset

**Dataset:** Mall Customer Segmentation Dataset
**Source:** Kaggle

**Dataset size:** 200 customer records

**Dataset Link:**
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Dataset Features

| Feature                | Description                       |
| ---------------------- | --------------------------------- |
| CustomerID             | Unique customer identifier        |
| Gender                 | Customer gender                   |
| Age                    | Customer age                      |
| Annual Income (k$)     | Customer annual income            |
| Spending Score (1-100) | Customer spending behaviour score |

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** — Data manipulation and analysis
* **Scikit-learn** — Machine learning
* **K-Means Clustering** — Customer segmentation
* **StandardScaler** — Feature standardization
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook / Google Colab**

---

## 🔄 Project Workflow

### 1. Data Loading

The dataset was loaded into a Pandas DataFrame from the CSV file.

### 2. Data Inspection

Initial data inspection was performed to understand the dataset structure, including:

* Dataset shape
* Column information
* Data types
* Missing values

### 3. Exploratory Data Analysis

Exploratory analysis was conducted to understand customer characteristics and purchasing behaviour.

Visualizations included:

* Customer age distribution
* Annual Income vs. Spending Score scatter plot

### 4. Feature Selection

The following features were selected for customer segmentation:

* **Annual Income (k$)**
* **Spending Score (1-100)**

These variables were used to identify customer groups based on income and spending behaviour.

### 5. Data Standardization

The selected features were standardized using **StandardScaler** before applying the clustering algorithm.

Standardization helps ensure that the selected variables are placed on a comparable scale for clustering.

### 6. K-Means Clustering

The **K-Means clustering algorithm** was applied to segment customers into distinct groups.

The **Elbow Method** was used to determine an appropriate number of clusters.

### 7. Customer Segmentation Visualization

The resulting customer segments were visualized using:

* Customer segmentation scatter plot
* Cluster distribution visualization

### 8. Cluster Profiling

The identified clusters were analyzed based on:

* Average annual income
* Average spending score
* Number of customers in each cluster

### 9. Business Insights

The resulting customer groups were interpreted from a business perspective.

The analysis identified groups such as:

* **High-value customers**
* **Premium customers**
* **Target customers**
* **Low-spending customers**

Marketing strategies were suggested for different customer segments based on their purchasing behaviour.

---

## 📈 Visualizations

The project includes the following visualizations:

* Customer Age Distribution
* Annual Income vs. Spending Score
* K-Means Elbow Method
* Customer Segmentation Scatter Plot
* Cluster Distribution Visualization

---

## 💡 Business Insights

Customer segmentation provides businesses with a structured way to understand differences in customer behaviour.

Potential applications include:

### High-Value Customers

Customers demonstrating strong spending behaviour can be targeted with loyalty programs, premium services, and exclusive offers.

### Premium Customers

High-income and high-spending customers can be approached with personalized and premium product offerings.

### Target Customers

Customers with potential for increased engagement can be targeted through personalized promotions and marketing campaigns.

### Low-Spending Customers

Customers with lower spending behaviour can be approached with appropriate discounts, promotions, and engagement strategies.

---

## 🧠 Key Skills Demonstrated

This project demonstrates practical experience in:

* Exploratory Data Analysis
* Data Preprocessing
* Feature Selection
* Feature Standardization
* Unsupervised Machine Learning
* K-Means Clustering
* Elbow Method
* Cluster Profiling
* Data Visualization
* Business Insight Generation
* Customer Segmentation

---

## ✅ Final Outcome

The project successfully segmented customers based on their **annual income and spending behaviour** using K-Means clustering.

The resulting customer groups provide a foundation for understanding different customer profiles and developing **personalized, data-driven marketing strategies**.

---

## 📁 Project Structure

```text
Customer-Segmentation-KMeans/
│
├── Customer_Segmentation_KMeans.ipynb
├── Mall_Customers.csv
└── README.md
```

---

## 👩‍💻 Author

**Amna Naveed**

MPhil Statistics | Data Analyst
