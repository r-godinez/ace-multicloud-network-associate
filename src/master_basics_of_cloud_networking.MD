# Master the Basics of Cloud Networking 
- *MY NOTES*

~ *NOTES FROM SLIDES*

## Learn the Basic Networking Capabilities of the Primary CSPs
- Summary: Recognize the basic native networking capabilities of the primary CSP (AWS, MS Azure, GCP, and OCI)

~ By the end of this training, you should be able to recognize the basic native networking capabilities of the primary cloud service providers (Amazon Web Services, Microsoft Azure, Google Cloud Platform and Oracle Cloud Infrastructure).

### Recap
**Cloud Service Provider (CSP)**: 3rd party company offering cloud-based platform infrastructure, application, or storage services.

**Infrastructure**: Compute, Storage, Network

### Exploring CSP Essential Services
- CSP offer a variety of infrastructure services such as compute, storage, and networking. 

~ Cloud service providers (CSPs) offer various services encompassing various aspects of cloud computing. Leveraging their extensive data centers and robust compute resources, CSPs deploy, manage, and scale digital infrastructure and platform services for diverse customer organizations. Below are some common services provided by CSPs

#### Identity and Access Management (IAM)
- who can do what to which resource

~ A logically isolated portion of a cloud provider's infrastructure that mimics the capabilities of a traditional physical data center but is entirely virtualized and managed through software. It encompasses a combination of compute, storage, networking, and other resources needed to support the operations and applications of an organization.

#### Core Services
- Compute, Storage, Network, Database

~ Core services are fundamental computing resources provided by cloud service providers. The services include compute, storage, network, and database.

#### Resources
- Specific instances that you can create

~ In the context of cloud computing, resources refer to various components or entities that users can provision and utilize within the cloud environment to build and run their applications. These resources can include virtual machines, databases, networking components, containers, load balancers, and more.

#### Virtual Data Center
- Collection of resources you can create within a geography

~ A logically isolated portion of a cloud provider's infrastructure that mimics the capabilities of a traditional physical data center but is entirely virtualized and managed through software. It encompasses a combination of compute, storage, networking, and other resources needed to support the operations and applications of an organization.

#### Dedicated Connectivity
- Private path connectivity from on-prem to CSP region

~ Services enable organizations to establish private, high-performance network connections between their on-premises infrastructure and the cloud provider's data centers. This typically involves options like dedicated leased lines, virtual private networks (VPNs), or direct connections such as AWS Direct Connect or Azure ExpressRoute. Dedicated connectivity offers advantages such as improved network performance, reliability, security, and lower latency than public internet connections for accessing cloud resources.

### The Primary CSP Leaders
- We will explore the primary CSP
- CSP offer services on an **on-demand**, **self-provisioning basis** allowing customers to subscribe and pay on monthly or quarterly billing structures. Some providers tailor their services to specific industries

~ Cloud service providers typically offer their services on an on-demand, self-provisioning basis, allowing customers to subscribe and pay for them through monthly or quarterly billing structures. Some providers set themselves apart by tailoring their services to specific industries, delivering functionality and tools tailored to their needs. For example, healthcare cloud products cater to healthcare providers' requirements for storing, optimizing, and securing personal health information.

#### Amazon Web Service (AWS)
***Key Point***
- One of the largest cloud providers with over 200 services.
- SLAs are provided for individual services.
- 33 regions and 105 availability zones worldwide. (One of the most important considerations when evaluating a cloud provider is the number of global regions and availability zones offered.)
- Offers SDKs, web portal, and AWS CLI for management.
- ~30% of market

~ AWS stands as one of the largest cloud providers, boasting a catalog of over 200 services. Instead of offering a standardized uptime commitment across its entire cloud, Amazon provides service-level agreements (SLAs) for individual services.

~ With 33 global regions and 105 availability zones (*as of 2024, refer to the CSP for current number) the breadth of AWS's infrastructure is noteworthy. AWS offers software development kits (SDKs) for developers to seamlessly interact with cloud resources, along with both web portals and command-line interfaces (CLIs) for administrative tasks.

#### Microsoft Azure
***Key Point***
- Second-largest cloud provider.
- SLAs are provided for individual services.
- 60+ regions with multiple availability zones.
- User-friendly Azure portal, Azure CLI, and Azure PowerShell.
- ~24% of market

