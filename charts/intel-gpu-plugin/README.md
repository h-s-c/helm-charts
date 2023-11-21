# intel-gpu-plugin

![Version: 0.20.0](https://img.shields.io/badge/AppVersion-0.20.0-informational?style=flat-square)

The Intel GPU plugin facilitates offloading the processing of computation intensive workloads to GPU hardware

## Source Code

* <https://github.com/intel/intel-device-plugins-for-kubernetes/blob/master/cmd/gpu_plugin>

## Dependencies

| Repository | Name | Version |
|------------|------|---------|
| https://library-charts.k8s-at-home.com | common | 4.5.2 |

## TL;DR

```console
helm repo add helm-charts https://h-s-c.github.io/helm-charts
helm install intel-gpu-plugin helm-charts/intel-gpu-plugin
```
