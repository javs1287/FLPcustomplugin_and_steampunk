# Create an SAP Fiori Launchpad Custom Plugin with SAP Business Application Studio and SAP S/4HANA Embedded Steampunk

## Description

This repository contains the material for creating a custom SAP Fiori Launchpad plugin with SAP Business Application Studio along with instructions on how to use Embedded Steampunk in SAP S/4HANA 2022 or higher to create custom developer extensibility services for consumption in this custom Fiori Launchpad Plugin.  

## Overview

In this section we will describe the main activities to be run for creating a custom Fiori Launchpad Plugin that consumes a custom service in Embedded Steampunk in SAP S/4HANA 2022 or higher.

The objective of creating this custom Fiori Launchpad plugin is for your end-users to be able to quickly distinguish which system and client they have logon to in the system. The information will be displayed in the SAP Fiori Launchpad header title section and through this custom Fiori plugin the user will see the System ID along with client number information as shown in the image.

![Plugin Overview](images/overview.png)

## Requirements

The requirements to follow the exercises in this repository are:

* You have installed the _latest_ ABAP Development Tools (ADT), see [ABAP Development Tools](https://tools.hana.ondemand.com/#abap).
* You have an SAP S/4HANA 2022 system deployed in an on-premise Sandbox or via SAP Cloud Application Library (CAL).
* You have fully configured SAP Fiori and have developer access to the backend system where embedded SAP Fiori is deployed.
* You have fully setup Cloud Connector and created a destination to your backend S/4HANA system.

## Exercises

Follow these steps to build a custom SAP Fiori Launchpad Plugin consuming Embedded Steampunk Services.
- [Getting Started](exercises/ex_0/)
- [Exercise 1 - Setting up Embedded Steampunk](exercises/ex_1/)
- [Exercise 2 - Creating a backend function module to expose system details](exercises/ex_2/)
- [Exercise 3 - Creating an HTTP Service](exercises/ex_3/)
- [Exercise 4 - Adding a Release Contract](exercises/ex_4/)
- [Exercise 5 - Testing your HTTP Service](exercises/ex_5/)
- [Exercise 6 - Creating and Deploying a Fiori Launchpad Plugin in SAP Business Application Studio](exercises/ex_6/)
- [Exercise 7 - Activating Plug-in on the on-premise ABAP Platform](exercises/ex_6/)
- [Exercise 8 - Testing your Custom Fiori Launchpad Plugin](exercises/ex_7/)


## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
