<h1>Log Analysis Basics</h1>

<h2>What Are Logs?</h2>
Logs are recorded events or transactions within a system, device, or application. Specifically, these events can be related to application errors, system faults, audited user actions, resource uses, network connections, and more. 
Each log entry contains relevant details to contextualize the event, such as its timestamp (the date and time it occurred), the source (the system that generated the log), and additional information about the specific log event.

<h2>Why Are Logs Important?</h2>

- **System Troubleshooting:** Analyzing system errors and warning logs helps IT teams understand and quickly respond to system failures, minimizing downtime, and improving overall system reliability.
- **Cyber Security Incidents:** In the security context, logs are crucial in detecting and responding to security incidents. Firewall logs, intrusion detection system (IDS) logs, and system authentication logs, for example, contain vital information about potential threats and suspicious activities. Performing log analysis helps SOC teams and Security Analysts identify and quickly respond to unauthorized access attempts, malware, data breaches, and other malicious activities.
- **Threat Hunting:** On the proactive side, cyber security teams can use collected logs to actively search for advanced threats that may have evaded traditional security measures. Security Analysts and Threat Hunters can analyze logs to look for unusual patterns, anomalies, and indicators of compromise (IOCs) that might indicate the presence of a threat actor.
- **Compliance:** Organizations must often maintain detailed records of their system's activities for regulatory and compliance purposes. Regular log analysis ensures that organizations can provide accurate reports and demonstrate compliance with regulations such as GDPR, HIPAA, or PCI DSS.

<h1>Elements Of A Log</h1>

<p align="center">
<img src="https://i.imgur.com/Z0d0mGF.png" height="150%" width="150%" alt="Prompt Engineering"/>
<br />
<br />
</p>

<h2>Timestamp</h2>

![image](https://github.com/dante-falls/TryHackMe_Stuff/assets/29386604/c486d8aa-0554-46ae-a971-ade1c64d8969)

**A Log's timestamp is a way to record what time and date an event happened at.**

<h2>Source IP Address <---> Destination IP Address</h2>

![image](https://github.com/dante-falls/TryHackMe_Stuff/assets/29386604/0458ed44-1787-4c00-b000-cdadfb72d3d5)

**Most Log's will typically have a source IP and destination IP so that it is possible to see who did what on the network.**

<h2>Severity Level</h2>

![image](https://github.com/dante-falls/TryHackMe_Stuff/assets/29386604/b69aea7f-9641-489d-a4d7-b42b8d43328c)

**Log entries are often given a severity level to categorize and communicate their relative importance or impact.**

<h2>Action Taken</h2>

**Some systems can actively generate an alert.**

![image](https://github.com/dante-falls/TryHackMe_Stuff/assets/29386604/616bdec7-0fdd-4da0-8070-810968c475bc)

<h2>Source/Destination Zones</h2>

**Some Log generators will include a section that explains where the incident took place between the systems.**

![image](https://github.com/dante-falls/TryHackMe_Stuff/assets/29386604/f7878522-a31d-433b-b403-5adbd5a29dc8)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
