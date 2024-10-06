# SOC Microsoft Defender for Cloud Integration and Continuous Export Lab
![Screenshot 2024-10-06 181549](https://github.com/user-attachments/assets/15ded097-832f-4503-a1ce-3ec9094c5b4d)

In this lab, I enabled Microsoft Defender for Cloud (MDC) for both the Log Analytics Workspace and the subscription, covering VMs, storage accounts, SQL instances, and key vaults. The lab involves configuring continuous export of logs to a centralized Log Analytics Workspace for unified security monitoring. I ensured all data collection is enabled, and that logs from various resources are routed correctly. This hands-on project demonstrates my ability to integrate cloud security solutions and manage continuous log exports for comprehensive threat detection in a SOC environment.



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Defender

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Enable Microsoft Defender for Cloud for Log Analytics Workspace
- Step 2 - Enable Microsoft Defender for Cloud for Subscription
- Step 3 - Enable Microsoft Defender for Cloud Continuous Export in Environment Settings


<h2>Deployment and Configuration Steps</h2>

- Enable Microsoft Defender for Cloud for Log Analytics Workspace
- Enable Defender Plans for VMs and SQL Instances on VMs [Save after]
- Enable Data Collection (All Events) [Save after]
![Screenshot 2024-10-06 182903](https://github.com/user-attachments/assets/ae596bdd-d48f-46f8-ac9d-35c0df38f29c)
![Screenshot 2024-10-06 183054](https://github.com/user-attachments/assets/4ad12848-9644-4c8e-8779-6b4b44ece4f1)

- Enable Microsoft Defender for Cloud for Subscription
- Servers (VMs), Storage Accounts, Key Vault, SQL Server
- Make sure logs are being set to correct log analytics workspaces
![Screenshot 2024-10-06 183729](https://github.com/user-attachments/assets/e6b97e89-c4de-4249-8d4a-de5482897892)
![Screenshot 2024-10-06 184103](https://github.com/user-attachments/assets/5860cf23-2260-4406-adc9-9e9b8ffd99a9)

- Enable Microsoft Defender for Cloud Continuous Export in Environment Settings
- Make sure to Export to the correct Log Analytics Workspace
- Do it for every single thing
![Screenshot 2024-10-06 184844](https://github.com/user-attachments/assets/563556f4-435a-4601-a75c-ccbb30cec6af)










