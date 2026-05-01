# 🚀 Suricata SIEM with Elastic Stack

## 🔍 Overview
Designed and implemented a **mini SIEM pipeline** to detect, ingest, and visualize network threats in real-time using Suricata and Elastic Stack.

---

## 🧠 Architecture
Suricata (IDS) → Filebeat → Elasticsearch → Kibana

---

## ⚙️ Features
- Real-time **network threat detection**
- Log ingestion using **Filebeat pipelines**
- Structured indexing in **Elasticsearch**
- Interactive dashboards in **Kibana**
- Detection of suspicious traffic patterns

---

## 🔍 Sample Detection
Example alert captured:

> **GPL ATTACK_RESPONSE – Potentially Bad Traffic**

---

## 📊 Dashboards

### Kibana Dashboard
![Kibana Dashboard](./screenshots/kibana-dashboard.png)

### Suricata Alerts
![Suricata Alert](./screenshots/suricata-alert.png)

---

## 🛠️ Tech Stack
- Suricata (IDS/IPS)
- Filebeat
- Elasticsearch
- Kibana
- Ubuntu (UTM)

---

## 📈 Outcome
- Built a **SOC-style monitoring pipeline**
- Achieved **real-time visibility into network events**
- Successfully validated detection using simulated traffic

---

## 🔭 Future Enhancements
- ML-based anomaly detection
- Threat intelligence integration
- Automated alerting

