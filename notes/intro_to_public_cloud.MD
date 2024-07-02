## Introduction to Public Cloud Networking 
### A brief history:
- 1970: On-Premise networks was the traditional model of managing IT infrastructure and organizations. They involve hosting hardware, software, and networking equipment ON-SITE providing control and security over data. LAN were introduced, allowing computers within organizations to connect and share resources on-premises, such as printers and files
- 1980: Emergence of WAN enabling organizations to connect geographically dispersed locations. Tech such as leased lines and early IP facilicated communication between sites
- 1990: Internet connectivity became widespread and VPNs gained popularity for secure remote access and connecting branch offices. On-Premise infrastructure remained dominant
- 2000: Cloud networking began to gain traction as companies explored different avenues for managing digital infrastructure. Early cloud computing services like AWS offered organizations the ability to host applications and data remotely. Adoption was limited however cloud-based solutions were recongized for their scalability and cost-effectiveness compared to traditional on-premise setups.
- 2010: Significant turning point for Cloud Networking with introdutions of major platforms like Azure, GCP. These offerings expanded the capabilities of cloud computing, allowing organizations to migrate increasely complex workloads to the cloud. As cloud technology matured, it became a cornerstone of digital transformation initiatives across various industries. Today, public cloud services play a vital role in powering modern applications and driving innovation on a global scale.
### Identify the Characteristics of On-Premise Data Centers vs. Cloud
In this section, we will look in-depth at the characteristics of on-premises networks and examine how they differ from the cloud.
#### Location and Ownership
On-Premise:
- physically located within organization's premises, fully owned, operated, and maintained by the organization emcompassing all hardware, software, and networking equipment.
Cloud
- hosted in remote off-premise data cetners by 3rd party vendors, subscribed to by organizations on a pay-as-you-go basis elminating the need for owning and maintaining physical infrastructure.
#### Infrastrucutre Control 
On-Premise:
- maintain FULL CONTROL over infrastructure emcompassing servers, storage, networking devices and security systems allowing for customization and configuration tailored to their specific needs and preferences.
Cloud:
- cloud providers oversee and administer the underlying infrastructure encompassing servers, networking, storage, and virtualization technology while users, who have limited control over physical hardware, can configure and manage resources via web-based interface or API.
#### Expenditure
On-Premise:
- Capital Expenditure: on-premise data center demands SUBSTANTIAL INTIAL CAPITAL INVESTMENT covering hardware procurement, software licensing, cooling infrastructure, backup power systems, and ongoing facility maintenance.
Cloud: 
- Operational Expenditure: ORGANIZATION PAYS FOR CONSUMED RESOURCES ON A SUBSCRIPTION OR USAGE-BASED PRICING MODEL, covering costs of compute instances, storage, data transfer, and supplementary services like databases, AI, and analytics.
#### Scalability and Flexibility 
On-Premise:
- scalability is hindered by PHYSICAL LIMITATIONS. If additional resources are needed, they must be purchased then configured
Cloud: 
- virtually LIMITLESS SCALABILITY allowing to adjust resource levels in response to demand fluctuations based on user pre-defined rules or triggers
#### Security and Compliance
On-Premise:
- organizations directly OVERSEE the security measures and compliance standards with responsibilties such as implementing physical security protocols, firewalls, intrusion detection systems, encrpytion protocols for data protection.
Cloud:
- Cloud providers enforce stringent security measures and compliance standards to safeguard data and uphold regulatory requirements, incorporating features like encryption, identity and access management, network security, and compliance certifications such as SOC 2 and ISO 27001.
#### Maintenance and Support
On-Premise:
- Maintenance tasks, including hardware repairs, software updates, and system monitoring, are internally managed by IT staff or outsourced to third-party service providers, with organizations accountable for ensuring the uptime, reliability, and performance of the data center infrastructure.
Cloud:
- Cloud providers manage maintenance tasks such as hardware upgrades, software patches, and infrastructure monitoring, while service-level agreements (SLAs) ensure uptime, performance, and support, with round-the-clock technical assistance available for critical issues.

On-Premise: (NOT Abstract)
Definition: On-Premises (on-prem) data centers are physical infrastructures managed by an organization's IT team. They offer full control over data management processes and customization options.
Public Cloud: (Abstract)
Definition: A public cloud is a type of cloud computing in which resources, such as servers and storage, are hosted and managed by third-party providers.

### Private, Publics, and Hybrid Clouds
In this section, we will take a closer look at the differences between Private, Public, and Hybrid clouds.

