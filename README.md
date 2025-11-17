# Accelerated-credit-card-fraud-detection-using-RAPIDS-on-EMR

Accelerated credit card fraud detection using RAPIDS on EMR
Credit card fraud detection system using GPU-accelerated RAPIDS on AWS EMR. By integrating cuDF, cuML, and Apache Spark on GPU-enabled clusters, the project processes large-scale transaction data significantly faster and more cost-effectively than traditional CPU-based approaches.

**Problem Statement**

Credit card fraud is a growing issue in digital payments.

Traditional detection systems based on CPU models are often slow and struggle with large volumes of data.

The challenge is to build a fraud detection system that is both accurate and fast enough to scale with real-time financial systems.

**Highlights**

Built an end-to-end fraud detection pipeline using Spark and RAPIDS

Achieved 30–40% speed improvement over CPU-only clusters on EMR

Trained and evaluated multiple models including Logistic Regression, Random Forest, Decision Trees, and Clustering

Used both real-world and synthetic datasets with 100K+ records

Compared performance metrics, model accuracy, and execution time across CPU and GPU environments

Tuned feature engineering and data balancing to improve fraud classification

**Tools & Technologies**

Apache Spark (3.0+)

RAPIDS cuDF + cuML

AWS EMR with GPU nodes (g4dn.2xlarge)

Python, Pandas, scikit-learn

Jupyter + Livy for remote notebook execution

CSV, Parquet formats for large-scale data processing

**Models Implemented**

Logistic Regression (GPU and CPU versions)

Random Forest

Decision Tree

K-Means Clustering

K-Nearest Neighbors (KNN)

**Summary**

A high-performance fraud detection pipeline leveraging GPU-accelerated RAPIDS on AWS EMR, achieving up to 40% speed improvement over traditional Spark models while maintaining high accuracy.
