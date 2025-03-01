---
title: "如何在Apache Cassandra中增加分区大小可以减少超过30%的磁盘使用"
date: "2023-08-19T16:15:00" 
track: "datastorage"
presenters: "John Del Castillo"
stype: "英文演讲"
---
您知道Apache Cassandra中的过度分区会导致过多的存储需求吗?

在本次演讲中，我们将探讨Instaclustr如何将指标数据的存储空间减少30%以上，从244tb减少到157tb，并提高集群的总体性能——只需对我们正在使用的表的模式做一个小小的改变。

作为我们托管服务的一部分，Instaclustr管理着超过10,000个客户服务器，该系统的一部分包括来自操作系统和运行应用程序的实时指标收集，这些应用程序存储在70个节点的Apache Cassandra集群中。

我们将详细解释现有模式旨在解决的问题，Cassandra专家如何确定我们需要更改的内容，以及为什么更改能够在不对下游系统进行重大更改的情况下大幅提高我们的存储效率。
 ### Speakers: 
 <img src="https://img.bagevent.com/resource/20230606/1034424690.jpg" width="200" /><br>约翰·德尔·卡斯蒂略: NetApp, 技术专员, 我是一名软件工程师，拥有超过15年的开发跨多种语言和技术的企业软件解决方案的经验。

我在Instaclustr工作了6年，担任首席工程师，去年我担任了技术传道者，专门从事开源技术。

在这个角色中，我探索开源技术的前景，探索新的解决方案，记录有趣的用例，并创建书面和视频内容，以帮助教育和鼓励人们将开源用于他们的业务。
 <br><br>