# Welcome to IBM Cloud

Cloud computing can be complex and confusing, but we're here to help you make sense of it. This is a technically focused set of pages that will allow you to explore the technology, see the latest best practices, and help you master the IBM Cloud.

This page is still taking shape, but it should always be in an "under construction" mode, as we remove links that are no longer relevant, and add links to new relevant materials.  The idea here is not to give you EVERY possible link on a topic, but instead to steer you to content that is high quality, and that has been applied in the real world.

The structure here is important.  On this page are links for people getting started with using these technologies on IBM Cloud.  The `/docs` folder contains additional markdown pages that contain links to technical material that is "deeper" and targeted to more advanced users.

_Note: Why is this titled "bluemix-landing-page"?  In the past, the IBM Cloud platform was called "Bluemix", and I didn't want to change the title of the project and have people lose their bookmarks to this page._

# Contents
- **[Introduction - Getting Started](https://github.com/dtoczala/bluemix-landing-page#introduction---getting-started)**
   - [IBM Cloud - a Platform as a Service (PaaS)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#ibm-bluemix---a-platform-as-a-service-paas)
   - [IBM Softlayer - an Infrastructure as a Service (IaaS)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#ibm-softlayer---an-infrastructure-as-a-service-iaas)
   - [Architecting Cloud Applications](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#architecting-cloud-applications)
- **[Infrastructure Sevices and APIs](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#infrastructure-services-and-apis)**
   - [Compute](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#compute)
   - [Storage](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#storage)
   - [Network](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#network)
   - [Security](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#security)
   - [Containers](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#containers)
   - [VMware](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#vmware)
   
- **[Platform Sevices and APIs](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#bluemix-services-and-apis)**
   - [APIs](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#apis)
   - [Application Services](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#application-services)
   - [Blockchain](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#blockchain)
   - [Cloud Foundry Apps](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#cloud-foundry-apps)
   - [Data and Analytics](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#data-and-analytics)
   - [DevOps](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#devops)
   - [Finance](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#finance)
   - [Functions](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#functions)
   - [Integrate](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#integrate)
   - [Internet of Things (IoT)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#internet-of-things-iot)
   - [Mobile](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#mobile)
   - [Network](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#network)
   - [Security](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#security)
   - [Watson](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#watson)
- **[IBM Cloud Administration](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#ibm-cloud-administration)**
   - [Organization of Your IBM Cloud](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#organization-of-your-ibm-cloud)
   - [Tools You Can Use](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#tools-you-can-use)
- **[Common IBM Cloud Use Cases](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#common-bluemix-use-cases)**
   - [Cognitive Applications](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#cognitive-applications)
- **[Common Tips and Tricks](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#common-tips-and-tricks)**
   - [Debugging Node.js and Java applications on Bluemix](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#debugging-nodejs-and-java-applications-on-bluemix)
   - [Staying Aware of Watson and Cloud Best practices](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#staying-aware-of-watson-and-cloud-best-practices)
---
# Introduction - Getting Started

## IBM Cloud - a Platform as a Service (PaaS)

Bluemix is the former name of the IBM Cloud PaaS product which provides a wide array of services and capabilities that allow you to move your computing workload to a scalable and "on demand" foundation.  Some of these services are in the category of "Infrastructure as a Service" (or IaaS), some of them are in the category of "Software as a Service" (or SaaS), and some are "Functions as a Service" (or FaaS).  Give the marketing folks some more time and they will come up with some new "as a service" category.

The general idea is to use digital resources on an "as needed" basis, and to pay for them on an "as used" basis.  This allows organizations to avoid buying hardware and software that is underutilized or ignored.  When coupled with the concepts of [DevOps](https://www.ibm.com/cloud-computing/learn-more/what-is-devops/) and [microservices architectures](https://martinfowler.com/articles/microservices.html), the IBM Cloud platform can become a key foundation for a culture of innovation and continuous improvement.

The IBM Cloud itself is based on [Cloud Foundry](https://www.cloudfoundry.org/) (although this is evolving), which is an open source cloud application platform for developing and deploying enterprise cloud applications.

### References for Further Reading
- [Lionel's Bluemix Help](http:/ibm.biz/bluemixhelp) - this page is an "unofficial" collection of links done by Lionel Mace.  Nice collection of places to start from.
- [Common Bluemix ID and Billing Questions](https://www.ibm.com/blogs/bluemix/2017/08/common_qa/) - great guide on common Bluemix ID and billing questions with good answers.  We use this a lot.
- [Managing Resource Groups](https://console.bluemix.net/docs/admin/resourcegroups.html#rgs) - it's just a link to the documentation, but this new feature introduced in November 2017 allows you more freedom and options in organizing your development efforts on the IBM Cloud.
- [Free Course - Bluemix Essentials](https://developer.ibm.com/courses/all/bluemix-essentials/) - a free introductory course that will help you learn the essential concepts and terminology of the IBM Bluemix platform.
- [Bluemix Annoyances and Work Arounds](docs/bluemix-faq.md) - sub-page with guidance on how to work around some of the minor annoyances you might encounter with Bluemix.
- [Five facts you may not know about Cloud Foundry](https://www.ibm.com/developerworks/cloud/library/cl-5-facts-about-cloud-foundry/index.html) - a deeper technical article outlining the capabilities and limitations of Cloud Foundry, which deals with 5 common misconceptions about the platform.
- [Getting Started with the IBM Cloud CLI](https://console.bluemix.net/docs/cli/reference/bluemix_cli/get_started.html#getting-started) - online documentation introducing use of the command line interface for the IBM Cloud.
- [Service Availability Catalog by Region](https://mycatalog.mybluemix.net/) - shows availability of services based on region, type of service and some other filters.  Is the Watson Conversation service available in the Australian region?  Find out here...

## IBM Softlayer - an Infrastructure as a Service (IaaS)

Softlayer is the IBM Cloud IaaS product which provides a wide array of  infrastructure capabilities that allow you to move your computing workload to a scalable and "on demand" foundation.  These are exposed within the IBM Cloud interface as "Infrastructure", and allow you to select from different resource options like Devices, Storage, Network, Security, as well as some add-on services.

### References for Further Reading
- [Regulate access to your network resources with IBM Cloud security groups](https://www.ibm.com/blogs/bluemix/2017/09/network-security-groups/) - this page is good place to start for learning about creating, using and maintaining security groups.

## Architecting Cloud Applications

In traditional Enterprise application development it is assumed that the underlying infrastructure has 99.999% availability and that applications can be scaled by adding more hardware. The ops focus is largely at the infrastructure level. Cloud applications are more typically based on [micro-service architectures](https://www.ibm.com/devops/method/content/architecture/microservices/), which put the ops and reliability focus on the application.  This distinction is important and critical, and it represents a paradigm shift for most application architects and developers.

When architecting cloud applications, you need to be aware of the fact that Cloud resources are just like your old on premise hardware resources - they fail from time to time.  Using microservices and cloud you should be able to distribute "copies" of your microservices to different cloud locations, making them more resilient.  Don't depend on "the Cloud" to do it for you.  In this way you can more easily tune and scale your overall application (adding more microservice instances to address bottlenecks), as well as making it more resilient and flexible.

### References for Further Reading
- [What are Microservices?](https://developer.ibm.com/cloud-microservices/) - a quick discussion of microservices and how they work with Agile development practices and Cloud infrastructures.  Good overview.
- [Site Reliability Engineering, the Cloud Approach to Operations](https://www.ibm.com/blogs/bluemix/2017/08/site-reliability-engineering-cloud-approach-operations/) - a quick discussion of the importance of Site Reliability Engineering for Cloud applications.
- [99.95% availability. Balancing release velocity and reliability](https://www.ibm.com/blogs/bluemix/2017/09/sre-availability-balancing-release-velocity-reliability/) - a quick discussion of the importance of monitoring to DevOps, and how this impacts the reliability of cloud based applications.

---
# Infrastructure Services and APIs

## Compute

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Storage

Cloud Object Storage (COS) is one form of storage available to users of the IBM Cloud platform.  Cloud Object Storage provides storage in the cloud of a persistent set of objects - for later retrieval.  You can store, manage and access your data via a self-service portal and RESTful APIs.

### References for Further Reading
- [Working With IBM Cloud Object Storage In Python](https://medium.com/ibm-data-science-experience/working-with-ibm-cloud-object-storage-in-python-fe0ba8667d5f) - A simple project that shows how to use Cloud Object Storage (COS) in conjunction with a [Data Science Experience (DSX)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#data-and-analytics) project, all in Python.

## Network

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Security

Ipso facto lipitor walla-walla

### References for Further Reading
- [The top ten security articles you need to read](https://www.ibm.com/developerworks/security/library/se-top-security-articles-you-need-read/index.html) - We're sorry, a link to an article with more links.  But good for general security awareness.

## Containers

A container is a standard way to package an app and all its dependencies so that the app can be moved between environments and run without changes.  Containers in the IBM Cloud are [Docker images](https://docs.docker.com/engine/userguide/storagedriver/imagesandcontainers/), from your [Docker registry](https://console.bluemix.net/docs/containers/cs_planning.html#cs_planning_images), that are deployed on [Kubernetes](https://console.bluemix.net/docs/containers/cs_ov.html#kubernetes_basics).  This is how you should deploy your microservices based applications for improved scalability and survivability.

A key piece of Kubernetes functionality is provided by [Istio](https://istio.io/), a microservice mesh that includes routing, ingress control, microservice discovery, and other benefits for your Kubernetes cluster.  Istio is a joint effort by IBM, Google, Lyft, 

### References for Further Reading
- [Container, Docker, Kubernetes Overview](https://console.bluemix.net/docs/containers/cs_ov.html#cs_ov) - From the IBM Cloud documentation.  A simple place to learn the basic concepts.
- [Kubernetes Service Policies](https://www.ibm.com/blogs/bluemix/2017/10/kubernetes-service-policies/) - Read this BEFORE you begin to deploy Kubernetes clusters into your environment.  Failure to do so will result in your clusters being visible globally in your account.  [David Callies](https://www.ibm.com/blogs/bluemix/author/dbcallieus-ibm-com/) post explains how to define and setup policies for your Kubernetes clusters.  You'll thank us later.
- [Speed deployment on Kubernetes with Helm Chart – Quick YAML example from scratch](https://www.ibm.com/blogs/bluemix/2017/10/quick-example-helm-chart-for-kubernetes/) - Great hands-on tutorial on using containers, Kubernetes, and Helm to deploy a simple application.
- [Enable your microservices with advanced traffic management and request tracing capabilities using Istio](https://developer.ibm.com/code/patterns/manage-microservices-traffic-using-istio/) - a good demo (with code) for the beginner who wants to learn more about Istio.
- [How Istio manages microservice applications – A traffic flow analysis](https://developer.ibm.com/dwblog/2017/how-istio-manages-microservice-applications/) - a quick read and associated video, which explains how Istio does the routing to your Kubernetes based microservices.

## VMware

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound


---
# Platform Services and APIs

## APIs

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Application Services

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Blockchain

Blockchain is one of the most talked about new technologies in recent memory.  It is popular because it holds the promise of maintaining an unmutable hyper-ledger, meaning that a chain of events which cannot be modified or corrupted.  This serves as the foundation for many crypto-currencies like [Bitcoin](https://bitcoin.org/en/) and [Etherium](https://ethereum.org/).  Blockchain can also be used to manage contracts, financial transactions, supply chain, health data, and other types of use cases where there is a need for a shared ledger, with full auditability and security.

### References for Further Reading
- [IBM Blockchain Developer Center](https://developer.ibm.com/blockchain/) - a good landing page for news and information on Blockchain technology, geared for developers.
- [Blockchain basics: Glossary and use cases](https://www.ibm.com/developerworks/cloud/library/cl-blockchain-basics-glossary-bluemix-trs/) - learn the terminology first, and examples of typical use cases, and then move on and learn more about Blockchain.
- [IBM Blockchain 101: Quick-start guide for developers](https://www.ibm.com/developerworks/cloud/library/cl-ibm-blockchain-101-quick-start-guide-for-developers-bluemix-trs/index.html) - A great place to start in your exploration of Blockchain technology.  Highlights different ways to work with and deploy Blockchain based solutions and applications.
- [Blockchain Basics: Introduction to Distributed Ledgers](https://www.ibm.com/developerworks/cloud/library/cl-blockchain-basics-intro-bluemix-trs/) - a good overview of distributed ledgers and some basic Blockchain concepts.
- [Top 6 technical advantages of Hyperledger Fabric for blockchain networks](https://www.ibm.com/developerworks/cloud/library/cl-top-technical-advantages-of-hyperledger-fabric-for-blockchain-networks/index.html?ca=drs-) - an overview of the technical advantages of using Hyperledger fabric when implementing Blockchain solutions on the IBM Cloud platform.
- [IBM Blockchain Essentials Course](https://developer.ibm.com/courses/all/blockchain-essentials/) - a good course for developers who want to learn the basics of working with Blockchain.
- [Hyperledger Composer basics, Part 1 - Model and test your blockchain network](https://www.ibm.com/developerworks/cloud/library/cl-model-test-your-blockchain-network-with-hyperledger-composer-playground/index.html?ca=drs-) - the first in a series of tutorials showing how you can begin investigating and using Blockchain technology.

## Cloud Foundry Apps

Cloud Foundry allows you to develop applications using certain packaged environments, known as buildpacks.  These buildpacks provide the runtime environment for your application, and allow you to build and deploy this application on the IBM Cloud.

### References for Further Reading
- [Increase productivity with five Cloud Foundry plugins](https://www.ibm.com/developerworks/cloud/library/cl-cloud-foundry-plugins/index.html) - Article detailing 5 different Cloud Foundry plugins, how to install them and how to use them.
- [Essentials of Application Development on IBM Cloud](http://www.redbooks.ibm.com/redbooks/pdfs/sg248374.pdf) - This is an IBM Redbook (meaning that it is big - a 222 page PDF), but there is some good info in here.  Some of it may be out of date, as the platform has been changing wuite rapidly, but the concepts here are solid.
- [Developing Node,js Applications on IBM Cloud](http://www.redbooks.ibm.com/redbooks/pdfs/sg248406.pdf) - Another IBM Redbook, this is a 146 page PDF focused on Node.js development.  Good for someone learning Node.js (or new to it), and provides some simple examples with Express and React.

## Data and Analytics

This area is huge - and contains a variety of different database technologies, analytics platforms and technologies, data science tools and platforms (like the [Data Science Experience](https://datascience.ibm.com/), or DSX), and even Watson Machine Learning (WML).  We're just going to cover the highlights here, and provide some good starting points for where to learn more.

The [Cloudant NoSQL DB](https://console.bluemix.net/catalog/services/cloudant-nosql-db) is often used as a solid no SQL option for storing JSON and other unstructured types of data.  It is compatible with CouchDB (and uses some of the same tools).

The [Data Science Experience](https://datascience.ibm.com/) is used by data scientists as a single area with common tools and visualization technologies for their data science work.  Often these data science efforts will be used to build a [Watson Machine Learning](https://console.bluemix.net/catalog/services/machine-learning) (WML) model.

### References for Further Reading

#### Code
- [Create an analytics application in IBM Data Science Experience (DSX) and Deploy it in Watson Machine Learning (WML)](https://github.com/ibm-cloud-architecture/refarch-data-science) - a GitHub project that walks through creating an analytics application and and deploying the model in Watson Machine Learning.
- [Working With IBM Cloud Object Storage In Python](https://medium.com/ibm-data-science-experience/working-with-ibm-cloud-object-storage-in-python-fe0ba8667d5f) - A simple project that shows how to use [Cloud Object Storage (COS)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#storage) in conjunction with a Data Science Experience (DSX) project, all in Python.
- [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) - a great little animation that highlights some basic machine learning concepts around classification and training.  

#### Cloudant
- [Cloudant NoSQL DB backup and recovery](https://console.bluemix.net/docs/services/Cloudant/guides/backup-cookbook.html#cloudant-nosql-db-backup-and-recovery) - From the online documentation - goes over the basics.  Also see the section on [Disaster Recovery and Backup](https://console.bluemix.net/docs/services/Cloudant/guides/disaster-recovery-and-backup.html#disaster-recovery-and-backup).

## DevOps

The IBM Cloud platform supports a variety of DevOps services, which help organizations create software development toolchains and environments for doing [Continuous Integration (CI)](https://en.wikipedia.org/wiki/Continuous_integration) and [Continuous Delivery (CD)](https://en.wikipedia.org/wiki/Continuous_delivery).  These allow you to provide an Agile development environment where changes are built and deployed in an automated manner, allowing teams to move quickly into development environments, integrating code as they deliver.

In March 2018, IBM released a Cloud delivery environment called [Microclimate](https://microclimate-dev2ops.github.io/).  It claims to be able to deploy to multiple Cloud environments, and is built to provide an end to end development environment that lets you rapidly create, edit, and deploy applications. Applications are run in [Docker containers](https://www.docker.com/what-container) from day one and can be delivered into production on [Kubernetes](https://kubernetes.io/) through an automated DevOps pipeline using [Jenkins](https://jenkins.io/). Microclimate can be installed locally or on IBM Cloud Private.  it sounds pretty sharp, but it's new so we don't know how wonderful it really is yet.

### References for Further Reading
- [Quickly Develop, Build, and Deploy Applications on IBM Cloud with DevOps services - Part 1](https://www.ibm.com/blogs/bluemix/2017/07/quickly-develop-build-deploy-applications-ibm-cloud-devops-services/) - Steve Weaver goes through deploying a toolchain and setting up a development pipeline on the IBM Cloud.
- [Quickly Develop, Build, and Deploy Applications on IBM Cloud with DevOps services - Part 2](https://grunt) - Steve Weaver goes through the steps to deploy a toolchain for an already existing application on the IBM Cloud.
- [Master continuous integration and delivery with the IBM Devops Toolchain](https://www.ibm.com/blogs/bluemix/2016/08/master-continuous-integration-delivery-ibm-devops-toolchain/) - good article, worth the time to check out.
- [Learn to use GitHub with GitHub Learning Lab](https://www.zdnet.com/article/learn-to-use-github-with-github-learning-lab/) - not comfortable with GitHub, or never used it before?  Then go through this education path from GitHub and get comfortable.
- [Integrate Jenkins with your toolchain to send job notifications, track code deployments](https://www.ibm.com/blogs/bluemix/2017/06/integrate-jenkins-to-your-toolchain/) - guidance on how to integrate your Jenkins server into an IBM DevOps Toolchain that deploys your applications to the IBM Cloud.  The integrations here are really nice - Slack notifications, PagerDuty alerts, etc.
- [Documentation for Microclimate](https://microclimate-dev2ops.github.io/document) - the online documentation, has some guided help for you.

## Finance

This area of the catlog is filled with a series of third-party financial applications and services.  This changes over time, and we don't have a lot of direct experience in working with these services.  Some of them look to be quite interesting and powerful - we suggest that you do your homework and research the capabilities, capacity, and costs associated with any of these services.

## Functions

IBM Cloud Functions (based on [Apache OpenWhisk](https://openwhisk.incubator.apache.org/)) is a Function-as-a-Service (FaaS) platform which executes functions in response to incoming events and costs nothing when not in use.

### References for Further Reading
- [OpenWhisk/Functions Concepts](https://console-regional.ng.bluemix.net/openwhisk/learn/concepts) - A great starting point to understand the concepts behind the Functions capability.
- [Functions CLI](https://console-regional.ng.bluemix.net/openwhisk/learn/cli) - install and test out the Functions CLI.
- [Invoking a microservice hosted on IBM Cloud Functions](https://developer.ibm.com/tv/dw-mailbag-invoking-microservice-hosted-ibm-cloud-functions/) - a humorous video on how to call an IBM Cloud Function from a Node.js application.
- [Capture audience feedback with IBM Bluemix OpenWhisk](https://www.ibm.com/blogs/bluemix/2017/02/capture-audience-feedback-with-ibm-bluemix-openwhisk/?social_post=812305763&fst=Learn&linkId=34571093) - great demo application implemented on a "serverless" platform using IBM Cloud Functions.

## Integrate

There are a few different services included under the integrate category of services.  By their nature, these services tend to have a lot in common with other services and service areas.  Some of the more popular ones are the [Secure Gateway](https://console.bluemix.net/catalog/services/secure-gateway) and [API Connect](https://console.bluemix.net/catalog/services/api-connect) services.

The [Secure Gateway](https://console.bluemix.net/catalog/services/secure-gateway) Service provides a quick, easy, and secure solution for connecting anything to anything. Rather than bridging your environments at the network level like a traditional VPN that begins with full access and must be limited from the top down, Secure Gateway provides granular access only to the resources that you have defined.

[API Connect](https://console.bluemix.net/catalog/services/api-connect) is a comprehensive end-to-end API lifecycle solution that enables the automated creation of APIs, simple discovery of systems of records, self-service access for internal and third party developers and built-in security and governance. Using automated, model-driven tools, create new APIs and microservices based on Node.js and Java runtimes — all managed from a single unified console.

### References for Further Reading
- [Secure Gateway with Watson Services on IBM Cloud](https://developer.ibm.com/recipes/tutorials/secure-gateway-with-watson-services-on-ibm-cloud/) - This "receipe" is a quick how-to approach to setting up a Secure Gateway instance with some Watson services that are located on the IBM Cloud.  A nice and quick example.

## Internet of Things (IoT)

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Mobile

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Network

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Security

Security is something that you need to seriously consider when constructing cloud based applications and systems.  The IBM Cloud offers a variety of Security services, but you need to make sure that your approach to security covers multiple levels from multiple perspectives.

If you are doing penetration testing or load testing of IBM Cloud based applications, please let the IBM Cloud team know about this.  otherwise our IBM Cloud security team and security infrastructure could shut down your application, mistaking your testing as a DDOS attack or some other security event.

#### References for Further Reading
- [The top ten security articles you need to read](https://www.ibm.com/developerworks/security/library/se-top-security-articles-you-need-read/index.html) - We're sorry, a link to an article with more links.  But good for general security awareness.
- [List of IP Ranges for various datacenters](https://knowledgelayer.softlayer.com/faq/what-ip-ranges-do-i-allow-through-firewall) - For determining what IP ranges to use for the various data centers, when configuring your own security.


### IBM Cloud Identity & Access Management (IAM)

You can manage users across the IBM Cloud platform and Infrastructure services from the Users page for your account.  This utilizes the Identity & Access Management (IAM) interface.  Using this interface, you have the ability to limit the access of IBM Cloud users to certain areas of your IBM Cloud footprint (spaces and organizations), as well as limiting the access and roles for a user based on a particular service.  You can also create Service IDs, which will limit the scope and access of a particular service (or set of services).  By creating and assigning keys for these users and services, you have the ability to limit access and visibility for both individual users aand services.  By rotating your keys (deleting and recreating new keys) on a regular basis, you are able to keep your IBM Cloud infrastructure secure.

#### References for Further Reading
- [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/) - An introduction to some of the concepts and capabilities of IAM.
- [Managing Users and Access Policies](https://console.bluemix.net/docs/iam/iamusermanage.html#iamusermanage) - part of the overall documentation of IAM, this section details the specific steps that you will take to set up and provide users access to your IBM Cloud infrastructure.
- [User Roles and Permissions](https://console.bluemix.net/docs/iam/users_roles.html#userroles) - a listing of user roles and permissions based on scope and visibility.
- [Bluemix CLI Commands for Managing Keys and Policies](https://console.bluemix.net/docs/cli/reference/bluemix_cli/bx_cli.html#bx_commands_iam) - a listing and description of the various command line options for managing keys and policies for IAM.

### App ID

Use the IBM Cloud App ID service to add authentication to your mobile and web apps and protect your back-end systems. You can also host user profile info that you can use to build engaging experiences. App ID supports authentication using social identity providers, so that users can log-in with their existing Facebook and Google accounts.  This is meant to support user authentication, and should not be your only security consideration.

#### References for Further Reading
- [Securing single page apps with App ID service](https://www.ibm.com/blogs/bluemix/2017/09/securing-single-page-apps-app-id-service/) - A simple tutorial showing an example of how to implement user authentication using the App ID service.

### General Data Protection Regulation (GDPR)

General Data Protection Regulation (GDPR) is a hot topic recently.  It is a European regulation that covers how data is stored, protected, and handled.  This isn't really a security topic in the way that most people think of security, as they consider approaches securing applications and identities.  It's in the security section because it addresses DATA security.

#### References for Further Reading
-[General Data Protection Regulation (GDPR) Principles and Primer]() - a quick blog post that covers GDPR at a high level and dicusses some approaches to dealing with GDPR.

## Watson

Watson and all of the cognitive capabilities of IBM are exposed as services on the IBM Cloud platform.  This topic is huge, and there is a [whole GitHub repository (similar to this one), focused on the Watson services](https://github.com/dtoczala/watson-landing-page).  For information on specific Watson services, see that repository.

The Watson cognitive services can be broken up into some rough groupings that characterize how we think, and the capabilities that are available today.  These areas are:
- **Language** - the ability to understand conversational language.  Also includes grasping concepts from language, forming personality profiles, translating languages, and understanding tone and context.
- **Speech** - the ability to speak (text-to-speech) as well as listen (speech-to-text).
- **Vision** - the ability to "see" digital images, and to then discern information based on the images themselves.
- **Insights** - the ability to ingest data, and then provide insights on the data.

### References for Further Reading
- [Watson Landing Page](https://github.com/dtoczala/watson-landing-page) - A GitHub repository similar to this one, with pages of guidance and links to best practices that organizations adopting Watson have found valuable.
- [A beginner's guide to artificial intelligence, machine learning, and cognitive computing](https://www.ibm.com/developerworks/library/cc-beginner-guide-machine-learning-ai-cognitive/index.html) - A quick article on the history of artificial intelligence and cognitive computing.  Interesting just for background information.

---
# IBM Cloud Administration

One of the nice things about a Platform as a Service (PaaS) and Infrastructure as a Service (IaaS) is that you have the ability to provide computing environments quickly for your internal development customers.  In order to do this, you need to manage and administer your IBM Cloud environment.   There are some basic administrative things that you should be aware of - and that you need to put into place.

## Organization of Your IBM Cloud

You need to break up your IBM Cloud account into different Cloud Foundry organizations (or orgs), with a single org for each project and team.  You can then add users to an org, and give them access, roles and permissions so they can do work within that org.  You can then create individual spaces underneath that org, with each space representing a different stage of development, or development environment.  It is then possible for each team to create their own deployment pipelines which will provide a DevOps capability for their project - and automated deployments to a variety of different environments.  You can read more about this approach in [Bluemix and Watson – Getting started right](https://developer.ibm.com/dwblog/2017/ibm-cloud-bluemix-watson-new-customers/).  It is also explained in [Using Organisations more effectively in IBM Cloud](https://thebluemixdigest.wordpress.com/2018/04/10/using-organisations-more-effectively-in-ibm-cloud/).

You can also use Resource Groups to help define groups of resources in your infrastructure, and then provide the ability to limit access to those resources.  The article on [Resource Groups and Access Management](https://www.ibm.com/blogs/bluemix/2017/12/resource-groups-access-management/) discusses some best practices for managing and using resource groups to help provide security.

Another really good source of information on setting up roles and DevOps pipelines, is the guidance on [best practices for organizing users, teams and applications](https://console.bluemix.net/docs/tutorials/users-teams-applications.html#best-practices-for-organizing-users-teams-applications).  There are some good diagrams and explanations in here, with guidance around Kubernetes, Helm, DevOps, user roles and IAM security.

## Tools You Can Use

Here is a list of some of the tools that are available to help in the administration and management of your IBM Cloud infrastructure.  Check these out and use the ones that seem to fit best with your own usage of the IBM Cloud.

- [My Console](http://myconsole.mybluemix.net/) - a simple app deployed out on the IBM Cloud which will ask for your credentials, and will then display an interactive view of your IBM Cloud environment and usage.
- [Billing Insights](https://mybilling.mybluemix.net/#/login) - this application is nice, read the [blog post on the tool](https://www.ibm.com/blogs/bluemix/2017/09/get-real-time-billing-insights-bluemix-account/), and you can grab the [code for it from GitHub](https://github.ibm.com/maria-borbones/mybilling) and deploy your own version if you want.
- [Administering Your IBM Cloud Account](https://developer.ibm.com/dwblog/2018/administering-your-ibm-cloud-account-a-script-to-help/) - blog post with an associated [GitHub repository](https://github.com/dtoczala/IBM_Cloud_Admin) which has a Python script for an interactive and scriptable command line tool to help administer your IBM Cloud account.


### References for Further Reading
- [Bluemix and Watson – Getting started right](https://developer.ibm.com/dwblog/2017/ibm-cloud-bluemix-watson-new-customers/) - good overview and strategy for organizing your IBM Cloud account infrastructure.
- [Using Organisations more effectively in IBM Cloud](https://thebluemixdigest.wordpress.com/2018/04/10/using-organisations-more-effectively-in-ibm-cloud/) - good overview and video on the concepts driving the Account/Organization/Space organization of a CloudFoundry based cloud account.
- [Resource Groups and Access Management](https://www.ibm.com/blogs/bluemix/2017/12/resource-groups-access-management/) - discusses some best practices for managing and using resource groups to help provide security and to help organize your work on the IBM Cloud.
- [Best practices for organizing users, teams and applications](https://console.bluemix.net/docs/tutorials/users-teams-applications.html#best-practices-for-organizing-users-teams-applications) - good diagrams and explanations on user roles and IAM security.  Also has examples of typical user roles.
- [Monitoring Bluemix usage and spending](https://developer.ibm.com/dwblog/2017/monitoring-bluemix-usage-and-spending/) - this quick article explains how to monitor your current usage and spending on the IBM Cloud via the IBM Cloud console.

---
# Common IBM Cloud Use Cases

One of the nice things about a Platform as a Service is the fact that it provides a pattern for how to deploy applications and workload onto the Cloud.  Below are some of the more common patterns (or generic use cases) that we have seen deployed on the IBM Cloud.

When building cloud based applications and systems, it is often useful to think of things using the dessert analogy.  We often picture projects as **cupcakes** (small, tasty, proves that the ingredients work together and form something useful), **cakes** (medium sized, proves that the cupcake can scale and serve a wider audience), and **wedding cakes** (big, tasty, built to serve a large population).  When using this analogy, you can think of the various services as your ingredients (add a pinch of Storage capability, two cups of Watson services, a cup of a Node application,....).  The effort to build the project is the baking - and your development and implementation team are the bakers.  What we highlight in the sections below are the basic receipes that have yielded good cupcakes/cakes/wedding cakes.

Now just because you have the recipe, it doesn't mean that you will be successful.  Just like a receipe in the real world, how you combine the ingredients is important, the skill of your baker is important, and the little things that you add for "flavor" are important too.  Each of the receipes below are good starting points, but you should make sure that what you are baking will work for your ultimate audience.  Don't waste time/money/effort making a 3 tier wedding cake when a cupcake will satisfy the needs of your organization.  Heck, sometimes all they want is a [blueberry muffin](https://www.eater.com/2016/3/11/11203948/puppy-bagel-teenybiscuit).

And just like in the real world, there are a lot of specialty bakeries out there that will make custom cakes and cupcakes for you.  If you're not very good in the kitchen, then this might be your best bet.

### References for Further Reading
- [Call Analytics Integrated Application](https://github.com/rodalton/call-analytics) - an EXCELLENT piece of code done by [Ronan Dalton](https://github.com/rodalton) that uses a Java application in combination with various Watson services, Cloud Object Storage (COS), and DB2 on Cloud.  Does analytics of call center recordings using the cognitive capabilities of Watson.

## Cognitive Applications

There are a variety of proven patterns that you see in the world today.  Everything from Chatbots, to digital assistants, to strategic insight gatherers.  Artifical intelligence is a relatively young field, so our list of use cases is always growing, as people come up with new an innovative applications of the cognitive technologies. 

### References for Further Reading
- [Cognitive Use Cases](https://github.com/dtoczala/watson-landing-page#common-use-cases) - The "use case" section from the [Watson Landing Page](https://github.com/dtoczala/watson-landing-page).

## Microservice Architectures

Many organizations are moving towards [microservice architectures](https://www.ibm.com/cloud/garage/content/architecture/microservices/) as a way to implement business systems in a way which will easily scale, and provides flexibility for future growth.  A microservice approach also allows development organizations to more easily implement and support [Continuous Integration (CI)](https://en.wikipedia.org/wiki/Continuous_integration) and [Continuous Delivery (CD)](https://en.wikipedia.org/wiki/Continuous_delivery) approaches to support applications development.

## References for Further Reading

- [Microservices from Theory to Practice: Creating Applications in IBM Bluemix Using the Microservices Approach](http://www.redbooks.ibm.com/Redbooks.nsf/RedbookAbstracts/sg248275.html?OpenDocument) - an IBM Redbook, this is a long and technically dense review of Microservice architectures and techniques that can be used with the IBM Cloud environment.
- [My microservice has crashed, now what?](https://www.ibm.com/blogs/bluemix/2017/05/microservice-crashed-now/) - a nice article (along with code) outlining the pros and cons of different ways to deploy microservices in a high-availability aechitecture.
---
# Common Tips and Tricks
This section will cover some of the common tips and tricks used by Cloud development professionals, and covers some of those things that are not addressed in the documentation.

## Common Cloud Best Practices and Good Habits
There are some generic best practices and good habits that we have found make life easier for software development teams working in a Cloud environment.  Here's a quick list of some of the better ones that we have seen:
- [Deploying Production Cloud Applications - A Readiness Checklist](https://dtoczala.wordpress.com/2018/01/17/deploying-production-cloud-applications-a-readiness-checklist/) - A list of some common sense things that you should make sure that you have addressed before you deploy that Cloud based application for production use.
- Use a functional ID for your Cloud accounts (as highlighted in [Bluemix and Watson – Getting Started Right](https://dtoczala.wordpress.com/2017/05/26/bluemix-and-watson-getting-started-right/), that way your organization "owns" your development and deployment environments, not some employee (who may leave your company tomorrow....)

## Debugging Node.js and Java applications on IBM Cloud
One of the more difficult things to do is debugging a Node.js or Java application in a cloud environment.  This excellent video on [using App Management on Bluemix](https://www.ibm.com/blogs/bluemix/2015/10/advanced-debugging-node-apps-bluemix/) by [Sai Vennam](https://www.ibm.com/blogs/bluemix/author/svennam92gmail-com/) shows you how easy it is to profile and debug your applications on the IBM Cloud platform.  For more information, check out the [App Management documentation](https://console.bluemix.net/docs/manageapps/app_mng.html) on the IBM Cloud.  It's easy to do, requires no additional services, and can be enabled with the switch of a single environment variable.

## Staying Aware of Watson and Cloud Best practices
There are some very good sources for current material on best practices with the Watson services.  Often these are published in a few "hotspots", and it's possible for you to monitor these so you are always aware of the latest information.  Here are some RSS feeds to some key "hotspots":

- [RSS feed for Cloud Computing blogs on developerWorks](https://developer.ibm.com/dwblog/category/cloud-computing/feed/)
- [RSS feed for Cognitive Computing blogs on developerWorks](https://developer.ibm.com/dwblog/category/cognitive-computing/feed/)

_Note: You can also follow your favorite author by subscribing to an RSS feed for just their content.  The RSS feed follows this format:_
```
https://developer.ibm.com/dwblog/author/<author_id>/feed/
```
Here are some examples:
- To follow Dan Toczala's content, use https://developer.ibm.com/dwblog/author/dtoczala/feed/.
- To follow Joe Kozhaya's content, use https://developer.ibm.com/dwblog/author/kozhaya/feed/
