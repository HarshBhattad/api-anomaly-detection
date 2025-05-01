# 🚨 Intelligent API Anomaly Detection using Machine Learning & Time Series Forecasting

This project simulates a real-world anomaly detection pipeline for API monitoring. It uses a hybrid approach combining unsupervised machine learning (Isolation Forest) and time-series forecasting (Prophet) to detect silent failures, traffic anomalies, and abnormal latency patterns across a large-scale synthetic API log dataset.

The goal is to catch failures that go unnoticed in traditional monitoring — such as successful 200 OK responses with invalid payloads or regional spikes in 5xx status codes — and proactively surface them using robust data science methods.

---

## 📌 Project Highlights

- Built on a synthetic dataset of 50,000 API log records
- Combined ML + statistical forecasting for layered anomaly detection
- Detected:
  - Silent API failures (200 OK but invalid payload)
  - Regional spikes in error codes
  - Unexpected traffic drops
  - Latency surges beyond rolling averages
- Delivered clear visualizations and a final anomaly dashboard

---

## 📁 Folder Structure

API-Anomaly-Detection/
├── api_anomaly_detection.ipynb     # Main notebook with full pipeline  
├── master_anomalies.csv            # Final combined anomaly report  
├── requirements.txt                # Python dependencies  
├── README.md                       # Project overview and documentation  
└── plots/                          # (Optional) Output visualizations  

---

## 🔧 Tools & Technologies Used

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn (Isolation Forest)  
- Prophet (Facebook/Meta)  
- Matplotlib, Seaborn  
- Jupyter Notebook, Git, GitHub  

---

## 🚀 How to Run This Project

1. Clone the repository:
```
git clone https://github.com/YOUR_USERNAME/api-anomaly-detection.git
cd api-anomaly-detection
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Launch the notebook:
```
jupyter notebook api_anomaly_detection.ipynb
```

---

## 📊 What the Project Does

- Converts timestamps and creates rolling metrics  
- Detects silent failures, traffic volume drops, and error spikes  
- Trains an Isolation Forest model for feature-based anomaly detection  
- Uses Prophet to forecast API traffic and detect volume-based anomalies  
- Merges both into a master anomaly table with categorization and visual reports  

---

## 📈 Sample Visualizations

- Line plot of response time over time  
- Bar chart of anomalies by service  
- Heatmap of error rate by environment  
- Timeline of combined anomalies

---

## 🎯 Project Outcomes

- Detected 60+ real-time anomalies across 50,000 API logs  
- Categorized silent failures that 200 OK responses would have missed  
- Demonstrated layered detection using ML + forecasting  
- Delivered stakeholder-ready metrics, plots, and a final anomaly report  

---

## 💡 Skills Demonstrated

- Data cleaning & feature engineering  
- Unsupervised ML (Isolation Forest)  
- Time-series modeling (Prophet)  
- Real-world system monitoring design  
- Data visualization & communication  

---

## 🙋‍♂️ Author

**Harsh Bhattad**  
Master’s in Systems Analytics, Stevens Institute of Technology  
📧 hbhattad@stevens.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/harsh-bhattad)

---

## 📄 License

This project is open-source and available for educational and portfolio use.
