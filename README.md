# Capture and Analyze Network Traffic Using Wireshark

## Objective
The goal of this task is to capture live network packets using Wireshark and identify basic protocols and traffic types.

## Tools
- Wireshark (free packet analyzer)

## Deliverables
- A packet capture (.pcap) file
- A short report summarizing the protocols identified in the packet capture

## Task Guide
1. Install Wireshark on your system.
2. Start capturing packets on your active network interface.
3. Generate network traffic by browsing a website or pinging a server.
4. Stop the capture after about one minute.
5. Use Wireshark's filtering capabilities to filter packets by protocol (e.g., HTTP, DNS, TCP).
6. Identify and note at least three different protocols present in the captured traffic.
7. Export and save the capture file in .pcap format.
8. Summarize your findings including protocol details and observations.

## Outcome
By completing this task, you will gain practical skills in packet analysis and a better awareness of network protocols.

## Protocols Captured and Descriptions

- *ICMP (Internet Control Message Protocol):*  
  ICMP is used by network devices, like routers, to send error messages and operational information. For example, it helps in indicating when a service is not available or a host cannot be reached. A common use of ICMP is the "ping" command, which checks if a device is reachable over the network.

- *DNS (Domain Name System):*  
  DNS translates human-readable domain names (like www.example.com) into IP addresses that computers use to identify each other on the network. When you type a URL into your browser, DNS helps find the corresponding server's IP address so your computer can connect to it.

- *TCP (Transmission Control Protocol):*  
  TCP is one of the core protocols of the Internet protocol suite. It provides reliable, ordered, and error-checked delivery of a stream of data between applications running on hosts communicating via an IP network. It is used for most web traffic, email, and file transfers.

## Key Concepts
- Packet capture
- Protocol analysis
- TCP/IP
- Network troubleshooting
- Packet filtering
