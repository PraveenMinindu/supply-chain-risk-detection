# 🚚 Predictive Supply Chain Risk & Anomaly Detection
**Objective:** Minimizing financial loss by predicting logistics disruptions before they happen.

This project implements an intelligent monitoring system that scans global shipment data to detect anomalies and predict risks. Instead of reacting to delays, this system categorizes them by severity, allowing managers to focus on high-value "At-Risk" shipments.

### 🧠 Technical Implementation:
- **Anomaly Detection:** Isolation Forest algorithm to flag "Outlier" shipments that deviate from standard delivery windows.
- **Risk Classification:** Random Forest Classifier trained on route history, supplier reliability, and environmental factors.
- **Explainability:** Integrated SHAP values to explain *why* a shipment is marked as high-risk.

### 💼 Business Impact:
- **Value at Risk (VaR):** Automatically calculates the dollar value tied up in delayed shipments.
- **Proactive Mitigation:** Provides a 72-hour early warning window for 90% of high-risk routes.