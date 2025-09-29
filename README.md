## Wireshark Packet Analysis Report

## Project Overview
This project demonstrates basic hands-on network traffic analysis using Wireshark. The aim is to capture live packets on the local network, identify three or more key protocols, and summarize the packet details for educational and protocol awareness purposes.

Repository Contents
analyzing_network_traffic.pcap
The main Wireshark packet capture showing live network traffic.

# screenshots/
Folder containing screenshots of protocol filtering and packet analysis:

screenshot_quic.jpg – QUIC protocol details
screenshot_tcp.jpg – TCP protocol details
screenshot_dns.jpg – DNS protocol details
screenshot_http.jpg – HTTP protocol details

## Key Steps Performed
Installed Wireshark and initiated capture on the chosen interface[task5.jpg].

Simulated network traffic by browsing websites and pinging servers.

Filtered and analyzed captured packets by protocol:

QUIC: Modern encrypted transport protocol

TCP: Reliable connection establishment and payload transfer

DNS: Domain resolution queries to web servers

HTTP: Application layer GET/POST transactions

Saved the packet capture as a .pcap file and documented findings in the report.

## Main Findings
QUIC protocol is heavily used for encrypted web traffic, especially by Google-based services.

TCP protocol forms the basis for reliable data delivery, seen in handshake and acknowledgment sequences.

DNS queries enable translation from website names to IP addresses, vital for traffic routing.

HTTP requests show typical web browsing interactions, including GET/POST operations and content retrieval.

## How to Use
Open the .pcap file with Wireshark.

Use display filters (e.g., quic, tcp, dns, http) to view specific protocol packets.

Refer to the included screenshots for reference and guidance.

Read the report.md for a summary and interpretation of captured network activity.
