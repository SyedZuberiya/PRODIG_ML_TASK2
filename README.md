# 🛍️ Mall Customers Analysis

This project performs exploratory data analysis (EDA) on a dataset of mall customers. The goal is to analyze customer demographics and spending behavior to understand patterns and group customers effectively. This could serve as a foundation for applying clustering techniques (like KMeans) to segment customers based on various factors such as age, annual income, and spending score.

---


## 🎯 Overview

In this project, we perform a comprehensive analysis of customer data from a mall. The dataset includes various features such as:

- **Age**: The age of the customer.
- **Gender**: The gender of the customer.
- **Annual Income (k$)**: The annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned to the customer based on their spending behavior.

The goal is to explore these features through visualizations and identify any patterns or trends, which may later help in customer segmentation.

---

## 📂 Dataset

- **Dataset**: The dataset used in this project is a CSV file containing customer information.
  - **Link to Dataset**: The dataset is assumed to be loaded as `Mall_Customers.csv`.
  - The dataset consists of the following columns:
    - `CustomerID`: Unique identifier for each customer.
    - `Gender`: Gender of the customer (Male/Female).
    - `Age`: Age of the customer.
    - `Annual Income (k$)`: Annual income of the customer in thousands of dollars.
    - `Spending Score (1-100)`: Spending score based on customer behavior.

---

## 🛠 Tech Stack

- **Python**: Programming language used.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.
- **Plotly**: For interactive plots.
- **Scikit-learn**: For applying machine learning models (like KMeans clustering) and metrics.

---


### 1. Clone the repository
Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/mall-customers-analysis.git
cd mall-customers-analysis
