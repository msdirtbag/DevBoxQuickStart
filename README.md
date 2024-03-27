# DevBoxQuickStart 1.0

This project makes w10/w11 Dev Boxes avaible to the selected Entra ID Security Group with a Azure Virtual Network that can be connected to most things. 

## What is Microsoft Dev Box?

Microsoft Dev Box is an Azure service designed to enhance developer productivity by providing self-service access to cloud-based workstations—referred to as dev boxes. These dev boxes are meticulously preconfigured, project-specific environments that allow developers to dive straight into coding without the hassle of manual setup or configuration. 

Self-Service Access: Developers can access Microsoft Dev Box on demand, creating a seamless experience for setting up their development environment. Gone are the days of waiting for IT teams to provision workstations; with Dev Box, developers take control of their own setup.

Preconfigured Developer Boxes: Dev boxes come preloaded with essential tools, libraries, and dependencies specific to the project.

Avoid Configuration Conflicts: Working across multiple dev boxes is a breeze. Developers can switch between different project contexts without worrying about conflicting configurations.

Integration with Microsoft Intune: Dev Box management extends beyond the virtual realm. Dev Boxes are automatically managed with Microsoft Intune.

Project-Based Configurations: Dev Box images can be tailored to match specific workflows. Whether it’s a web app, machine learning project, or game development, each dev box is customized.


   ![Deploy](./images/overview.png)


## Overview

This project deploys the following Azure resource types:

- Azure Automation Account 
- User Managed Identity

## Deployment

1. Hit the blue "Deploy" button below.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmsdirtbag%2FDevBoxQuickStart%2Fmain%2Fmain.json)

2. Specify your settings. 

   <img src="./images/specify.png" alt="Specify"

3. Login to your Microsoft Dev Box. 

   <img src="./images/login.png" alt="Login"


