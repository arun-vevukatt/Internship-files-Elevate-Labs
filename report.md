# Network Traffic Capture using Wireshark

## Objective
To capture live network traffic and identify at least three types of protocols.

## Tools Used
- Wireshark v4.x

## Steps Performed
1. Started Wireshark on the active network interface.
2. Visited `example.com` in a browser.
3. Sent a ping to `google.com` using the terminal.
4. Stopped capture after ~1 minute.
5. Applied filters to inspect specific protocols.

## Protocols Identified
### 1. HTTP
- **Website Visited:** example.com
- **Request Method:** GET
- **Response Code:** 200 OK

### 2. DNS
- **Queried Domain:** google.com
- **Query Type:** A
- **Response IP:** 142.250.xx.xx

### 3. ICMP
- **Pinged Host:** google.com
- **Packet Type:** Echo (ping) request and reply

## Deliverables
- `network_capture.pcap` – Packet capture file (placeholder in this case)
- `report.md` – This file with the protocol analysis

