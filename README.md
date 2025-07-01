# Task-5-Capture-and-Analyze-Network-Traffic-Using-Wireshark

## 📌 Objective
Capture live network packets using Wireshark and analyze the traffic to identify basic network protocols.

## 🛠 Tools Used
- *Wireshark* (Network Protocol Analyzer)

## 🧪 Steps Performed

1. Installed and launched Wireshark.
2. Started capturing packets on the active network interface.
3. Generated traffic by browsing websites and pinging servers.
4. Stopped the capture after 1 minute.
5. Filtered packets by protocol (dns, tcp).
6. Identified two protocols: *TCP* and *DNS*.
7. Exported the capture as a .pcap file.
8. Analyzed packet data and documented key observations.

## 📂 Files Included

- [network_traffic_capture.pcap](network_traffic_capture.pcap): Packet capture file.
- [Wireshark_Task5_Report.pdf](Wireshark_Task5_Report.pdf): Detailed report with protocol analysis and sample packet information.

## 📊 Protocols Identified

| Protocol | Description                                | Packet Count |
|----------|--------------------------------------------|--------------|
| TCP      | Connection-oriented protocol for reliable communication | ~120         |
| DNS      | Domain name resolution to IP addresses     | ~30          |

## 📄 Summary

The packet capture revealed active DNS queries for domain resolution and multiple TCP connections. The TCP handshake process was visible along with encrypted HTTPS traffic. No HTTP packets were observed due to encrypted communication.
