+++
title = "Logging and monitoring"
description = "Logging and monitoring for Kubeflow"
weight = 110
+++


[Prometheus](https://prometheus.io/) is a monitoring tool often used with Kubernetes. If you configure Kubernetes Engine Monitoring and include Prometheus support, then the metrics that are generated by services using the [Prometheus exposition format](https://prometheus.io/docs/instrumenting/exposition_formats/) can be exported from the cluster and made visible as [external metrics](https://cloud.google.com/monitoring/api/metrics_other#externalgoogleapiscom) in Cloud Monitoring.

To configure and use Prometheus with Kubernetes Engine Monitoring, see [the GCP documentation](https://cloud.google.com/monitoring/kubernetes-engine/prometheus).