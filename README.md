# Active Directory Lab
## Overview
Built a Windows Server 2022 Active Directory lab environment in Microsoft Azure to gain hands-on experience with identity management, DNS, Group Policy, and Windows Server administration.
## Environment
| Component     | Details       |
| ------------- | ------------- |
| Cloud Platform  | Azure  |
| Operating System |	Windows Server 2022 |
| Domain|	corp.local|
|Domain Controller|	winlab01|
|Services|	Active Directory Domain Services (AD DS), DNS|

## Objectives
* Deploy Active Directory Domain Services
* Configure Active Directory-integrated DNS
* Create Organizational Units (OUs)
* Create and manage users and security groups
* Implement Group Policy
* Simulate an enterprise identity management environment

## Active Directory Configuration
### Organizational Units
Created the following OUs:
* IT
* HR
* Finance

### User Accounts

Created user accounts for each department and organized them within their respective OUs.

### Security Groups

Created and assigned users to the following groups:

* IT-Admins
* HR-Users
* Finance-Users

## DNS Configuration

Verified Active Directory-integrated DNS functionality.
Validated domain controller registration and service records using:
```
nslookup
set type=SRV
_ldap._tcp.dc._msdcs.corp.local
```

Confirmed successful DNS resolution for the domain controller and LDAP services.

## Group Policy

Implemented a domain password policy to enforce stronger authentication requirements.

Configuration included:

* Password complexity enabled
* Minimum password length of 12 characters

## Skills Demonstrated:

* Active Directory Domain Services (AD DS)
* DNS Administration
* User and Group Management
* Group Policy Management
* Identity and Access Management (IAM)
* Windows Server 2022 Administration
* Azure Virtual Machines
* Troubleshooting and Validation
## Lessons Learned
* Active Directory relies heavily on DNS for service discovery and authentication.
* Organizational Units provide a logical structure for managing users and resources.
* Security groups simplify access management and role-based administration.
* Group Policy enables centralized configuration and enforcement of security settings.
## Screenshots
* Server Manager
* Active Directory Users and Computers
* DNS Manager
* Organizational Unit Structure
* Security Groups
* Group Policy Management
