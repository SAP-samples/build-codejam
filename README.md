# CodeJam - With SAP Build, Create Apps, Processes, and Business Sites Without Coding

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/build-codejam)](https://api.reuse.software/info/github.com/SAP-samples/build-codejam)

## Description

This repository contains the material for the CodeJam on using **SAP Build** to create a process, an app, and a business site. 

Specifically, you will get to know the environment by creating:

* A sales order approval process (**SAP Build Process Automation**).
* An app that lets users specify sales order data and trigger that process (**SAP Build Apps**).
* A business site in which you will embed that app (**SAP Build Work Zone**).

![SAP Build](/images/MyPresentation.png)


### What you will build

You will build an application that allows a user to enter sales order data, and then allows a manager to approve the sales order. To make all this simpler for the user, you will embed the app inside a business website along with other related apps and tools.

To accomplish this, you will create 3 inter-related parts using for each one of the SAP Build tools:

- First, you will create the process with SAP Build Process Automation for taking sales order details, which will send a request for approval to the manager.
- Second, you will create an app with SAP Build Apps that allows a user to enter sales order details and sends the data to the process and triggers the process.
- And third, you will create a workspace in SAP Build Work Zone and embed the app there.

![image](https://user-images.githubusercontent.com/11659786/231709754-a833a81f-d9ee-4911-9dfe-710fcdcc404c.png)


### Following the exercises

During the CodeJam you will complete each exercise one at a time. At the end of each exercise there are questions; these are designed to help you think about the content just covered, and are to be discussed with the entire CodeJam class, led by the instructor, when everyone has finished that exercise.

If you finish an exercise early, please resist the temptation to continue with the next one. Instead, explore what you've just done and see if you can find out more about the subject that was covered. That way we all stay on track together and can benefit from some reflection via the questions (and answers).

The exercises are written in a conversational way; this is so that they have enough context and information to be completed outside the hands-on session itself. To help you navigate and find what you have to actually do next, there are pointers like this 👉 throughout that indicate the things you have to actually do (as opposed to just read for background information).


### The exercises

Here's an overview of the exercises in this CodeJam.

* [Getting Started with the SAP Build Lobby](exercises/ex0-Getting-Started/README.md)
* SAP Build Process Automation
  * [Exercise 1.1 - Create Sales Order Business Process](exercises/ex1-SAP-Build-Process-Automation/ex1.1/README.md)
  * [Exercise 1.2 - Run the Sales Order Business Process](exercises/ex1-SAP-Build-Process-Automation/ex1.2/README.md) 
* SAP Build Apps
  * [Exercise 2.1 - Create SAP Build App to Trigger Workflow](exercises/ex2-SAP-Build-Apps/ex2.1/README.md)
  * [Exercise 2.2 - Populate Dropdown with SAP Data (ES5)](exercises/ex2-SAP-Build-Apps/ex2.2/README.md)
  * [Exercise 2.3 - Check Status of Process from SAP Build App](exercises/ex2-SAP-Build-Apps/ex2.3/README.md)
  * [Exercise 2.4 - Deploy SAP Build App to SAP BTP](exercises/ex2-SAP-Build-Apps/ex2.4/README.md)
* SAP Build Work Zone
  * [Exercise 3.1 - Add a Workspace to SAP Build Work Zone](/exercises/ex3-SAP-Build-Work-Zone/ex3.1/README.md)
  * [Exercise 3.2 - Add a Web Dynpro ABAP App to Your SAP Build Work Zone](/exercises/ex3-SAP-Build-Work-Zone/ex3.2/README.md)
  * [Exercise 3.3 - Integrate an SAP Build App Application into SAP Build Work Zone](/exercises/ex3-SAP-Build-Work-Zone/ex3.3/README.md)

## Feedback

If you can spare a couple of minutes at the end of the session, please help me improve for next time by giving me some feedback.

Simply use this [Give Feedback](https://github.com/SAP-samples/build-codejam/issues/new?assignees=&labels=feedback&template=session-feedback-template.md&title=Feedback) link to create a special "feedback" issue, and follow the instructions in there.

## How to obtain support

[Create an issue](https://github.com/SAP-samples/build-codejam/issues) in this repository if you find a bug or have questions about the content.

For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## Contributing

If you wish to contribute code, offer fixes or improvements, please send a pull request. Due to legal reasons, contributors will be asked to accept a DCO when they create the first pull request to this project. This happens in an automated fashion during the submission process. SAP uses [the standard DCO text of the Linux Foundation](https://developercertificate.org/).

## License

Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
