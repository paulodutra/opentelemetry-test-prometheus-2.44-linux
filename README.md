## Prometheus 2.44.0 Linux - Test opentelemetry

**Prerequisite:** Using the Operating System Linux amd64

1. After clone the repository. To run the application, execute the commands bellow:

```
wget -O prometheus-2.44.0.tar.gz https://github.com/prometheus/prometheus/releases/download/v2.44.0/prometheus-2.44.0.linux-amd64.tar.gz
tar -vzxf prometheus-2.44.0.tar.gz
cp prometheus.yml prometheus-2.44.0.linux-amd64/prometheus.yml
cd prometheus-2.44.0.linux-amd64/
./prometheus
```

OBS: The tutorial of opentelemetry-js in version 0.16.0:  https://github.com/open-telemetry/opentelemetry-js/tree/v0.16.0/getting-started, on step **Collect metrics using OpenTelemetry** suggested used the prometheus in this way.

2. Access the tools using the Browser at the address: http://localhost:9090/



