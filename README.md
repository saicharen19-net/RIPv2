Lab Summary: RIPv2 Configuration in Cisco Packet Tracer
In this lab, I implemented and tested RIPv2 routing across a multi-router topology using Cisco Packet Tracer. Key configurations include:
- ✅ Assigned hostnames to all devices as per the topology for clarity and identification.
- ✅ Configured router interfaces with IP addresses aligned to the network diagram.
- ✅ Assigned IP addresses to PCs to enable end-to-end connectivity.
- ✅ Enabled RIPv2 on all routers to facilitate dynamic routing.
- ✅ Applied passive interface on R3’s LAN port to prevent routing updates from being sent to internal hosts.
- ✅ Introduced a Rogue router connected to the switch to simulate a security test—verifying that passive interfaces effectively hide internal routing information.

🔍 Skills Demonstrated:
- Routing protocol configuration (RIPv2)
- Passive interface security technique
- IP addressing and subnetting
- Network simulation and troubleshooting

🔍 Skills Demonstrated:
- Routing protocol configuration (RIPv2)
- Passive interface security technique
- IP addressing and subnetting
- Network simulation and troubleshooting

📊 Final Implementation Snapshot
<img width="1886" height="574" alt="image" src="https://github.com/user-attachments/assets/576a4e16-dcc7-409f-af81-ebbc832884cd" />

✅ Ping Test: End-to-End Connectivity Verification
Shows successful ping between PCs across routers, confirming RIPv2 routing is operational.
<img width="684" height="439" alt="image" src="https://github.com/user-attachments/assets/8bc29651-e578-4c8b-8f4c-a542aa695ad5" />

✅Rogue Router: show ip route Output Blocked by Passive Interface
Demonstrates how passive interface configuration prevents internal route visibility to unauthorized devices.
<img width="676" height="263" alt="image" src="https://github.com/user-attachments/assets/2e5d1d0e-2c61-4f23-a1e5-3b038ecce264" />

👨‍💻 Author Sai Charen

Skilled in Networking, Cisco Packet Tracer, and Enterprise IT Solutions.

