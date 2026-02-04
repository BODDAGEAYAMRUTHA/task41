# task41
# Cloud Infrastructure Monitoring & Alerting

## 📌 Project Overview
This project demonstrates the implementation of a proactive monitoring solution using **[Insert Cloud Provider: AWS/Azure/GCP]**. The goal was to ensure high availability and performance of cloud resources by tracking key metrics, visualizing data through custom dashboards, and automating notifications for critical system events.

## 🛠️ Tech Stack
* **Cloud Provider:** [e.g., AWS]
* **Monitoring Service:** [e.g., Amazon CloudWatch]
* **Notification Service:** [e.g., Amazon SNS]
* **Monitored Resources:** [e.g., EC2 Instances, Auto Scaling Groups]

## 📊 Monitoring Strategy
I configured the following metrics to ensure the health of the infrastructure:

| Metric | Threshold | Action |
| :--- | :--- | :--- |
| **CPU Utilization** | > 80% for 5 mins | Trigger Critical Alarm |
| **Status Check Failed** | Any failure | Immediate Admin Notification |
| **Network In/Out** | Unusual Spikes | Log for Capacity Planning |
| **Memory Usage** | > 85% | Warning Alert |

## 🚀 Implementation Steps
1.  **Metric Collection:** Configured agents to collect system-level performance data.
2.  **Dashboard Creation:** Built a centralized visualization board to monitor real-time resource health.
3.  **Alarm Configuration:** Set up static thresholds for performance bottlenecks.
4.  **Notification Pipeline:** Integrated an automated notification system to alert engineers via Email/SMS when thresholds are breached.

## 📸 Evidence of Completion
*(Pro-tip: Upload your screenshots to a folder named 'screenshots' in this repo and link them below)*

### Custom Dashboard
![Dashboard Screenshot](screenshots/dashboard.png)

### Configured Alerts
![Alerts Screenshot](screenshots/alerts.png)

## ⚠️ Challenges & Learnings
* **Metric Granularity:** Finding the balance between high-resolution monitoring and cost/noise management.
* **Simulating Load:** Using stress-test utilities to verify that the alarm triggers correctly under pressure.
* **Threshold Tuning:** Adjusting "Evaluation Periods" to prevent "flapping" alarms (alerts that turn on and off too quickly).
