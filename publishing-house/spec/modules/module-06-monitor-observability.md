# Module 06 — Monitor Model Performance through Observability

### Brief Overview

A production AI service requires ongoing visibility into how the model is performing under real usage. This module introduces the observability dashboard in Red Hat AI Enterprise and shows attendees how to monitor model serving metrics. Attendees explore dashboards, observe key metrics under load, and analyze how serving behavior changes as the application sends requests to the model service.

### Audience and Time

- **Personas:** AI engineers, platform engineers, AI operations teams
- **Prerequisites:** Module 05 completed (end-to-end workflow validated; application actively sending requests to the model service)
- **Duration:** 20 min

### Learning Objectives

- Monitor model serving metrics through the observability dashboard
- Analyze serving behavior under load to identify performance trends

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Explore the observability dashboard | 5 min |
| 2 | Monitor key model serving metrics | 5 min |
| 3 | Generate load and observe metric changes | 5 min |
| 4 | Analyze performance trends | 5 min |

### Detailed Steps

1. Navigate to the observability dashboard in Red Hat AI Enterprise.
2. Locate the model serving metrics panel for the deployed model.
3. Review the available metrics: request rate, latency (p50, p95, p99), throughput, error rate, and resource utilization.
4. Observe the current metric values reflecting traffic from the application.
5. Generate additional load by sending multiple concurrent requests through the application.
6. Monitor the dashboard as metrics update in response to the increased load.
7. Observe how latency and throughput change under higher request volume.
8. Analyze the relationship between request rate, latency, and resource utilization.
9. Identify any performance trends or thresholds where serving behavior changes.
10. Review how these metrics inform scaling and capacity decisions for the model service.

### Key Takeaways

- The observability dashboard provides real-time visibility into model serving behavior, including latency, throughput, and error rate.
- Monitoring under load reveals how the model service responds to increased demand and where performance thresholds exist.
- Serving metrics inform operational decisions such as scaling policies, capacity planning, and alerting thresholds.

### Infrastructure Notes

- The observability dashboard must be configured and accessible in the Red Hat AI Enterprise environment.
- Metrics collection must be active for the model server deployed in Module 01.
