Windows 10 Honeypot on Azure with Sentinel Monitoring

Overview:

This project sets up a vulnerable Windows 10 honeypot on Microsoft Azure and utilizes Microsoft Sentinel to track and analyze attacks in real time. The Sentinel map feature provides visualization of attacker origins.

Features:

Deployment of a Windows 10 honeypot VM in Azure
Configuration of security group rules to allow inbound traffic
Logging and monitoring via Microsoft Sentinel
Attack origin visualization using Sentinel maps

Deployment Steps:

Create a Windows 10 VM on Azure
Navigate to the Azure portal
Deploy a new Windows 10 virtual machine
Configure network security rules to allow inbound connections (e.g., RDP, SMB, or other targeted ports)
Install Monitoring Tools on the VM
Enable Windows Event Logging
Set Up Microsoft Sentinel
Enable Sentinel on Azure
Connect Sentinel to Log Analytics Workspace
Create Attack Visualization in Sentinel
Open Sentinel in Azure
Navigate to the Map feature
Enable Geo-location tracking to visualize attack sources

Usage:
Monitor real-time attack attempts on the VM
Analyze attack patterns and sources using Sentinel’s dashboard
Modify honeypot vulnerabilities to attract different attack vectors



