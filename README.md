# Active-Directory-Centralized-Management
Centralized Active Directory domain implementation using Windows Server 2022
# Centralized Active Directory Management with Windows Server 2022

## Overview
This project involves deploying a centralized Active Directory (AD) domain using Windows Server 2022 to enhance IT infrastructure security, streamline user management, and enforce security policies aligned with industry standards like NIST and CIS.

## Objectives
- Centralize IT management using Active Directory.
- Enforce robust security policies for password management, account lockout, and auditing.
- Validate compliance with NIST and CIS benchmarks.

## Implementation Steps
1. **Setup Active Directory**:
   - Installed Windows Server 2022 and configured it as a domain controller.
   - Created the `ad.local` domain for centralized user and resource management.
2. **Organizational Units and Groups**:
   - Defined `Executives` and `Research` OUs for role-specific management.
   - Created user groups with tailored permissions.
3. **User and Client Configuration**:
   - Created user accounts and joined Windows 10 clients to the domain.
   - Tested user login functionality.
4. **Security Policies**:
   - Implemented password policies, account lockout thresholds, and login hours.
   - Enabled audit logging to monitor activities.
5. **Validation**:
   - Verified policy enforcement using RSoP and Event Viewer.
   - Ensured compliance with NIST and CIS standards.

## Outcomes
- Simplified IT operations through centralized management.
- Enhanced security posture with robust policies and compliance validation.
- Improved user experience with streamlined administration.

## Skills Demonstrated
- Active Directory configuration and management.
- Group Policy enforcement.
- Compliance with NIST and CIS standards.
- System validation using RSoP and Event Viewer.
