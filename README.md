<h1>Dynamic Host Configuration Protocol</h1>
<h2>Objective</h2>
To configure and implement Dynamic Host Configuration Protocol (DHCP) in Cisco Packet Tracer by assigning one router as the DHCP server and another router as a DHCP client and relay agent. This lab focuses on creating DHCP address pools, configuring IP address ranges and default gateways, enabling DHCP client functionality on router interfaces, and using the ip helper-address command to relay DHCP requests between different networks. The goal is to understand and troubleshoot automated IP address assignment across multiple subnets while ensuring proper network connectivity and communication between devices.
<h2>Program</h2>
<p align="center">
<img src="https://i.imgur.com/81IvzKp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
On this project, we want to configure R2 as a dhcp server by creating the three networks labeled that will be using a dhcp pool along with its own default gateway (except the network between R1 and R2). And on R1 connecting to R2, we want to create its interface as a dhcp client so that it can automatically request its own ip address to be configured on the interface and the interface connected towards the client as a dhcp relay agent for the PC requesting an IP address from the dhcp server.
<p align="center">
<img src="https://i.imgur.com/2HXvmjQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
<img src="https://i.imgur.com/PjI7NUG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
To verify that the routers are properly configured, let’s request an IP address on PC1 and PC2 through command prompt.
<p align="center">
<img src="https://i.imgur.com/hBh96V2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
<img src="https://i.imgur.com/58gY0Zp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
