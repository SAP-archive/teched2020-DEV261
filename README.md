# DEV261 - Build Cloud-Native Extensions for SAP Solutions Based on Kubernetes

## Description

This repository contains the material for the SAP TechEd 2020 session called DEV261 - Build Cloud-Native Extensions for SAP Solutions Based on Kubernetes. 

In May 2020, SAP launched "SAP Cloud Platform, Kyma runtime", a Kubernetes-based runtime created with open-source project Kyma to easily build cloud-native extensions for the Intelligent Enterprise. Try it out yourself and use microservices combined with serverless functions to extend the Intelligent Enterprise. Furthermore, consume capabilities offered by SAP Cloud Platform and integrate them easily into the extension scenario.

## Overview

This session introduces attendees to using the "SAP Cloud Platform, Kyma runtime" which is the cloud-native runtime part of SAP Cloud Platform. It makes it easy for developers to get started deploying highly scalable workloads containerized in Docker by providing a set of tools within Kyma runtime:
* **Built-in Service Mesh:** Service-to-service communication and proxying 
* **Built-in Serverless engine:** Build lightweight use cases with serverless functions
* **Event Hub:** React to applications’ business events
* **API Gateway:** Expose securely APIs of built apps
* **Service Catalog:** Easy instantiation and consumption of services made available to the runtime

## Requirements

The requirements to follow the exercises in this repository are:
- [ ] Have a Kyma runtime deployed in your SAP Cloud Platform ([trial](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/ccb83c700e8d4bb8aa545d7307b8b08a.html) account or CPEA-based [account](https://blogs.sap.com/2020/05/13/sap-cloud-platform-extension-factory-kyma-runtime-how-to-get-started/)). **This will take 1-2 hours to complete!**
- [ ] Have `kubectl` (version 1.17 and newer) installed on your local machine following [this tutorial](https://developers.sap.com/tutorials/cp-kyma-download-cli.html)

**To make full use of this hands-on session**, the following tools shoud be ready as well:
- [ ] [Docker](https://www.docker.com/) installed with a valid public account
- [ ] [GIT](https://git-scm.com/downloads) (version 2.24 and newer) installed
- [ ] [Go](https://golang.org/doc/install) language (1.15 and newer) installed
- [ ] [Node.js](https://nodejs.org/en/download/) (version 12.18 and newer) installed
- [ ] [UI5 Tooling](https://sap.github.io/ui5-tooling/) (version 2.4.4 and newer) installed

If you can't install the above tools, we can show you how to follow the tutorial via the Kyma runtime console UI. Though you can complete each step, you will miss to learn how to make use of Kyma runtime. 

## Exercises

Let's get started with the exercises! We will show you how to create a Docker container, deploy it to Kyma runtime, making it accessile, and adding a UI to it. If there is enough time, you can as well continue by adding an event trigger to the just-deployed app. This will be possible as well after this session has ended.

1. [Deploying MSSQL in the Kyma Runtime](https://developers.sap.com/tutorials/cp-kyma-mssql-deployment.html)
1. [Deploying a Go MSSQL API Endpoint in the Kyma Runtime](https://developers.sap.com/tutorials/cp-kyma-api-mssql-golang.html)
1. [Deploying a SAPUI5 frontend in the Kyma Runtime](https://developers.sap.com/tutorials/cp-kyma-frontend-ui5-mssql.html)

### Bonus tutorials: add eventing to the exercise
4. [Deploy the Commerce Mock Application in the Kyma Runtime](https://developers.sap.com/tutorials/cp-kyma-mocks.html)
5. [Triggering a Mircoservice with an Event](https://developers.sap.com/tutorials/cp-kyma-microservice-trigger.html)


## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
