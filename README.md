# Welcome to Bluemix

Cloud computing can be complex and confusing, but we're here to help you make sense of it. This is a technically focused set of pages that will allow you to explore the technology, see the latest best practices, and help you master cthe IBM Cloud.

This page is still taking shape, but it should always be in an "under construction" mode, as we remove links that are no longer relevant, and add links to new relevant materials.  The idea here is not to give you EVERY possible link on a topic, but instead to steer you to content that is high quality, and that has been applied in the real world.

The structure here is important.  On this page are links for people getting started with using these technologies on Bluemix.  The `/docs` folder contains additional markdown pages that contain links to technical material that is "deeper" and targeted to more advanced users.

# Contents
- **[Introduction - Getting Started](https://github.com/dtoczala/bluemix-landing-page#introduction---getting-started)**
   - [IBM Bluemix - a Platform as a Service (PaaS)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#ibm-bluemix---a-platform-as-a-service-paas)
   - [IBM Softlayer - an Infrastructure as a Service (IaaS)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#ibm-softlayer---an-infrastructure-as-a-service-iaas)
   - [Architecting Cloud Applications](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#architecting-cloud-applications)
- **[Bluemix Sevices and APIs](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#bluemix-services-and-apis)**
   - [Contaners](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#containers)
   - [Infrastructure](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#infrastructure)
   - [VMware](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#vmware)
   - [Application Services](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#application-services)
   - [Blockchain](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#blockchain)
   - [Cloud Foundry Apps](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#cloud-foundry-apps)
   - [Data and Analytics](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#data-and-analytics)
   - [DevOps](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#devops)
   - [Finance](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#finance)
   - [Functions](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#functions)
   - [Integrate](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#integrate)
   - [Internet of Things (IoT)](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#internet-of-things-iot)
   - [Network](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#network)
   - [Schematics](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#schematics)
   - [Security](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#security)
   - [Storage](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#storage)
   - [Watson](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#watson)
   - [Web and Mobile](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#web-and-mobile)
- **[Common Bluemix Use Cases](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#common-bluemix-use-cases)**
   - [Cognitive Applications](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#cognitive-applications)
- **[Common Tips and Tricks](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#common-tips-and-tricks)**
   - [Staying Aware of Watson and Cloud Best practices](https://github.com/dtoczala/bluemix-landing-page/blob/master/README.md#staying-aware-of-watson-and-cloud-best-practices)
---
# Introduction - Getting Started

## IBM Bluemix - a Platform as a Service (PaaS)

Bluemix is the IBM Cloud PaaS product which provides a wide array of services and capabilities that allow you to move your computing workload to a scalable and "on demand" foundation.  Some of these services are in the category of "Infrastructure as a Service" (or IaaS), some of them are are in the category of "Software as a Service" (or SaaS), and some are "Functions as a Service" (or FaaS).  Give the marketing folks some more time and they will come up wth some new "as a service" category.

The general idea is to use digital resources on an "as needed" basis, and to pay for them on an "as needed" basis.  This allows organizations to avoid buying hardware and software that is underutilized or ignored.  When coupled with the concepts of [DevOps](https://www.ibm.com/cloud-computing/learn-more/what-is-devops/) and [microservices architectures](https://martinfowler.com/articles/microservices.html), the Bluemix platform can become a key foundation for a culture of innovation and continuous improvement.

Bluemix itself is based on [Cloud Foundry](https://www.cloudfoundry.org/) (although this is evolving), which is an open source cloud application platform for developing and deploying enterprise cloud applications.

### References for Further Reading
- [Lionel's Bluemix Help](http:/ibm.biz/bluemixhelp) - this page is an "unofficial" collection of links done by Lionel Mace.  Nice collection of places to start from.
- [Common Bluemix ID and Billing Questions](https://www.ibm.com/blogs/bluemix/2017/08/common_qa/) - great guide on common Bluemix ID and billing questions with good answers.  We use this a lot.
- [Bluemix Annoyances and Work Arounds](docs/bluemix-faq.md) - sub-page with guidance on how to work around some of the minor annoyances you might encounter with Bluemix.

## IBM Softlayer - an Infrastructure as a Service (IaaS)

Softlayer is the IBM Cloud IaaS product which provides a wide array of  infrastructure capabilities that allow you to move your computing workload to a scalable and "on demand" foundation.  These are exposed within the Bluemix interface as "Infrastructure", and allow you to select from different resource options like Devices, Storage, Network, Security, as well as some add-on services.

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
# Bluemix Services and APIs

## Containers

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Infrastructure

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## VMware

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Application Services

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Blockchain

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Cloud Foundry Apps

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Data and Analytics

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## DevOps

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Finance

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Functions

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Integrate

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Internet of Things (IoT)

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Network

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Schematics

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Security

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Storage

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Watson

Watson and all of the cognitive capabilities of IBM are exposed as services on the Bluemix platform.  This topic is huge, and there is a [whole GitHub repository (similar to this one), focused on the Watson services](https://github.com/dtoczala/watson-landing-page).  For information on specific Watson services, see that repository.

The Watson cognitive services can be broken up into some rough groupings that characterize how we think, and the capabilities that are available today.  These areas are:
- **Language** - the ability to understand conversational language.  Also includes grasping concepts from language, forming personality profiles, translating languages, and understanding tone and context.
- **Speech** - the ability to speak (text-to-speech) as well as listen (speech-to-text).
- **Vision** - the ability to "see" digital images, and to then discern information based on the images themselves.
- **Insights** - the ability to ingest data, and then provide insights on the data.

### References for Further Reading
- [Watson Landing Page](https://github.com/dtoczala/watson-landing-page) - A GitHub repository similar to this one, with pages of guidance and links to best practices that organizations adopting Watson have found valuable.

## Web and Mobile

Ipso facto lipitor walla-walla

### References for Further Reading
- [grunt](https://grunt) - A simple sound

---
# Common Bluemix Use Cases

One of the nice things about a Platform as a Service is the fact that it provides a pattern for how to deploy applications and workload onto the Cloud.  Below are some of the more common patterns (or generic use cases) that we have seen deployed on Bluemix.

When building cloud based applications and systems, it is often useful to think of things using the dessert analogy.  We often picture projects as **cupcakes** (small, tasty, proves that the ingredients work together and form something useful), **cakes** (medium sized, proves that the cupcake can scale and serve a wider audience), and **wedding cakes** (big, tasty, built to serve a large population).  When using this analogy, you can think of the various services as your ingredients (add a pinch of Storage capability, two cups of Watson services, a cup of a Node application,....).  The effort to build the project is the baking - and your development and implementation team are the bakers.  What we highlight in the sections below are the basic receipes that have yielded good cupcakes/cakes/wedding cakes.

Now just because you have the recipe, it doesn't mean that you will be successful.  Just like a receipe in the real world, how you combine the ingredients is important, the skill of your baker is important, and the little things that you add for "flavor" are important too.  Each of the receipes below are good starting points, but you should make sure that what you are baking will work for your ultimate audience.  Don't waste time/money/effort making a 3 tier wedding cake when a cupcake will satisfy the needs of your organization.  Heck, sometimes all they want is a [blueberry muffin](https://www.eater.com/2016/3/11/11203948/puppy-bagel-teenybiscuit).

And just like in the real world, there are a lot of specialty bakeries out there that will make custom cakes and cupcakes for you.  If you're not very good in the kitchen, then this might be your best bet.

### References for Further Reading
- [grunt](https://grunt) - A simple sound

## Cognitive Applications

There are a variety of proven patterns that you see in the world today.  Everything from Chatbots, to digital assistants, to strategic insight gatherers.  Artifical intelligence is a relatively young field, so our list of use cases is always growing, as people come up with new an innovative applications of the cognitive technologies. 

### References for Further Reading
- [Cognitive Use Cases](https://github.com/dtoczala/watson-landing-page#common-use-cases) - The "use case" section from the [Watson Landing Page](https://github.com/dtoczala/watson-landing-page).

---
# Common Tips and Tricks
This section will cover some of the common tips and tricks used by Cloud development professionals, and covers some of those things that are not addressed in the documentation.

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
