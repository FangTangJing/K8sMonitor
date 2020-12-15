# K8sMonitor
基于Prometheus的K8s集群的监控和数据搜集

实现规则:
- 基于Prometheus云原生实现
- Prometheus、Thanos、Victoriametrics集搜集+存储
- 支持基于apiserver做节点发现的大规模节点数据拉取
- 支持大规模节点的hash拉取策略，环境Prometheus内存问题
[部署文档](https://www.noalert.cn/post/ru-he-yong-yuan-sheng-prometheus-jian-kong-da-gui-mo-kubernetes-ji-qun/)
