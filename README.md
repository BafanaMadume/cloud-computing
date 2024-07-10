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

* The cloud makes building connections between employees, business partners, and customers easier.
*  These relationships are key to a company’s success, and building better communications, feedback mechanisms, and transparency will benefit everyone.
*  As IT transforms itself to help guide the cloud strategy, the organization can become an agent of change.
*  With the use of well-defined cloud services supported by standard Application Programming Interfaces (APIs), it is possible to more quickly establish new innovative applications and services to support partners and suppliers.
*  As an organization moves forward with connecting its ecosystem together more tightly, it will find an increasing need to manage the myriad of data sources a company and others maintain as though they were a single pool of information.
*  It’s a complex task that requires careful business and architectural planning.
*  When these applications, processes, and data services are freed from their traditional constraints, the business benefits will be compelling.

## THE BUSINESS IMPERATIVES

* **Past vs. Present:** Traditional business models involved creating long-lasting applications and platforms that could take years to develop. Today, cloud services allow new businesses to quickly launch services with minimal upfront investment.
* **Advantage of Cloud Startups:** New companies have no legacy systems to maintain and can leverage the cloud to test innovative ideas and disrupt established markets.
* **Modernizing IT is Crucial:** Keeping up with modern IT practices (including cloud adoption) is essential to stay competitive. The deeper benefit is enabling rapid innovation to stay ahead of potential competitors.
* **Building a Cloud Strategy:** Collaboration across the business is needed to establish a well-defined cloud strategy. 
* **Cloud Migration Process:** Modernizing critical applications and moving workloads to the cloud can streamline IT operations. Careful evaluation helps decide which workloads stay on-premises and which move to the cloud.
* **Cloud Partner Selection:** Management will choose cloud services that meet security, governance, and stability requirements. Using multiple clouds is possible, but limiting the number of vendors simplifies management.
* **Benefits of Cloud Strategy:**  A well-defined cloud strategy allows for innovation, protects customer relationships, and provides a competitive advantage.

