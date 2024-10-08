# Inspecting-Network-Traffic-<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
I completed this project to observe various network traffic to and from Azure Virtual Machines with Wireshark to gain a better understanding of Firewalls and protocols. <br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDP, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>Steps</h2>

- Created two virtual machines in Azure one Windows 10 and One Ubuntu Server
- Used ping command to test connectivity between the two machines
- Installed Wireshark
- Used Wireshark to filter and analyze traffic
- Created an Inbound security rule in Azure Security Group
- Used ssh in powershell to connect to Ubuntu server command line

<h2>Analyzing ICMP Network Traffic</h2>

<p>

![Pinging VM 2 and showing traffic with ICMP filter](https://github.com/user-attachments/assets/75725500-be75-4f65-891e-73d51f1d6572)

- Using powershell to ping the Ubuntu Server virtual machine

- Using Wireshark to filter ICMP traffic.
</p>
<br />

<h2>Using Azure Network Security Group </h2>




![Denying ICMP traffic](https://github.com/user-attachments/assets/1c5594e6-7eac-41de-9d9e-d6a8239a85d7)

 - Creating inbound security rule to block ICMP traffic.
 
![Rule](https://github.com/user-attachments/assets/3862e62b-a18a-4e8f-bd92-ab9da599eba4)





![no reply firewall blocking ICMP4 traffic](https://github.com/user-attachments/assets/de4dab6a-ebeb-4a96-9bca-463430d364c3)

- Successfully configured firewall to block ICMP traffic.
</p>
<p>
</p>
<br />


<h2>SSH </h2>

![ssh into VM2](https://github.com/user-attachments/assets/e22404e4-c085-4dc8-8d36-ef7b9fdecc61)

- Using ssh to login to Ubuntu serve
- Filtering ssh traffic on Wireshark
</p>
<br />
