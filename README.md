# 📊 Industrial Ops & Telemetry

[![Docker](https://img.shields.io/badge/Infrastructure-Docker-2496ED.svg)](https://www.docker.com)
[![Prometheus](https://img.shields.io/badge/Monitoring-Prometheus-E6522C.svg)](https://prometheus.io)
[![Grafana](https://img.shields.io/badge/Visualization-Grafana-F46800.svg)](https://grafana.com)

---
Part of the [Industrial Portfolio 2026](https://github.com/Brainfeed-1996/industrial-portfolio-2026) ecosystem.

## Architecture
- **Prometheus**: Time-series database for metrics.
- **Grafana**: Dashboarding for visualization.
- **Docker Compose**: Orchestration of the telemetry stack.

## SRE/Monitoring
- Prometheus targets include the Zero-Trust Identity service and Edge AI IDS.
- Built-in alerting for security events and service downtime.

## ADR
- [ADR-001: Use Prometheus for Metrics Collection](docs/adr/001-prometheus-metrics.md)
- [ADR-002: Grafana for Security Visualization](docs/adr/002-grafana-dashboards.md)