![Screenshot 2024-07-08 095648](https://github.com/BafanaMadume/cloud-computing/assets/141032267/1ee1e5be-ca1a-4d5b-bc2b-eff261b23d37)

## Optimizing Your Existing Business

* **Customers Already Use Cloud Services:** Many customers use cloud services in their daily lives and expect businesses to do the same.
* **Need for Agility:**  Customers expect rapid changes and responsiveness to their needs. Businesses without cloud agility risk losing customers.
* **Example: Traditional vs. Cloud-based Furniture:** A physical furniture store faces competition from online cloud-based businesses offering wider variety and faster delivery.
* **Hybrid Model for Success:** The traditional store can combine its physical presence with cloud services to offer a wider selection, online ordering, and in-store pickup.
* **Leveraging Data and Innovation:** Customer data collected through the cloud can inform product selection, customization, and innovative services.
* **Cloud Enables Experimentation:** The cloud allows businesses to experiment with new ideas and services without high upfront investment.

## MODERN DEVELOPMENT AND DEPLOYMENT STRATEGIES
* **DevOps for Cloud Innovation:** DevOps, combining development and deployment techniques, is crucial for building innovative cloud applications.
* **Agile Development with DevOps:**  DevOps emphasizes an iterative development process focused on customer needs and success metrics.
* **Cloud Application Considerations:** Applications should be:
    * **Customer-centric:** Designed based on customer needs and usage data.
    * **Intuitive and engaging:** Encourage user interaction and continued engagement.
    * **Modular and flexible:** Adaptable to changing customer needs and environments.
    * **Partner-friendly:** Allow easy integration with complementary services.
    * **Multi-cloud ready:** Function seamlessly across different cloud platforms and on-premises environments.  
* **DevOps Benefits:** Enables continuous development and deployment (CI/CD) for faster feature delivery and updates.

**Example:**

- A custom suit tailoring SaaS application can leverage DevOps to quickly develop and deploy a requested "design approval" feature.
-  Previously, such a feature might take months to reach customers in a traditional release cycle.
-  With DevOps, the feature can be developed, tested, and deployed in days, improving customer satisfaction and responsiveness.

## REVISITING YOUR BUSINESS MODEL

* **Cloud Facilitates Business Model Transformation:**  Cloud computing simplifies adapting existing models and experimenting with new ones to drive business growth. 
* **Software as a Growth Driver:**  Previously seen as just a business expense, cloud-based software is now a key driver for innovation and success (e.g., Uber, Airbnb, Netflix).
* **Cloud Benefits for Innovation:**
    * **Rapid Application Development:** Cloud enables building and modifying applications quickly. 
    * **Data-driven Insights:** Cloud facilitates data analysis to understand customer needs and expectations.  
* **Need for Continuous Business Model Review:** Companies should regularly re-evaluate their models even after success, as the cloud empowers competitors to find weaknesses.
* **Disruption Through New Models:**  The goal is to create business models that are more compelling than existing ones to stay ahead of the curve.

## TRANSFORMING THE BUSINESS MODEL

## Experimenting with New Business Models in the Cloud

* **Cloud as an Experimentation Platform:** The cloud's agility and flexibility make it ideal for testing new business ideas (e.g., subscription services, website redesign).
* **Benefits of Cloud Experimentation:**
    * **Rapid Prototyping:** Easily create new websites or applications to test different approaches.
    * **Targeted Testing:** Test new models with a select group of customers to evaluate potential and gather feedback.
* **Business Model Components:** Elements that can be adjusted to change how a business operates and interacts with its customers and partners:
    * **Target Customers:** Who are you selling to? Can you reach new market segments?
    * **Partnerships:** Who are your current partners? Are there strategic partnerships to explore?
    * **Product/Service Offerings:** Can you offer tiered or introductory options to attract new customers?
* **Cloud Enables Customer-Centric Models:**  Cloud facilitates offering compelling solutions that address customer needs and drive sales. 

* **Strategies for Experimentation:**
    * **New Subsidiary/Brand:** Create a separate entity with a new brand to test the business model in a controlled environment.
    * **Phased Implementation:** Start small by limiting customers or service offerings within the new model, allowing for controlled growth based on results.
    * **Iterative Testing:** Experiment with different approaches until you find a model that works for your business and customer base

#  PART 2 Architectural Considerations for the cloud Environment
1. Understanding Cloud Concepts (Chapters 1-2).
2. Cloud Architecture Consideration (Chapters 3-6).
- Understand the nature of workloads.
- Define the imperative for Application Programming Interfaces (APIs).
- Determine workload portability.
- Manage workloads across clouds.
- Explain the importance of cloud standards.
- Inspect cloud services.

## RETHINKING THE TYPE OF CONSTITUENTS YOUR CLOUD SERVES

* **Two constituents** that are part of the cloud ecosystem determine how you view the cloud architecture

* **CLOUD CONSUMERS**: The individuals and groups within your business unit that use different types of cloud services to get a task accomplished. A cloud consumer could be a developer using computing services from a public cloud.
* **DIRECT CUSTOMERS**: Users who often take advantage of services that your business has created within a cloud environment. End users of your service have no idea that you are using a public or private cloud.
* **Cloud service provider**:  Commercial vendors or companies that create their own capabilities.Commercial vendors sell their services to cloud consumers,In contrast, a company might decide to become an internal cloud service provider to its own employees, partners, and customers,either as an internal service or as a profit center. These providers also create applications or services for these environments.

 ## Cloud Architecture Considerations Based on Your Role

**Cloud Consumer:**

* **Focus:** Selecting the right cloud services to meet business needs.
* **Responsibility:** Choosing and integrating services, not necessarily architecting them individually.
* **Challenge:** Avoiding disconnected service silos that are difficult to manage.
* **Benefit:** Technologies like containerization and microservices simplify service integration.

**Cloud Service Provider (CSP):**

* **Focus:** Architecting the entire cloud environment and building optimized services.
* **Responsibilities:**
    * Designing the cloud infrastructure.
    * Building and maintaining cloud-based applications and services.
    * Ensuring service consistency for customers (short-term and long-term).
* **Types of CSPs:**
    * Commercial vendors selling cloud services.
    * Private cloud providers serving employees and partners.
* **Additional Consideration:** Creating an environment that seamlessly connects with an ecosystem of partners.
![Screenshot 2024-07-08 105455](https://github.com/BafanaMadume/cloud-computing/assets/141032267/9d2c406f-5773-49e3-a2fd-82c5b99abf0a)

### The National Institute of Standards and Technology (NIST) Cloud Reference Model


**Cloud Service Consumers:**

* Represented on the left side of Figure 12 (not shown).
* Encompass various users of cloud services, both internal and external to a business.
* Cloud service management ensures services are readily available to address evolving business needs.
* This category includes applications, middleware, infrastructure, and services built on traditional on-premises models.
* The model also acknowledges the role of a cloud auditor (internal or external) who verifies if the consumer meets its obligations.

**Cloud Service Providers (CSPs):**

* Can be commercial companies or internal IT departments acting as a cloud service provider.
* Offer underlying physical and virtualized resources to run various cloud services.
* May also develop applications and business services specifically for the cloud environment.

**Interconnected Cloud Ecosystem:**

* Different cloud models (public, private, hybrid) are interrelated, not isolated.
* A network of partners supports various vendors with their cloud offerings.
* CSPs are responsible for providing a unified architecture to manage these services consistently.

**Cloud Service Management:**

* Crucial for any CSP to effectively manage and deliver services.
* Management platforms provide:
    * Support for service operation
    * Performance monitoring to ensure services meet business requirements

**Cloud Provider Responsibilities:**

* Support all major cloud models (public, private, hybrid).
* Manage the physical and virtual environment.
* Link all cloud models and supporting environments through service orchestration.
    * Without orchestration, services would become disconnected silos.

**Overall Cloud Management:**

* Effective management is essential for all components within the cloud provider model.
* Services are needed to:
    * Support core business functions.
    * Manage configurations.
    * Provide on-demand resource allocation.
    * Ensure interoperability and service portability between different cloud environments.

## PLANNING FOR DEPLOYMENT

* ## Hybrid Cloud Architectures: Complexity and Management

This passage explains the complexities of hybrid cloud architectures and how to manage them effectively. Here are the key takeaways:

* **Hybrid Cloud as a Service Mix:** A hybrid cloud isn't a single model, but rather a combination of various services from different platforms. There's no one-size-fits-all architecture.
* **Focus on Service Relationships:** From an architectural standpoint, it's crucial to understand how different services within the hybrid cloud interact with each other.
* **Cloud Management Technologies:** Utilizing cloud management tools is essential for architecting a hybrid cloud effectively (details on multi-cloud management in Chapter 4).
* **Distributed Services and Relationships:** In a hybrid cloud, services are never truly unified but remain distributed. Understanding these relationships is paramount.
* **Best Practices for Management:** 
    * **Service Templates:** Create templates defining service functionalities, usage rules, and dependencies.
    * **Change Management:**  The architecture should be adaptable to accommodate future additions like SaaS applications or new partner services.
* **Environmental Behavior:** Consider how the entire hybrid environment behaves under various circumstances (e.g., adding new services, changing workloads).

#### HYBRID MODELS HAVE FOUR PRIMARY ARCHITECTURAL CONSIDERATIONS

##### 1. **LATENCY AND PERFORMANCE**
   ## Hybrid Cloud Performance and Latency Management
* **Performance Monitoring is Crucial:** Continuously monitor and measure your entire hybrid cloud platform to ensure optimal performance.
* **Latency Considerations:** High latency (slow response times) can negatively impact customer experience. 
    * Example: Transaction processing might be best suited for a private cloud or data center to minimize latency caused by data transfer between networks in a public cloud environment.
* **Workload Placement:**
    * Applications requiring frequent data access and manipulation might perform better on-premises or in a private cloud.
    * Customer relationship management (CRM) or HR applications might function well with acceptable latency using a SaaS model in a public cloud.
* **Location of Services:** Consider the physical location of cloud services and how they interact with each other. High-frequency data exchange between services might require them to reside in the same cloud environment.
* **Public vs. Private Cloud Selection:** The choice depends on the service being delivered and its performance requirements. 
    * Public cloud services might be suitable for collaborative workspaces or low-volume data access.
    * Private or on-premises solutions might be better for mission-critical applications requiring high performance.
* **Building Flexibility:** Design your hybrid cloud with flexibility to adapt to changing latency needs. 
    * Example: A collaborative workspace might initially function well in a public cloud, but a high-volume transaction platform might require migration to a private cloud for optimal performance.
* **Composite Services and Latency:** Consider latency across the entire composite service when combining multiple services (public, private, on-premises). 
    * Identify components that benefit from the public cloud while maintaining overall service level requirements.
* **Microservices and Containers for Reduced Latency:** Microservices and containers with orchestration can improve performance in complex hybrid cloud environments.
    * Tight coupling of microservices and well-defined APIs can minimize latency.
    * Leverage caching mechanisms to optimize data access within services and reduce latency.
 
##### 2. **SECURITY:PLANNING IN CONTEXT**
## Security Considerations in Hybrid Cloud Planning

* **Security Based on Customer Needs:**  Security measures should reflect the level of sensitivity of customer data being stored or processed.
    * Example: Informational resources like product data sheets might have lower security requirements compared to a platform managing private health data.
* **Security Considerations Upfront:** Security needs must be well-defined before designing the hybrid cloud architecture.
* **Matching Cloud Provider Capabilities:** Choose cloud providers whose security offerings align with your specific security requirements.

##### 3. **Governance:Getting the right balance**
## Governance and Compliance in Hybrid Cloud Architecture

* **Industry Regulations:**  
    * Many industries have compliance standards (best practices) that dictate how data is handled and secured in the cloud.
    * Choose cloud partners that meet your industry's specific governance requirements. In some cases, using a third-party cloud provider might not be feasible.
* **Data Residency Laws:**  
    * Some countries have strict regulations regarding data storage location (e.g., data must be physically stored within the country).
    * Cloud architecture must consider process management services to ensure data residency compliance.
    * Depending on the country, data storage might be centralized or distributed across locations.
* **Cloud Provider Capabilities:** 
    * Select cloud providers that offer features to enforce data governance policies automatically.
    * Validate that your cloud providers can meet your specific requirements, such as deploying applications and data in designated regions.
* **Matching Architecture with Regulations:** 
    * Your hybrid cloud architecture must comply with your company's internal governance policies and relevant industry regulations.

**Managing Colocation in Hybrid Cloud Environments**

* **Balancing Cost and Performance:** 
    * In a hybrid cloud, striking a balance between affordability and performance is crucial. 
    * This might involve keeping certain applications on-premises (traditional middleware or private cloud) that are not well-suited for a public cloud environment.
* **Application Architecture for Hybrid Cloud:** 
    * Well-architected applications and services are more adaptable to hybrid cloud environments.

##### 4.Reliability in the Context of Change
**Cloud as Part of the Bigger Picture:**

* Cloud computing isn't a standalone solution, but a piece of a comprehensive IT architecture.

**Planning for Success:**

* Design your architecture with business goals, performance needs, and customer experience in mind.

**The Importance of Latency:**

* High latency (slow response times) can hinder performance and user experience. (Refer to "Latency and Performance" section for details)

**Tight Coupling vs. Loose Coupling:**

* Tightly coupled services with many dependencies might struggle in a public cloud due to latency.
* Loosely coupled services designed for easy integration are ideal for public clouds.

**The Hybrid Approach:**

* Most organizations benefit from a hybrid cloud model combining on-premises resources, private clouds, and public cloud services.

**Benefits of Hybrid Cloud:**

* Improved customer experience through better service and protection.
* Potential for a unified platform with flexible deployment options across various environments (public, private, data center) offered by some vendors.

**Holistic Approach is Key:**

* Considering all these factors during architecture design leads to a well-optimized cloud environment that serves customers effectively.

## SETTING THE RIGHT POLICIES AND BUSINESS RULES

## Policy and Business Rules in Hybrid Clouds
  

* **Policy and Rule Governance:** 
    * Traditionally, companies view policies and rules from a broad governance perspective.
    * In a hybrid cloud, these policies and rules need to be integrated from an architectural standpoint to be effective.
* **On-premises vs. Hybrid Cloud Policy Implementation:** 
    * Implementing policies within a single, on-premises environment might be simpler.
    * A hybrid cloud requires ensuring policy application across diverse components (public cloud, private cloud, on-premises).
* **Example: Data Residency Policy:** 
    * A policy requiring French customer data to be stored in France needs to be implemented as a middleware service.
    * This service would control data movement based on pre-defined rules and conditions.
* **Centralized Policy Management:** 
    * Implementing policies within individual components of a hybrid cloud is impractical.
    * A centralized policy management approach is preferred.
 
  ## Navigating the Choices in a Hybrid World

**Business Needs Drive Architecture:**

* Business requirements should guide the selection of cloud services and the overall architectural approach.

**Matching Service Levels to Platforms:**

* Choose platforms that align with your service level requirements:
    * **Real-time performance & guaranteed uptime:** Public cloud services with strong QoS (Quality of Service) or private cloud environments offer greater control. 
    * **Availability & manageability:** Customer relationship management (CRM) might function well in a SaaS (Software as a Service) model within a public cloud.

**Service Interactions and Dependencies:**

* Consider how services need to interact with each other within the hybrid cloud. 
* Identify standalone services that don't require integration with others.

**Optimizing for Customer Needs:**

* The ultimate goal is to create a hybrid cloud environment that effectively meets the needs of your customers.

## Optimizing for Workloads 
* **Workload Optimization:** A core principle in hybrid cloud architecture is optimizing workloads across different cloud environments. This is essential for meeting customer requirements effectively.
* **Interoperability Across Workloads:** 
    * **Federation:** Linking different cloud environments through standardized interfaces (federation) enables workload interoperability. 
    * **Common Interfaces:** Regardless of federation, there should be common interfaces across various cloud services (public and private) to facilitate data and service access.
* **Unimpeded Data and Service Access:** Even without federation, cloud consumers must have a simple way to access data and services across different cloud environments and networks.

## SUPPORTING A DYNAMIC LIFE CYCLE
**Shifting From Disconnected Tools to Services:**

* Traditional IT environments often involve disconnected tools and functionalities.
* Cloud computing, based on a service-oriented architecture (SOA), abstracts these complexities from users and offers services as building blocks.

**Life Cycle Focused on Change:**

* The cloud enforces a discipline of expecting and managing change.
* The architecture needs to be adaptable to accommodate:
    * Fluctuating numbers of users, applications, and workloads.
    * New services and evolving industry standards.

**Benefits of a Dynamic Cloud Model:**

* Faster application development and deployment.
* Easier service integration and linking.
* Improved communication between developers and deployment teams.
* Streamlined user provisioning (e.g., adding users through acquisitions).
* Simplified security updates and management (security as a service).

**Key Considerations for a Dynamic Hybrid Cloud Life Cycle:**

* **Services-based Model:** Break down siloed applications, processes, and services into consumable services.
* **Reduced Dependencies:** Minimize dependencies between services to enable future flexibility.
* **Performance Optimization:** Prioritize performance to ensure a positive customer experience.
* **Predictability, Security, and Governance:** Create a reliable, secure, and well-managed environment for long-term business success.

## MANAGING A HYBRID AND MULTICLOUD ENVIRONMNENT

**What Are You Managing**
**Divided the capabilities that you will need to manage into five categories:**

* SaaS applications
* External cloud resources
* Internal cloud resources
* External cloud resources
* Managing external services

#### Managing SaaS Applications
** challenges and solutions for IT departments in managing SaaS applications used by businesses.**
**Challenges:**

* Employees can easily use unauthorized SaaS applications, leading to security risks and lack of control for IT.
* SaaS applications vary in quality - some lack features important for businesses, like secure data storage and integration with other applications.
* When there are issues with a SaaS application, users expect IT to fix them regardless of the real cause (SaaS vendor or cloud provider).

**Solutions:**

* Collaborate with business units to create a list of approved SaaS applications that meet security and usability needs.
* Develop a central repository of approved SaaS applications for easy access and employee self-service.
* Encourage employees to report unmet needs so IT can find authorized solutions.
* Proactively research and approve a comprehensive set of SaaS tools to reduce reliance on unauthorized options.
* Act as an advocate for users when there are problems with SaaS applications, even if they are caused by external vendors.

**Optimizing SaaS Management**
Once a business has set the ground rules for using SaaS within the organization and educated users on the best practices of using public SaaS applications, it can take additional steps to improve costs, productivity, and security. As use of SaaS applications expands through an enterprise, IT and security teams should review use of SaaS applications. Security should examine actual use to understand whether any practices are risking loss of the business’s intellectual property (IP), 

**A SaaS Cautionary Tale**
As a business modernized itself with a cloud-based office productivity suite for creating marketing content, employees were thrilled with the ability to create and edit content at any time, whether in the home office or on the road
Their organization was widely distributed physically and having their documents in the cloud allowed sharing and reviews from many divisions of the business, regardless of where they were located.
* Users quickly became used to the SaaS application and became dependent on its powerful features.
* * Cloud suite benefits: Increased flexibility for remote work and document collaboration.
 * Outage impact: Major disruption due to widespread reliance on the suite.
 * IT challenges:
    * Blamed despite limited control over vendor's service.
    * Unclear responsibility with existing SLA.
    * Difficulty identifying outage source (application, network, etc.)
 * Potential IT shortcomings:
    * Lack of redundancy plan (failover solution).
    * Weak SLA with the vendor (uptime guarantees, communication).
 * The fix: Proactive IT measures for business continuity.
    * Redundancy plans (alternative solutions or secondary vendor).
    * Stronger SLAs (uptime guarantees, clear communication during outages).
  
---
* Cloud Access Management (CAM) =  is a form of identity management that is specifically targeted to cloud service.
*  Using CAM, users can be explicitly given rights to specific SaaS applications (and not to others), and governance specified for what information they can access.
*  Security can use CAM to formalize which company personnel can access which SaaS applications and the rights they can exercise within SaaS applications.
*  IT will be interested in how many employees are using each SaaS application, and what they use the application for.
*   As more people use a SaaS application, IT may be able to use that information to negotiate better terms for using the SaaS application from its vendor.

#### Managing External Cloud Resources
* Businesses use many types of external or public cloud resources that require management. Resources may be virtual machines that developers use, storage for backups or disaster recovery, databases for big data activities
* Cloud resources are the building blocks used to create applications. These infrastructure services are designed as a layer below SaaS applications and therefore are the responsibility of software developers.
* Understanding who is using cloud services is important because that is where management should be focused.Management of cloud services is typically practiced in IT and software development organizations.

**Visibility and Control of External Resources**

* As with SaaS applications, simply grabbing a cloud resource to execute a task is often too easy. To be successful, you need to have the ability to apply controls so that you can gain visibility into the cloud applications and services.
* The biggest management challenges of external cloud resources are identifying the most appropriate services to use, verifying their characteristics (performance, security, cost, and so on), and making sure that these services are used exclusively.
* The rationale for using these resources to the exclusion of other resources is that after a service has been selected, investments in training, testing, and building infrastructure software will occur to make the service work effectively.
* We should avoid selecting and using a different service that has the same functionality, as it can double the costs of using the functionality.

**The General cycle for approval ,use ,and eventual resue of cloud services is**

1. Identify and define the functional requirements of the software being developed.
2. Research resources available from the cloud providers that are already used by the business to find a good match. Extend the search to other cloud providers if adequate solutions are not found or if additional cloud providers should be nurtured in the spirit of multicloud.
3. Perform tests in a pilot project to verify the resource(s) found in Step 2 meet the functional requirements.
4. If the testing is successful, form a business relationship with the service vendor and get access to the production version of the resource. The vendor may be a cloud provider or a third party who makes its software available in a cloud platform. If the testing is not successful, go back to Step 2 or consider building the resource internally.
5. Document the new service and its availability to the full development organization.
6. On a regular basis, perhaps yearly, revisit existing resources (internally developed as well as external resources), the requirements they need to meet, and their operational history and issues.

**The Importance of Self Service**
* The idea of creating a catalogue of approved computing resources that consumers may select from is critical to being able to manage in a consistent and predictable way. It is a simple idea, but a very important one.
* Cloud providers make it as easy as possible for consumers to find and use their services. At the low pay-as-you-go prices of most cloud resources.

* The challenge is to make it easier for employees to use the company’s catalogue to select what they want rather than go to the cloud themselves. To do so, the company must get ahead of the curve to understand the requirements and needs of development organizations.

#### SERVICE LEVEL AGREEMENTS (SLAs) 
* Every cloud resource comes with a contractual agreement, known as a service level agreement (SLA),that outlines what the provider is delivering, along with the customer’s responsibilities

**Cloud Service Level Agreements (SLAs) Explained in Bullet Points:**

* **What is an SLA?** A contract between a cloud provider and customer outlining service delivery and responsibilities.
* **What's included in an SLA?** It details factors like uptime, accuracy, response time, security, etc. These are crucial for choosing resources that meet performance needs.
* **Vendor vs. Customer Responsibility:**
    * Vendor is responsible for outages due to their mistakes (misconfiguration).
    * Vendor is clearly responsible for security breaches they cause.
    * Grey areas exist: outages due to natural disasters or third-party network issues might not be covered.
* **Vendor's Liability:** Even if responsible, an SLA might not cover lost business during downtime. Customers may need separate insurance.
* **Performance Claims:** SLAs also define performance guarantees. Uptime is a key metric, with vendors competing for the highest percentage (e.g., 99.99% vs. 99.999%). 
* **Downtime Impact:** A small difference in uptime can translate to significant downtime depending on the workload (e.g., minutes for a test vs. disaster for a critical system).

![Screenshot 2024-07-09 103908](https://github.com/BafanaMadume/cloud-computing/assets/141032267/2dc7a571-0468-4b6d-978d-2e33d2ada7e3)

#### ADDRESSING POOR CLOUD AND COMPUTING BEHAVIORS
**Curbing Risky Cloud and Computing Behaviors:**

* **Security Threats:** Even with secure cloud environments, user actions can introduce risks.
    * Weak passwords are a prime example, potentially leading to data breaches or system damage. 
* **BYOD (Bring Your Own Device):**  Security concerns arise when employees use personal devices for work.
    * IT needs to ensure proper software and security best practices are followed on these devices.
* **Employee Education:**  Training employees about cybersecurity risks associated with poor practices is crucial.
* **Governance Strategies:**  Companies implement controls to define which systems/data employees can access based on their roles (Role-Based Access Control - RBAC).
* **Social Media Risks:**  Sharing company information or practices on social media can be a security concern, especially for younger employees unfamiliar with the risks.

### Managing Internal Cloud Resources

## Key Considerations for Managing Internal Cloud Resources

As cloud adoption becomes widespread for delivering services, effective resource management is critical for success. Here's a breakdown of key considerations for private and hybrid cloud deployments:

| Consideration | Description |
|---|---|
| Self-Service | Empowering internal users with self-service capabilities for cloud resources streamlines access and provisioning. |
| SLAs (Service Level Agreements) | Establishing SLAs ensures consistent performance and accountability for cloud services provided internally. |
| Approved Resources | Maintaining a catalog of approved resources ensures users have access to secure and compliant cloud services. |

While these considerations overlap with public cloud consumption, there are key differences:

| Consideration | Private/Hybrid Cloud | Public Cloud |
|---|---|---|
| Consumer Base | Typically limited to a single business, allowing for more targeted service offerings. | Highly diverse consumer base with a wider range of needs. |

### Managing a hybrid cloud environment

* **Security Focus:** Briefly mention how stricter security requirements in private/hybrid clouds can translate to a more curated selection process, leading to a secure and compliant environment.
* **Internal SLAs:** You could touch upon the importance of defining Service Level Agreements (SLAs) for internal cloud services to ensure performance meets user expectations.
* **Monitoring Differences:** Briefly highlight the difference in monitoring responsibilities between public and private clouds. Public cloud vendors manage their resources, while private cloud IT teams take the lead.

**Understanding the role of internal SLAs**
**Why are SLAs important?**

* **Formalized Expectations:** SLAs define clear performance and operational targets for internal cloud services, improving user satisfaction.
* **Performance Troubleshooting:**  SLAs provide objective benchmarks to identify issues. Performance problems can be attributed to the application itself or the underlying resources based on SLA adherence.

**Responsibilities:**

* **Public Cloud:** The public cloud vendor is responsible for managing resources and meeting SLAs. However, customers (businesses) should monitor the vendor's performance to ensure compliance. 
* **Private Cloud:** IT operations have the primary responsibility for monitoring private cloud resources and services to meet internal SLAs.

**Key Differences:**

* **Responsiveness:** Public cloud vendors might have slower response times due to their larger customer base.
* **Focus:** Private cloud providers have a single customer (themselves) and a greater incentive to ensure all services function effectively, potentially leading to faster issue resolution.
* **Management Focus:**  Monitoring SLAs becomes a priority for internal stakeholders, including executives, as performance directly impacts the company's bottom line.

## Managing Internal services

**Key Points:**

* **Diverse User Base:**  Internal cloud services cater to users across departments with varying technical expertise. They expect reliable, secure applications with professional support, regardless of the cloud environment (private, public, or hybrid).
* **Support Responsibilities:**  Support for internal applications can come from IT or a dedicated internal call center. 
* **Effective Support:**  Providing timely and high-quality support is crucial. 
    * **Third-Party Applications:** Support relies on the vendor although internal support should be aware of common user issues.
    * **Internal Applications:** Development teams play a role in supporting internally developed applications.
* **Collaboration is Key:**  Development and support teams need to work closely to ensure robust applications with minimal support needs.
* **Monitoring Public Cloud Resources in Hybrid Clouds:**  Several approaches exist to monitor the performance of public cloud resources used in a hybrid environment:
    * **Separate Test Environment:**  Pros: Avoids impacting application performance. Cons: Results may not reflect real-world application experience.
    * **Test Software in Hybrid Cloud:**  Pros: More realistic performance testing. Cons: Can impact hybrid cloud infrastructure performance.
    * **Public Cloud Resource Dashboard:**  Pros: Easy access to performance information if available. Cons: Relies on vendor-provided data.
    * **Application Instrumentation:**  Pros: Most accurate performance monitoring, minimal impact on application. Cons: Requires careful implementation.

**Best Practices:**

* **Automated Monitoring and Reporting:**  Automate performance testing and reporting to reduce manual effort.
* **Alerting System:**  Implement an automated notification system to alert support teams of critical performance issues.

## Monitoring The Cloud Infrastructure  
* Monitoring Private/Hybrid Clouds: Similar to public cloud vendors, organizations should monitor the operational status of their private and hybrid cloud environments to ensure basic services are functioning properly. This information is crucial for initial troubleshooting by support personnel

## Monitoring applications and Services

* **Support Personnel:** Application usage data helps support teams understand user actions and troubleshoot issues effectively.
* **User Experience (UX) Experts:** By analyzing user interactions, UX experts can identify interface issues, streamline workflows, and discover bugs.
* **Product Managers:** User activity data helps product managers confirm feature usage and identify opportunities for improvement or new features.
* **Developers:** Application logs provide insights into crashes, operational patterns, and areas for application optimization. 
* **Business Analysts:**  Key Performance Indicators (KPIs) derived from application data reveal if applications are meeting business goals.
* **AI and Machine Learning:** Advanced analytics can identify recurring problems or predict potential issues based on historical data.

**Data Visualization for Informed Decisions:**

The vast amount of data generated by cloud applications necessitates effective presentation for user comprehension. Here's how information is transformed for better decision-making:

* **Analysis Software:** Processes and condenses raw data into a manageable format.
* **Visualization Techniques:** Present information in a clear and visually appealing way (e.g., charts, graphs).

**Dashboards: Tailored Information for Different Audiences:**

Dashboards are a powerful tool for presenting operational data to specific user groups with customized views based on their needs:

* **Support:** Focuses on user troubleshooting information.
* **Developers:** Emphasizes performance data and user behavior insights.
* **Product Managers:** Highlights KPIs and usability data.
* **Executives:** Provides high-level status updates and customer acceptance metrics.

## Managing External Services
* One characteristic of a hybrid cloud environment is that an organization will have a variety of services that need to be managed.
* To be successful, visibility and control over external and internal resources is critical.

**DevOps and Deployment to Public Clouds**
* best practices for developing software for the cloud are based on DevOps practices.
* DevOps combines Development with Operations and enables continuous development and deployment of software.
* DevOps streamlines the management of application and service life cycles by eliminating handoffs between development and operations and makes the software more robust because developers are now paying more attention to operational issues.
* After an application is deployed to the cloud, DevOps engineers continue to watch the software while it is running.
*  If operational issues come up, the engineers responsible for the software are immediately involved and can either solve problems tactically in the cloud or, if necessary, make changes to the application and redeploy it with fixes as quickly as the code can be changed and tested.

**External System Monitoring**
* With applications and services used by customers in other companies, it is even more important that system monitoring gathers application and service usage than it was within a single company.
*  After all, companies have many more opportunities to quiz their own employees about how well systems work than quizzing employees of other companies.

**Application and Service Life Cycles**

* **Continuous Availability:**  Public cloud users expect applications and services to be "always on and always available."
* **Zero-Downtime Upgrades:**  Upgrading applications must happen seamlessly without impacting ongoing user activity. 
* **Failover Mechanisms:**  Designing for failover ensures that application failures only cause brief interruptions, preventing complete outages or data loss.

**Why is this important?**

* **User Experience:**  Downtime and disruptions negatively impact user experience and satisfaction.
* **Potential Data Loss:**  Outages can lead to data loss, posing a significant risk.
* **Public Cloud Scrutiny:**  Public cloud environments are subject to more scrutiny compared to private deployments, making outages more visible.

**How to Achieve High Availability:**

* **DevOps Practices:**  Continuous integration and deployment (CI/CD) pipelines can automate testing and deployments, minimizing downtime during updates.
* **Scalability and Redundancy:**  Designing applications to scale and have redundant components ensures service continuity during failures.
* **Robust Monitoring:**  Continuously monitoring applications and infrastructure helps identify and address potential issues proactively.

## The Future of Multicloud Management

* **Hybrid Cloud Fabric:**  Multiple services and deployment models are creating a complex hybrid cloud landscape.
* **Unified Management:**  The ability to manage all internal and external cloud services is becoming increasingly critical.
* **Multi-Cloud Complexity:**  Organizations often leverage multiple public cloud providers alongside private and third-party services, leading to significant complexity as deployments scale.

**Essential Questions for Effective Multi-Cloud Management:**

* **Service Inventory:**  Identify all currently used services and anticipate future needs.
* **Business Alignment:**  Ensure services fulfill specific business requirements.
* **Security and Governance:**  Verify that all services meet security and governance standards.
* **Data Residency:**  Confirm that data storage complies with geographical regulations.
* **Latency Considerations:**  Evaluate overall environment latency to ensure acceptable performance for users.

**Moving Beyond Silos:**

* Avoid managing services as isolated entities (applications, storage, etc.).
* Implement an infrastructure and approach that provides a unified interface across all services.
* This ensures consistency, predictability, and simplifies overall management.

# 5 Standards in A MultiCloud World
* Defining standards.
* Understanding the evolution of standards.
* Categorizing standards.

## What are Standards
* Standards are established common and repeatable practices that have been agreed to by a business or group.
* An open standard is one that is publicly and freely available, one that has been developed in a public context where anyone who is affected by the standard can contribute.
* An open standard assumes that experienced developers will contribute to the viability of the offering.
*  different vendors, groups, and end users collaborate to develop standards based on the broad expertise of a large number of stakeholders.
*  Organizations can leverage these standards as a common foundation and build on top of them
*  Broad adoption of open standards throughout an industry or other groups is critical in order to yield the benefits
*  Building software that complies with standards allows systems to work together, reduces costs by allowing competition between different implementations of a standard, and gives consumers more choices while ensuring compatibility.
*  Simply put, without standards or agreed upon approaches, moving your infrastructure or applications from one cloud provider to another or from on-premises to a public or private cloud is a difficult prospect that can slow an organization’s development.

**Evolution of Standards**
Standards have generally been established in four ways:

1. **Multinationall bodies**:Treaties or other similar international legal agreements typically govern these bodies. These groups generally have long procedures and red tape before an agreement is reached. Members may be diplomats instead of technical experts.
   - The International Organization for Standards (ISO) is one such group and is comprised of representatives from countries all over the world.
   -  ISO has developed more than 17,500 standards covering many subject areas,
   -  Governance: Treaties or international agreements.
   -  Process: Lengthy procedures and bureaucracy.
  **Multinational Bodies (e.g., ISO):**
    * Governance: Treaties or international agreements.
    * Process: Lengthy procedures and bureaucracy.
    * Members: Typically diplomats, not always technical experts.
    * Benefits: Broad global recognition.
    * Examples: International Organization for Standards (ISO).

2. **Industry Consortiums (e.g., Apache Group):**
    * Governance: Self-organized, often around specific industry needs.
    * Process: More streamlined and quicker than multinational bodies.
    * Members: Usually include competitors who collaborate for mutual benefit.
    * Benefits: Faster development and agility.
    * Examples: The Apache Software Foundation, The Open Group, World Wide Web Consortium (W3C), OASIS.
* A consortium is typically an organized group dedicated to developing standards for a specific industry requirement.
* Even though the members may be competitors, they know that coming together will help everyone.
*  The Apache Group, The Open Group, World Wide Web Consortium, and OASIS are some examples of industry consortiums.

3. **Ad Hoc Groups:**
    * Governance: Self-organized with minimal procedures.
    * Process: Very flexible and adaptable.
    * Formation: Often built around open-source initiatives.
    * Benefits: Fastest development and ability to adapt to rapid technological change.
    * Drawbacks: Difficulty reaching consensus on complex issues.
    * Examples: Loosely organized online communities or more formal open-source project groups.
*  Ad hoc groups are self-organized and governed. These groups are often built around open-source initiatives.
*  They can be a loose body that discusses their matters through an Internet message board, or they may be more formally organized.
*  These groups have even fewer processes than industry consortiums and are therefore able to quickly adapt and change as technology moves.
*  A downside to the lower process overhead is that when difficult decisions need to be made or problems arise, getting to the correct solution and reaching a consensus may be difficult or impossible.
  
4. **De Facto Standards:**
    * Emergence: Arise organically through widespread adoption of a particular approach or product.
    * Creation: Not established by a specific body, but by industry practices.
    * Example: Popular programming languages or protocols.
* A de facto standard emerges when an approach or product is used so extensively used that it becomes a standard
*  important distinction is that a de facto standard is not created by a specific body or organization, but instead develops through practice. Often, de facto standards emerge when industry best practices converge.

**According to the National Institute of Standards and Technology (NIST), standards can be categorized based on their level of maturity**

* None
* Under Developmet
* Approved
* A reference
* Market accepted
* Retired 

## Categories of Cloud-Related Standards

#### SDOS VS SSOS
*  Standards Developing Organizations (SDOs)
*  Standards Setting Organizations (SSOs)  can be differentiated by how they create a standard.
*  **SDO** comes together to create and develop a standard
*   **SSOs** only set a standard. An SSO relies on an external body to develop the technical specifications and then subsequently adopts those specifications as a standard.
*    **For a standard to truly succeed, it needs to be:**
     - Broadly recognized and adopted by vendors,
     - Broadly adopted and demanded by consumers,
     - Open source
* If these criteria are not met, a “standard” is far from standard and is instead just a document.
* Establishing cloud standards is important because standards help improve choice, reduce cost, and improve quality.
*  While standards are being developed in many specific areas, areas, where standards are being broadly developed, include the following:
   - Interoperability
   - Portability
   - Security
 
#### Interoperability
* Interoperability is the ability for independent systems to work together and/or share information.One of the most important aspects of interoperability is the ability to enable applications to exchange data in a multicloud or on-premises data centre.
* One of the most important aspects of interoperability is the ability to enable applications to exchange data in a multicloud or on-premises data centre. also includes independent cloud deployments working together, such as public clouds from different vendors or interoperability between a private cloud and an external public cloud.
* Goal is most easily achieved when one vendor offers cloud products for different contexts: **public**, **private**, and **hybrid clouds**
* Interoperability is especially important in a multicloud environment because the goal of being able to easily move workloads among multiple clouds requires some means of achieving interoperability
* APIs are important, but problems can arise. If every cloud provider develops a different API, you run into the problem of API proliferation, a situation where there are so many APIs that organizations have difficulty managing and using them all.
*  Having proprietary APIs leads to vendor lock-in, which means that once you start using a particular vendor, you are committed to it
*  One of the most important emerging standards for cloud interoperability and orchestration is **Kubernetes**.
*  Kubernetes provides an open-source container orchestration platform that can automate the tasks of creating modern applications
*   Kubernetes has emerged as an important open-source standard that is being widely adopted.

*   Several emerging open-source standards are critical for interoperability that are related to Kubernetes.
   **Standards** include:
    - ``**Istio**`` =  a service mesh that is designed to enable services to connect to each other in a secure and controlled manner
    - ``**Calico**`` = another open-source standard that allows networking and network policy within a Kubernetes cluster across clouds,
    - ``**Helm**`` = an open-source platform, a package manager for Kubernetes that enables developers to package, configure, and deploy applications and services onto a Kubernetes cluster.

* The benefit of the combination of Kubernetes with services such as Istio, Calico, and Helm is that it permits developers to write services once and deploy them on any cloud
* With a Kubernetes and microservices approach, developers can push code out to any deployment model without changing the entire app.
* This capability allows an increased ability to respond to customer feedback, competition, and potential security issues.

* ``**Knative**`` is a pure Kubernetes universal resource model that provides a consistent API-based wrapper service for legacy workloads
* Knative can work with a variety of models, including Cloud Foundry, OpenShift, and serverless frameworks, such as Apache OpenWhisk and Fission, which are both built on top of Kubernetes and Istio in order to support serverless event driven functions.
*  ``**Open Services for Lifecycle Collaboration (OSLC)**``= The OSLC is working on the specifications for linked data to be used to federate information and capabilities across cloud services and systems.

*  The following **two interoperability** standards were developed and accepted specifically for the cloud:

1. ``Open Cloud Computing Interface (OCCI)``:A set of standards developed by the Open Grid Forum,OCCI is a protocol and API for all kinds of management tasks and utilizes the REST (Representational State Transfer) approach for interaction. It began its life as a management API for IaaS services,It now supports PaaS and SaaS deployments.
2. ``The Cloud Data Management Interface (CDMI)``:  Developed by the Storage Networking Industry Association (SNIA), it defines the functional interface that applications should use to create, retrieve, update, and delete data elements from the cloud. It also utilizes a RESTful approach

#### Portability 
* Portability enables you to take applications, data, or instances running on one vendor’s system and deploy it on another vendor’s implementation.
* The goal of portability is to allow your components (such as an application or data) to be moved between different contexts without modification.
* At one time, this would have required each context to provide the same APIs and a set of reusable services to execute consistently.
* However, new approaches allow portability between contexts regardless of the platform, operating system, location, storage, or anything else in a provider’s environment
* ``Portability`` of workloads from one cloud to another is a key requirement for mature hybrid computing environments. It is only through standards that portability will happen.
* the ``**Open Virtualization Format (OVF)**`` developed by the ``**Distributed Management Task Force (DMTF)**`` focuses on portability and interoperability for virtual machines.
* On the data side, if the data is being moved from one application to a different application, then standard formats and protocols are needed for data to be moved between one environment and another.
* Most experts believe that this kind of data portability is more difficult than application portability because there are different kinds of data  with different volumes, and that ultimately the control of that data belongs to the data’s owner.
* The ``**CDMI standard**`` has been approved to help in data portability. Another standard currently under development by the ``IEEE`` is ``IEEE P2301``, Draft Guide for Cloud Portability and Interoperability Profiles (CPIP).

#### Security 
* Cloud security is a significant concern and one must make sure that the right controls, procedures, and technology are in place to protect your corporate assets.
*  Your organization has invested a great deal internally to protect your assets, and it is reasonable to assume that your cloud provider will do the same.
*  A sound security strategy is especially true in a hybrid environment where your private cloud or data centre has touchpoints with public cloud services.
*  Cloud security standards are a set of processes, policies, and best practices that ensure the proper controls are placed over an environment to prevent application, information, identity, and access issues

*  ``**Authentication and authorization**``: Several standards are in use to verify the identity of a person or computer, including standards associated with the following keys:
IETF RFC 3820: X.509 Public Key Infrastructure (PKI) Proxy Certificate Profile
IETF RFC5280: Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile
ITU-T X.509 | ISO/IEC 9594-8 — The Directory: Public Key and attribute certificate frameworks: Information technology — open systems interconnection.
* ``**Security monitoring and incident response**``: Some standards have been approved to handle security monitoring and incident response, including the best practices developed by NIST in the NIST SP 800-61Rev. 2 Computer Security Incident Handling Guide.
* ``**Confidentiality, integrity, and availability of data**``: A number of standards that have been on the market for some time deal with encryption of data, keys, and data transport. These standards include the Key Management Interoperability Protocol (KMIP), developed by OASIS, and FIPS 186-3 Digital Signature Standard (DSS), developed by NIST.
* ``**Security policy management**``: These standards set forth best practices and procedures for implementing policies around security. FIPS 200: Minimum Security Requirements for Federal Information and Information Systems developed by NIST is an example of this kind of standard.

#### Organizations building Momentum Around Standards

* Some of these standards bodies are not necessarily looking to create new standards. Instead, they are looking to leverage existing best practices and standards, such as those used in implementing the web

**Cloud Security Alliance**
* The Cloud Security Alliance (CSA) was formed in late 2008 when cloud security became important in users’ minds. Its founding members include Dell, PGP, QualSys, Ascaler, and the Information Systems Audit and Control Association (ISACA).
* CSA itself is not a formal standards body. However, its objectives include promoting understanding between users and providers of cloud computing regarding security requirements and researching best practices for cloud security.

The CSA offers training in three areas
- Governance, Risk Management, and Compliance (GRC)
- Payment Card Industry Data Security Standard (PCI DSS) controls in the cloud
- Cloud Computing Security Knowledge (CCSK)

* The CSA also provides a certificate in CCSK via a 50-question timed online test
*  the CSA rolled out its Security, Trust & Assurance Registry (STAR), a free, publicly accessible registry that documents the security controls provided by cloud vendors
*  The registry is a form of self-regulation by cloud providers and is meant to help ensure that CSA best practices become de facto standards.
*  Recent reports produced by the CSA include version 3 of its Security Guidance for Critical Areas of Focus in Cloud Computing

#### Distributed Management Task Force (DMTF)

* The ``DMTF`` (www.dmtf.org) has been around for nearly 30 years and may best be known for its common information mode
* which is a common view of IT equipment. Its goal is to bring the IT industry together to collaborate on systems management standards.
* The ``DTMF`` formed the Cloud Management Initiative to advance standards and technologies across the various DMTF working groups, including the ``Cloud Management Working Group (CMWG)``, the ``Cloud Auditing Data Federation Working Group (CADF)``, the ``Software Entitlement Working Group (SEWG)``, and the ``Open Virtualization Working Group (OVF)``.

#### Cloud Standards Customer Council (CSCC)
* The OMG (Object Management Group;ormed in 1989 and is an international group focused on developing enterprise integration standards for a wide range of industries, including government, life sciences, and health care. The OMG creates many working groups that focus on issues important to both vendors and customers.
* One important group within the OMG is called the Cloud Standards Customer Council (CSCC)
* The CSCC (www.cloud-council.org) provides modelling standards for software and other processes and has brought together many of the most influential companies in cloud computing.
* The goal of the CSCC is to establish a set of customer-driven/end-user requirements to ensure cloud users have the same flexibility and openness that they have with traditional IT environments.
*  CSCC will prioritize key interoperability issues in reference architecture, security and compliance, cloud management, and hybrid clouds.

#### Open Commons Consortium(OCC)
* The OCC (www.occ=data.org), previously the Open Cloud Consortium, was formed in 2008. One of its goals is to support the development of standards for cloud computing and frameworks for interoperability among clouds.
* it operates cloud infrastructure. It also manages cloud computing infrastructure to support scientific research
* The OCC has a number of working groups.

#### The Open Group
* The Open Group (http://www.opengroup.org/) is a global consortium with more than 400 member organizations that focuses on achieving business objectives through standards.
* Its goal is to lead the development of vendor-neutral IT standards and certifications. In the cloud, the Open Group Cloud Work Group is looking to create a common understanding among various groups about ensuring safe and secure architectures.
* The group is working with organizations such as the Cloud Security Alliance to make this happen.

#### Storage Networking Industry Association (SNIA)
* The SNIA (www.snia.org) has focused for more than 20 years on developing storage solution specifications and technologies, global standards, and storage education.
*  This organization’s mission is to “lead the storage industry worldwide in developing and promoting vendor-neutral architectures, standards, and educational services that facilitate the efficient management, movement, and security of information.
*  The SNIA is responsible for the Cloud Data Management Interface. Applications can use this functional interface “to create, retrieve, update and delete data elements from the Cloud.”
*  Clearly, this standard is important for hybrid cloud environments that deal with data between on-premises and public cloud deployments

#### Vertical Groups
* vertical industry groups — groups comprised of members from a particular industry such as technology and retail, are also beginning to look at cloud standards.

* ``TeleManagement Forum (TM Forum)``: This large group consists of service providers, cable and network operators, software suppliers, equipment suppliers, and systems integrators. It has provided a standardized operational framework for the creation, delivery, and monetization of digital services. It recently launched its TM Forum Cloud & New Services Initiative that focuses on leveraging these standards into the cloud marketplace.
* ``Association for Retail Technology Standards (ARTS)``: The goal of this group is to create an open environment where retailers and technology vendors can work together to create international retail technology standards

## The Impact Of Standards On The Multicloud
* Standards, whether developed by SDOs or through the de facto method, play an important role in cloud computing and in a multicloud model.
* In a multicloud world, many interfaces are between those that exist at your cloud provider and your applications, data, servers,

**Standards let you do the following:**
* Move your infrastructure or applications from one cloud provider to another. With cloud standards across clouds, you do not have to rewrite code. In a multicloud world, where you may have part of the resources associated with an application on your own premises and part with a cloud provider, this capability is important because it enables your organization to be more flexible about where your resources may be located.
* Prevent vendor lock-in. Lock-in occurs when you are so entrenched with a particular provider and its interfaces that moving to another provider is too costly
* Integrate applications more easily between your on-premises data center and private and public cloud environments.
*  Face it; integrating your assets across multiple environments can be time-consuming and costly if every cloud provider has a proprietary model.Standards help to make integration easier and eliminate many common barriers.
