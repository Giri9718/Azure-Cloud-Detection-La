<h1>AZURE CLOUD DETECTION LAB<h1>

<h2>Introduction</h2>

<br />
The Azure Cloud Detection Lab Project focuses on leveraging Microsoft Sentinel, a cloud-based SIEM/SOAR solution, to enhance cybersecurity monitoring, detection, and response capabilities within a cloud environment. This lab provides hands-on experience in configuring and deploying Azure resources, implementing security best practices, analysing Windows security event logs, and utilizing Kusto Query Language (KQL) to query logs and create custom analytic rules.
<br />

<h2>Lab Objective</h2>

1.Configure and Deploy Azure Resources: Log Analytics Workspace, Virtual Machines, and Azure Sentinel
<br>
2.Implement Network and Virtual Machine Security Best Practices.
<br>
3.Utilize Data Connectors to bring data into Sentinel for Analysis.
<br>
4.Understand Windows Security Event logs and configure Security Policies.
<br>
5.Utilize KQL to query Logs and write Custom Analytic Rules.
<br>
6.Utilize MITRE ATT&CK to map adversary tactics, techniques, detection, and mitigation procedures.
<br>

<p align="center">
<img src="https://i.imgur.com/vaqEjfK.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<h2>Requirements</h2>

1.Free Azure Subscription (30-day free trial).
<br>
2.Microsoft Sentinel Free Trial
<br>
3.Microsoft Defender for Cloud (enabled for the lab).
<br>

<h2>Lab Steps</h2>
<h3>1.Setup Lab Resources</h3>
Create Free Azure Account: Sign up for a free Azure Subscription using the provided link.
<br>
Create a Resource Group: Create a new resource group in the Azure Portal to group all lab resources.
<br>
Deploy a Virtual Machine: Deploy a Windows Virtual Machine in Azure with default settings.
<br>

<p align="center">
<img src="https://i.imgur.com/O3FOfEO.jpg(https://i.imgur.com/O3FOfEO.jpg)" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<h3>2.Network and Virtual Machine Security</h3>
Configure Network Security Groups (NSG) and enable Just in Time Access for VM security.
<p align="center">
<img src="https://i.imgur.com/SYXvHoD.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<h3>3.Create Log Analytics Workspace and Deploy Sentinel</h3>
Create a Log Analytics Workspace and deploy Azure Sentinel for centralized log management and analysis.
<p align="center">
<img src="https://i.imgur.com/FGYydec.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<h3>4.Getting Data into Sentinel</h3>
Configure data connectors and data collection rules to bring data from the VM into Sentinel.
<p align="center">
<img src="https://i.imgur.com/5G71sj7.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<h3>5.Windows Security Events and KQL</h3>
Generate security events on the VM and use KQL to query logs and extract relevant information.
<p align="center">
<img src="https://i.imgur.com/SJUbKqt.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<br>
<p align="center">
<img src="https://i.imgur.com/mcqDVB1.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<h3>6.Writing Analytic Rules and MITRE ATT&CK</h3>
Create custom analytic rules in Sentinel to detect specific security events and explore MITRE ATT&CK tactics and techniques related to persistence.
According to the MITRE Attack Framework, “Adversaries may abuse task scheduling functionality to facilitate initial or recurring execution of malicious code. Utilities exist within all major operating systems to schedule programs or scripts to be executed at a specified date and time”.
<p align="center">
<img src="https://i.imgur.com/1YcZx7x.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<br>
<p align="center">
<img src="https://i.imgur.com/67zuPmL.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<br>
<p align="center">
<img src="https://i.imgur.com/QEIDYpE.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>Conclusion</h2>

The Azure Cloud Detection Lab Project provides a comprehensive hands-on experience in leveraging cloud-based SIEM/SOAR capabilities to enhance cybersecurity monitoring and detection. By following the step-by-step lab guide and exploring various aspects of Azure Sentinel, participants gain valuable insights into real-world cybersecurity challenges, detection techniques, and mitigation strategies.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
