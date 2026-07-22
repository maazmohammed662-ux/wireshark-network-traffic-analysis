# wireshark-network-traffic-analysis
Network traffic analysis project using Wireshark — captured live packets, analyzed TCP/UDP/QUIC protocols, and used filters to inspect conversations and packet-level data.

# Network Traffic Analysis using Wireshark

## Project Overview
This project shows how I used Wireshark to capture and analyze live network traffic on my system. I looked at different types of traffic (TCP, UDP, QUIC), examined conversations between my system and various destinations, applied filters to isolate specific traffic, and inspected individual packets in detail.

## What I Did
- Captured live Wi-Fi network traffic using Wireshark
- Analyzed different protocols including TCP, UDP, TLS, and QUIC
- Used the Conversations tool to view traffic exchanged between my device and multiple destination IPs
- Broke down traffic by protocol type (Ethernet, IPv4, IPv6, TCP, UDP) to see packet counts, bytes transferred, and connection duration
- Applied custom display filters (like filtering by IP address and by port) to isolate specific traffic
- Inspected individual packets down to the byte level, including packet headers and payload data
- Reviewed Wireshark's coloring rules to understand how different traffic types are visually categorized

## Tools Used
- Wireshark (packet capture and analysis)

## Key Observations
- Identified the top destination IPs my system communicated with, along with total bytes sent and received
- Found that most traffic was encrypted (TLS 1.3 and QUIC protocols), reflecting modern secure web browsing
- Used filters such as ip.addr and tcp.port to narrow down traffic to specific conversations
- Reviewed TCP and UDP conversation statistics including packets sent/received and speed (bits/sec) in both directions
- Explored packet details including Ethernet, IP, TCP/UDP headers, and raw hex data for a captured QUIC packet

