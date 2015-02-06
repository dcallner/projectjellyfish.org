---
layout: document
priority: 2
section: B. Getting Started
status: published
title: Basic
---

#### Jellyfish Core
API layer of Jellyfish. It provides a REST based API for Jellyfish-UX and for the Jellyfish Mobile application.


#### Jellyfish API

 The core of Jellyfish is made up of two parts; Jellyfish API and Jellyfish UX.  Jellyfish API is a Ruby on Rails application that is the work horse of Project Jellyfish.  It is a fully scalable REST server that powers the Jellyfish UX and Jellyfish Mobile.  Jellyfish API (with Jellyfish UX) can work as the cornerstone of your IT management infrastrucrure, or it integrate into your existing IT management solition

#### Jellyfish UX

 Jellyifsh UX is an Angular / HTML5 application using NodeJS that provides an advanced interface for both end-users and admins.  For end-users it acts as a marketplace and self-service portal.  For admin, it allows them to create a catalog of services that they would like to offer their end-users.  

#### ManageIQ

Project Jellyfish is utilizing the Service Catalog capabilities provided by ManageIQ to automate the provisioning of additional cloud services such as storage, virtual machines, and relational databases by different providers. Through the use of the ManageIQ REST API, jellyfish-core is able to send provision request to any created Service Catalog Item, which will fire off the service provisioning. At the end of service provisioning, ManageIQ will send the status of the provisioning with any needed information.
