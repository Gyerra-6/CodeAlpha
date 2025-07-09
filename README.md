# CodeAlpha - Basic Network Sniffer

This project is a **Basic Network Sniffer** developed as part of the **Cyber Security Internship** offered by [CodeAlpha](https://www.codealpha.tech). It allows you to capture and analyze real-time network packets using Python.

## Project Objective
The goal of this project is to:
- Understand how network data is transmitted.
- Capture live packets from the network interface.
- Analyze key packet information like:
  - Source and Destination IP addresses
  - Protocol used (TCP, UDP, ICMP, etc.)
  - Payload data

---

## Technologies Used

- Python 3.x
- [Scapy](https://scapy.readthedocs.io/en/latest/) – A powerful Python-based packet manipulation tool.

---

## Features

- Captures live network packets  
- Displays source & destination IPs  
- Identifies network protocol (TCP/UDP/ICMP)  
- Extracts and shows packet payload data  

---

## GitHub Repository Structure

CodeAlpha_NetworkSniffer/
│
├── basic_network_sniffer.py
├── README.md
└── demo.gif / screenshot.png (Optional)

---

## Installation & Setup

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/CodeAlpha_NetworkSniffer.git
   cd CodeAlpha_NetworkSniffer
   ```

---

2. **Install required package**:
    pip install scapy
   
3. **Run the sniffer with administrator/root privileges**:
    sudo python basic_network_sniffer.py

```
## How to Run
Install scapy:
pip install scapy

## Run with admin/root privileges:
sudo python basic_network_sniffer.py
```

---

## How It Works:

- Uses scapy's sniff() function to capture packets.
- Extracts key information such as IP source/destination, protocol, and payload.
- Displays each packet’s metadata in real time.

---

## Sample Output:

[+] Packet Captured
Source IP      : 192.168.1.10
Destination IP : 142.250.182.142
Protocol       : TCP
Payload        : b'E\x00\x00<\x1cF@\x00@\x06...'

---

## Developed By
**Gayathri Yerra
Cyber Security Intern – CodeAlpha**
