Suricata IDS/IPS Lab

This lab explores the installation, configuration, and testing of **Suricata**, an open-source IDS/IPS engine used for network traffic inspection. It demonstrates how to detect potential threats by analyzing packets in real time.

System Details
- Virtualization: Hyper-V
- OS:Kali GNU/Linux 2025.2
- Suricata Version: Kali GNU/Linux 2025.2

What I Did [to edit]
- Installed and Configured Suricata on a local Linux VM
- Configured custom rules to detect ICMP, HTTP, SSH, and suspicious DNS traffic
- Integrated a basic GUI (Scirius CE) for better alert visualization
- Used sample `.pcap` files to simulate attacks (e.g., port scans, brute force)
- Captured logs and alerts in `/var/log/suricata/`

