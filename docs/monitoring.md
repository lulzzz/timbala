# Monitoring

## Metrics
AthensDB exposes metrics in the [Prometheus format][] over HTTP. You can use these metrics
to define alerts for monitoring or create operational dashboards.

[Prometheus format]: https://prometheus.io/docs/instrumenting/exposition_formats/

## Logging

AthensDB logs errors or warnings to stderr and informational messages to
stdout, in JSON format.

## Tracing

Support for OpenTracing is [planned][], allowing for easier performance
debugging.

[planned]: https://github.com/mattbostock/athensdb/issues/42