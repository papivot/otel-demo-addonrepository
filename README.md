# OpenTelemetry Demo Helm AddonRepository

## Source

[https://opentelemetry.io/docs/platforms/kubernetes/helm/demo/](https://opentelemetry.io/docs/platforms/kubernetes/helm/demo/)

The Open Telemetry Demo is a *microservice-based distributed system* intended to illustrate the implementation of OpenTelemetry (observability) in a near real-world environment. As part of that effort, the OpenTelemetry community created the OpenTelemetry Demo Helm Chart so that it can be easily installed in Kubernetes.

## Included Files

All these files are deployed on the Supervisor and leverages VKS v3.7 or higher. 

- `addonRepository.yaml`: Declares the upstream Helm repository for the OpenTelemetry demo chart. 
- `addonInstall.yaml`: Handles the installation of the OpenTelemetry demo chart on VKS clusters, including a workaround for the helm-controller bug in VKS v3.7.
