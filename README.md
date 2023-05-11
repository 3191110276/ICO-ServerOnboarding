# Intersight Orchestration Server Onboarding

This repository contains workflows that help you with onboarding new servers into your Intersight environment quickly. These examples are based on workflows in Intersight Orchestration.

Right now we have examples for the following operating systems:
* [VMware](#vmware)
* [Windows Server](#windows-server)
* [Ubuntu Server](#ubuntu-server)

To get started, download the package.json file and import it into your Intersight account. For instructions on importing a workflow, please have a look here: [Intersight Helpdocs](https://intersight.com/help/saas/resources/Workflow_Designer#importing_a_workflow).

Please keep in mind that these workflows are provided as examples only. Please go ahead and test them in your own environment. If you encounter any issues, or if you would like to request new features, please use the GitHub mechanisms to provide feedback.

> **Warning**: The current version of the workflows is not yet supported on the Intersight appliances. Starting with the next releease, all workflows should be supported on the appliance as well.

<!---
https://img.shields.io/badge/Status-Ready-green
-->

## VMware
Below you can find workflows that should help with building a VMware environment.


### New VMware Cluster
![Testing](https://img.shields.io/badge/Status-Testing-orange)

This workflow sets up a new VMware Cluster. The following elements are created:
* Server Profile Template with custom LAN Connectivity Policy
* VMware Cluster
* Distributed Virtual Switch (DVS)


### Install VMware on local disk - Cisco Mode
![Testing](https://img.shields.io/badge/Status-Testing-orange)

This workflow provisions one or multiple ESXi hosts. For each host it will:
* Create and deploy a new UCS server profile
* Install VMware operating system using Cisco-provided kickstart file
* Connect the host to vCenter and add it to an existing Cluster
* Add a Distributed Virtual Switch (DVS) to the host


### Install VMware on FC SAN - Cisco Mode
![In Development](https://img.shields.io/badge/Status-In%20Development-red)


### Add VLAN to VMware Cluster
![In Development](https://img.shields.io/badge/Status-In%20Development-red)




## Windows Server
Below you can find workflows that should help with building a Windows Server environment.


### Install Windows on local disk - Cisco Mode
![Testing](https://img.shields.io/badge/Status-Testing-orange)

This workflow provisions one or multiple Windows Server hosts. For each host it will:
* Create and deploy a new UCS server profile
* Install Windows Server operating system using Cisco-provided kickstart file


### Install Windows on FC SAN - Cisco Mode
![In Development](https://img.shields.io/badge/Status-In%20Development-red)




## Ubuntu Server
Below you can find workflows that should help with building an Ubuntu Server environment.


### Install Ubuntu on local disk - Custom Mode
![In Development](https://img.shields.io/badge/Status-In%20Development-red)


### Install Ubuntu on FC SAN - Custom Mode
![In Development](https://img.shields.io/badge/Status-In%20Development-red)
