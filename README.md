# Industrial Ops & Telemetry

Centralized observability hub for monitoring the Zero-Trust ecosystem.

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
