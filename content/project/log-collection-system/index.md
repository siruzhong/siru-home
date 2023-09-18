---
title: log-collection-system
summary: Using Go language, the configuration center etcd, message middleware Kafka, search engine ElasticSearch, time series database InfluxDB, and log collection system developed by visualization platform Kibana and Grafana.

tags:
  - log-collection-system
date: "2023-09-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: https://github.com/siruzhong/log-collection-system

image:
  caption: Photo by Siru ZHONG
  focal_point: Smart
---

Every business system has logs. When a problem occurs in the system, logs are needed to locate and solve the problem. When the system machine is relatively small, it is enough to log in to the server to view it. However, under today's distributed system architecture, a complete system is often deployed on many machines through module splitting. It is not a problem to log in to view each machine one by one. In reality, a log collection system is needed to provide a unique entrance for complete collection of all log information.
