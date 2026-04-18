# 🌐 Network Traffic Analysis using tcpdump & tshark

## 🚀 Overview
This project demonstrates hands-on network traffic capture and analysis using **tcpdump** and **tshark** on macOS.  
It focuses on understanding packet-level data, analyzing encrypted traffic, and interpreting network behavior.

---

## 🎯 Objectives
- Identify network interfaces  
- Capture live network traffic  
- Save packet captures (.pcap files)  
- Analyze traffic using tcpdump and tshark  
- Interpret protocols and packet-level details  
- Follow safe and ethical practices  

---

## 🛠 Environment
- macOS (MacBook Pro M4 Pro)  
- Terminal: zsh  
- Tools:
  - tcpdump  
  - tshark (Wireshark CLI)  
  - Homebrew  

---

## ⚙️ Commands Used

```bash
ifconfig -a
tcpdump -D
sudo tcpdump -i en0 -c 100 -w capture.pcap
sudo tcpdump -i en0 -w capture.pcap
tcpdump -r capture.pcap -n
