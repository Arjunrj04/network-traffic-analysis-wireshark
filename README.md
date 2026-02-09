# Network Traffic Analysis and Intrusion Detection using Wireshark

## Project Overview
This project focuses on analyzing live network traffic on a Windows system using Wireshark to identify suspicious patterns and potential intrusion indicators. The goal is to simulate a basic SOC analyst workflow involving traffic monitoring, analysis, and incident reporting.

## Objectives
- Capture live network traffic on a Windows machine
- Analyze ICMP, TCP, and DNS traffic
- Detect abnormal or suspicious network behavior
- Document findings and propose mitigation steps

## Environment
- Operating System: Windows 10
- Network Interface: Wi-Fi
- Tools:
  - Wireshark
  - Npcap
  - Command Prompt

## Traffic Analysis Performed
- ICMPv6 Echo Request and Reply analysis
- Continuous ICMP traffic generation using ping
- TCP traffic analysis on port 443 (HTTPS)
- Detection of TCP retransmissions

## Findings
- High frequency ICMP echo requests observed from an internal host
- TCP retransmissions detected, indicating possible network latency or congestion
- Encrypted HTTPS traffic observed over TCP port 443

## Incident Summary
- Incident Type: ICMP Flood Simulation
- Severity: Low
- Impact: Potential network congestion
- Recommendation: Enable ICMP rate limiting and continuous traffic monitoring

## Outcome
This project demonstrates practical SOC-level skills in network traffic monitoring, packet analysis, and incident documentation using Windows-based tools.

## Future Enhancements
- DNS anomaly detection
- IDS rule-based detection
- Integration with SIEM tools
