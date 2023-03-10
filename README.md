# Disaster Recovery Application Model
An application model for defining Disaster Recovery.

DRAM (Disaster Recovery Application Model) defines a high-level abstraction and application docking standards for disaster recovery. It provides a modeling approach for disaster recovery functions in hybrid cloud environments, making it easier to manage and deploy disaster recovery plans in the cloud.

To enable application-specific disaster recovery, DRAM (Disaster Recovery Application Model) provides an application-centric approach similar to virtual machines, databases, and containers. DRAM focuses on providing higher-level APIs for defining application disaster recovery, making it scalable, vendor agnostic, and with automatic failover. This approach addresses the critical requirements for data security and business continuity in modern applications, resulting in a simpler, more consistent, and reliable disaster recovery solution.

DRAM (Disaster Recovery Application Model) is compatible with [OAM](https://github.com/oam-dev/spec) (Open Application Model). While OAM focuses on delivery, it can help DRAM define deployment programs quickly and easily for specific environments. This compatibility allows for a more streamlined and efficient approach to disaster recovery in cloud-native applications.

## Introduction
[todo] there would be an pic.

### Disaster Recovery Application Model Standardization:

1. Application-centric approach: Define the disaster recovery deployment with a self-contained model that focuses on the application rather than the container or orchestrator.
2. Clarity and extensibility: Develop an open standard to modularize disaster recovery delivery into reusable pieces and assemble them into a deployment plan using a consistent and higher-level API.
3. Vendor agnostic: Create an abstraction layer that enables simple and robust disaster recovery delivery across hybrid environments, including Kubernetes, cloud providers, and IoT devices.
4. Automated failover: Support automated failover to reduce downtime and ensure that applications can continue to operate in the event of a disaster.
### Advantages of the Disaster Recovery Application Model:

1. Simplified deployment: By focusing on the application rather than the underlying infrastructure, the disaster recovery deployment process can be simplified, reducing the need for developers to spend time on infrastructure details.
2. Reusability: A standardized approach to modularizing disaster recovery delivery into reusable pieces can make it easier to manage and update disaster recovery plans over time.
3. Vendor agnostic: By using an abstraction layer, the disaster recovery application model can be deployed across different environments, making it easier to switch between different vendors or solutions as the needs of the organization change over time.
4. Automated failover: With support for automated failover, organizations can reduce the risk of downtime and ensure that applications remain available in the event of a disaster, improving the overall resilience of the system.

## Why
The current challenge in disaster recovery is the high cost and limited effectiveness of unified solutions that attempt to backup all applications and data indiscriminately. This Application-centric approach reduces storage and bandwidth requirements, speeds up backup and recovery times, and enables finer-grained control over the recovery process, improving accuracy and reliability. And the most important, for application it's should not transparent.

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


