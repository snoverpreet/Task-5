# Task-5

**Capture and Analyze Network Traffic Using Wireshark.**

**Step 1: To install wireshark** 
But in kali linux we have this as pre-installed tool 
just need to write wireshark in terminal and it will run the tool 

There are two types of filter in wireshark 
1. Capture Filter 
2. Display Filter 

Display Filter
ip.addr == <ip address>

Click a packet and read the three panes:

Top (list): frame #, time, source, destination, protocol, info.

Middle (details): expandable protocol fields (Ethernet → IP → TCP → HTTP).

Bottom (bytes): raw bytes.

Helpful actions:

Right-click → Follow → TCP Stream (reconstructs the conversation — useful for HTTP).

Right-click a DNS packet → Decode As if needed.

Use Analyze → Expert Information to find anomalies (retransmits, errors).

Use built-in stats for your report
Statistics → Protocol Hierarchy — list of protocols and packet counts.

Statistics → Conversations — top talkers (IP pairs).

Statistics → Endpoints — endpoints by bytes/packets.

Statistics → IO Graphs — visualize traffic over time.
