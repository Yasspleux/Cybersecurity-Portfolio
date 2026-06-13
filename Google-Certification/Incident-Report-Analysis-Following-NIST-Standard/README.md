# Incident Report Analysis following NIST Standard

## 📝 Scenario Overview
As a cybersecurity analyst for a multimedia company (providing web design, graphic design, and social media marketing), I was tasked with investigating and responding to a recent Denial of Service (DoS) attack. The organization's internal network was compromised for two hours due to an incoming flood of ICMP packets, halting normal internal network traffic and access to resources.

## 🔍 Incident Investigation
The investigation revealed that a malicious actor exploited an unconfigured firewall to send a flood of ICMP pings, overwhelming the network. 

To mitigate the attack, the incident management team:
* Blocked incoming ICMP packets.
* Took all non-critical network services offline.
* Restored critical network services.

## 🛡️ Network Hardening & Resolution
Following the event, the network security team implemented several preventative measures:
* **Firewall Configuration:** Added a new rule to limit the rate of incoming ICMP packets.
* **IP Spoofing Prevention:** Enabled source IP address verification on the firewall.
* **Traffic Monitoring:** Deployed network monitoring software to detect abnormal patterns.
* **Intrusion Detection/Prevention:** Implemented an IDS/IPS system to filter suspicious ICMP traffic.

## 🎯 Project Objective
The objective of this project is to analyze the security event and develop a comprehensive plan to improve the company's network security posture using the **National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF)**. The analysis covers the five core functions:
1. **Identify:** Audit internal networks, systems, devices, and access privileges.
2. **Protect:** Implement policies, procedures, and tools to mitigate threats.
3. **Detect:** Improve monitoring capabilities for faster incident detection.
4. **Respond:** Contain, neutralize, and analyze incidents while improving processes.
5. **Recover:** Restore affected systems and data to normal operation.
