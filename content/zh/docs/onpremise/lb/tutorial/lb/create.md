---
title: "新建负载均衡实例"
date: 2021-12-17T16:07:23+08:00
weight: 10
description: >
    新建负载均衡实例
---

### 前提条件

- 已[新建负载均衡集群]({{< relref "../lbcluster/create" >}})
- 已在负载均衡均衡集群中[添加负载均衡节点]({{< relref "../lbagent/create" >}})并[部署节点]({{< relref "../lbagent/deploy" >}})

### 操作步骤

1. 在负载均衡实例页面，单击顶部“全部”或“本地IDC”页签，单击列表上方 **_"新建"_** 按钮，进入新建本地IDC负载均衡实例页面。
2. 设置以下参数：
    - 指定项目：管理员和域管理员需要在创建负载均衡实例时指定负载均衡实例所属的项目。
    - 区域：选择负载均衡所属的区域和可用区。
    - 名称：设置负载均衡实例的名称。
    - 平台：仅支持{{<oem_name>}}平台。
    - 集群：选择同一区域和可用区下的负载均衡集群。
    - 网络：选择IP子网，将随机在该IP子网中分配一个IP地址作为负载均衡的虚拟服务IP。目前仅支持经典网络（default VPC）。
3. 单击 **_"确定"_** 按钮，完成操作。