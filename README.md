# HC Vagrant and RH Ansible
Simple deployment strategy using Vagrant and Ansible for provisioning a Virtual Machine (VM), locally. 

Task: 
- Deploy a virtual machine - locally
- Provision packages and services: 
  - Git
  - Apache
  - net-tools

The scope is to build the Virtual Machine on Virtual Box, without the need to build and deploy following the step-by-step manual. All should run automated with the idea using DevOps CD - Continuous Deployment procedure, using Vagrant to configure and deploy the VM on my localhost and assign Ansible, to perform the installation/setup tasks **within** the deployed VM.
