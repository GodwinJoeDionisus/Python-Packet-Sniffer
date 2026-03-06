\# Python Packet Sniffer



A simple Python-based network packet sniffer built using the Scapy library.  

This tool captures live network packets and displays basic information such as source IP, destination IP, and protocol.



\## Features

\- Captures live network packets

\- Displays source and destination IP addresses

\- Identifies protocol used

\- Lightweight and beginner-friendly



\## Technologies Used

\- Python

\- Scapy



\## How It Works

The program uses Scapy to sniff network traffic and analyze packets.  

When a packet contains an IP layer, the script extracts and prints the source IP, destination IP, and protocol.



\## Usage



Run the script:



python packet\_sniffer.py



Then generate traffic, for example:



ping google.com



The sniffer will display captured packets in real time.



\## Disclaimer

This project is created for \*\*educational and cybersecurity learning purposes only\*\*.  

Only monitor networks you own or have permission to analyze.

