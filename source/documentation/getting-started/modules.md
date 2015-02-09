---
layout: document
priority: 3
section: B. Getting Started
status: published
title: Modules
---

#### ManageIQ

Project Jellyfish is utilizing the Service Catalog capabilities provided by ManageIQ to automate the provisioning of additional cloud services such as storage, virtual machines, and relational databases by different providers. Through the use of the ManageIQ REST API, jellyfish-core is able to send provision request to any created Service Catalog Item, which will fire off the service provisioning. At the end of service provisioning, ManageIQ will send the status of the provisioning with any needed information.

[Learn how to install and configure ManageIQ](https://github.com/projectjellyfish/api/blob/master/MANAGEIQ.md)


#### Chef

Project Jellyfish is using the Chef configuration management tool to install, configure, and manage the various software components of the cloud environment, operating system, and project itself.  Using Chef allows Project Jellyfish to move beyond just the abiity of IaaS, and allows us pre-configure systems for specific roles, or to apply base settings to servers (such as security policies or IAM connections), and it allows for rapid patch management (updating 10,000+ servers in a matter of minutes).  


[Find our Cookbooks in the Supermarket](https://supermarket.chef.io/users/boozallenhamilton)


#### Sensu

Sensu integration coming soon!
