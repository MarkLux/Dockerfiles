## 说明

用于代理墙外镜像的docker files

使用阿里云镜像仓库构建

## 目录

格式：`原镜像地址 => 代理后镜像地址`

- k8s.gcr.io/heapster-amd64:v1.5.4 => `registry.cn-qingdao.aliyuncs.com/gcr-mock/heapster:latest`

- k8s.gcr.io/heapster-grafana-amd64:v5.0.4 => `registry.cn-qingdao.aliyuncs.com/gcr-mock/grafana:latest`

- k8s.gcr.io/heapster-grafana-amd64:v5.0.4 => `registry.cn-qingdao.aliyuncs.com/gcr-mock/influxdb:latest`

- k8s.gcr.io/metrics-server-amd64:v0.2.1 => `registry.cn-qingdao.aliyuncs.com/gcr-mock/metrics-server:latest`

- k8s.gcr.io/addon-resizer:1.8.1 => `registry.cn-qingdao.aliyuncs.com/gcr-mock/addon_resizer:latest`