# 马哥带你七天精通kubernetes(K8s)

课程大纲

```
一、Kubernetes集群架构

1、Kubernetes集群架构概述

2、Master及各组件

3、Node及相关组件

4、核心附件CoreDNS、HeapSter（Prometheus）、Dashboard及Ingress Controller概述

5、核心资源类型：Pod、Deployment、Service

二、Kubernetes快速入门

1、Kubernetes集群的部署方法及部署要点

2、部署Kubernetes分布式集群

3、kubectl使用基础

4、命令式应用部署、扩缩容、服务暴露

三、资源配置清单及Pod资源

1、Kubernetes API中的资源配置格式

2、资源类型、API群组及其版本介绍

3、Pod资源及其配置格式

4、使用配置清单创建自主式Pod资源

5、标签及标签选择器

6、Pod的节点选择器

7、容器存活状态探测及就绪状态探测

四、Pod控制器

1、Pod控制器及其功用

2、通过配置清单管理ReplicaSet控制器，包括扩缩容及更新机制

3、Deployment控制器基础应用及滚动更新：灰度部署、金丝雀部署、蓝绿部署的实现；

4、DaemonSet控制器基础应用及使用案例

五、Service资源对象

1、Service及其实现模型

2、Service的类型及其功用

3、各Service类型的创建及应用方式

4、Headless Service

5、基于DNS的服务发现简介

6、Ingress类型及实现方式

7、Ingress Controller及部署

8、Ingress使用案例：发布http及https的tomcat服务

六、K8S-存储卷

1、存储卷及其功用

2、常见的存储卷类型及应用：emptyDir、hostPath、nfs、glusterfs等

3、PV及PVC

4、StorageClass及PV的动态供给

5、ConfigMap

6、Secret

七、StatefulSet

1、有状态及无状态应用对比

2、有状态应用的容器难题

3、StatefulSet及其应用

4、案例

八、网络模型及网络策略

1、flannel工作原理及host-gw等实现方式

2、calico及其应用

3、网络策略及其工作机制

4、基于calico的网络策略的实现

九、认证、授权及准入控制

1、Kubernetes的认证、授权及准入控制机制

2、ServiceAccount

3、令牌认证及证书认证

4、RBAC及其实现机制

5、Role和RoleBinding

6、ClusterRole和ClusterRoleBinding

十、调度器

1、资源需求、资源限额及其应用

2、Pod优选级类别

3、Pod调度器工作原理

4、预选及预选策略

5、优选及优选算法

6、高级调度方法

十一、资源监控及HPA

1、HeapSter、InfluxDB及Grafana实现资源监控

2、HPA v1

3、Prometheus及Grafana实现资源监控

4、Metrics-Server

5、HPA v2

十二、helm及日志收集系统

1、helm工作原理

2、helm部署及其应用

3、部署efk日志收集系统

十三、基于Kubernetes的DevOps介绍
```
