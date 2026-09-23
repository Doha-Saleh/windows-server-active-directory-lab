# Windows Server & Active Directory Lab

## Project Overview

This project is a hands-on Windows Server administration lab built using Oracle VirtualBox and Windows Server 2022.

The goal of the project was to practice essential IT infrastructure and system administration tasks in a virtualized environment.

## Environment

* Windows Server 2022 Standard Evaluation
* Oracle VirtualBox
* 4 GB RAM allocated to the virtual machine
* Active Directory Domain Services
* Domain: `doha-lab.local`

## Tasks Completed

### 1. Active Directory

* Installed and configured Active Directory Domain Services (AD DS)
* Created the domain `doha-lab.local`
* Created an Organizational Unit (OU) named `IT-Users`
* Created a domain user: `Doha User`
* Created a Security Group: `IT-Admins`
* Added the domain user to the security group

### 2. Group Policy

* Created a Group Policy Object named `IT-Security-Policy`
* Linked the GPO to the domain
* Configured a user policy to prohibit access to Control Panel and PC settings
* Used `gpupdate` and `gpresult` to verify Group Policy application
* Tested the policy successfully

### 3. DNS

* Verified the Active Directory-integrated DNS zone
* Verified the `doha-lab.local` domain using `nslookup`
* Reviewed Active Directory DNS records

### 4. DHCP

* Installed the DHCP Server role
* Authorized the DHCP Server in Active Directory
* Verified the DHCP Server configuration

## Skills Practiced

* Windows Server Administration
* Active Directory
* User and Group Management
* Organizational Units
* Group Policy
* DNS
* DHCP
* Basic Network Administration
* Virtualization with Oracle VirtualBox
* IT Troubleshooting

## Evidence

Screenshots documenting the configuration and tests are available in the `Screenshots` folder.

## Project Outcome

This lab provided practical experience with Windows Server infrastructure, Active Directory administration, Group Policy, DNS, DHCP, and basic IT system administration.
