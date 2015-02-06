---
layout: document
priority: 1
section: B. Getting Started
status: published
title: Overview and Requirements
---

#### Overview
Project Jellyfish is an IT broker system. It allows administrators to create a product catalog of any type of service (IaaS, TaaS, PaaS, or even Staff) and allows them to be assigned a cost, and then users can create projects and add those services to a project. Jellyfish current supports IaaS via ManageIQ and Chef.  Project Jellyfish has 3 main components: Jellyfish-Core, Jellyfish-UX, and ManageIQ.

__Jellyfish-Core__ is the API layer of Jellyfish. It provides a REST based API for Jellyfish-UX and for the Jellyfish Mobile application.

#### Requirements
Jellyfish-Core has the following requirements:

    •	Ruby 2.1.5
    •	PostgreSQL 9.3.x
    •	ManageIQ (Anand)

For the latest documents on Jellyfish Core please visit: [github.com/projectjellyfish/core](https://github.com/projectjellyfish/core)

__Jellyfish-UX__ is the HTML5 User Interface for Project Jellyfish. It provides an HTML5 front-end to Jellyfish-Core for users to purchase services, and for admins to add new products and services.

For the latest documents on Jellyfish-UX please visit: [github.com/projectjellyfish/ux](https://github.com/projectjellyfish/ux)
