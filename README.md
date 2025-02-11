# VMWare_Virtual_Home_Lab
A comprehensive guide to setting up a VMware Virtual Home Lab using VMware ESXi. This lab offers hands-on experience in:  
* Active Directory (AD), DNS, and DHCP using Windows Server 2019  Network Segmentation &amp; 
* Security with pfSense  Intrusion Detection &amp;
* Log Management using Security Onion  Virtualization &amp;
* System Administration using VMware ESXi

Introduction:
This project is a VMware Virtual Home Lab designed to simulate an enterprise IT environment for learning and experimentation. It provides hands-on experience with Active Directory (AD), DNS, DHCP, Firewall Security, and Intrusion Detection Systems (IDS) using virtualized infrastructure.

Features & Components:
The lab runs on VMware ESXi and includes multiple virtual machines (VMs) with essential network services:

1. VMware ESXi – The Virtualization Platform
* Enterprise-grade Type-1 hypervisor for running multiple VMs.
* Used to simulate real-world IT environments efficiently.
* Supports vSphere for VM management and automation.

2. Windows Server 2019 – Active Directory & DNS/DHCP
* Acts as the Domain Controller (DC) for centralized user authentication.
* Active Directory (AD): Manages users, computers, and security policies.
* DNS (Domain Name System): Resolves hostnames within the network.
* DHCP (Dynamic Host Configuration Protocol): Assigns IP addresses dynamically to devices.

3. pfSense – Firewall & Network Segmentation
* Open-source firewall used for network security and traffic control.
* Manages network segmentation using VLANs.
* Implements firewall rules, VPN, and threat protection.
* Provides Secure Remote Access.

4. Security Onion – Intrusion Detection & Log Management
* A powerful Intrusion Detection System (IDS) and Network Security Monitoring (NSM) solution.
* Includes tools such as:
    * Suricata / Zeek (Bro): Network-based IDS.
    * Elasticsearch, Logstash, Kibana (ELK Stack): Log aggregation and analysis.
    * Cybersecurity dashboards for monitoring threats and analyzing logs.
 
System Requirements:
To run this home lab, the following hardware is recommended:
* Processor: Multi-core CPU with virtualization support (Intel VT-x / AMD-V).
* RAM: Minimum 32GB (recommended for running multiple VMs smoothly).
* Storage: SSD or NVMe drive for faster VM performance.
* Network: NIC with multiple ports for VLAN segmentation.

Installation & Setup Guide:
1. Install VMware ESXi
* Download VMware ESXi and install it on a physical server.
* Configure networking and storage settings for VMs.
2. Create Virtual Machines (VMs)
* Set up a Windows Server 2019 VM and configure Active Directory, DNS, and DHCP.
* Deploy a pfSense VM and configure firewall rules and VLANs.
* Install Security Onion and set up network monitoring and IDS.
3. Network Configuration
* Define subnets and VLANs for segmentation.
* Set up firewall rules in pfSense for security control.
4. Security Monitoring & Log Analysis
* Enable Security Onion IDS rules to detect threats.
* Use Kibana dashboards to analyze logs and alerts.

Use Cases
* System Administration: Learn Active Directory, DNS, DHCP, and user management.
* Networking & Security: Configure firewalls, VLANs, and intrusion detection.
* Cybersecurity Training: Analyze real-time network traffic and logs.
* Testing Virtualization & Automation: Experiment with VMware snapshots and scripting.

Conclusion
This VMware Virtual Home Lab provides an enterprise-like environment to gain hands-on experience in networking, security, and system administration. It is an ideal setup for IT professionals, cybersecurity learners, and system administrators.

