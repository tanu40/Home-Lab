# 🔐 Cybersecurity Home Lab – VirtualBox (Internal Network Setup)

## 📌 Project Overview

This project demonstrates the setup of a personal cybersecurity home lab using Oracle VM VirtualBox on a Windows host machine.

The lab environment consists of:

- 🐉 Kali Linux (Attacker Machine)
- 🖥 Windows 10 (Target Machine)

Both virtual machines are connected using an **Internal Network** configuration inside VirtualBox, creating a completely isolated virtual environment. This setup allows safe security testing, malware analysis, and attack simulations without exposing the host machine or external network.

---

## 🏗 Lab Architecture

Host Machine:
- Windows OS
- Oracle VM VirtualBox (Hypervisor)

Virtual Machines:
- Kali Linux – Used for penetration testing and offensive security practices
- Windows 10 – Used as a target system for testing and analysis

Network Configuration:
- Adapter Type: Internal Network
- Network Name: (Example: intnet-lab)
- Both VMs connected to the same internal virtual switch
- No internet access inside the lab (Fully isolated environment)

This creates a **private virtual LAN** that exists only inside VirtualBox.

---

## 🌐 Network Setup Details

- Both VMs assigned IP addresses within the same subnet
- Example:
  - Kali Linux: 192.168.100.10
  - Windows 10: 192.168.100.20
  - Subnet Mask: 255.255.255.0

Connectivity verified using:
- ping
- ipconfig / ifconfig
- arp
- netstat

This confirms both machines can see and communicate with each other within the isolated lab network.

---

## 🎯 Objectives

- Build a safe and controlled cybersecurity testing lab
- Practice penetration testing techniques
- Perform network reconnaissance
- Conduct vulnerability scanning
- Simulate attack scenarios
- Analyze malware safely
- Strengthen SOC and Blue Team skills

---

## 🛠 Tools & Technologies Used

- Oracle VM VirtualBox
- Kali Linux
- Windows 10
- Nmap
- Metasploit
- Wireshark
- Netcat

---

## 🔎 Security Activities Performed

- Network scanning and enumeration
- Port scanning
- Service identification
- Exploitation testing
- Packet capture and traffic analysis
- Malware execution in isolated VM
- Basic incident investigation simulation

---

## 🔒 Why Internal Network?

Using Internal Network ensures:
- Complete isolation from the host system
- No exposure to external networks
- Safe malware testing environment
- Controlled attack simulations

This setup prevents accidental spread of malicious files outside the lab.

---

## 📸 Screenshots

(Add screenshots here)
- VirtualBox network settings
- IP configuration of both VMs
- Successful ping test
- Nmap scan results
- Exploitation results

---

## ⚠️ Disclaimer

This lab environment is built strictly for educational and ethical cybersecurity practice.

All testing is performed inside an isolated internal virtual network.

Do NOT conduct unauthorized testing on real-world systems.

---

## Author

Tanushka Kumbhar

Aspiring SOC Analyst 
