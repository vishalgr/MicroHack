# Welcome to Devops With GitHub Hackathon

## Overview

Contoso is Insurance company, they provide a full range of long-term insurance services to help individuals who are under-insured. From the beginning, they grew faster than anticipated and have struggled to cope with rapid growth. During their first year alone, they added over 100 new employees to keep up with the demand for their services. To manage policies and associated documentation, they use a custom-developed Windows Forms application, called Policy Connect. Policy Connect uses an Azure Sql database as its data store. 
Contoso recently started a new web and mobile projects to allow policyholders, brokers, and employees to access policy information without requiring a VPN connection into the Contoso network. The web project is a based on .NET Core 3.1 , which connects to PolicyConnect database using REST APIs. They eventually intend to share the REST APIs across all their applications including the mobile app. They already have plan in place to Host Web Applications on Azure. Policy Documents for Policy Holders are stored in Cloud Storage and retrieved using Web and Mobile apps using APIs.Contoso Architecture team has already created blueprint of their deployments on Azure. Work with your team to Assess Solution requirements. Create step by step plan as listed in Hackathon tasks and deploy solution components. Source Code is provided as part of this reposistory. Contoso team needs your help to create Github Workflows or Azure DevOps workflows to automate CI/CD and deploy application on Azure. Security is prime concern for them hence ensure secrets,connectionstring and Web APIs are secured.


![Solution BluePrint](/images/solutionblueprint.png)
