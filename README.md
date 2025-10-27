# Wireshark

1) Open wireshark and go to eth0

   <img width="304" height="64" alt="image" src="https://github.com/user-attachments/assets/f9a595e0-d01b-4316-9c00-1f2a8f8e07a0" />

2) Send a ping to google.com

   <img width="539" height="184" alt="image" src="https://github.com/user-attachments/assets/31f46de2-2b91-415b-a499-c5bf37cdfe6f" />

3) Analyse wireshark results

   Protocols

   DNS
   
   <img width="834" height="179" alt="image" src="https://github.com/user-attachments/assets/7fc3577a-ecc3-4617-bb39-d97e9608ecf0" />

   ICMP
   
   <img width="834" height="138" alt="image" src="https://github.com/user-attachments/assets/c61ac565-94d7-4ec0-aec8-31b9218e8f2b" />

   ARP
   
   <img width="834" height="185" alt="image" src="https://github.com/user-attachments/assets/80f2f6fa-7cd4-4d00-a0a9-bb9d2a308626" />

   **Questions**

1. **What is Wireshark used for?**
   Wireshark is a network protocol analyzer used to capture, inspect, and analyze network traffic in real time. It helps identify what data is flowing through the network, which protocols are being used, and can diagnose network issues or detect suspicious activity.

2. **What is a packet?**
   A packet is a small unit of data transmitted over a network. It contains a header (with routing and protocol information) and a payload (the actual data being sent). Networks transfer data in packets so it can be efficiently sent and reassembled at the destination.

3. **How to filter packets in Wireshark?**
   Wireshark provides a display filter bar at the top. You can filter packets by typing protocol names or expressions such as `http`, `dns`, `tcp`, or `icmp`.

4. **What is the difference between TCP and UDP?**
   TCP (Transmission Control Protocol) is connection-oriented, ensures reliable delivery, and uses acknowledgments and retransmissions. UDP (User Datagram Protocol) is connectionless, faster, but does not guarantee delivery or order.

5. **What is a DNS query packet?**
   A DNS query packet is sent from a client to a DNS server to resolve a domain name (like google.com) into its corresponding IP address.

6. **How can packet capture help in troubleshooting?**
   Packet capture helps identify where communication is failing, detect latency, dropped packets, misconfigurations, or malicious traffic by showing what is actually being transmitted across the network.

7. **What is a protocol?**
   A protocol is a set of rules that define how data is transmitted and received over a network, ensuring devices communicate correctly (e.g., TCP, HTTP, DNS).

8. **Can Wireshark decrypt encrypted traffic?**
   Wireshark cannot normally decrypt encrypted traffic like HTTPS or SSH unless you have the appropriate decryption keys or use specific debugging setups that provide session keys.


   




