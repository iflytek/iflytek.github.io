---
title: 从Helm Chart进行安装
weight: -20
---

当你已经创建好K8S集群,通过本节内容,您可以迅速创建 `AI推理服务框架` 社区版。

<!--more-->

{{< toc >}}

## Install requirements

* 已经创建完成的K8s集群 （k8s > 1.11）

* 提前安装好 Helm ，如未安装，请参考 [安装手册](https://helm.sh/docs/intro/install/)

* Git工具


```Shell
# clone helm chart
git clone git@github.com:xfyun/Athena_deploy.git

# 进入目录
cd Athena_deploy

# 配置values.yml

# Configure
helm install athena .

```
## Install Details

### Configure Mysql 

```shell
cd charts/mysql
# 配置values.yml
```


### Configure Zookeeper

```shell
cd charts/zookeeper
# 配置values.yml
```

### Configure Polaris

```shell
cd charts/zookeeper
# 配置values.yml
```

### Configure WebGate/

```shell
cd charts/zookeeper
# 配置values.yml
```

### Configure LoadBalance

```shell
cd charts/zookeeper
# 配置values.yml
```



### Command Tool: Download pre-build release bundle


### Usage && Examples



