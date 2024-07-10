# ACE Associate Exam Review
## About Aviatrix
Aviatrix software provides a platform for companies to build networking and security infrastructure in the public cloud. The platform provides architecture applicable to both single and multiple public cloud deployments. Currently, the software supports public clouds such as AWS, Azure, GCP, and OCI.
- pioneer of Multi-Cloud Network Architecture (MCNA)

MCNA is unlike any other architecture because it embraces, controls, and manages not only the native cloud constructs but also provides advanced services beyond what the Cloud Services Providers (AWS, Azure, GCP, OCI and Alibaba Cloud) can provide. It provides a consistent and repeatable architecture across multiple clouds, being the first in the industry to do so, making it an essential part of the present and future of the public cloud.


## Public Networking

## Amazon AWS Networking Introduction

## Microsoft Azure Networking Introduction

## Google GCP Networking Introduction

## Oracle OCI Networking Introduction

## Alibaba Cloud Networking Introduction

## Multi-Cloud Network Architecture
Aviatrix creates a purpose-built Multi-Cloud Network Architecture (MCNA) by implementing a data plane through dynamic and software-defined routing with a centralized control plane. Security is built into the network architecture through segmentation, encryption, ingress and egress filtering, and security services insertion. Aviatrix also leverages orchestrating cloud-native constructs, where necessary, in building and controlling the enterprise network and life-cycle management of the overall architecture. 

The architecture is valid for single-cloud-single-region, single-cloud-multiple-regions, or multiple-clouds-multiple-regions and can be easily referenced by both green and brownfield businesses with no issues. This is a common and repeatable architecture across multiple clouds, which creates simplicity and abstraction for the users by hiding all the underlying complexities and limitations of Cloud Service Providers. Because this architecture functions as a reference, it is vendor-agnostic. 

![alt text](diagrams/mcna_1.png)

MCNA architecture defines four distinct layers at a high level. These are Cloud Core, Cloud Security, Cloud Access, and Cloud Operations.

![alt text](diagrams/mcna_2.png)

***Cloud Core:***
The cloud core of the multi-cloud network architecture goes beyond simple connectivity. It scales and supports the rapid evolution of applications and businesses. It also delivers a common data plane by supporting native cloud constructs, APIs, and adds advanced capabilities to form a common data plane with the visibility and control required to optimize the multi-cloud network. Within the cloud core, there are two subdivisions: The applications layer and the global transit layer.

***The Applications Layer:***
This is where the applications are. These applications could be sitting in VPC/VNET and running as instances or VMs. The Aviatrix controller embraces the native constructs of the cloud from this layer. This is the area where applications are deployed using their respective operating systems. 
 
***The Global Transit Layer***:
Aviatrix software enables enterprise IT to easily deploy a high-availability, multi-cloud network data plane with end-to-end encryption, high-performance encryption, multi-cloud security domains, and operational telemetry operations teams need. This is the main point of connection for every aspect of the cloud. This global transit layer also has the notion of inserting services in its platform, which is done through the service insertion framework.  
 
***Cloud Security***:
Cloud security is a crucial part of the MCN architecture. This layer encompasses all the other layers of the cloud. It ensures that all the areas in the cloud, such as the applications, transit, and access layer are secure. The MCNA model enforces cloud security in many aspects, such as when connecting cloud to on-premise, ingress, egress, and security within the cloud security with encryption and security segmentation. 
 
***Cloud Access***:
The multi-cloud access layer is a crucial layer of the multi-cloud network when interconnecting to on-premise resources. This layer ensures that the cloud is securely accessible by all the components of a business. This architecture sets the multi-cloud foundation by securely bringing employees, partners, customers, branch offices, and legacy data centers into the cloud as one cohesive unit.
 
***Cloud Operations***:
This layer provides full visibility for all aspects of the cloud, meaning that it encompasses each layer. It is a centralized operations plane. This is also the layer of the cloud that encompasses the most crucial tools, such as troubleshooting, visibility, and automation. 

![alt text](diagrams/mcna_3.png)

MCNA showcases a centralized controller to manage single or multiple clouds with a global, distributed, unified and normalized data plane. 






## Aviatrix Platform Features
### Platform
***A Centralized Controller***: Aviatrix offers a centralized controller to make complex networking easy and does not require any background knowledge of networking command-line interfaces.

This controller is also the entry-point for multi-cloud automation, which can be done using Application Programming Interface or Terraform.

It is a browser-based, point-and-click management console that orchestrates both native (AWS, Azure, GCP, and OCI) constructs and advanced services from Aviatrix. This centralized controller also deploys Aviatrix Gateway instances for multi-cloud, on-premise, and edge connectivity.
 
***A Distributed and Common Data-Plane***: The Aviatrix platform embraces native cloud constructs and extends the functionality using advanced networking and security, which are both provided by Aviatrix Controller and Gateways.

The Aviatrix gateways can be considered as service nodes, providing a robust and common data-plane within a Cloud or across multiple Clouds.

As part of the data-plane, these gateways work to provide services such as transit routing, high-performance encryption, egress and ingress control, edge connectivity, on-premise connectivity, and user-VPN services.

 
***Operational Visibility***: CoPilot, one of Aviatrix's many services, allows users to have full operational visibility in their network, all while informing them of any issues in their cloud network.
 
***Multiple Accounts and Clouds***: Aviatrix is also able to integrate multiple accounts and clouds seamlessly and on one single interface. This allows customers to interconnect AWS, Azure, and Google Cloud with the same point and click flow.
 
***Security & Compliance***: To help its service run smoothly, Aviatrix provides many security and compliance measures. It allows users to manage security domains, such as the Development domain and the Production domain, and also allows for Virtual Private Cloud connectivity through Connection Policies. Users are able to easily apply firewall filters based on tags or specific address ranges, CIDR, protocols, and ports.

Aviatrix services are also integrated with AWS GuardDuty to block malicious activity automatically at the Virtual Private Cloud network level.

### Overview

### Cloud Security

### Cloud Access

## Operations, Visibility, and Troubleshooting











## Technology Partner Integrations

### Cloud Partners
·        Amazon Web Services
·        Microsoft Azure
·        Google Cloud Platform
·        Oracle Cloud Infrastructure
·        Hashicorp

### Technology Integration Partners
·        Splunk
·        Palo Alto Networks
·        Terraform by HashiCorp
·        Check Point
·        Okta
·        Megaport
·        DataDog
·        Centrify
·        Duo Security
·        Ansible
·        SignalFx
·        Fortinet