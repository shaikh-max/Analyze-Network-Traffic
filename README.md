# Analyze-Network-Traffic
📑 Network Traffic Analysis Report using Wireshark
 Task 5 — Capture and Analyze Network Traffic
Tool Used: Wireshark (Free)

🎯 Objective
To capture live network packets and identify basic protocols and traffic types using Wireshark.

📦 Tools Required
Wireshark (installed on local system)

📋 Steps Performed
Installed and opened Wireshark.

Started live packet capture on the active Wi-Fi network interface.

Browsed websites (e.g., windows.msn.com, google.com) and performed ping tests.

Stopped the capture after 1 minute.

Applied filters like dns, tcp, and arp to isolate traffic types.

Exported the capture as a .pcap file.

Analyzed and documented the protocol details.

📊 Protocols Identified
S.No.	Protocol	Purpose	Captured Packets Summary
1	DNS (Domain Name System)	Resolves domain names to IP addresses.	Standard DNS query and response packets for domains like windows.msn.com, google.com.
2	TCP (Transmission Control Protocol)	Provides reliable, ordered, and error-checked delivery of data between applications.	TCP handshake packets (SYN, ACK) and data transfer over port 443 for HTTPS communication.
3	ARP (Address Resolution Protocol)	Maps IP addresses to MAC addresses within a local network.	ARP requests and replies like Who has 192.168.241.207? Tell 192.168.241.38.

