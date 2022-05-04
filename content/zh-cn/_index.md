---
title: AI技术开源计划
geekdocNav: false
geekdocAlign: center
geekdocAnchor: false
---

<!-- markdownlint-capture -->
<!-- markdownlint-disable MD033 -->

<span class="badge-placeholder">[![Build Status](https://img.shields.io/drone/build/thegeeklab/hugo-geekdoc?logo=drone&server=https%3A%2F%2Fdrone.thegeeklab.de)](https://drone.thegeeklab.de/thegeeklab/hugo-geekdoc)</span>
<span class="badge-placeholder">[![Hugo Version](https://img.shields.io/badge/hugo-0.83-blue.svg)](https://gohugo.io)</span>
<span class="badge-placeholder">[![GitHub release](https://img.shields.io/github/v/release/xfyun/AthenaServing)](https://github.com/xfyun/AthenaServing/releases/latest)</span>
<span class="badge-placeholder">[![GitHub contributors](https://img.shields.io/github/contributors/xfyun/AthenaServing)](https://github.com/xfyun/AthenaServing/graphs/contributors)</span>
<span class="badge-placeholder">[![License: Apache2.0](https://img.shields.io/github/license/xfyun/AthenaServing)](https://github.com/xfyun/AthenaServing/blob/master/LICENSE)</span>

<!-- markdownlint-restore -->

讯飞AI技术开源计划围绕在经过内部业务多年打磨后的AI算法、训练、推理、服务工具、平台框架、系统方案, 根据其技术通用度,逐步对外部进行开源、开放

{{< button size="large" relref="inferservice/quick-start/getting-started/" >}}快速开始{{< /button >}}


## Saas/Paas
{{< columns >}}
### [高性能AI推理服务化框架](https://github.com/xfyun/AthenaServing)

依托科大讯飞多年的AI算法引擎云服务化经验及云原生的不断探索实践,不仅可以满足引擎云服务化后,服务的稳定性,也可以通过 [引擎托管平台]() 享受到相关云原生组件的方便与快捷。AI算法引擎开发者可以专注于算法的演进与研究,无需分心进行硬件资源的管理及云服务化的诸多开发运维工作。

<--->

### 轻量级MLOps训练平台

基于开源MLops编排框架开发的轻量级训练平台系统, 支持 Horovod, Tensorflow, Pytorch , NoteBook 等主流训练框架, 用户只需提供对应的框架训练脚本,提前上传或者同步待训练的数据集,即可在此平台进行训练。

<--->

### 多协议存储网关

支持 S3, HTTP, Posix, NFS等多种协议上传下载,存储后端;支持文件系统存储(NFS,POSIX,LocalFileSystem等),用户可以不再需要关注具体存储选型,通过存储网关可以自动根据文件信息以及对应的策略配置,将文件存储到合适的存储后端。

{{< /columns >}}

{{< columns >}}

### [XMQTT](https://github.com/xfyun/xmqtt)

XMQTT是一个完全开源的MQTT消息代理，适用于物联网、M2M和移动应用程序，可以处理百万并发的客户端连接。 为设备提供安全可靠的连接通信能力，向下连接海量设备，支撑设备数据采集上云，并且完全兼容MQTT 3.1和3.1.1规范。 它是基于开源项目surgemq 进行开发的， 在此基础上对稳定性和性能做出了改善，并增加了一些新的特性。

<--->

### [XNS](https://github.com/xfyun/xns)
XNS 是一个基于golang fasthttp 框架构建的一个高效的httpDNS 服务，目前已经在讯飞云实践，承担着讯飞云大部分流量调度的任务。 httpDNS是一种提供http协议域名解析的服务。 支持自定义各种解析规则，满足不同的域名解析场景。能够根据用户所在地，就近分发最近，最优的地址(实现该功能需要ip地址池)。 同时使用httpDNS 可以绕过运营商的DNS解析，实现流量秒级切换，没有运营商DNS的解析残留问题。

<--->

### 工具集

* [NLP相关工具集](https://ymcui.com/resources.html)
* [AI模型通用加载器](https://github.com/xfyun/aiges)
* [Argo VCJob工作流插件](https://github.com/xfyun/argo-volcano-executor-plugin)
* [Flags](https://github.com/xfyun/flags)


{{< /columns >}}



## 算法、数据集
{{< columns >}}

### [数据集](https://github.com/xfyun/datasets/tree/master)

最新讯飞AI开源训练数据集集合，包含NLP, CV, 语音等多领域,逐步开放内部部分工业级数据集

<--->

### [预训练模型](https://ymcui.com/resources.html)


联合哈工大实验室, 逐步开放可公开的预训练模型

<--->

### [模型算法](https://ymcui.com/resources.html)

联合哈工大实验室, 逐步开放一些开源模型算法

{{< /columns >}}


## 基础设施
{{< columns >}}

### Kube On Kube

AICloud k8s master 多集群管理方案，包含在离线业务混部实践(TODO)

<--->

### Liqo

使用Liqo保证业务组件高可用方案(In Progress)

<--->

### [更多开源建议](https://xfyun.github.io/contribute/proposal/)

汇聚近期的开源计划，以及一些开源构想、设计, 有兴趣的开源开发者可以踊跃参与共享！秀出你的代码


{{< /columns >}}

## 社区联系

{{< columns >}}

<!-- markdownlint-capture -->
<!-- markdownlint-disable MD033 -->

<figure class="third">
    <img src="/imgs/argo.png" width="20%">
    <img src="/imgs/volcano.png" width="20%">
    <img src="/imgs/k8s.png" width="20%">
    <img src="/imgs/pytorch.png" width="20%">
    <img src="/imgs/tf.png" width="20%">
    <img src="/imgs/paddle.png" width="20%"  >

</figure>
<!-- markdownlint-restore -->

{{< /columns >}}
