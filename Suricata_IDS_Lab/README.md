Suricata IDS/IPS Lab

Overview
This lab explores the installation, configuration, and testing of **Suricata**, an open-source IDS/IPS engine used for network traffic inspection. It demonstrates how to detect potential threats by analyzing packets in real time.

Suricata is widely used in both enterprise and cloud environments for its performance and open architecture. This project helps build practical skills in network visibility and basic intrusion detection.

---

Environment
- **OS**: Ubuntu 22.04 LTS (Virtual Machine)
- **Interface**: Web GUI via Scirius Community Edition
- **Traffic Source**: Sample PCAP files and live traffic

---

What I Did
- Installed Suricata on a local Linux VM
- Configured rules to detect HTTP, SSH, and suspicious DNS traffic
- Integrated a basic GUI (Scirius CE) for better alert visualization
- Used sample `.pcap` files to simulate attacks (e.g., port scans, brute force)
- Captured logs and alerts in `/var/log/suricata/`

Sample Alert Output
- To include