~ Like AWS, Azure maintains separate SLAs for its services, guaranteeing uptime levels depending on configurations. With 60-plus regions and multiple availability zones, Microsoft's global presence is robust. Its user-friendly portal simplifies resource management, and Azure CLI and Azure PowerShell complement it for administrative tasks.

~ Moreover, Azure's integration with other Microsoft products and services, such as Windows Server, Active Directory, and Office 365, offers seamless compatibility and interoperability for enterprises already invested in the Microsoft ecosystem. This integration facilitates hybrid cloud deployments and enables organizations to leverage existing tools and skills in their cloud journey.

#### Google
***Key Point***
- Third-largest cloud platform.
- SLAs are provided for individual services.
- 40 regions and over 120 availability zones.
- Offers gcloud CLI, supports Linux-style commands, and is available for multiple operating systems.
- ~11% of market

~ Google aligns SLAs with specific services, ensuring uptime commitments based on service tiers. Its extensive network spans 40 regions and over 120 availability zones, particularly strong in regions like North America. Google provides the Google Cloud Command Line Interface (gcloud CLI) for managing resources, which is available across multiple operating systems, including Linux, macOS, and Windows. 

~ Google Cloud's expertise in areas such as artificial intelligence (AI), machine learning (ML), data analytics, and Kubernetes orchestration further enhances its position in the cloud networking industry. Customers can leverage Google Cloud's advanced technologies to build innovative solutions, analyze large datasets, and deploy containerized applications at scale.

## Recognize Common Cloud Service Provider Use Cases
In this section, we will explore scenarios in which the primary cloud service providers (CSPs) are commonly used.

- In some cases, One CSP is better than another. Ex: if you're using Microsoft services like AD SQL, then Azure would be best.

### Common Scenarios for CSP Selection

#### AWS
- mature ecosystem
- broad service portfolio
- Offers a wide range of cloud services, including hosting internal applications, managing large databases, implementing machine learning algorithms, and deploying IoT solutions.

~ Enterprise Solution: An established enterprise with a diverse range of IT needs might choose AWS due to its mature ecosystem and broad service portfolio. Whether it's hosting internal applications, managing large databases, implementing machine learning algorithms, or deploying IoT solutions, AWS offers a comprehensive suite of services to address these requirements.

#### Azure
- significant investments in Microsoft technologies
- operating in highly regulated industries like finance or healthcare
- Emphasizes seamless integration with technologies such as Windows Server, Active Directory and SQL Server

~ Hybrid Cloud Deployment: A company with a significant investment in Microsoft technologies, such as Windows Server, Active Directory, and SQL Server, might opt for Azure for its seamless integration with the Microsoft ecosystem. Azure's hybrid cloud solutions would allow them to extend their on-premises infrastructure to the cloud while maintaining compatibility and familiarity with existing tools and systems.

~ Regulated Industries: Organizations operating in highly regulated industries like finance or healthcare may choose Azure for its strong emphasis on security and compliance. Azure's compliance certifications and security features make it a suitable platform for handling sensitive data and meeting regulatory requirements.

#### GCP
- data-driven company looking to derive insights from large datasets
- enterprises adopting containerization and microservices architecture 
- Specializes in data management and analytics, offering services like BigQuery for data warehousing and analysis, as well as machine learning tools like TensorFlow

~ Big Data and Analytics: A data-driven company looking to derive insights from large datasets might leverage GCP's expertise in data management and analytics. Google Cloud Platform offers services like BigQuery for data warehousing and analysis, as well as machine learning tools like TensorFlow for building predictive models.

~ Containerized Applications: Enterprises adopting containerization and microservices architectures could benefit from GCP's proficiency in Kubernetes and container orchestration. GCP's Kubernetes Engine provides a managed platform for deploying, managing, and scaling containerized applications, appealing to organizations seeking agility and scalability.

#### OCI
- Industries requiring intensive computational tasks like scientific research, engineering simulations, and financial modeling
- Enterprises already using Oracle products like databases and software
- A database service that appeals to industries requiring intensive computational tasksd

~ For businesses already using Oracle products like databases and software, OCI offers a natural and potentially cost-effective way to migrate workloads to the cloud while maintaining compatibility. This caters to industries requiring intensive computational tasks such as scientific research, engineering simulations, and financial modeling.

#### Alibaba Cloud
- expand operations into the Chinese market by providing cloud services tailored for local requirements, regulations, and business practices.

~ Market Expansion in China: Alibaba Cloud enables businesses to expand their operations into the Chinese market by providing cloud services tailored for local requirements, regulations, and business practices.
