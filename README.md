# prometheus
介绍

1.alert文件

该文件包括告警的yaml文件信息

2.kube-state-metrics文件

该文件是官方的kube-state-metrics，需要监控的时候可以部署

3.prometheus

包括prometheus的yaml文件，采用nfs持久化数据

4.rules_targets

需要挂载的文件，rules是添加的规则，target是监控的目标对象。

5.mysql-exporter.yaml

监控mysql的exporter

6.node-exporter.yaml

监控node信息的exporter

7.redis-exporter.yaml

监控redis的exporter

