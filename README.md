# Monitoring System
In this project, a monitoring system has been established using Docker Compose to monitor system resources with Prometheus, Grafana, and Node Exporter.

---

## Getting Started
You can start the project by entering the following command in your terminal:

docker compose up -d

## Grafana Login
Next, access the Grafana interface from your browser:

🖥️ http://localhost:3000

## Login Credentials:

User: admin
Password: admin

## Dashboard
When Grafana opens, a dashboard is automatically loaded. This dashboard visualizes system metrics (e.g., CPU usage) using data sourced from Prometheus.

![Grafana Dashboard](./grafana.png)


## Alerting System
The project includes automatically loaded alert rules using Grafana's alerting system. These rules, which can be viewed in the "Alert rules" section, are designed to notify you when predefined thresholds are reached.

![Grafana Alert](./grafanaalert.png)


You can also check the "Active notifications" section.

![Grafana Alert2](./grafanaalert2.png)

### Alert Rules
The alert rules are defined within the grafana/provisioning/alerting/grafana_provisioned_alerts.yaml file.

