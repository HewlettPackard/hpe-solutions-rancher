# HPE_INTERNAL_ONLY  
Anisble_Rancher
This repository contains Ansible Playbooks for installing highly available Rancher 2.0 on RHEL 7.6 on both VMware Vsphere v6.7 virtual machine or on Bare metal servers 
kindly refer to the Deployment_Guide_Rancher20_on_RHEL76.pdf file before begining in the repository for how to use these playbooks effectively 
To install rke, Kubectl and help tool local on the ansible engine host you could either install and configure the path manually or use the Toolslocal.yml playbook 
for all the scripts the following copyrights holds true 
============================================================================================================================
For any suggestions and feedback please contact author email  eaj@hpe.com 

###
## Copyright (2018) Hewlett Packard Enterprise Development LP
##
## Licensed under the Apache License, Version 2.0 (the "License");
## You may not use this file except in compliance with the License.
## You may obtain a copy of the License at
##
## http://www.apache.org/licenses/LICENSE-2.0
##
## Unless required by applicable law or agreed to in writing, software
## distributed under the License is distributed on an "AS IS" BASIS,
## WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
## See the License for the specific language governing permissions and
## limitations under the License.
#### 
===========================================================================================================================================================================
This repository contains the resources for deploying Rancher 2.x software on HPE Synergy and Nimble platforms.
The Ansible playbooks included here are for automated configuration and deployment of infrastructure and relevant software required for this RA. The scripts contain the parameters specific to the RA setup in the HPE Lab. The scripts will require changes per your environment.
The playbooks are for creation and deletion of Virtual machines, installing Docker, setting up Kubernetes cluster and deploying Rancher software, installing rke, helm and kubectl tools etc.
The following link points to the RA whitepaper on:  HPE Reference Configuration for Rancher Kubernetes-as-a-Service on HPE Synergy and HPE Nimble Storage
URL - https://h20195.www2.hpe.com/V2/GetDocument.aspx?docname=a50000789enw

The RA can also be manually (through CLI) deployed using the guidance provided in the following Rancher link:
https://rancher.com/docs/rancher/v2.x/en/overview/

LICENSE - Referenced by content in this repository
