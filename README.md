# Splunk SIEM Lab – Cross-Platform Installation & Configuration

This project documents the **end-to-end installation and configuration** of Splunk across multiple environments, designed as a **cumulative guide** for learners and professionals setting up a SIEM lab.  

## ✨ Why This Project?
When I was setting up Splunk, I noticed there wasn’t a single **comprehensive resource** that walked through the process for **different operating systems**. Most tutorials were fragmented, requiring readers to piece together steps from multiple sources.  

To solve this, I created a **step-by-step installation document** that consolidates the entire workflow — from installing Splunk Enterprise on a macOS host to configuring Splunk Universal Forwarders on both Kali Linux and Windows VMs.  

## 🔧 What’s Included
- **Splunk Enterprise (Indexer)** installation on macOS host  
- **Splunk Universal Forwarder** installation on:
  - Kali Linux VM (handling journald → rsyslog integration for proper log forwarding)  
  - Windows 10 VM (capturing Windows Event Logs)  
- **Forwarder to Indexer communication** over port `9997`  
- **Log monitoring setup** for `/var/log` (Linux) and Windows Event Logs  
- **Troubleshooting steps** for common setup challenges (e.g., journald vs rsyslog in Kali)  
- **Architecture diagram** illustrating the data flow between host and VMs  

## 📊 Skills Demonstrated
- SIEM Setup & Configuration  
- Log Management & Forwarding  
- Cross-platform Troubleshooting (Linux & Windows)  
- Splunk Administration (Indexer, Forwarder, Index setup)  
- Security Monitoring Fundamentals
  
## 🚀 Next Steps
This lab is a foundation for building more advanced **security monitoring and threat detection use cases** using Splunk. Future work will include:  
- Creating custom dashboards  
- Setting up alerts and rules for suspicious activity  
- Exploring integrations with threat intelligence feeds  
