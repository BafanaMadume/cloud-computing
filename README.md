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

## CLOUD DELIVERY MODELS
* **Infrastructure as a Service (Iaas):** The hardware infrastructure is provided to the consumer,The consumer assumes responsibility for all layers above that hardware.. The CSP manages hardware failures, firmware updates, device drivers, and hardware compatibility. **consumer installs** and **manages the operating system on top of the hardware as well as any services and applications that run above that operating system**
* **Platform as a Service (PaaS):** The service structure is provided by the CSP It is up to the consumer to populate that structure, manage it on a day-to-day basis, and assume responsibility for the content. Support for the hardware, as well as the service platform that hosts the content, is offloaded to the CSP.
* **Software as a Service (SaaS):**  consumer is being provided with the direct use of the software. Responsibility for the hardware where that software runs the operating system upon which it runs, and the installation and patching of the software itself are all offloaded to the CSP.

#### INFRAsTRUCTURE AS A SERVICE(IaaS)

* IaaS provides virtual servers with operating systems, storage, and networking on demand, similar to a physical server but more flexible.
*  The easiest way to think of IaaS is that it provides a virtual server that is equivalent to a physical server — you have to select an operating system (for example, Linux, Windows, and so on), and everything “up the stack” to the applications that will run.
* IaaS provides virtual servers with operating systems, storage, and networking on demand, similar to a physical server but more flexible.
* There are two main types:
    * **Public IaaS**: Offered by cloud providers like Amazon Web Services (AWS) or Microsoft Azure. Pay-as-you-go model, easy to access with a credit card.
    * **Private IaaS**: Built by an organization's IT department for internal use or partners. Access is controlled by company policies and may involve users bringing their own tools.
 
**Iaas Examples**
* **AWS EC2**
* **Microsoft Azure**
* **Rackspace**
* **Digital Ocean**

