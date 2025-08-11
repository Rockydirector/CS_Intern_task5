# Capture and Analyze Network Traffic Using Wireshark

## Objective
The goal of this task is to **capture live network packets** using Wireshark and **identify basic protocols and traffic types** to build hands-on skills in network analysis.


## Tools Used
- **Wireshark** (Free, Open Source)
- Operating System: Windows/Linux/Mac (Any with network connectivity)


## Steps Performed

1. **Installed Wireshark**
   - Downloaded from [https://www.wireshark.org/](https://www.wireshark.org/)  
   - Installed with default settings.

2. **Started Packet Capture**
   - Selected the **active network interface** (Wi-Fi or Ethernet).
   - Clicked **Start Capturing Packets**.

3. **Generated Network Traffic**
   - Browsed multiple websites.
   - Used `ping` command to a public server (`ping google.com`).

4. **Stopped Capture**
   - Stopped capture after ~1 minute to keep file size small.

5. **Filtered by Protocol**
   - Applied filters such as:
     - `http` → View HTTP traffic
     - `dns` → View DNS queries
     - `tcp` → View TCP packets

6. **Identified Protocols**
   - Found **3+ protocols**:
     - **HTTP** – Web traffic.
     - **DNS** – Domain name resolution.
     - **TCP** – Connection-oriented transport protocol.

7. **Exported Capture**
   - Saved file as `capture.pcap`.

8. **Created Report**
   - Summarized protocols and key packet details.


## Findings

| Protocol | Purpose | Example Packet Details |
|----------|---------|------------------------|
| **HTTP** | Web requests/responses | GET /index.html HTTP/1.1 |
| **DNS**  | Domain resolution | Query for `google.com` |
| **TCP**  | Data transmission | SYN, ACK handshake |


##  Key Concepts
- Packet capture  
- Protocol analysis  
- TCP/IP fundamentals  
- Network troubleshooting  
- Wireshark filtering


## Example Screenshots
*(Include actual screenshots in a folder named `screenshots/`)*

![Wireshark Capture Example](screenshots/sample.png)


## Conclusion
Wireshark can capture and analyze various network protocols such as HTTP, DNS, and TCP.  
By applying filters and examining packet details, it is possible to study network behavior, troubleshoot issues, and understand data communication processes.
