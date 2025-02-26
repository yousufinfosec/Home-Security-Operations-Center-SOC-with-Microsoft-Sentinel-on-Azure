# Home-Security-Operations-Center-SOC-with-Microsoft-Sentinel-on-Azure

In this project, I built a basic home Security Operations Center (SOC) using Azure and Microsoft Sentinel. The purpose was to simulate an environment where I could detect, monitor, and respond to real-world cyber threats

Steps taken:
- Setting Up an Azure Subscription: Created a Virtual Machine (VM), and exposed it to the internet as a honeypot to attract simulated attack attempts.
- Configuring Log Analytics: Configured a Log Analytics Workspace to collect all logs from the VM and other Azure resources for central analysis.
- Integrating with Microsoft Sentinel: Integrated Microsoft Sentinel to analyze logs, create custom detection rules, and automate threat detection.
- Incident Detection and Querying: Developed custom KQL queries for detecting failed login attempts and other suspicious activities. Created dashboards and alerts to visualize potential attack vectors.
- Building an Attack Map: Used Sentinel's mapping features to track real-time hacker activity, visualize attack sources, and understand attack patterns.
By completing this project, I learned some valuable skills in cloud security, threat detection, and incident response using Azure. <br><br>

Technologies used:
- Azure
- Microsoft Sentinel
- Log Analytics Workspace
- KQL (Kusto Query Language) <br><br>


Screenshots of the Project:

1. Resource Group Creation (Which is used to organize and manage related resources in Azure)

![resorce grp](https://github.com/user-attachments/assets/aa232b3d-b80d-4efc-9e7c-4c38820528a0) <br><br><br>


2. Virtual Machine Creation (Honeypot)

![2 cretaed vm](https://github.com/user-attachments/assets/40fc5ea3-0c02-4ab5-8c69-43fc58188983) <br><br><br>


3. Log Analytics Workspace Setup (setup of the Log Analytics Workspace where logs are collected and sent for analysis in Microsoft Sentinel)

![image](https://github.com/user-attachments/assets/6aced3b4-8ec9-4b1c-9557-5d930d2acc10) <br><br><br>


4. Sentinel Integration (Workspace for monitoring and threat detection)

![image](https://github.com/user-attachments/assets/42355b64-63a9-4d8e-ae2b-6587a9f08d94)
![sentinellog1](https://github.com/user-attachments/assets/3c9c1bd8-bd3a-414d-9c8e-ca29c430b7c6)
![image](https://github.com/user-attachments/assets/0a7744bb-d9e3-4422-8e02-7fd9d44eda5f) <br><br><br>


5. Custom Detection Rules (Designed to monitor and alert for any suspicious activity)

![image](https://github.com/user-attachments/assets/c86b5938-a475-435a-84ae-ac0689641f8c)

![image](https://github.com/user-attachments/assets/e98988f4-5d3a-4ab0-802a-a3d1261b03b7) <br><br><br>


6. Attack Map Visualization (visual representation of the real time attack map built using Sentinel to track hackers activities)

![image](https://github.com/user-attachments/assets/bae99498-347a-480a-8cb0-a6b667195971)






