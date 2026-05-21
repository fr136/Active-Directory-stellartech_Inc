# Active Directory Enterprise Lab

## Overview

Deployment of a secured Active Directory infrastructure simulating a small enterprise environment under Windows Server and GNS3.

## Objectives

- Centralized identity management
- AGDLP implementation
- NTFS permissions management
- Group Policy deployment
- Redundancy with multiple Domain Controllers
- Secure access management

## Infrastructure

- DC1 : Primary Domain Controller
- DC2 : Secondary Domain Controller + Global Catalog
- SRV1 : File Server
- NAT + Layer 2 Switch

## Technologies

- Windows Server 2022
- Active Directory
- DNS
- GPO
- NTFS
- AGDLP
- GNS3## Active Directory Security & Monitoring

## Active Directory Security & Monitoring

This lab evolved beyond a standard Active Directory deployment into a security-oriented enterprise infrastructure simulation focused on Windows administration, identity management and Active Directory security concepts.

The environment was designed to reproduce a small enterprise infrastructure under Windows Server within GNS3, including centralized authentication, access control, network services and security policy management.

### Infrastructure Overview

The infrastructure includes:

- Multiple Domain Controllers for redundancy and resiliency
- Centralized DNS management
- Dedicated file server with secured shared resources
- Organizational Units (OU) for departmental segregation
- Group-based access control using the AGDLP model
- Group Policy Objects (GPO) for centralized administration
- Simulated enterprise network topology under GNS3

### Active Directory Administration

Implemented Active Directory administration tasks include:

- Domain deployment and configuration
- Organizational Unit design
- User and group management
- AGDLP permission model implementation
- Centralized authentication management
- Domain Controller redundancy configuration
- Security policy deployment through GPO
- Shared resource management with NTFS permissions

### Security Policies & Hardening

Several security-oriented GPOs were deployed in order to simulate enterprise hardening practices:

- Password complexity and account lockout policies
- Restriction of Control Panel access
- Registry editing restrictions
- Command Prompt restrictions
- Centralized desktop policy deployment
- Network drive mapping through Group Policy Preferences (GPP)

### File Server Security

The file server infrastructure was configured using role-based access control principles.

Each department was assigned:
- Dedicated shared folders
- Dedicated domain local groups
- Restricted NTFS permissions
- Controlled access through Active Directory groups

This configuration simulates real-world enterprise access segmentation and least privilege enforcement.

### Active Directory Security Concepts

The project also integrates multiple Active Directory attack and defense concepts commonly encountered in enterprise environments and SOC operations.

Studied concepts include:

- NTLM authentication
- Kerberos authentication
- LLMNR poisoning
- NTLM relay attacks
- Pass-the-Hash techniques
- Kerberoasting
- Active Directory misconfigurations
- Authentication abuse scenarios
- Windows event monitoring
- Security event detection concepts

### Monitoring & Detection

The lab environment was designed to support future security monitoring integration, including:

- Windows Event Log analysis
- Detection engineering concepts
- SIEM integration workflows
- Security monitoring methodologies
- Threat detection fundamentals
- Incident analysis workflows

### Skills Demonstrated

- Active Directory Administration
- Windows Server Administration
- Group Policy Management
- AGDLP Access Control
- NTFS Permissions Management
- Enterprise Infrastructure Design
- DNS Administration
- Identity & Access Management
- Security Hardening
- Threat Detection Fundamentals
- Security Monitoring Concepts
- Enterprise Documentation
- Network Segmentation Concepts

## Future Improvements

Planned future improvements include:

- Wazuh SIEM integration
- Sysmon deployment
- Advanced Windows logging
- Security alert correlation
- Active Directory hardening
- Detection rule creation
- Attack simulation & monitoring
- SOC-oriented incident scenarios

## Screenshots

### GNS3 Topology



### Active Directory Structure

share-permissions-engineering

### Group Policy Management

