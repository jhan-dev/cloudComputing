# cloudComputing
 - Sources and material provided by IBM.

## How does cloud computing work?
Cloud computing stores and processes information over the internet instead of relying on a local hard drive to store the data. 
Uploading to a cloud over local storage accomplishes 2 benefits.

  - It can store and process much larger amounts of information faster.
  - It can deliver results to any device that has an internet connection, not restricted to a device or set of local terminals.


### Examples of cloud services:
  - Netflix, Dropbox, Microsoft Office Online, iTunes, etc...

As long as a service doesn’t require you to be physically close to the storage hardware, it can deliver information to you from the cloud. Deposit a check through your phone? Upload a photo for your friends?  You’re in the cloud!

### Cloud services take 3 forms:
![Alt text](images/cloud_cloudDeploymentModel.jpg)

### Public clouds share storage and computing space
Public clouds are owned and operated by companies that offer their customers rapid access to affordable computing resources. This is the classic cloud computing model, in which small businesses and individuals like you can access a lot of computing power over the Internet. It’s easy to scale when users need more power or storage. Because many users are working inside one large bank of information but their data must be kept separate and secure, this kind of cloud is organized by what’s called multi-tenant architecture.

### Private clouds protect a single entity’s information
A private cloud is operated for a single organization. It can be hosted and managed either by that organization or by a provider, and its servers can reside either inside or outside the organization itself. Of course, this privacy also means that as a private cloud’s data expands, the organization has to install more and more private servers. Organizations prefer a private cloud if they need tight control over where their data is being held, how it is organized, and how it is protected. Private clouds can be very secure—but they are expensive!

### Hybrid clouds divide their storage into private slices
What if a business needs the low cost and scalability of a public cloud, but also needs a secure environment for product development or confidential data? These organizations wind up spreading their workloads across data centers, private clouds, and public clouds—thereby creating hybrid clouds.

A hybrid cloud mixes public and private resources. It’s a bit of this and a bit of that, with some data in a public cloud, and some in a private cloud, provided by multiple vendors who offer different levels of cloud usage. A hybrid cloud’s combination of physical and virtual servers allows organizations to rent what they need, on demand, helping them control costs while providing some flexibility.

![Alt text](images/cloud_cloudDeploymentOptions.jpg)

## Cloud "as a service"
### Three service models

Any traditional service can be delivered through cloud. The concept is called anything as a service, or (XaaS).

The three most popular service models of cloud computing:
 - Software as a service (SaaS)
 - Platform as a service (PaaS)
 - Infrastructure as a service (IaaS)

![Alt text](images/cloud_cloudAsAService.jpg)

### SaaS
With SaaS, software and data both reside online. Users can log in on a browser from almost any kind of device on almost any operating system, enter what they need, and out pops their result. Since their organization doesn’t need special software to use SaaS, it doesn’t have to buy applications. Instead it pays for yearly or per-user subscriptions to the service.

When you hear SaaS, think of uses like email or online shopping.

### PaaS
With PaaS, a vendor provides only the platform—meaning the infrastructure, operating systems, storage, and much of the code. The user’s organization manages the application’s resources and the data.

When you hear PaaS, think of containers, databases, runtime, and integration.

### IaaS
Companies turn to IaaS when they want to build their own applications from the ground up, or move existing applications from a data center into the organization to cut down on IT costs. With IaaS, a vendor provides the infrastructure and architecture like hardware, software, servers, and storage, and also handles expensive support systems like backup, security, and maintenance. This leaves the organization’s computing architecture on the web so that teams in different locations can work together, while keeping application development inside the company’s own online structure.

When you hear IaaS, think of computing, storage, and networking resources.

### Multicloud
Is the use of more than one public cloud. It lets a company choose different services from different public clouds. For example, the company might mix several public IaaS environments like IBM Cloud, Amazon Web Services, and Microsoft Azure, so they’re not locked into one cloud provider. Multicloud requires careful planning! Organizations considering it must look for a provider whose architecture can scale and integrate with the company’s existing systems.

### Clouds and premises
  - Often people talk about private and public cloud and confuse it with premises. For example, they might think that public cloud is off premises (true), while private cloud is always on premises (false).

  - Off premises is a solution that runs on hardware in a different location than the end users. That’s because most cloud vendors run their own data centers off premises from the organizations whose data they store. Their customers’ system administrators have the same access to the data as they would on premises.

  - On premises is a solution installed and hosted in-house, usually supported by a third party. Often the on-premises private cloud, also known as an “internal cloud,” is hosted inside an organization’s own data center. It can be easier to protect and maintain, but more limited in size and harder to scale up as the organization grows.

  - Some cloud vendors offer a hybrid solution. This means they allow companies to mix on premises at the company’s data center with off premises at the vendor’s data center. This can be helpful if a company’s business comes in bursts. The company can depend on its own data center most of the time, but expand onto the vendor’s data center when the load is high.

