<table>
<tr>
<td width="180">

<img src="images/Petra.png" width="150">

</td>

<td valign="middle">

# Supply Chain Performance and Delivery Risk Analysis Using Business Intelligence

</td>
</tr>
</table>


---

## Project Overview

This project applies *Business Intelligence (BI)*, *Data Analytics*, and *Machine Learning* techniques to analyze supply chain operations and improve delivery performance, operational efficiency, and profitability.

Using a real-world supply chain dataset containing *180,519 records and 53 attributes*, the project transforms operational data into actionable insights through data visualization, predictive analytics, and clustering techniques.

---

[Objectives](docs/Supply%20Chain%20Performance%20and%20Delivery%20Risk%20Analysis%20Using%20Business%20Intelligence.md#business-intelligence-project-description-and-objectives)

* Analyze supply chain performance and operational efficiency.
* Identify factors affecting delivery delays.
* Predict late delivery risk using machine learning models.
* Segment operational patterns using clustering techniques.
* Develop interactive dashboards to support data-driven decision-making.

---

## Dataset Overview

The dataset contains information related to:

* Orders and Transactions
* Products and Categories
* Customers and Segments
* Shipping Operations
* Delivery Performance
* Sales and Profitability
* Regional Operations
* Late Delivery Risk

---

## Data Cleaning and Transformation

The dataset was prepared using KNIME through:

* Data type conversion
* Duplicate removal
* Missing value handling
* Data standardization
* Feature transformation
* Data filtering

![Data Cleaning](images/Cleaning.png)

---

## Business Intelligence Dashboards

### 1. Supply Chain Operations & Delivery Performance Overview

![Dashboard 1](images/1.png)

**Key Insights**

* Sales and profit overview
* Customer segmentation analysis
* Delivery performance monitoring
* Shipping mode distribution
* Regional operational analysis

---

### 2. Supply Chain Profitability & Shipping Performance

![Dashboard 2](images/2.png)

**Key Insights**

* Product profitability analysis
* Sales vs profit comparison
* Regional profitability evaluation
* Shipping efficiency assessment

---

### 3. Late Delivery Risk & Logistics Performance

![Dashboard 3](images/3.png)

**Key Insights**

* Late delivery risk monitoring
* Delivery delay impact analysis
* Regional logistics performance
* Shipping mode effectiveness

---

### 4. Supply Chain Risk & Regional Performance

![Dashboard 4](images/4.png)

**Key Insights**

* Customer profitability
* Regional risk analysis
* Product category performance
* Shipping performance comparison

---

## Machine Learning Models

### Logistic Regression

Workflow:

![Logistic Regression Workflow](images/Logistic.png)

**Results**

* Accuracy: **83.4%**
* Strong baseline classification model
* Effective at identifying late deliveries

Confusion Matrix:

![Logistic Regression Confusion Matrix](images/CML.png)

Performance Metrics:

![Logistic Regression Results](images/ResultsLogistic.png)

---

### Random Forest

Workflow:

![Random Forest Workflow](images/Random.png)

**Results**

* Accuracy: **97.5%**
* Highest predictive performance
* Excellent classification balance

Confusion Matrix:

![Random Forest Confusion Matrix](images/CMR.png)

Performance Metrics:

![Random Forest Results](images/ResultsRandom.png)

---

## Model Comparison

| Metric    | Logistic Regression | Random Forest |
| --------- | ------------------- | ------------- |
| Accuracy  | 83.4%               | 97.5%         |
| Recall    | High                | Very High     |
| Precision | Good                | Excellent     |
| F-Measure | Good                | Excellent     |

### Best Performing Model

🏆 **Random Forest**

The Random Forest model outperformed Logistic Regression and achieved the highest prediction accuracy for late delivery risk.

---

## Clustering Analysis

K-Means clustering was applied to identify operational patterns and supply chain segments.

Workflow:

![Clustering Workflow](images/Clustering.png)

Cluster Centroids:

![Cluster Centroids](images/Centroids.png)

Cluster Distribution:

![Cluster Distribution](images/ClusteringDist..png)

### Cluster 0 – High-Risk Delayed Orders

* High delivery risk
* Frequent delays
* Strong sales contribution

### Cluster 1 – Moderate Performance Operations

* Balanced operational performance
* Moderate profitability
* Moderate delivery risk

### Cluster 2 – High-Performance On-Time Orders

* Lowest operational risk
* Stable profitability
* High delivery efficiency

---

## Technologies Used

### KNIME

* Data preprocessing
* Feature engineering
* Logistic Regression
* Random Forest
* K-Means Clustering

### Power BI

* Dashboard development
* KPI monitoring
* Data visualization
* Business intelligence reporting

### Other Tools

* Microsoft Excel
* Machine Learning Techniques
* Data Analytics Methods

---

## Key Findings

* Shipping mode significantly impacts delivery performance.
* Delivery delays increase operational risk.
* Regional differences affect profitability and logistics efficiency.
* Random Forest achieved the best predictive accuracy (**97.5%**).
* Clustering identified meaningful operational segments.
* Interactive dashboards support business decision-making.

---

## Business Value

This project helps organizations:

* Predict delivery delays
* Improve logistics planning
* Reduce operational risks
* Optimize supply chain performance
* Increase profitability
* Support data-driven decision-making

---

## Conclusion

This project demonstrates how Business Intelligence, Data Analytics, and Machine Learning can be integrated to transform raw supply chain data into actionable insights.

The combination of **Power BI dashboards**, **predictive analytics**, and **clustering techniques** provides an effective solution for improving supply chain visibility, reducing delivery risks, and supporting strategic business decisions.
