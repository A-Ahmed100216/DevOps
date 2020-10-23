# What is DevOps?
DevOps is a combination of the work conducted by Development Teams and Operations Teams.
Prior to the formation of a ‘DevOps’ roles, these two departments functioned as separate entities with Development 
focussing upon tasks such as implementing new product features, fixing bugs and ensuring security. 
These are then deployed into build environments to check integration.
But a build environment is not fully reflective of the production environment so
deployment can be problematic. Comparatively, Operations are responsible for tasks such as
running servers and, monitoring and growing capacity. However, this did lead to some dysfunction 
among teams, thus the creation of a ‘DevOps’ role which encompassed several best practices.
These include:
* Continuous Integration – Developers regularly merge code changes into a central repository and run tests so as to quickly find and address bugs.
* Continuous Delivery – Changes in code and automatically built and tested so as to be prepared for release if the need arose. This allows developers to have a deployable product available at all times.
* Microservice – Building a single application as a set of small services, each of which run and communicate via an interface. Each service has a single purpose. 
* Infrastructure as a Code – Infrastructure is provisioned and managed using software development techniques. This allow for quick deployment.  
* Monitoring and Logging – Monitoring metrics to measure how the infrastructure performance affects the end user. 
* Communication and Collaboration – Key cultural aspects of the DevOps philosophy. This is achieved through methodologies such as Agile which promote an iterative and collective workflow as well as communication across the organisation.  

## Tools
Tools
A range of tools are available to meet a range of DevOps needs. Tools may include:
* AWS CodePipeline/Code Deploy/CodeBuild = These are all AWS services which can be used for the purposes of continuous integration and continuous deliver, for example. CodeBuild is a fully managed service that compiles code, runs tests, and produces read-to-deploy software. 
* Git – Git is a version control software which allows teams to collaborate and share source code. It also ensures all previous versions are available This embodies the DevOps philosophy of communication and collaboration a well as supporting continuous integration wherein code is continuously merged into repositories. 
* Jenkins - Jenkins is an open source CI/CD server therein allowing code to be iterated and deployed as quickly as possible.
* Docker - Container Platform which enables distributed deployment and automates app deployment. 
* Kubernetes - Container orchestration platform which works with Docker and allows you to automate the mangement of many containers. 
* Ansible - Configuration management tool which allows you to configure infrastructure and automate deployment. Ansible uses a IAAC approach. 

# Cloud Computing 

![cloud](https://github.com/A-Ahmed100216/DevOps/blob/main/cloud-computing.png)

Cloud Computing is the on-demand delivery of a range of services such as Compute, Storage, and Databases, over the internet, utilising a pay-as-you-go pricing model. 

## What is SAAS, PAAS, IAAS?
There are three models of cloud computing. These are:

![Models](https://github.com/A-Ahmed100216/DevOps/blob/main/Models.png)
* IAAS – Infrastructure as a Service – This refers to the fundamental building blocks required such as servers. This offers a high level of flexibility. An example of an IAAS platform is AWS which provisions servers and services via the Cloud.
* PAAS – Platform as a Service – This is a framework which provides users with the underlying infrastructure and services such as storage, networking etc.
* SAAS – Software as a Service is the final application delivered to users. A common example is Gmail wherein users do not manage any other underlying infrastructure. 

## Deployment 
Deployment is typically categorised into three main categories:
* On-Premise – This type of deployment occurs on premise and entails building, deploying and maintaining physical servers.
* Cloud / Public Cloud – The service provider hosts infrastructure and provisions to customers via the internet.
* Hybrid - This is a mixture of both Cloud and on-premise where some tasks may be completed using the cloud, and others, typically tasks which prioritise discretion, may opt for on-premise. 

# References:
[AWS,no date](https://aws.amazon.com/devops/)
[Ranger, S. 2018](https://www.zdnet.com/article/what-is-cloud-computing-everything-you-need-to-know-about-the-cloud/)
[Monus, A. 2018](https://raygun.com/blog/best-devops-tools/)