**TARGET AUDIENCE**
* IT administrators
![Screenshot 2024-07-05 093910](https://github.com/BafanaMadume/cloud-computing/assets/141032267/ec73b160-b3f3-4eec-b207-6e475cdc3c9f)

#### PLATFORM AS A SERVICE(PaaS)

* PaaS builds upon IaaS by adding a layer of development tools and middleware on top.
* This allows organizations to focus on application development without worrying about infrastructure setup or operating systems.
* Think of it as a ready-made development environment on the cloud or within your own network.
* PaaS can be used for general development or specific platforms like Salesforce, which allows creation of industry-tailored CRM applications.
* Overall, PaaS increases development speed and efficiency
* A PaaS offers a consistent set of programming and middleware services that ensure developers have a well-tested and well-integrated way to create applications in a cloud environment.
*  A PaaS environment brings development and deployment together to create a more manageable way to build and deploy applications.

 **PaaS Examples**
 
*  **Google App Engine**
*  **Heroku**
*  **AWS ElasticBeanstalk**
*  **Salesforce**

**Target Audience**

* Developers
* DBAs

![Screenshot 2024-07-05 095928](https://github.com/BafanaMadume/cloud-computing/assets/141032267/48621735-7383-44d4-922d-48068349352d)

#### SOFTWARE AS A SERVICE(SaaS)
* SaaS provides complete, ready-to-use business applications over the internet.
* These applications are hosted by the provider (like Google or Salesforce) and accessible through a web browser.
* Multiple users from different companies can access the same application (multi-tenant model).
* Customers pay a subscription fee, typically per user, and don't need to worry about maintaining underlying infrastructure or platforms.
* Their main concern is the application's functionality, performance, security, and how well it meets their needs

  **SaaS Examples**
  * Microsoft Office 365
  * Google Apps
  * WebEx
  * Dropbox
  * Netflix
 
**Target Audience**
* End-users

![Screenshot 2024-07-05 100649](https://github.com/BafanaMadume/cloud-computing/assets/141032267/556be05b-4a0a-4d34-9542-95c11d9572d3)
---

## THE COMPUTING RESOURCES LIFE CYCLE
* A basic concept of both public and private cloud computing is that users only employ computing resources when needed and pay only for the resources they actually utilize during the time they use them.
* **Pay-as-you-go model:** Cloud users only pay for the resources they use, unlike traditional data centers where resources are purchased upfront.
* **Scalability:** Cloud providers need to have extra resources available to handle unpredictable user demands. 
* **Resource metering:** Cloud providers closely monitor resource usage to accurately bill users.
* **Dynamic allocation:** When a user finishes using a resource, it's returned to the pool for others to use.
* **Elasticity:** Cloud providers can use additional services from other providers to meet unexpected demands, without impacting the user experience.

### UNDERSTANDING SELF-SERVICE PROVISIONING AND ELASTICITY

**SELF-SERVICE PROVISIONING**
* Cloud users can directly order, configure, and launch cloud services through a web interface, in minutes or even seconds
* This eliminates the traditional data center approach where IT departments handle requests, leading to delays and hindering development.

**Benefits of Self-service Provisioning**
* Faster application development and deployment.
* Quicker time to market for new products and services.
* Reduced costs by eliminating manual IT involvement.

**Elasticity:**
* Cloud resources can automatically adjust their capacity based on usage.
* This ensures resources are available when needed (scaling up) and avoids unnecessary costs when not in use (scaling down).

Benefits of Elasticity:
* Improved application performance by having resources readily available
* Cost efficiency by paying only for what you actually use.

* Together, self-service provisioning and elasticity empower cloud users to be more agile and cost-effective.

### ESTABLISHING A DYNAMIC LIFE CYCLE ACROSS WORKLOADS AND DATA

**Cloud as federated environment**
* The cloud consists of various resources spread across locations.
* These resources work together to deliver services.
* Workloads (independent services) need to be organized for efficient management.

**Workload placement**
* Workloads should be placed in the appropriate cloud environment (public, private) based on their needs.
* Legacy systems might require a private cloud for faster transactions.

**MULTI-Cloud strategy**
* Organizations should consider using multiple cloud providers for optimal benefits.
* This allows workloads and data to move seamlessly across different providers and regions.

**Workload considerations for a dynamic life cycle**

* Location: Place workloads near customers for better performance.
* Scalability: Adapt workloads based on changing demand (up or down).
* Cost and features: Move workloads between providers for better cost, reliability, or features.

  #### Management Services
* **Importance:** Management services are essential for ensuring your cloud applications function well and meet user needs (customers, employees, partners). This applies to any cloud deployment model (public, private, hybrid).
* **Core services:**
    * Network monitoring: Identifies and addresses network issues that can disrupt user experience.
    * Application/workload health monitoring: Detects potential problems in applications and helps support teams deliver better service.
    * Security and governance: Protects applications, data, and ensures compliance with regulations.
    * Data management: Facilitates data movement between cloud and physical environments in hybrid models.
* **Integration services:** Manage connections between different cloud environments (hybrid and multi-cloud) for seamless operation.

## The Changing Role of the DATA Center
**The data center's role in a hybrid cloud:**

* Data centers aren't going away. They house critical systems and legacy applications that aren't suited for the cloud.
* Virtualization helps streamline data center management by decoupling software from hardware.

**Security considerations:**

* Modern cloud security is robust, but some data requires stricter physical security due to regulations or sovereignty concerns.

**Private cloud: A stepping stone for agility**

* Companies create private clouds to offer self-service app development environments with faster provisioning and automation.
* This fosters experimentation and faster time-to-market for new applications.

**Public cloud for scalability and global reach**

* Public clouds offer elastic resources to handle surges in demand, like Mr. Price's seasonal sale.
* They also enable easy replication of applications across regions for global businesses.

**Hybrid cloud: Combining public and private clouds**

* Businesses can leverage SaaS applications in the public cloud while keeping sensitive data private in their data center.
* Integration tools enable data flow between these environments.

**Choosing between private and public cloud**

* Private cloud is better for storing sensitive data subject to regulations or for applications that aren't cloud-ready.
* Public cloud is ideal for applications requiring scalability, global reach, or faster service rollouts.

**Data center as a stepping stone to public cloud**

* A private cloud can be a staging ground for migrating applications to the public cloud.
* It helps manage "virtual machine sprawl" and prepare applications to be cloud-native.

Overall, the data center transforms into a private cloud component in a hybrid model, enabling businesses to leverage the strengths of both public and private cloud deployments.

---

#2.EMBRACING THE BUSINESS Imperative

### UNDERSTANDING IT TRANSFORMATION
*  While the IT organization in the past had total control of computing resources, now IT is tasked with providing oversight, management, and vetting of options.
* IT must be able to provide the business with ways to integrate processes and data across silos.The security organization is also responsible for ensuring security and compliance.
*  IT now has to provide oversight and management of both cloud and on-premises computing services.This means that IT needs to provide a transition plan for applications that no longer have the modularity to support business requirements.
*  IT operations have to ensure that performance in a hybrid and multicloud world is consistent and predictable.

### Escaping the IT Legacy Trap

**Challenges of migrating legacy applications to the cloud:**

* Legacy applications are often complex and tightly coupled with other systems, making them difficult to move.
* Lifting and shifting these applications to the cloud is expensive and offers minimal benefits.
* They require significant resources due to inefficient development for older computing models.

**The solution: Modernization before migration**

* Legacy applications need to be refactored to remove dependencies and become modular services.
* This allows for easier updates and avoids carrying inefficiencies to the cloud.
* Modernization is crucial to unlock the innovation potential of cloud computing for these applications.

* What is the solution? The applications have to be transformed and modernized, which means that dependencies are removed from the applications. The application is redesigned as a set of modular services. When possible, frequently used services are written once and reused. The bottom line is that it is imperative that these legacy applications are updated and modernized to gain the innovation benefits of the cloud.

## Preparing for the cloud 
**Cultural shift is key for successful cloud adoption:**

* Don't rush into cloud migration without a plan or educating everyone involved.
* Foster collaboration between IT and business units for a smooth transition.
* Establish clear guidelines and governance to balance freedom with control.

**Planning for the cloud:**

* Assess existing applications: modernize or find suitable SaaS alternatives.
* Consider adopting DevOps practices for agile software development in the cloud.
* Prepare for skill changes across the organization by providing training and hiring cloud experts.

**Phased approach for cloud adoption:**

* Start with pilot projects to gain experience and identify challenges.
* Continuously learn, adapt, and refine processes as you migrate to the cloud.
* Leverage cloud adoption as an opportunity to improve IT skills and unlock new career paths.

**Overall, cloud adoption is a strategic move for business agility, not just a technological upgrade.**

## Building For Innovation
