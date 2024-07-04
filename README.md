# CLOUD COMPUTING

## Outcomes
* Analyze the different cloud models to design the best solution to support business requirements.
* Manage and maintain servers, including OS configurations, access control and virtualization.
* Analyze system requirements to successfully execute workload migrations to the cloud.
* Maintain and optimize cloud environments, including proper automation and orchestration procedures, backup and restore operations, and disaster recovery tasks.
* Troubleshoot capacity, automation, connectivity and security issues related to cloud implementations

## Module 1: CLOUD COMPUTING FUNDAMENTALS
*  The cloud is changing how organizations are planning to deliver services to their customers, suppliers, and partners. They're using cloud services to increase the pace of business and to offer new and innovative services.

### What is the cloud?
* the impact of cloud has revolutionized the way organizations operate ,offering essential features like on-demand access to computing **power and storage** ,virtually unlimited scalability and flexible pricing models.
* Adoption of cloud technologies is focused primarile on cost reduction and shifting technology expenditures from  capital to operational expenses.
* As a result, most organizations have embraced a pragmatic hybrid cloud strategy, utilizing a combination of public and private cloud services based on their specific business needs
* They retain critical applications within their data centers while leveraging innovative Software as a Service (SaaS) applications and cloud infrastructure services.

## 5 CHARACTERISTICS Defined by NATIONAL INSTITUTE OF STANDARDS AND TECHNOLOGY (NIST):

**On-Demand Self-Service**
* Consumers can provision resources as needed and automatically.Cloud services consumers can provision services on an as-needed basis, without the need to work with the CSP (Cloud service provider) directly.These resources might include additional computer power ,additional storage,new websites or even database services

**Broad Network Access**
* client devices and traditionalmserver deployments are able to access cloud-based resources across the network.
* Network might include the local on premises network or the internet or it might include both.
* Cloud resources have the potential to be globally accessible

**Resource Pooling**
* The cloud service provider(CSP) pools resources in a multitenant mmodel and adjust resource allocation on an on demand basis.the specific distribution of hardware resources id abstracted from the consumer.
* CSPs pool network,storage and compute capabilities and then dynamically and automatically allocate those resources might physically be located.
* So in most cases the next time those services are used  by consumers the resources locations might have changed.
* CSP manages the resources and maximizes their use.

**Rapid Elasticity**
* Resources are provisioned and released to adjust for change in demandand consumption, in this case the process may be automatic or manual.
* Server resources in a traditional model are purchased as a capital expenditure and whether or not those resources are efficiently utilized,their cost and their capabililites are fixed.
* With cloud-based computing ,resources are dynamically allocated ,making for far more efficient utlization of those resources.
* So servers that might have been underutlized for most of the year no longer need to be purchased and maintained.

**Measured Service**
* Metering of resources is monitored ,controlled and billable.CSPs meter the utlization of their resources .
* Having metering permits more efficient and dyanmic resource allocation.
* it also permits the CSPs to bill consumers accurately for exaclty the quantity of resources consumed

## Cloud Computing Ecosystems
the ecosystem consists of three categories of players

### Consumers of Services
   - These are everyday end users like myself that use cloud services in their day-to-day business activities
    **Examples**
     * **Microsoft OneDrive**: OneDrive is a file hosting and synchronization services that is offered by Microsoft,it enables users to store and share files and access them from any device,this includes PCs ,Macs and mobile devices
     * **Google Drive**: Google Drive is a cloud storage and file backup provider offered by google,it offers free storage for personal use and allows users to store files,collaborate on documents and share files witth others.
     * **Icloud**: Icloud is a cloud storage and synchronization that is provided by Apple.It allows users  to store their photos,videos ,documents and other files that one can access from all Apple devices.
  
### Provider of Services

These cloud providers offer a variety of functions ranging from infrastructure services to different applications and tools
**Examples of Prominent Providers**

* **Amazon Web Servies (AWS)**: it is a comprehensive cloud computing platform provided by Amazon.It offers a wide array of services,including **computing power**,**storage** ,**databases**,**networking**,**analytics**,**machine learning**.
*  **Microsoft Azure**: is a cloud computing platform that is offered by Microsofyt ,it provides a range of services for building ,deploying and managing applications and services through Microsofy managed data centers.
*  **Google Cloud Platform(GCP)**: GCP is a suite of cloud computing computing services offered by Google.It provide infrastructure,storage ,AI,Machine learning ,data analytics ,and other services to help business scale and innovate
* **IBM Cloud**: IBM cloud is a collection of cloud comptuing services provided by IBM,it offers infrastructure,platform ,and software as a servic(IaaS,PaaS and SaaS) solutions,along with tools for data analytics ,AI,and blockchain
* **Oracle Cloud infrastructure**: Oracle cloud infrastructure is and Iaas platfrom which is offered by Oracle.It provides a broad range of cloud services such as **Compute**, **storage** , **networking** , **database** , and applications with focus on enerprise workloads.
* **Alibaba Cloud**: Alibaba Cloud is the cloud computing arm of alibaba Group,a Chinese multinational conglomerate.It offers a wide range of cloud services ,including computing ,storage ,networking ,database ,Ai and security , it has a strong presence in Asia-Pacific Region

