---
layout: document
priority: 4
section: B. Getting Started
status: published
title: Blueprints
---

A Jellyfish blueprint is a packaged solution that formulates how to take the core jellyfish product, combine with other tools, install, configure and use for a specific problem or use case such as automated PaaS or data analytics.

#### Basic Cloud Broker
The Basic Cloud Broker blueprint provides broker functionality with a simple setup of combining core with a single component.

Components:
* [Jellyfish Core](https://github.com/projectjellyfish/api)
* [ManageIQ](http://manageiq.org/download/)


#### Advanced Cloud Broker
If you need a more advanced system that takes advantage of the benefits of Chef such as simplifying the catalog creation and allowing for a more complex bundled application stacks and advanced application monitoring use the Blueprint below.

Components:
* [Jellyfish Core](https://github.com/projectjellyfish/api))
* [ManageIQ](http://manageiq.org/download/)
* [Chef](https://supermarket.chef.io/users/boozallenhamilton)
* [Sensu (coming soon)](http://sensuapp.org/)
