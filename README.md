# Azure Sentinel Security Operations Center (SOC) Lab

This project simulates a basic SOC built using Microsoft Azure and Microsoft Sentinel, designed to monitor, detect, and alert on RDP-related security events in a virtualized lab environment.

## Lab Summary

- Deployed a Windows Virtual Machine in Azure.
- Configured the machine for RDP access to simulate real-world attack surfaces.
- Set up Microsoft Sentinel via a Log Analytics Workspace.
- Connected the VM's event logs to Sentinel using data connectors and Azure Monitor Agent (AMA).
- Created custom detection rules to alert on successful RDP sign-ins, simulating brute-force or unauthorized access attempts.

> This lab was inspired by the [Tactiq.io YouTube guide](https://www.youtube.com/watch?v=IJUkGuirTGQ) and adapted to suit my own learning objectives.

## Tools Used

- Microsoft Azure
- Microsoft Sentinel (SIEM)
- Azure Log Analytics
- Windows Event Logs
