# Global-Threat-Monitoring-and-Geolocation-Mapping-with-Azure-Sentinel-(SIEM)

## Overview

This repository contains the code and documentation for a cybersecurity project that leverages Azure Sentinel, Microsoft's cloud-native SIEM solution, to detect and analyze cyber threats in real-time. The project includes a live virtual machine acting as a honeypot to attract and monitor incoming attacks, with a focus on Remote Desktop Protocol (RDP) brute force attacks. Additionally, custom PowerShell scripts are used to extract geolocation data from attackers' IP addresses, which is then visualized on the Azure Sentinel Map for enhanced threat intelligence.


## Project Features
1. Create a virtual machine that acts as a honey pot.
2. Setup Azure Sentinel (SIEM) and connect it to a live virtual machine.
3. Attract and monitor live attacks (RDP Brute Force) from all around the world.
4. Use a custom PowerShell script to extract the attackers Geolocation information from the attackers' IP addresses.
5. Plot it on the Azure Sentinel Map to get a clear view of locations of the origin of the attacks and enhanced threat intelligence.

## Query entry after setting up a honeypot and attracting live attacks


<img width="1510" alt="Screenshot 2024-02-25 at 4 23 11 PM" src="https://github.com/Avikaj/Global-Threat-Monitoring-and-Geolocation-Mapping-with-Azure-Sentinel-SIEM-/assets/151662350/465d9cb4-69a0-449a-8234-bdd51695a6b4">

## View of locations of origin of attacks on the Azure Senitel Map

<img width="1077" alt="Screenshot 2024-02-25 at 4 22 46 PM" src="https://github.com/Avikaj/Global-Threat-Monitoring-and-Geolocation-Mapping-with-Azure-Sentinel-SIEM-/assets/151662350/7ab63faf-b7fb-4045-8273-6073705eeb33">





