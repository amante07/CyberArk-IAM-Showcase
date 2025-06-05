# CyberArk-IAM-Showcase

This lab project demonstrates a robust enterprise-grade Identity and Access Management (IAM) solution using **CyberArk Privileged Access Management (PAM)** integrated with **Active Directory (AD)**. The goal is to showcase the secure management of privileged accounts, automation of credential rotation, and enforcement of least privilege principles in a simulated corporate environment.

---

## Project Highlights

- **Active Directory Setup**  
  Deployed a Windows Server as a Domain Controller for the `securelab.local` domain, created Organizational Units (OUs), and provisioned user accounts with secure password policies.

- **User and Role Management**  
  Segregated users into OUs such as Admins and HelpDesk, enforcing role-based access control.

- **CyberArk Vault Installation & Integration** (Planned)  
  Prepare for installation and configuration of CyberArk Vault server integrated with AD for centralized privileged account management.

- **PowerShell Automation**  
  Used PowerShell scripts for AD user creation, OU management, and GPO enforcement to automate repetitive administrative tasks.

- **Security Best Practices**  
  Enforced password complexity, account lockout policies, and laid groundwork for least privilege delegation.

---

## Project Status

- Phase 1: Active Directory infrastructure and user provisioning — **Completed**  
- Phase 2: CyberArk Vault installation and AD integration — **In Progress**  
- Phase 3: Automation of password rotation and access workflows — **Upcoming**  
- Phase 4: Reporting, auditing, and security enhancement — **Upcoming**

---

## How to Use This Repository

This repo contains PowerShell scripts and configuration instructions to replicate the AD environment and CyberArk integration steps. It is designed for security professionals and system administrators looking to learn or demonstrate CyberArk PAM deployment in a Windows Server environment.

---

## Skills Demonstrated

- Active Directory domain controller setup and management  
- OU and user provisioning with PowerShell  
- CyberArk PAM concepts and planned implementation  
- Security best practices in enterprise IAM  
- Automation with scripting for efficiency and accuracy  

---

## Next Steps & Contributions

- Complete CyberArk Vault deployment and integration scripts  
- Add detailed guides for CyberArk Safe creation and privileged account management  
- Develop automated workflows for access requests and password rotations  
- Expand documentation with diagrams and troubleshooting tips  

---

## Contact / Feedback

Feel free to reach out with questions or suggestions. Contributions and collaboration are welcome to further enhance this lab environment.

---
