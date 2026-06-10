# Observability Stack for DevOps (Prometheus + Grafana + Loki + Tempo + OpenTelemetry)

## 📌 Overview
This project implements a complete **cloud-native observability system** for monitoring, logging, and tracing containerized applications using industry-standard tools.

It provides a unified platform to observe:
- Metrics (Prometheus)
- Logs (Loki + Promtail)
- Traces (Tempo + OpenTelemetry)
- Dashboards (Grafana)

---

## 🏗️ Architecture

Application → OpenTelemetry Collector →  
├── Metrics → Prometheus → Grafana  
├── Logs → Loki → Grafana  
└── Traces → Tempo → Grafana  

Additional:
- cAdvisor → Container metrics
- Node Exporter → Host metrics

---💡 Key Features
Centralized logging system using Loki + Promtail
Real-time metrics monitoring using Prometheus     
Distributed tracing system using Tempo + OpenTelemetry
Unified visualization using Grafana dashboards
Container-level monitoring using cAdvisor
Host-level monitoring using Node Exporter     
Fully containerized setup using Docker Compose

---

🎯 Key Learnings
Built end-to-end observability pipeline for cloud-native systems
Integrated metrics, logs, and traces in a single platform
Implemented OpenTelemetry-based distributed tracing
Designed production-like DevOps monitoring architecture
Improved debugging and troubleshooting efficiency using centralized observability
---


## 🛠️ Tech Stack

- Docker & Docker Compose
- Prometheus
- Grafana
- Loki
- Promtail
- Tempo
- OpenTelemetry Collector
- cAdvisor
- Node Exporter

---

## 🎯 Features

- Centralized logging system (Loki)
- Real-time metrics monitoring (Prometheus)
- Distributed tracing (Tempo)
- Unified visualization (Grafana dashboards)
- Container-level monitoring (cAdvisor)
- Host-level monitoring (Node Exporter)
- Fully containerized setup using Docker Compose

---

## 🚀 How to Run

```bash
git clone https://github.com/Lingaraj-1/observability-stack-monitoring.git
cd observability-stack-monitoring
docker-compose up -d

---

🌐 Access Services
Grafana → http://localhost:3000
Prometheus → http://localhost:9090

---
📊 Dashboards

The following dashboards are available in Grafana:

Infrastructure Monitoring Dashboard
Logs Dashboard (Loki)
Distributed Tracing Dashboard (Tempo)
Prometheus Targets & Metrics

📌 Add screenshots here:

Grafana Infrastructure Dashboard
Loki Logs View
Tempo Traces
Prometheus Targets
---
📁 Project Structure
.
├── docker-compose.yml
├── prometheus/
├── grafana/
├── loki/
├── promtail/
├── otel-collector/
├── notes-app/
└── screenshots/

---

💡 Key Features
Centralized logging system using Loki + Promtail
Real-time metrics monitoring using Prometheus
Distributed tracing system using Tempo + OpenTelemetry
Unified visualization using Grafana dashboards
Container-level monitoring using cAdvisor
Host-level monitoring using Node Exporter
Fully containerized setup using Docker Compose

---

🎯 Key Learnings
Built end-to-end observability pipeline for cloud-native systems
Integrated metrics, logs, and traces in a single platform
Implemented OpenTelemetry-based distributed tracing
Designed production-like DevOps monitoring architecture
Improved debugging and troubleshooting efficiency using centralized observability
---
