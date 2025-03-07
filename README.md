# **Cybersecurity Portfolio**

## **Overview**
Welcome to my cybersecurity portfolio! This repository showcases my hands-on work in cybersecurity, including my learning journey with various tools and techniques. Below, you’ll find details about the projects I’m working on, such as setting up an **Intrusion Detection System (IDS)** with **Snort**, collecting and analyzing logs with **Splunk**, and simulating attacks with **Metasploit**.

### **Tools and Technologies Used:**
- **Snort**: Open-source IDS for monitoring network traffic and detecting malicious activity.
- **Splunk**: Data aggregation and visualization tool for analyzing logs and alerts.
- **Metasploit**: Framework for penetration testing and simulating attacks.
- **Kali Linux**: A Debian-based distribution used for penetration testing.
- **VMware/Oracle VirtualBox**: Virtualization tools to create isolated environments for testing.

---

## **Lab Setup**

### **1. Virtual Machine Setup:**
I used **VMware/Oracle VirtualBox** to set up a virtualized environment for my cybersecurity lab, including:
- **Windows Desktop** and **Windows Laptop** as attack targets.
- **Snort** and **Splunk** running on a **Linux VM** for intrusion detection and log aggregation.
- **Metasploit** running on a **Kali Linux VM** to simulate attacks.

<!-- TODO: Add screenshot of my virtual machines and network setup. -->

### **2. Network Configuration:**
- **Bridged Mode**: Initially used bridged networking to allow internet access to all VMs for software installation.
- **Internal Network Mode**: Switched to internal network mode to simulate attacks in an isolated environment, ensuring no impact on external systems.

<!-- TODO: Add screenshot of network configuration settings. -->

---

## **Projects**

### **1. Setting up Snort IDS:**
I installed and configured **Snort** as an IDS to monitor network traffic for malicious activity. This includes:
- Downloading and configuring **Snort** rules.
- Testing **Snort**'s ability to detect various attack scenarios (e.g., buffer overflow, port scanning).

<!-- TODO: Add screenshot of Snort in action showing alerts triggered. -->

### **2. Splunk Log Aggregation:**
I configured **Splunk** to collect logs from **Snort**, allowing for easy analysis of detected threats. This includes:
- Parsing **Snort** alerts and visualizing them in **Splunk** dashboards.
- Creating custom reports for monitoring attack patterns.

<!-- TODO: Add screenshot of Splunk dashboard with visualized logs. -->

### **3. Simulating Attacks with Metasploit:**
Using **Metasploit**, I simulated various attacks (e.g., SQL injection, buffer overflow) to see how **Snort** detects them and how **Splunk** aggregates the logs.

<!-- TODO: Add screenshot of Metasploit in action or a simulated attack in progress. -->

---

## **Future Work:**
- Expand the lab to include more tools like **Wireshark**, **Nmap**, and **Burp Suite** for network analysis and vulnerability scanning.
- Experiment with creating automated attack detection and response workflows.
- Explore additional security measures like **firewalls**, **VPNs**, and advanced **IDS/IPS** systems.

---

## **How to Reproduce the Lab:**

### **Prerequisites:**
- Virtualization software (e.g., **VMware** or **Oracle VirtualBox**)
- Access to **Snort**, **Splunk**, **Kali Linux**, and other required software.

### **Steps:**
1. Install **VMware** or **Oracle VirtualBox** and set up virtual machines.
2. Install **Snort** and **Splunk** on a Linux-based VM.
3. Set up **Metasploit** on a **Kali Linux VM**.
4. Configure network settings for isolated testing.
5. Run simulated attacks using **Metasploit** and monitor **Snort**’s detection capabilities via **Splunk**.

---

## **License**
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
