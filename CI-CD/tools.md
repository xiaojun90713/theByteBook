# CI/CD 典型工具链

在 CI/CD 工程实施中，Jenkins 和 Gitlab 已成为流程中的核心工具，其中 Jenkins 。现如今的 CI/CD 中，集合容器技术、镜像仓库、容器编排系统等各类工具链，已成为企业、各类组织效率提升必不可少的基础支撑。


<div  align="center">
	<img src="../assets/cicd-tools.png" width = "600"  align=center />
	<p>图：CI/CD 典型工具链</p>
</div>

目前，CI/CD 典型的工具链包括持续集成、持续交付、持续部署与基础工具类。

## 基础工具

Jenkins 是一个被广泛使用的可扩展的持续集引擎，提供了数以百计的插件来支持自动化构建、测试、部署相关的各类任务，Jenkins 在2.0版本中提供的流水线即代码(Pipeline as Code) 能力。贯穿于 CI/CD  整个过程，将原本独立运行与单个或多个节点的任务串联起来，从而实现单个任务难以完成的复杂发布流程。

Prometheus 是新一代的云原生监控系统，它是一个开源的完整监控解决方案，对传统的监控系统测试、告警模型进行了彻底颠覆的重新设计，形成了基于中央化的规则计算、统一分析和告警的新一模型。

为了实现统一的用户管理和权限管理，我们需要引入一套统一的用户管理系统，OpenLDAP 则是目前较为广泛应用的系统。

## 持续集成

典型的源码管理工具是 Gitlab，同时也可以完成代码评审等工作。

代码构建根据编程语言不同而不同，譬如 Java 构建工具包括 Maven、Gradle。单元测试框架 如 JUnit、TestNG等。

