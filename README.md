<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
Step 1: Understand Azure Network Protocols
</p>
<p>
Learn the basics of TCP/IP, UDP, ICMP, and their roles in communication between Azure VMs, load balancers, and on-premises networks.
Focus on how Azure uses these protocols for virtual networking.
</p>
<br />

<p>
Step 2: Configure Network Security Groups (NSGs)
</p>
<p>
Create and apply inbound and outbound security rules to allow or block traffic based on protocol, port, and IP range.
For example:
TCP: Allow HTTPS traffic (port 443).
ICMP: Enable for diagnostics (optional).
</p>
<br />

<p>
Step 3: Set Up Virtual Network Peering
</p>
<p>
Use virtual network (VNet) peering to enable connectivity between Azure VNets.
Understand the protocols Azure uses to optimize communication between VNets (e.g., BGP for routing).
<br />

<p>
Step 4: Test and Optimize Protocol Configuration
</p>
Use tools like Azure Network Watcher to diagnose connectivity issues.
Test protocol-specific scenarios (e.g., verifying HTTP/S traffic through a load balancer).
<p>
  
</p>
