# 📡 Network Troubleshooting and Packet Analysis Lab

## 🧠 Objective
To capture and analyze network traffic using Wireshark and develop an understanding of TCP/IP communications, protocols, and network troubleshooting techniques.

---

## 🛠️ Tools & Technologies
- **Wireshark**
- **TCP/IP Protocol Suite**
- **Windows/Linux OS (for packet generation)**
- **Command Line Tools:** `ping`, `tracert`/`traceroute`, `netstat`

---

## 📝 What I Did
- Captured live network traffic using Wireshark on a local machine
- Applied filters to isolate HTTP, DNS, TCP handshakes, and ICMP packets
- Analyzed:
  - TCP 3-way handshake (SYN, SYN-ACK, ACK)
  - HTTP GET/POST request structure
  - DNS query/response timing
  - ICMP echo requests (ping)
- Identified packet loss and high latency using `ping` and `tracert`
- Interpreted packet flags, TTL, port numbers, and MAC/IP addresses
- Documented findings and annotated packet flow in screenshots

---

## 📸 Screenshots

---<img width="1120" alt="Screenshot 2024-05-05 at 5 13 14 PM" src="https://github.com/user-attachments/assets/3087d425-a286-49d5-a65e-2b5cfe33cea9" />
<img width="1000" alt="ip addr" src="https://github.com/user-attachments/assets/44c5b040-6c1e-4f0f-aaa3-4213b1697165" />
<img width="1005" alt="ip dst==" src="https://github.com/user-attachments/assets/7dc9a89f-87cb-4975-b2fd-ba2af0c256c1" />
<img width="1002" alt="ip addr== tcp" src="https://github.com/user-attachments/assets/17fe6d04-9ece-4a55-9df2-56a5b3001d4e" />

![dnsfiltersearch-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/02ec6f63-e211-4f3b-8e14-db6a552b0c40)
![sshfiltersearch-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/f3d4d20d-6acd-4fe7-89a3-daaece5e2c24)
![wiresharkpacketsniffingnmapipconnection-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/c61e7a13-30e5-4cf5-bc72-ca5236b08940)
![wlan0monpacketsniffing-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/20a99a54-6c9b-4f7c-bf03-1e85ea7c7a35)



## ✅ Key Takeaways
- Learned to navigate and filter large packet datasets in Wireshark
- Understood how key protocols operate at different OSI layers
- Gained experience identifying latency, routing paths, and dropped packets
- Built foundational skills useful in network support and cybersecurity roles

---

## 🔄 Reflections & Next Steps
- Next time, I'll simulate a Man-in-the-Middle (MITM) attack for deeper inspection
- Plan to explore Wireshark’s graphing and expert analysis tools
- Consider scripting repetitive packet analysis using `tshark`


