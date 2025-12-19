# Azure Sentinel HoneypotLab
# Overview:
This project simulates a real world SOC environment using Azure Sentinel. It involved deploying a cloud based honeypot, collecting and analyzing security logs, monitoring authentication attempts, and visualizing attack activity. Through this lab, I gained hands on experience with SIEM based threat detection, log analytics, and cloud security monitoring in Microsoft Azure.


## Step 1: Azure Environment
Created core Azure resources used for security monitoring.
<img width="1787" height="936" alt="image" src="https://github.com/user-attachments/assets/1debafe9-be04-40ea-aee9-cd12aae0f40c" />


---

## Step 2: Honeypot Virtual Machine
Deployed a Windows VM exposed to the internet to attract attacks.
<img width="944" height="802" alt="image" src="https://github.com/user-attachments/assets/6ef0edba-486b-4149-8ed1-a2ca20d00892" />
<img width="2397" height="327" alt="image" src="https://github.com/user-attachments/assets/f0af4ca5-74f7-4e8b-a65b-3eb61a21d9b7" />



---

## Step 3: Centralized Logging (Sentinel)
Forwarded VM security logs to Microsoft Sentinel for analysis (Event ID 4625).
<img width="2884" height="1744" alt="image" src="https://github.com/user-attachments/assets/f0930f24-f327-425c-ba67-9b43cb2fcb62" />


---

## Step 4: Attack Map Visualization
Visualized global attack ip sources using a Sentinel workbook map.
<img width="2331" height="1112" alt="image" src="https://github.com/user-attachments/assets/a3eb9dcd-02f1-40e9-ac6f-72abeb62cdcf" />


---

## Tools Used
Azure • Microsoft Sentinel • Log Analytics • KQL

### Key Takeaways
- Configured Azure Sentinel and Log Analytics for centralized security monitoring
- Analyzed failed and successful authentication attempts using security logs
- Visualized attack activity by geographic location
- Gained practical experience with SIEM operations in a cloud-based SOC environment