### Designer of Services

The following companies build applications and tools ,and often heir services are intended to work within a specific cloud ecosystem or a particular augment of a package cloud application

1. **Accenture**=global professional services company that offers cloud consulting and implementation services. They help businesses **design** and **deploy cloud solutions**, leveraging their expertise in cloud architecture, migration, and management.
2. **Deloitte**:multinational professional services firm that provides **cloud technology consulting** and **implementation services**,assist organizations in developing **cloud strategies**, **designing architectures**, and **implementing cloud** solutions across various industries.
3. **CapGemini**: Capgemini is a global consulting and technology services company that offers **cloud transformation services**.They help businesses design and implement cloud architectures, optimize cloud environments, and enable digital transformation through cloud technologies.
4. **IBM**:leading technology company that provides **cloud consulting and design services**. They assist organizations in designing hybrid cloud architectures, implementing **cloud-based applications**, and leveraging emerging technologies like AI and blockchain.
5. PricewaterhouseCoopers (PWC):multinational professional services firm that offers cloud technology consulting services.  They help businesses **design and implement cloud strategies**, **optimize cloud operations**, and **ensure compliance and security in cloud environments**.
6. **Cognizant** : IT services and consulting company that provides **cloud technology services**. They help organizations **design and implement cloud-based solutions**, **migrate applications to the cloud**, and **optimize cloud infrastructure**.
7. **Wipro**:global IT consulting and services company that offers **cloud consulting** and **implementation services**.
   They assist businesses in **designing cloud strategies**, **developing cloud-native applications**, and **ensuring seamless cloud integration**
8. **Tata Consultancy Services (TCS)**:IT services and consulting company that provides **cloud technology solutions**.They assist organizations in **cloud strategy development**, **cloud architecture design**, and **implementing cloud-based applications **and services.
9. **Infosys**: global consulting and IT services company that offers **cloud consulting** and **implementation services.** ,They help businesses design and **implement cloud solutions**, **migrate applications to the cloud, and optimize cloud infrastructure for improved performance.
10. **DXC Technology** : IT services company that provides **cloud consulting** and **implementation services**. They assist organizations in **designing cloud architectures**, **migrating applications to the cloud,and managing cloud environments**.

---
---

* ``Cloud computing`` is a method of providing shared computing resources ,including applications,computing ,storage ,networking ,development ,and deployment platforms as well as business processes.Cloud computing makes computing resources easier to use by providing standardization and also automation

* ``Standardization`` is the implementation of services by using a consistent approach supported by a set of consistent interfaces >Likewisethe cloud generally requires that processes be implemented through the use of automation.

* ``Automation``: Procss that is triggered based on business rules , Resource availability ,and security demands .Automation is required to support a self-service provisioning model . this is done to promote efficiency ,automation can ensure that after a provisioned service is no longer needed it can be returned to a resource pool.This type of rules-based automation can help with capacity planning and overall workload management.

* Many companies are discovering that having **Customer Relationship Management (CRM)** available as a service is a better way to support the sales team than the traditional on-premises software options.

### Understanding Cloud Deployment Models

**Cloud Components and Clients**
Three main components in a cloud service solution.

1. Client platform from which the cloud services are being accessed.
2. Second is the data center where the cloud services are being hosted.
3. Final component is the network connection between those two points.

<img width="599" alt="Screenshot 2024-07-04 at 13 51 03" src="https://github.com/BafanaMadume/cloud-computing/assets/141032267/295ffab1-7a6e-4f21-b85e-48734c29d571">

<img width="680" alt="Screenshot 2024-07-04 at 13 52 01" src="https://github.com/BafanaMadume/cloud-computing/assets/141032267/23c4fcca-94d5-4850-bc61-4baf19b57d75">

* Leading **cloud service providers (CSPs)**, like Microsoft and Amazon, operate a vast network of data centers worldwide
*  data centers are designed with redundancy, ensuring reliable power supply, internet connectivity, and physical security.
*  Cloud services cater to a wide range of consumers, encompassing individuals and businesses alike, on various platforms. These services can include **storage**, **email**, **e-commerce**, **office suites**, and **development environments**,
* The primary operating systems used on these client devices include Microsoft Windows, Apple macOS, Linux, iOS, and Android.
* The cloud service infrastructure can be managed internally by a single organization for its own use or managed by a CSP that provides services to many organizations. These two models can be combined into a hybrid solution.
* The network serves as the pathway connecting the client devices to the data centers of the CSPs
* Depending on the deployment model, the network connection can be owned and operated entirely by your company, providing a private and dedicated connection
* Alternatively, access to cloud services can be facilitated through the internet, utilizing the public network infrastructure.