Control Visibilty
        ^
        |
    On-Premise
    - On-prem infrastructure comprises computing resources within an organization, acting as a private data center. This setup provides full control over hardware and software, ensuring high security and customization. However, it requires significant capital expenditure and lacks the flexibility and scalability of cloud solutions. Upgrading and expanding these systems is time-consuming and resource-intensive, which can hinder rapid deployment and innovation.
    - Private Data Center
    - Very slow to respond to DevOps
        ^
        |
    Private Cloud
    - Private Cloud is Cloud Computing that meets the five characteristics defined by NIST. The typical private clouds are: AWS Outposts, Azure Stack and Google Anthos. You have the most control and visibility with a private cloud, but it may be the slowest in meeting application demands due to its reliance on infrastructure that can be slow to provision. An agile environment is essential for embracing DevOps. 
    - Single tenant Cloud Computing
    - Running on-prem infra
        ^
        |
    Hybrid Cloud
    - As the name suggests, a hybrid cloud allows the use of the same unified platform to interact with both private and public components.
    - Private and Public Cloud cooperating together 
        ^
        |
    Public Cloud
    - A public cloud is where multiple customers or tenants are hosted by a CSP, like Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform (GCP), Oracle Cloud Infrastructure (OCI), and Alibaba Cloud. Now, these customers or tenants share the same underlying hardware infrastructure in data centers that the CSPs own. Although there are some options to reserve hardware for dedicated instances,  it's mostly a shared infrastructure and a shared tenancy model.
    - Muliple Tenant
    - Hosted by Cloud Service Provider
    - Shared Infra
        ^
        |
Abstractions and Agility

### Cloud Services Foundational Models
#### Infrastructure as a Service (IaaS)
- Renting the building blocks of IT
- User configures infrastructure 
IaaS infrastructure as a service is where the CSP takes responsibility for the compute, storage, and networking service. The CSP abstracts the hypervisor and gives you access to the guest Virtual Machine (VM). You are responsible for the OS on that VM and all the libraries, middleware, and applications on that VM.
##### Use Cases:
IaaS is suitable for a wide range of use cases, including web hosting, application development and testing, data backup and disaster recovery, high-performance computing, and hosting of enterprise applications.
#### Platform as a Service (PaaS)
- Platform to implement code and deploying application, streamlines development process
- User implements code, infrastructure is already configured
PaaS platform is a service is where services are managed for you. You end up with a reduced level of control. For example, you can run a relational database service or platform without needing to install the underlying binaries or be responsible for hardening it or patching it or even ensuring it's uptime. You just need to bring your own code.
##### Use Cases:
PaaS is well-suited for a wide range of use cases, including web and mobile application development, API development, microservices architecture, IoT (Internet of Things) applications, and data analytics.
#### Software as a Service (SaaS)
- software is hosted by 3rd party provider, access software through web browser
- User uses software, code is already written and hosted on 3rd parties servers
SaaS software is a service for the pure consumption of a service. You have no control and, therefore, no responsibility for the application - for example, Microsoft 365 or Salesforce.
##### Use Cases:
SaaS is widely used across various industries and for different purposes. Common examples include email and productivity suites (e.g., Gmail, Microsoft Office 365), customer relationship management (CRM) software (e.g., Salesforce), collaboration tools (e.g., Slack, Microsoft Teams), and enterprise resource planning (ERP) systems (e.g., SAP Business One, Oracle NetSuite).

#### Public Cloud
One of the most fundamental concepts to grasp when talking about the public cloud is that, at the end of the day, it's just another Data Center. While it may seem abstract due to its virtual nature, the hardware infrastructure of Cloud Service Providers (CSPs) is subject to the same limitations and vulnerabilities encountered in traditional on-premise data centers.

However, the big difference here lies in the ownership and control of the hardware. In a public cloud environment, you're at the mercy of the CSP, and you have no direct control over the physical servers, storage devices, or networking equipment that your applications run on. This lack of direct control means that your organization relies heavily on the CSP's reliability, security measures, and compliance adherence. It also implies a shift in mindset from owning and managing hardware to managing service-level agreements (SLAs) and optimizing resource utilization in a shared environment.

##### Definitions
Private Clouds: Provisioned for exclusive use by a single organization. It should provide capabilities such as on-demand self-service, broad network access, resource pooling, rapid elasticity, and measured service. Managed internally or by a third party, or some combination of them, ideal for sensitive data handling. It may exist on or off premises.

Public Clouds: Operated by third-party providers, public clouds provide scalable and cost-effective cloud computing resources accessible over the internet.

Hybrid Clouds: These combine on-premises or private clouds with public clouds, enabling fluid data and application movement between environments. They maintain data control and security while offering scalability.

On-prem Infrastructure: Consists of physical and virtual resources within an organization’s own facilities, providing high security and control but requiring significant investment and ongoing maintenance.