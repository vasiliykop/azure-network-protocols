<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



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

- Creating Resource group in Azure
- Creating Windows 10VM and Ubuntu Server VM
- Remote connect via Microsft Remopte Desktop
- Install Wireshark

<h2>Actions and Observations</h2>

<p>
  Watching packet flow on Wireshark
</p>
<p>
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/d3461151-3868-429b-8c2d-e17177af2c14">
</p>
<br/>

<p>
  Pinging and filtering packets
</p>
<p>
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/329dc10f-05a4-480c-a568-2d11793056e7">
  </p>
<br/>

<p>
  Configuring Firewall in Azure to deny inbound ICMP
</p>
<p>
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/45cf9289-bdfa-479a-947c-d169972b8d13">
</p>
<br/>

<p>
  Watching packets flow after configuring Firewall
</p>
<p>
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/919b9642-be38-4ace-942e-0de7eff43c0e">
</p>
<br/>

<p>
  SSH into VM Ubuntu server
</p>
<p>
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/974c9d6f-f3fe-442d-805f-ad3b4201a71c">
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/0b64e06b-aece-4783-9896-422ca53ccbcd"
</p>
<br/>

<p>
  Filtering traffic in Wireshark
</p>
<p>
  <img src ="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/5ff5f0dd-ba01-47bb-82aa-d098122b83ee
">
</p>
<br/>

<p>
  Renewing DHCP
</p>
<p>
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/41554a0b-db5d-4ade-9931-400a56abcf1b">
</p>
<br/>

<p>
  Observing DNS tarffic from www.google.com
</p>
<p>
  <img src="https://github.com/vasiliykop/azure-network-protocols/assets/170582503/92bf39aa-d755-4ef6-8e97-4bfffe768993">
</p>

  





