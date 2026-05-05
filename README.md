# Basic Network Sniffer (CodeAlpha Internship Project)

## 📌 Project Description
This project is a basic network packet sniffer built using Python and Scapy.  
It captures live network traffic and displays important information such as source IP, destination IP, protocol type, and packet payload.

---

## ⚙️ Features
- Captures live network packets
- Displays Source IP and Destination IP
- Identifies protocols (TCP, UDP, ICMP)
- Extracts and displays packet payload
- Handles unreadable data using HEX format

---

## 🧰 Technologies Used
- Python
- Scapy library

---

## 🚀 How It Works
The program listens to network traffic in real-time and processes each packet:
1. Captures packets using Scapy sniff function
2. Extracts IP layer information
3. Identifies protocol type
4. Displays payload (decoded or HEX format if unreadable)

---

## 🖥️ How to Run

### 1. Install Scapy
```bash
pip install scapy

## 📚 Learning Outcomes

- Understanding how network packets flow  
- Basics of TCP/IP protocol structure  
- Real-time packet capturing using Python  
- Handling binary and encrypted network data  