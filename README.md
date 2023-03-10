# Disaster Recovery Application Model
An application model for defining Disaster Recovery.

DRAM (Disaster Recovery Application Model) defines a high-level abstraction and application docking standards for disaster recovery. It provides a modeling approach for disaster recovery functions in hybrid cloud environments, making it easier to manage and deploy disaster recovery plans in the cloud.

To enable application-specific disaster recovery, DRAM (Disaster Recovery Application Model) provides an application-centric approach similar to virtual machines, databases, and containers. DRAM focuses on providing higher-level APIs for defining application disaster recovery, making it scalable, vendor agnostic, and with automatic failover. This approach addresses the critical requirements for data security and business continuity in modern applications, resulting in a simpler, more consistent, and reliable disaster recovery solution.

DRAM (Disaster Recovery Application Model) is compatible with [OAM](https://github.com/oam-dev/spec) (Open Application Model). While OAM focuses on delivery, it can help DRAM define deployment programs quickly and easily for specific environments. This compatibility allows for a more streamlined and efficient approach to disaster recovery in cloud-native applications.

## Introduction
[todo] there would be an pic.

Disaster Recovery Application Model Standardization:
灾备应用模型标准化：
1. Application-centric approach: Define the disaster recovery deployment with a self-contained model that focuses on the application rather than the container or orchestrator.
以应用程序为中心的方法：使用专注于应用程序而非容器或编排器的自包含模型定义灾难恢复部署。
2. Clarity and extensibility: Develop an open standard to modularize disaster recovery delivery into reusable pieces and assemble them into a deployment plan using a consistent and higher-level API.
清晰性和可扩展性：开发一个开放标准，将灾难恢复交付模块化为可重用的部分，并使用一致的更高级别的 API 将它们组装成部署计划。
3. Vendor agnostic: Create an abstraction layer that enables simple and robust disaster recovery delivery across hybrid environments, including Kubernetes, cloud providers, and IoT devices.
与供应商无关：创建一个抽象层，支持跨混合环境（包括 Kubernetes、云提供商和 IoT 设备）进行简单而强大的灾难恢复交付。
4. Automated failover: Support automated failover to reduce downtime and ensure that applications can continue to operate in the event of a disaster.
自动故障转移：支持自动故障转移以减少停机时间并确保应用程序可以在发生灾难时继续运行。
Advantages of the Disaster Recovery Application Model:
容灾应用模型的优势：
1. Simplified deployment: By focusing on the application rather than the underlying infrastructure, the disaster recovery deployment process can be simplified, reducing the need for developers to spend time on infrastructure details.
简化部署：通过关注应用程序而不是底层基础设施，可以简化灾难恢复部署过程，减少开发人员在基础设施细节上花费时间的需要。
2. Reusability: A standardized approach to modularizing disaster recovery delivery into reusable pieces can make it easier to manage and update disaster recovery plans over time.
可重用性：将灾难恢复交付模块化为可重用部分的标准化方法可以使随着时间的推移管理和更新灾难恢复计划变得更加容易。
3. Vendor agnostic: By using an abstraction layer, the disaster recovery application model can be deployed across different environments, making it easier to switch between different vendors or solutions as the needs of the organization change over time.
与供应商无关：通过使用抽象层，灾难恢复应用程序模型可以部署在不同的环境中，从而随着组织需求的不断变化，更容易在不同的供应商或解决方案之间切换。
4. Automated failover: With support for automated failover, organizations can reduce the risk of downtime and ensure that applications remain available in the event of a disaster, improving the overall resilience of the system.
自动故障转移：借助对自动故障转移的支持，组织可以降低停机风险并确保应用程序在发生灾难时保持可用，从而提高系统的整体弹性。

## Why


## Spec

### Our Goal

### Overview

### Backup

### Sync & Transfer

#### CBT

### IOLog

### Migration

### Protection

#### Multi-Site High Availability


## Background 
For my first thinking, I hope that there is a container standard disaster application interface and find that the data does not have the most attention to the value of the data unless it is an application data.

After reading http://technosophos.com/2018/08/19/the-then-problem-tight-vs-weak-coupling.html, we want to point out: Is CDRI necessary?What's more?

OAM is a good model for guiding ideology, and then DRAM was born.


