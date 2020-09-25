# DEV261 - Build Cloud-Native Extensions for SAP Solutions Based on Kubernetes

## Description

This repository contains the material for the SAP TechEd 2020 session called DEV261 - Build Cloud-Native Extensions for SAP Solutions Based on Kubernetes. 

## Overview

This session introduces attendees to using the "SAP Cloud Platfor, Kyma runtime" which is the cloud-native runtime part of SAP Cloud Platform. It makes it easy for developers to get started deploying highly scalable workloads containerized in Docker by providing a set of tools within Kyma runtime:
* **Built-in Service Mesh:** Service-to-service communication and proxying 
* **Built-in Serverless engine:** Build lightweight use cases with serverless functions
* **Event Hub:** React to applications’ business events
* **API Gateway:** Expose securely APIs of built apps
* **Service Catalog:** Easy instantiation and consumption of services made available to the runtime

## Requirements

The requirements to follow the exercises in this repository are:
- [ ] Have a Kyma runtime deployed in your SAP Cloud Platform account ([trial](http://a.com) or CPEA-based [account](https://blogs.sap.com/2020/05/13/sap-cloud-platform-extension-factory-kyma-runtime-how-to-get-started/)). **This will take 1-2 hours to complete!**
- [ ] Have `kubectl`installed on your local machine following [this tutorial](http://a.com)

To make full use of this hands-on session, the following tools shoud be ready as well:
- [ ] [Docker](https://www.docker.com/) installed with a valid public account
- [ ] [GIT](https://git-scm.com/downloads) installed
- [ ] 

**Questions**
- [ ] Can we provide images to the Docker et al if people don't have Docker installed?
- [ ] Should we rather go via [this sample](https://github.com/SAP-samples/kyma-runtime-extension-samples/blob/master/sample-event-trigger-java/README.md) instead of the tutorials as they are more complex than suitable for the 90 minutes?

## Exercises

Let's get started with the exercises! As we will focus on bilding an extension case for an SAP application via Kyma runtime, you will start by simulating an application to be connected to your SAP Cloud Platform Global Account and pair it with Kyma runtime. Then you will continue step-by-step to deploy a microservice, bind it to an event, and deploy a UI to the extension. Lastly, we will show you how to make use of other SAP Cloud Platform services within Kyma runtime.
* [Deploy the Commerce Mock Application in the Kyma Runtime](https://developers.sap.com/tutorials/cp-kyma-mocks.html)
* 


## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
