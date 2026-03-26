# Transaction Anomaly Detection for Fraud Risk

This project focuses on identifying potential fraudulent transactions using data analytics techniques. The goal is to detect unusual patterns in transaction data such as abnormal amounts, high-frequency activity, and suspicious timing.

Dataset
- Transaction-level dataset (~100K+ records)
- Features include transaction amount, time, and user ID

Tools & Technologies
- Python (Pandas, NumPy, Matplotlib)
- SQL
- Exploratory Data Analysis (EDA)

Methodology

1. Amount-based Anomaly Detection
- Used Z-score to identify unusually high or low transaction values

2. Frequency Analysis
- Identified users with abnormally high transaction counts

3. Time-based Analysis
- Flagged transactions occurring at unusual hours (late night)

4. Combined Risk Flag
- Transactions flagged if any anomaly condition is met

Key Insights
- ~2–5% of transactions flagged as anomalies
- High-value transactions show strongest deviation
- Certain users exhibit unusually high transaction frequency
- Late-night transactions show higher risk patterns

Outcome
Developed a simple rule-based anomaly detection framework useful for early-stage fraud detection and risk monitoring.

Project Structure
- notebook → Python analysis
- sql → SQL queries for anomaly detection
- data → dataset
- `images/` → visualizations

Future Improvements
- Machine learning-based anomaly detection
- Real-time fraud monitoring system
- Dashboard using Power BI
