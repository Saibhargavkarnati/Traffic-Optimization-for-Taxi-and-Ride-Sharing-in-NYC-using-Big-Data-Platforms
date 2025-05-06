# 🚕 Traffic Optimization for Taxi and Ride-Sharing in NYC using Big Data Platforms

This project aims to optimize traffic flow and improve ride-sharing efficiency in New York City by leveraging big data platforms. By analyzing traffic volume and ride-sharing data using scalable tools like Apache Spark and AWS S3, we built a predictive model that helps forecast congestion and suggests actionable insights for city planners and transportation platforms.

---

## 📌 Project Objectives

- Identify traffic congestion patterns by time and location
- Predict vehicle volume across NYC road segments
- Provide data-driven recommendations for taxi dispatch and route planning
- Visualize trends and volatility in traffic across different segments and times of day

---

## 🗃️ Data Sources

- [NYC Yellow Taxi Trip Data (Parquet)](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- [NYC Traffic Volume Counts (CSV)](https://data.cityofnewyork.us/)
- Location Zone Lookup Table

All data was stored and accessed via **AWS S3 Buckets** for scalability and cloud-based processing.

---

## 🔧 Tools and Technologies

| Category           | Tools Used                          |
|--------------------|-------------------------------------|
| Data Processing    | Apache Spark, PySpark, Pandas       |
| Data Storage       | AWS S3, CSV, Parquet                |
| Machine Learning   | Spark MLlib (GBT Regressor, RF)     |
| Visualization      | Matplotlib, Seaborn                 |
| Development        | Google Colab                        |

### ⚡ Why Apache Spark?
- Handles large-scale datasets efficiently
- Supports distributed computing for fast processing
- Built-in MLlib for scalable machine learning

---

## 📊 Key Insights

- Top 10 congested segments identified by time of day
- Peak yellow cab demand around **5–7 PM** in Midtown
- High variability in traffic volume for some segments
- GBT model achieved **R² = 0.90**, indicating strong prediction accuracy

---

## 🎯 Recommendations

- Optimize real-time driver distribution based on predicted congestion
- Avoid dispatching drivers to highly congested areas during peak hours
- Integrate predictive routing into ride-hailing platforms

---

## 📈 Visual Outputs

- Traffic Volume Trend (24 hours)
- Volatility by Road Segment
- Actual vs Predicted Traffic Scatter Plot
- Congestion Ranking Visualizations

---

## 🧠 Future Opportunities

- Incorporate weather, event, and social data
- Integrate real-time streaming using Kafka and Spark Streaming
- Use Edge AI and Federated Learning for privacy-focused, real-time predictions


