# Create an SAP Fiori Launchpad Custom Plugin with SAP Business Application Studio and SAP S/4HANA Embedded Steampunk

## Description

This repository contains the material for step 5 of the 5 Steps to Fiori training.  

## Overview

In this session we will guide you to build a draft-enabled transactional SAP Fiori Elements Application based on the ABAP RESTful Application Programming Model (in short RAP). The underlying OData service will be exposed using the OData protocol, and the resulting app will look like this:

![APP Overview](images/app_overview.png)

The Fiori app you are going to implement is based on the RAP Flight Reference Scenario. To set the business context the scenario is the following: The department responsible for managing worldwide Travels for multiple Agencies is requesting you to build a new Fiori app with draft capabilities for processing (i.e. creating, updating and deleting) Travels.

Further reading: [Developing Transactional Apps with Draft Capabilities](https://help.sap.com/viewer/923180ddb98240829d935862025004d6/Cloud/en-US/71ba2bec1d0d4f22bc344bba6b569f2e.html)

## Requirements

The requirements to follow the exercises in this repository are:

* You have installed the _latest_ ABAP Development Tools (ADT), see [ABAP Development Tools](https://tools.hana.ondemand.com/#abap)
* You have an SAP S/4HANA 2020 system deployed in an on-premise Sandbox or via SAP Cloud Application Library (CAL)

## Exercises

Follow these steps to build a draft-enabled transactional Fiori app with RAP.

- [Getting Started](exercises/ex0/)
- [Exercise 1 - Database Tables](exercises/ex1/)
- [Exercise 2 - Core Data Services (CDS) Data Model](exercises/ex2/)
- [Exercise 3 - CDS Data Model Projection](exercises/ex3/)
- [Exercise 4 - Metadata Extensions](exercises/ex4/)
- [Exercise 5 - Business Service](exercises/ex5/)
- [Exercise 6 - Business Object Behavior](exercises/ex6/)
- [Exercise 7 - Actions](exercises/ex7/)
- [Exercise 8 - Determinations](exercises/ex8/)
- [Exercise 9 - Validations](exercises/ex9/)

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
