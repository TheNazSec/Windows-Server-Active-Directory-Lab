# Windows Server Active Directory Lab

This project is part of my hands-on learning in IT and cybersecurity.  
I built and configured a full **Active Directory Domain Services (AD DS)** environment using **Windows Server 2022** and a **Windows 10 client** in VirtualBox.  
The goal was to simulate a small business network with users, policies, and security controls—similar to a real-world IT environment.

---

## Purpose

The purpose of this project was to understand how Active Directory operates in practice—managing users, computers, and security policies from a central server.  
It also helped reinforce concepts from the **CompTIA Security+** certification by applying them in a controlled environment.

---

## Key Configurations

- Installed and configured **Active Directory Domain Services (AD DS)** and **DNS**  
- Created **Organisational Units (OUs)** and **User Accounts**  
- Applied **Group Policy Objects (GPOs)** to:  
  - Enforce password and account lockout policies  
  - Redirect user folders to the server  
  - Restrict Control Panel access for domain users  
- Enabled **auditing and logging** through Event Viewer to monitor login attempts and account changes  
- Configured **secure dynamic updates** and reviewed DNS logs  
- Troubleshot **time synchronization**, **DNS resolution**, and **network connectivity** issues

---

## Lessons Learned

- The importance of accurate **DNS configuration** and **time synchronization** in domain environments  
- How **Group Policy** enforces security and user access control  
- How to analyse **Event Viewer logs** for security auditing and issue diagnosis  
- The value of systematic troubleshooting for real-world IT environments

---

## Tools Used

- Windows Server 2022  
- Windows 10 Pro  
- Oracle VirtualBox  
- Group Policy Management Console (GPMC)  
- Event Viewer  

---

## Screenshots

**Preview: Virtual Network Diagram**

![Virtual Network Diagram](https://github.com/user-attachments/assets/49b41efa-392d-4156-a64c-4f35539d48e4)

---

## Documentation

The full project documentation, including purpose, objectives, implementation steps, and troubleshooting logs, is available below:  
[Windows Server Active Directory Lab.pdf](Documentation/Windows%20Server%20Active%20Directory%20Lab.pdf)


---

## Summary

This project provided practical experience in managing and securing a Windows Server domain.  
It helped me understand how IT administrators apply real policies, monitor system activity, and handle common issues in a business network.  
I will continue building on this foundation in my next project, which focuses on a **Help Desk Ticketing System** to simulate real support workflows.

---

**Author:** Nasir Ali  
**LinkedIn:** [www.linkedin.com/in/nasir-ali-043819349)

