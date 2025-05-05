# Ethernet-LAN-Switching-Lab
This lab project focuses on Ethernet LAN switching concepts using Cisco Packet Tracer. It is part of a networking fundamentals series aimed at helping learners understand switch behavior, MAC address learning, and ARP processes.
![image](https://github.com/user-attachments/assets/a2b20998-9c41-4054-bd1d-0dd6c43e4d82)

🖧 Topology
💻 4 PCs: PC1 – PC4

🔀 2 Switches: SW1 and SW2

🌐 Network: 192.168.1.0/24

🔌 Connections:
🖥️ PC1 → SW1 (Fa0/1)

🖥️ PC2 → SW1 (Fa0/2)

🖥️ PC3 → SW2 (Fa0/1)

🖥️ PC4 → SW2 (Fa0/2)

🌐 SW1 ↔ SW2 via Gigabit links (G0/1 ↔ G0/1)

🧼 Initial Conditions
📭 All MAC address tables on both switches are empty

❌ All ARP tables on PCs are empty

🎯 Objectives
🔍 Understand Frame Forwarding Without MAC Entries:
Predict what happens when PC1 pings PC3

Determine which messages are broadcast and who receives them

🧪 Simulate Ping in Cisco Packet Tracer:
Use Simulation Mode to inspect how packets are forwarded

📡 Generate Traffic for MAC Learning:
Ping between all PCs to allow switches to learn MAC addresses

🧾 Verify MAC Address Tables:
Use show mac address-table on each switch to confirm MAC entries

🔄 Clear Learned MAC Entries:
Use clear mac address-table dynamic to reset the MAC tables

🛠️ How to Use
Open the .pkt file using Cisco Packet Tracer

Run through the objectives above

Use Simulation Mode for better visibility into network behavior

🎓 Learning Outcomes
🧠 How switches learn MAC addresses

📡 Behavior of switches during unknown unicast and ARP broadcasts

🔧 Using show and clear commands on Cisco switches


