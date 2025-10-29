# Task 5 Report: Capture and Analyze Network Traffic

### Cyber Security Internship

## Overview

This report documents the step-by-step process of capturing and analyzing network traffic using Wireshark as part of a cybersecurity internship task. The main objective was to generate network traffic through continuous ping, capture packets, and analyze the various network protocols observed.

## Steps Performed

### Step 1: Launch Wireshark
- Open the Wireshark application to start monitoring network packets.

### Step 2: Select Network Interface
- Choose the active network interface (e.g., Wi-Fi) to capture live traffic on your system.

### Step 3: Start Continuous Ping to Generate Traffic
- Run the following terminal command to produce ICMP traffic by pinging google.com continuously for 60 seconds:
  ping -c 60 google.com

### Step 4: Capture and Stop
- After the ping command has completed, stop the packet capture in Wireshark.

### Step 5: Save Captured Packets
- Export and save the captured data as a `.pcap` file for further analysis and documentation.

### Step 6: Analyze Available Protocols
- Use Wireshark’s protocol hierarchy and filter features to identify and examine protocols present in the capture file.

## Protocols Observed

- **UDP (User Datagram Protocol):** Connectionless protocol used for time-sensitive transmissions such as streaming or domain lookups.
- **ARP (Address Resolution Protocol):** Maps IP addresses to MAC addresses on local network segments.
- **mDNS (Multicast DNS):** Resolves hostnames to IP addresses within small networks without a conventional DNS server.
- **ICMP (Internet Control Message Protocol):** Used for diagnostic and control tasks, notably ping requests and replies.

## Summary

This task provided practical experience in network traffic capture and analysis using Wireshark. It highlighted the importance of generating real network data for accurate protocol identification. Understanding these protocols supports effective network troubleshooting and cybersecurity diagnostics.

---

*This README accompanies the Task 5 HTML report for the Cyber Security Internship.*
