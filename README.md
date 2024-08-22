# Inspecting-Network-Traffic-<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDP, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Created two virtual machines in Azure one Windows 10 and One Ubuntu Server
- Used ping command to test connectivity between the two machines
- Installed Wireshark
- Used Wireshark to filter and analyze traffic
- Created an Inbound security rule in Azure Security Group
- used ssh in powershell to connect to Ubunto server command line

<h2>Analyzing ICMP Network Traffic</h2>

<p>

![Pinging VM 2 and showing traffic with ICMP filter](https://github.com/user-attachments/assets/75725500-be75-4f65-891e-73d51f1d6572)

- Using powershell to ping the Ubuntu Server virtual machine

- Using Wireshark to filter ICMP traffic.
</p>
<br />

<h2>Using Azure Network Security Group </h2>
![Blocking ICMP traffic on VM2 through Azure firewall](https://github.com/user-attachments/assets/d9be78e5-8112-49e3-931c-7ca500d7cb56)
![Denying ICMP traffic](https://github.com/user-attachments/assets/1c5594e6-7eac-41de-9d9e-d6a8239a85d7)
- Creating inbound security rule to block ICMP traffic
- 
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
