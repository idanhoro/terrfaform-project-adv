# CI/CD WITH AZURE DEVOPS

<img src="./images/cicd-pipeline.gif" width="700"/>

# Introduction

In this project, we used Terraform to create the infrastructure, as explained here:
[Terraform ](https://github.com/idanhoro/terrfaform-project-adv)

Ansible was used to configure the app servers as explained here:
[Ansible ](https://github.com/idanhoro/ansible-CD-project)

In the previous projects we have been using Terraform to provision the infrastructure of 
our application and we are using Ansible to automate the deployment process,
which is quite respectable but not enough. In this project we will finish automating
the entire process by using CI/CD methodologies to orchestrate the use of both
tools and deploy the changes made to the code continuously and automatically.

# Project Overview

This week’s project consists of using Azure Pipelines to configure a complete CI/CD pipeline
for the WeightTracker application that includes building the application and deploying it
into (an existent) infrastructure. As a bonus we are going to create an additional CI/CD pipeline
to automate the infrastructure updates when our Terraform code changes.

<img src="./images/azure-pipelines.png" width="700"/>

# Project Goals

- Create an Azure DevOps Organization
- Create a CICD (yaml) / CI (classic) Pipeline using Azure Pipelines (preferably using yaml over Classic)
- CI pipeline should trigger automatically on every commit
- Use Azure Artifacts to store your build Artifacts
- Create a CD Job using Yaml job (yaml) / Azure Release Pipelines (classic)
- Configure your CD stage to deploy to Staging using Continuous Deployment
- Configure your CD stage to deploy to Production using Continuous Delivery

# Requirements

- [Terraform ](https://github.com/idanhoro/terrfaform-project-adv)
- [Ansible ](https://github.com/idanhoro/ansible-CD-project)
- Virtual Machine that will be the Ansible Controller.
- Free Okta developer account for account registration, login


