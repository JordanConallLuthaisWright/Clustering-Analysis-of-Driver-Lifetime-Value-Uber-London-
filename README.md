# Clustering Data Analysis of Driver Lifetime Value (DLV) - Uber, London

Utilized Python, Pandas, and NumPy for data preprocessing and feature engineering. Applied K-Means clustering to segment drivers based on ride metrics. Used Seaborn and Matplotlib for data visualization. Conducted business analysis to derive actionable insights for driver retention, dynamic pricing, and performance optimization.

***This project analyzes Uber's driver lifetime value (DLV) using clustering techniques to segment drivers based on ride metrics and performance. The goal is to identify key drivers, optimize retention strategies, and improve overall driver engagement and earnings.***

---

By applying **K-Means clustering**, **data preprocessing**, and **feature engineering**, this project groups drivers into distinct categories based on their **lifetime value, ride frequency, duration, and performance metrics**. Key analysis areas include **driver segmentation**, **performance improvement recommendations**, and **targeted retention strategies**.

The findings offer actionable insights to **retain top performers**, **optimize pricing models**, and **enhance overall driver efficiency**, improving business operations and maximizing revenue.

---

## Project Aim  
This project utilizes **K-Means clustering** to analyze driver data, categorizing drivers into four groups: Bad, Fair, Good, and Excellent drivers. The goal is to **optimize driver retention**, **improve performance**, and **refine business strategies** in the ride-sharing industry.

---

## Technical Skills Demonstrated  
- **Data Preprocessing & Cleaning**: Handling **missing values**, **outliers**, and **categorical data** for clustering analysis.  
- **Clustering & Segmentation**: Implementing **K-Means clustering** to group drivers based on performance metrics.  
- **Feature Engineering**: Creating features such as **lifetime value**, **ride count**, and **driver tenure** to enhance analysis.  
- **Exploratory Data Analysis (EDA)**: Visualizing **driver performance trends** and segment characteristics using **Matplotlib** and **Seaborn**.  
- **Business Insights**: Deriving actionable recommendations for **dynamic pricing**, **targeted incentives**, and **driver performance improvement**.

---

## Files in This Repository  
| File | Description |
|------|------------|
| `Clustering Analysis of Driver Lifetime Value.ipynb` | Jupyter Notebook containing data preprocessing, clustering analysis, and business insights. |
| `driver_ids.csv` + 'ride_ids.csv' + 'ride_timestamps.csv' [inside zip] | Dataset containing driver performance metrics, ride data, and demographic information. |

---

## How to Run This Project  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/JordanConallLuthaisWright/clustering-analysis-driver-lifetime-value.git
2. **Navigate to the project directory**
   ```bash
   cd clustering-analysis-driver-lifetime-value
3. **Install dependencies**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
5. **Open and run "Clustering Analysis of Driver Lifetime Value.ipynb"**

---

## Business Scenario  
This project uses **clustering analysis** to categorize Uber drivers into different performance groups, helping the company make **data-driven decisions** to:

- **Identify high-performing drivers** and prioritize retention efforts.
- **Enhance the performance** of fair and bad drivers through targeted incentives and training.
- **Optimize pricing strategies** and **adjust service fees** based on cluster results.
- **Improve overall driver engagement** and maximize business revenue.

---

## **Key Business Scenarios Addressed**  

### **1. Driver Segmentation**  
- **Bad Drivers:** Drivers exhibiting low total lifetime value, ride frequency, and overall engagement.  
- **Fair Drivers:** Drivers showing moderate performance but with potential for improvement.  
- **Good Drivers:** High-performing drivers with consistent ride frequency, higher earnings, and a good reputation.  
- **Excellent Drivers:** Top-tier drivers with the highest performance metrics, contributing significantly to Uber's revenue.

### **2. Performance Improvement Strategies**  
- **Retention Strategies:** Focus on incentivizing **Good** and **Excellent Drivers** to ensure they remain on the platform.  
- **Targeted Incentives:** Provide personalized incentives to **Fair Drivers** to improve performance and push them toward higher clusters.  
- **Support for Bad Drivers:** Offer performance-enhancing workshops, allocate more rides, and optimize scheduling for **Bad Drivers**.

### **3. Dynamic Pricing Optimization**  
- **Price Adjustments:** Utilize clustering results to set **dynamic pricing models** based on the availability and performance of drivers in specific regions.  
- **Optimal Fare Structures:** Develop fare strategies that maximize both driver earnings and rider affordability, based on cluster insights.

---

## Methodology & Technical Skills Demonstrated  

### 1. Data Cleaning & Preprocessing  
- **Removed non-numeric features** and handled missing data.  
- **Standardized and normalized** features for clustering analysis.

### 2. K-Means Clustering  
- **Applied K-Means clustering** to segment drivers into performance-based groups.  
- **Determined optimal number of clusters** using the elbow method and visualized results.

### 3. Exploratory Data Analysis (EDA)  
- **Visualized distribution** of lifetime values, ride count, and duration by cluster.  
- **Identified performance patterns** and outliers across driver groups.

### 4. Business Insights & Recommendations  
- **Provided actionable business recommendations** to improve driver retention, optimize incentives, and enhance pricing strategies.

---

## Key Findings & Conclusion  
- **Cluster 0 (Bad Drivers)**: Drivers with low performance metrics and earnings.  
- **Cluster 2 (Fair Drivers)**: Moderate performance but room for improvement.  
- **Cluster 1 (Good Drivers)**: Consistent performance and high engagement.  
- **Cluster 3 (Excellent Drivers)**: Top performers with maximum earnings and ride frequency.
  
**Conclusion:** Data-driven strategies based on clustering analysis can help **retain top-performing drivers**, **improve underperforming drivers**, and **optimize pricing models** to boost overall business performance.

---

## **Contact & Contributions**
Feel free to explore and contribute! If you have any suggestions or improvements, feel free to submit a pull request or contact me.

- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)

---

### **Author:** Jordan  
[GitHub Profile](https://github.com/JordanConallLuthaisWright)
