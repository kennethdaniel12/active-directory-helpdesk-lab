# Active Directory Help Desk Lab

A hands-on IT support lab designed to simulate common Tier 1 Help Desk tasks in a Windows Active Directory environment hosted in AWS.

## Overview

I built and administered a Windows Active Directory environment in AWS to develop practical IT support skills.

The lab is used to simulate common Help Desk scenarios including:

* User account management
* Password resets
* Account lockouts
* Security group management
* Organizational Units (OUs)
* Computer/domain management
* Permissions
* Troubleshooting
* Help Desk ticket documentation

The goal of this project is to demonstrate practical troubleshooting and system administration skills relevant to an entry-level IT Support or Help Desk position.

## Environment

| Component             | Technology                       |
| --------------------- | -------------------------------- |
| Cloud Platform        | AWS EC2                          |
| Server                | Windows Server                   |
| Directory Services    | Active Directory Domain Services |
| DNS                   | Windows DNS                      |
| Client                | Windows                          |
| Remote Administration | RDP                              |
| Documentation         | GitHub / Markdown                |

## Skills Demonstrated

### Active Directory

* Creating and managing user accounts
* Resetting passwords
* Unlocking accounts
* Enabling and disabling accounts
* Creating and managing security groups
* Managing group membership
* Managing Organizational Units
* Managing computer objects
* Joining computers to a domain

### Windows Administration

* Windows Server administration
* Windows client administration
* Remote Desktop Protocol (RDP)
* Domain management
* DNS configuration
* Basic permissions management

### Help Desk

* Ticket-based troubleshooting
* User account troubleshooting
* Access requests
* Employee onboarding
* Employee offboarding
* Troubleshooting methodology
* Resolution documentation
* Verification of completed work

### AWS

* EC2
* Security Groups
* Cloud-hosted Windows infrastructure
* Remote administration

## Help Desk Scenarios

This project contains simulated support tickets based on common Tier 1 IT support requests.

| Ticket | Scenario             | Skills Demonstrated                           |
| ------ | -------------------- | --------------------------------------------- |
| 001    | New User Account     | User creation, OU placement, group membership |
| 002    | Password Reset       | Password management                           |
| 003    | Locked Account       | Account troubleshooting                       |
| 004    | Shared Folder Access | Groups and permissions                        |
| 005    | Employee Offboarding | Account disablement                           |
| 006    | Domain Join          | Windows and domain administration             |
| 007    | Department Transfer  | User and group management                     |
| 008    | Disabled Account     | Troubleshooting and account management        |

## Troubleshooting Approach

For each support scenario, I follow a structured troubleshooting process:

1. Identify the problem
2. Gather relevant information
3. Check the most likely causes
4. Determine the appropriate resolution
5. Implement the change
6. Verify the solution
7. Document the resolution

## Project Documentation

Detailed documentation, screenshots, and troubleshooting steps for each scenario are organized throughout this repository.

### Documentation

* [User Management](documentation/user-management.md)
* [Group Management](documentation/group-management.md)
* [Computer Management](documentation/computer-management.md)
* [Permissions](documentation/permissions.md)
* [Troubleshooting](documentation/troubleshooting.md)

### Help Desk Tickets

* [Ticket 001 — New User Account](tickets/001-new-user.md)
* [Ticket 002 — Password Reset](tickets/002-password-reset.md)
* [Ticket 003 — Locked Account](tickets/003-locked-account.md)
* [Ticket 004 — Shared Folder Access](tickets/004-access-request.md)
* [Ticket 005 — Employee Offboarding](tickets/005-employee-offboarding.md)
* [Ticket 006 — Domain Join](tickets/006-domain-join.md)
* [Ticket 007 — Department Transfer](tickets/007-department-transfer.md)
* [Ticket 008 — Disabled Account](tickets/008-disabled-account.md)

## Project Goal

The goal of this project is to demonstrate the ability to perform, troubleshoot, verify, and document common tasks associated with an entry-level IT Help Desk role.

This is a self-directed lab environment created for hands-on learning and portfolio development.
