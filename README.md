# Basic Azure Linux Vm ARM Template
This is a basic Azure ARM Template and associated PowerShell deployment script to create a Linux VM. 

This code is referenced in the blog post [Creating Azure Resources with ARM Templates Step by Step](https://blogs.msdn.microsoft.com/cloud_solution_architect/2016/11/11/creating-azure-resources-with-arm-templates-step-by-step) that explains how the deployment script and JSON files work together to allow you to create resources in Azure. 

To use these files to create a Linux VM (Ubuntu 14.04) in a new or existing resource group, use the following command in a powershell prompt:

    .\deploy.ps1 -subscriptionId [SubscriptionId] -resourceGroupName [ResourceGroupName]
     
To run from a command prompt:

    powershell -f deploy.ps1 -subscriptionId [SubscriptionId] -resourceGroupName [ResourceGroupName]
