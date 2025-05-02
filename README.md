# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info
![1](https://github.com/user-attachments/assets/96c4a334-9e05-4ee4-901d-8cf04d5a9ba8)
- **Start Capturing Packets**

• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.
![2](https://github.com/user-attachments/assets/acc4d5ae-504b-47ad-a434-e37203b967dc)

- **Apply Filters to Focus on Specific Traffic**
  
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.
![3](https://github.com/user-attachments/assets/7a1d0127-37c0-4174-8be5-5aed595c1ec6)
- **Analyze Packet Details**
  
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.
![4](https://github.com/user-attachments/assets/fe636ea2-c4f2-422a-8f12-092dc6c11e10)

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
