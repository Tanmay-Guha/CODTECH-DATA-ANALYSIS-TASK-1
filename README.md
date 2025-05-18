# 📊 Big Data Analysis with Dask and PySpark

This project demonstrates large-scale e-commerce data analysis using **Dask** and **Apache Spark** in Python. It showcases how to process, analyze, and visualize millions of transaction records using distributed computing frameworks.

## 🔧 Tools & Technologies Used

* [Dask](https://www.dask.org/): For parallel computing and efficient data manipulation on large datasets
* [PySpark](https://spark.apache.org/docs/latest/api/python/): For distributed data processing and cluster-based analytics
* [Matplotlib](https://matplotlib.org/): For visualizing revenue trends
* [Pandas & NumPy](https://pandas.pydata.org/): For data generation and transformation
* Google Colab: For running and sharing the notebook
* Apache Spark (Local and Cluster mode)

## 📂 Project Structure

* **Data Generation**: Creates synthetic data simulating 10 million e-commerce transactions.
* **Dask Operations**:

  * Basic statistics and summary
  * Top product revenue analysis
  * Daily revenue trend visualization
  * Rolling average revenue analysis
* **Spark Operations**:

  * Initializing local and cluster Spark sessions
  * Basic Spark DataFrame operations

## 📈 Visual Output

* Revenue trend over time
* 7-day moving average plot for better insights

## ⚙️ Setup Instructions

### 1. Requirements

Install required libraries if not available:

```bash
pip install dask[complete] matplotlib pandas numpy pyspark
```

### 2. Run in Jupyter Notebook / Google Colab

* Open the notebook in [Google Colab](https://colab.research.google.com/drive/1fpPxwksHbYdp8coHBPLbTizB0J-klHG3) or any local Jupyter environment.
* Run all cells sequentially to:

  * Generate synthetic data
  * Process using Dask and Spark
  * Visualize results

## 🚀 Spark Cluster Setup (Optional)

To run Spark in cluster mode, update the Spark master URL:

```python
.master("spark://your-cluster-master:7077")
```

Ensure Spark is properly configured and your cluster is running.

## 📌 Notes

* This project is for educational/demo purposes. Replace synthetic data with actual data sources (like CSV or Parquet) for real-world use.
* You can scale this solution easily for larger datasets using cloud clusters.

---

## 📃 License
This project is open for educational and personal use. Please credit if reused.

---

## 🙋‍♂️ Author
TANMAY GUHA

Email:- tanmayguha15@gmail.com

---
