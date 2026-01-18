# Network Traffic Monitoring Using Wireshark

## 1. Introduction
Network traffic monitoring is the process of observing and capturing data packets transmitted over a network in order to understand network behaviour and perfomance. This report documents a network traffic monitoring conducted using the Wireshark tool.

## 2. Objectives
The objectives of this network traffic monitoring analysis are :
- To capture live network traffic using Wireshark Tool
- To monitor commonly used network protocols
- To observe communication patterns within a network
- To identify normal metwork behaviour

## 3. Tool Used
Wireshark is an open-source network protocol analyser for capturing inspecting network traffic in real time. it provides detailed packet-level information and supports filtering protocol analysis

## 4. Monitoring Environment
- Opratating System : LINUX 
- Network Type : WLAN
- Network interface : WI-FI
- IP Version : IPV4
- Monitoring Duration : 15 Minutes

## 5. Monitoring Metholodology
Network traffic was monitored by launching Wireshark tool with administrative privileges and selecting the active network interface. Packet capture was capture was perfomed during normal network activity such as web browsing(Google.com) and ICMP requests.

## 6. Observations
During the monitoring period, various network protocols were observed including TCP,DNS,HTTPS and ICMP. DNS queries were frequently generated website access, and ICMP traffic dominated.

### 6.1 DNS CAPTURE
The following screenshot shows DNS protocol distribution
![DNS Capture](/home/siphesihle/Screenshots/dns_capture.png)

### 6.2 HTTP CAPTURE
The following screenshot shows HTTP protocol distribution
![HTTP Capture](/home/siphesihle/Screenshots/http_capture.png)

### 6.3 ICMP CAPTURE
The following screenshot shows ICMP protocol distribution
![ICMP Capture](/home/siphesihle/Screenshots/icmp_capture.png)


## 7. Security Observations
No suspicious or malicious traffic was observed during the monitoring period. Most traffic appeared to be normal and encrypted, indicating standard network usage.

## Conclusion
The network traffic monitoring exercise demonstrated the effectiveness of Wireshark in observing live network communication.The monitoring process provided insight into protocol usage and normal traffic patterns.
