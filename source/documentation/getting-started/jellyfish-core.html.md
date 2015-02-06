---
layout: document
priority: 2
section: B. Getting Started
status: published
title: Jellyfish Core
---
The core of Jellyfish is made up of two parts; Jellyfish API and Jellyfish UX. Jellyfish API is a Ruby on Rails application that is the work horse of Project Jellyfish.  It is a fully scalable REST server that powers the Jellyfish UX and Jellyfish Mobile.  Jellyfish API (with Jellyfish UX) can work as the cornerstone of your IT management infrastrucrure, or it integrate into your existing IT management solution.

#### Jellyfish API

__Jellyfish-API__ is the API layer of Jellyfish. It provides a REST based API for Jellyfish-UX and for the Jellyfish Mobile application.

Jellyfish API requires Ruby 2.0.0 and PostgreSQL 9.3.x

For the latest documents on Jellyfish API please visit: [github.com/projectjellyfish/core](https://github.com/projectjellyfish/api)


#### Jellyfish UX

Jellyifsh UX is an Angular / HTML5 application using NodeJS that provides an advanced interface for both end-users and admins.  For end-users it acts as a marketplace and self-service portal.  For admin, it allows them to create a catalog of services that they would like to offer their end-users.  

__Jellyfish-UX__ is the HTML5 User Interface for Project Jellyfish. It provides an HTML5 front-end to Jellyfish-Core for users to purchase services, and for admins to add new products and services.

Jellyfish UX requires Nodejs 0.10.x

For the latest documents on Jellyfish-UX please visit: [github.com/projectjellyfish/ux](https://github.com/projectjellyfish/ux)
