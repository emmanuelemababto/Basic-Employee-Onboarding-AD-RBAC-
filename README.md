# Basic-Employee-Onboarding-AD-RBAC-
"Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution.
# Basic Employee Onboarding (AD & RBAC)
### Northstar Medical Group | Identity & Access Management Lab

## Problem Statement

Northstar Medical Group had poorly managed Active Directory accounts due to mismanagement by its previous Managed Service Provider (MSP). The system lacked proper organization, and employees were sometimes assigned to the wrong departments or security groups. Manual user onboarding increased the risk of human errors and incorrect access permissions. These problems created potential HIPAA compliance risks because employees could gain unauthorized access to sensitive healthcare information.

## Solution Overview

I built a new Active Directory environment using Windows Server and created the NMG.com domain. I designed four Organizational Units (OUs) for Finance, HR, IT, and Operations to organize employee accounts. I created security groups for each department and implemented a flat Role-Based Access Control (RBAC) model to assign permissions based on job responsibilities. I provisioned 15 employee accounts and assigned them to their respective departments and security groups. This structure standardized employee onboarding, improved access management, and reduced the risk of unauthorized access. I also documented the configuration and troubleshooting steps to support future account management.

## Video Walkthrough

Video demonstration: Coming Soon – Link Will Be Added


## Tools Used

- Windows Server
- Active Directory Domain Services (AD DS)
- VirtualBox
- UTM
- Role-Based Access Control (RBAC)
- GitHub

## Project Timeline

- Day 1: Created the NMG.com domain and promoted NDG-DC01 to a domain controller.
- Day 2: Created four departmental OUs and security groups.
- Day 3: Provisioned 15 employee accounts and implemented RBAC.
- Day 4: Investigated and resolved Ticket NMG-0047 by correcting Jane Cooper's department and security group assignment.
- Day 5: Documented the lab, organized screenshots, and prepared the GitHub case study.

## Key Accomplishments

- Built the NMG.com Active Directory domain from scratch using Windows Server and AD DS.
- Organized 15 user accounts across four departments using OUs and security groups to implement RBAC.
- Resolved Ticket NMG-0047 by correcting an employee's access permissions and documenting the root cause and resolution.

## Security Impact

The new Active Directory structure improved user account organization and access management. Department-based security groups helped reduce the risk of employees receiving permissions outside their job responsibilities. The project also demonstrated HIPAA-aligned access control practices for protecting electronic protected health information (ePHI).

## Lessons Learned

I learned how to configure Active Directory, create user accounts, manage security groups, and apply RBAC. I also gained experience troubleshooting incorrect user permissions and documenting IT incidents. This project showed me how proper identity management can improve both security and employee productivity.
