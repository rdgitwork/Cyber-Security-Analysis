# Penetration Testing Project: CyberHowl Security

This repository contains the penetration testing report for CyberHowl Security's final project, conducted as part of the INFO2231 - Advanced Computer Security course. The project focuses on identifying and exploiting vulnerabilities in different virtual environments using ethical hacking techniques.

## Table of Contents
- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Machines Tested](#machines-tested)
- [Attack Methodologies](#attack-methodologies)
- [Results](#results)
- [Conclusion](#conclusion)
- [Screenshots](#screenshots)

## Introduction
This project was designed to enhance the understanding of penetration testing and ethical hacking. Our team, CyberHowl Security, set up virtual machines with known vulnerabilities and used Kali Linux and other penetration testing tools to exploit these weaknesses.

The report includes detailed descriptions of the vulnerabilities found and the actions taken to exploit them. The three machines targeted for exploitation were:
1. A Windows 10 environment.
2. A DVWA web application hosted on Ubuntu Linux.
3. A scenario exploiting human error via social engineering.

## Environment Setup

### Virtual Machines
- **Windows 10**: Vulnerabilities created by disabling security features such as Windows Defender and the firewall.
- **DVWA (Damn Vulnerable Web Application)**: A vulnerable web application hosted on an Ubuntu Linux machine.
- **Social Engineering Environment**: Simulated phishing attacks on users.

### Tools Used
- **Kali Linux**: Used for reconnaissance, scanning, exploitation, and post-exploitation.
- **Nmap**: Network scanning and vulnerability identification.
- **Metasploit Framework**: Exploitation of discovered vulnerabilities.
- **VirtualBox**: Hosting and managing all virtual environments.

## Machines Tested

1. **Machine 1: Windows 10**
   - Vulnerabilities: Outdated software, weak authentication mechanisms, and disabled security features.
   
2. **Machine 2: DVWA (Ubuntu Linux)**
   - Vulnerabilities: Cross-Site Scripting (XSS), SQL Injection, and Broken Authentication.

3. **Machine 3: Social Engineering (Unprotected Network)**
   - Attack simulated by crafting phishing websites to deceive users and harvest credentials.

## Attack Methodologies

- **Reconnaissance and Scanning**: Conducted using Nmap to gather network data, including open ports and services.
- **Exploitation**: Performed using Metasploit and other tools to gain unauthorized access.
- **Social Engineering**: Deployed phishing attacks through crafted web pages resembling legitimate services to obtain user credentials.

### Example Attack: Reverse TCP Injection on Windows
- A reverse TCP payload was injected into the Windows 10 machine, allowing us to establish a remote connection and gain control over the target system.

## Results

- **Windows Machine**: Successfully exploited weak security settings and gained access through reverse TCP injection.
- **DVWA Web Application**: SQL Injection and XSS vulnerabilities were successfully exploited.
- **Social Engineering Attack**: Users were tricked into providing credentials on a fake phishing page, demonstrating the vulnerability of human error.

## Conclusion
This project illustrates the importance of securing systems against various forms of attack, from technical exploits to social engineering. To mitigate these vulnerabilities, organizations must implement updated software patches, strict authentication mechanisms, and user training programs to ensure cybersecurity awareness.

## Screenshots

### 1. Virtual Environment Setup
![Virtual Setup]
(![image](https://github.com/user-attachments/assets/89245ce3-1faf-485f-9c2f-ac9055fe17e0)
)

### 2. Nmap Network Scan
![Nmap Scan]
(![image](https://github.com/user-attachments/assets/e82c4fb0-f0b0-4dbe-b9f6-f4990fbd851e)
)

### 3. Reverse TCP Injection
![TCP Injection](![image](https://github.com/user-attachments/assets/924d4b1a-9e8c-46e0-8006-0e00ff376cda)
)

### 4. Phishing Attack
![Phishing Attack]
(![image](https://github.com/user-attachments/assets/5f73b587-f1c6-41ac-bdd3-d84d66358ac1)
)

## Team Members
- **Hitarth Brijeshbhai Patel**: hpatel7905@conestogac.on.ca
- **Rudrakumar Patel**: rpatel2703@conestogac.on.ca
- **Shivang Chordia**: schordia1092@conestogac.on.ca
- **Divya Patel**: dpatel0488@conestogac.on.ca
- **Vansh Prajapati**: vprajapati8319@conestogac.on.ca
- **Deep Patel**: dpatel7589@conestogac.on.ca

## License
This project is for educational purposes only and should not be used for malicious activities.

---

You can adjust the screenshots and team details if necessary. Simply upload the images to the repository and update the links for the screenshots. Let me know if you need further modifications!
