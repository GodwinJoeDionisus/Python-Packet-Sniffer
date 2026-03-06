# Python Packet Sniffer

A simple Python-based network packet sniffer built using the Scapy library.  
This tool captures live network packets and displays useful information such as source IP, destination IP, and protocol.

---

## Project Overview

This project demonstrates how network traffic can be captured and analyzed using Python.  
Packet sniffing is an important concept in **network security and cybersecurity monitoring**.

The tool listens to network packets and prints important details about them in real time.

---

## Features

- Capture live network packets
- Display source IP address
- Display destination IP address
- Identify protocol type
- Lightweight and beginner-friendly cybersecurity project

---

## Technologies Used

- Python
- Scapy Library

---

## How It Works

The program uses the **Scapy library** to sniff packets from the network interface.

When a packet contains an **IP layer**, the script extracts:

- Source IP address
- Destination IP address
- Protocol number

The information is then displayed in the terminal.

Example output:
