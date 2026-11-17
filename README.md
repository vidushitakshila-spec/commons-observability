# commons-observability
1. Problem statement: Debugging production issues across distributed services is difficult without unified metrics, distributed tracing, and correlated log markers.

2. Concepts and terminology: Micrometer, OpenTelemetry, Trace ID, Span ID, Structured Logging, Prometheus Metrics.

3. Available technologies / algorithms: Micrometer Tracing, OpenTelemetry Java Agent, Prometheus, Grafana.

4. When to use what: Use in all applications to automatically inject trace contexts into HTTP headers and emit standardized operational metrics.

5. Java APIs and dependencies: micrometer-observation, micrometer-tracing-bridge-otel, Prometheus registry.

6. AWS equivalents: AWS X-Ray, Amazon CloudWatch Container Insights.

7. Architecture patterns: Distributed Tracing Propagation (W3C Trace Context), Observability-Driven Development.

8. Security considerations: Ensure trace spans and log markers do not capture sensitive query parameters or authorization headers.

9. Implementation examples: Custom Micrometer timer aspect measuring execution latency of critical security validators.

10. References and further reading: W3C Trace Context Specification.
