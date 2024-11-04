# Active Directory Installation on Windows Server 🖥️

<div align="center">

[![Windows Server](https://img.shields.io/badge/Windows_Server-2019-blue.svg)](https://www.microsoft.com/en-us/windows-server)
[![Active Directory](https://img.shields.io/badge/Active_Directory-Installation-green.svg)](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/active-directory-domain-services)

*A step-by-step guide for installing and configuring Active Directory on Windows Server*

</div>

## 📑 Table of Contents
- [Introduction](#-introduction)
- [Basic Concepts](#-basic-concepts)
- [Installation Steps](#-installation-steps)
- [Configuration](#-configuration)
- [Testing](#-testing)

## 📖 Introduction

This project demonstrates the implementation of Active Directory on Windows Server, providing centralized network resource management and user authentication services.

## 🌟 Basic Concepts

### Directory Service
A directory service stores, organizes and provides access to information in a computer operating system's directory.

### Active Directory
- Microsoft's directory service for Windows domain networks
- Provides authentication and authorization
- Manages and stores information about network resources

### Why Active Directory?
- Centralized resource administration
- Enhanced security management
- Simplified user management
- Group policy implementation
- Scalable directory services

## 🛠️ Installation Steps

### 1. Windows Server Installation
1. Boot from Windows Server installation media
2. Select installation preferences:
   - Language
   - Time format
   - Keyboard layout
3. Choose installation type:
   - Windows Server Standard
   - GUI installation

### 2. Active Directory Creation
1. Open Server Manager
2. Add roles and features
3. Select "Active Directory Domain Services"
4. Install required features
5. Complete installation wizard

### 3. Domain Controller Promotion
1. Promote server to domain controller
2. Configure domain settings:
   - Domain name
   - Forest level
   - Domain level
3. Set Directory Services Restore Mode (DSRM) password
4. Complete promotion process

## ⚙️ Configuration

### Create AD Users
1. Open Active Directory Users and Computers
2. Navigate to Users container
3. Create new user:
   - Username
   - Password
   - User properties

### Configure Roaming Profiles
1. Create profiles share
2. Set permissions
3. Configure user profile path
4. Test profile roaming

### Join Computer to Domain
1. Access system properties
2. Change computer domain
3. Provide domain credentials
4. Restart computer

## 🧪 Testing

### User Authentication Test
1. Log in with domain credentials
2. Verify access permissions
3. Check profile roaming

### Domain Services Test
1. Verify DNS resolution
2. Test network resources access
3. Validate group policies

## 📝 Documentation

### Active Directory Services
- Domain Services
- Certificate Services
- Federation Services
- Rights Management

### Benefits
- Centralized Management
- Enhanced Security
- Scalability
- Policy Implementation

## 🔒 Security Considerations

- Regular backups
- Strong password policies
- Audit logging
- Access control
- Regular updates

## ❗ Important Notes

- Ensure proper network configuration
- Back up server before installation
- Document all configuration changes
- Follow security best practices
- Regular maintenance required

## 🔍 Troubleshooting

Common issues and solutions:
- Login problems
- DNS issues
- Replication errors
- Group policy problems

## 📚 References

- [Microsoft Documentation](https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/active-directory-domain-services)
- [Windows Server Guide](https://docs.microsoft.com/en-us/windows-server/)
- [Active Directory Best Practices](https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/best-practices-for-securing-active-directory)

---

<div align="center">
  Created as part of Windows Server Administration Project
</div>