* **Public cloud**:A CSP owns the cloud deployment and allocates its resources to external, unaffiliated customers.Those customers share the public cloud’s resources without knowing precisely where their data is in relation to that of any other organization
* **Private cloud:** Services are provided to only a single organization
* **Hybrid Cloud**: There is a combination of two or more private, public, or community deployments

<img width="536" alt="Screenshot 2024-07-04 at 14 21 14" src="https://github.com/BafanaMadume/cloud-computing/assets/141032267/510a24af-1892-421f-884b-c28e236109a6">

#### THE PUBLIC CLOUD
* public cloud is a set of hardware, networking, storage, services, applications, and interfaces owned and operated by a third party for use by other companies or individuals.
*  CSPs offer public cloud services to virtually any customer. Customers use a subscription model to pay for access.
*  . Public clouds are viable because they offer many options for computing, storage, and a rich set of other services.
*  With many resources always available, public cloud consumers can quickly select, optimize, and use those resources that match the needs of the applications they will run in the public cloud.
*  Most public cloud providers offer a wide variety of APIs and services, such as security, and specialized infrastructure to support specific workloads like Graphic Processor Units (GPUs) for data science, application development pipelines, and other technologies to support customer needs.
*  Less cost-effective than multi-tenant approach
*  it is also on demand Availability
![image](https://github.com/BafanaMadume/cloud-computing/assets/141032267/3dbb23d2-dbe6-4345-a7b2-5a91a9a866db)

#### THE PRIVATE CLOUD
* Owned and operated by an organization for its internal use (employees, partners, customers)
* Can be managed by a 3rd party but exclusive to one company
* Organization has full control over the deployment
* Highly controlled environment, not publicly accessible (behind a firewall)
* Focus on governance, security, and compliance
* Appliance provides access to the vendor's public cloud services
* Necessary for organizations with strict security requirements or compliance regulations 

![image](https://github.com/BafanaMadume/cloud-computing/assets/141032267/ede628f9-528a-4af5-bb37-94c15f263b4f)


#### THE HYBRID AND MULTICLOUD MODEL


**Hybrid Cloud**

* Combines private cloud with public cloud services
* Goal: unified, automated, and well-managed computing environment
* Users shouldn't differentiate between on-premises and cloud services

**Multicloud**

* Two or more public clouds used within an organization
* Often arises from independent decisions by different teams
* Requires multicloud management for visibility, control, and choice

**Important Distinction**

* Not all public+private cloud use is hybrid/multicloud
* Hybrid/Multicloud creates value by using multiple services together

**Not Hybrid/Multicloud**

* Isolated public cloud use for development (no connection to private/data center)
* Standalone SaaS application with no data exchange
* Separate public cloud deployments for different departments

**Hybrid/Multicloud Examples**

* Public development platform sending data to private cloud/data center
* Leveraging multiple SaaS applications with data movement
* Business process designed as a service across environments
* Using a SaaS analytics platform with data from multiple clouds
* Moving workloads between public clouds based on cost/performance

<img width="599" alt="Screenshot 2024-07-04 at 14 55 15" src="https://github.com/BafanaMadume/cloud-computing/assets/141032267/3fc82d9b-530e-4ff2-bd64-7d17407ff4d1">

#### CLOUD WITHIN A CLOUD (Virtual Private Cloud)
* virtual private cloud (VPC), the concept of cloud within a cloud means a public CSP hosts your organization’s cloud services in an isolated segment, separated from any resources shared with other companies.
* Virtual private clouds are an example of single-tenant deployments. Sometimes there is confusion regarding the difference between VPC and private cloud deployments. Here are some key differences:

* VPC–logical isolation of the cloud deployment that resides on a CSP's infrastructure (and is therefore scalable).
* Private cloud–physical isolation of the cloud deployment in a private data center, a community data center, or CSP's infrastructure. It is limited by the available hardware and therefore less scalable.

#### Multinenancy 
This is the concept behind public cloud deployments. Multiple consumers, known as tenants, share computing resources owned and managed by the CSP. This is the opposite idea from a VPC deployment. It is multitenancy that provides the cost benefits behind shared resource utilization

#### Multi-cloud
 many multi-cloud variations, but some of the most common are combinations of cloud services spread among two or more public CSPs (such as AWS and Azure) as well as on a private cloud infrastructure. Multi-cloud deployments reduce reliance on a single vendor, provide greater service flexibility and choice, permit improved geographic control of data, and help manage disaster mitigation.

![image](https://github.com/BafanaMadume/cloud-computing/assets/141032267/8fe08da6-b092-44c6-8534-ea4c5965ac7b)

#### CLOUD COMPUTING ELEMENTS: RESOURCE POOLS/Cloud Models and Services

![image](https://github.com/BafanaMadume/cloud-computing/assets/141032267/d37c856f-d282-4ad1-b9a8-007e9ed5414b)
