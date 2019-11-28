# Incident Response
>  List of useful resources utilized in incident handling process to identify,contain and eradicate those who where illegally inside :smiling_imp: :gun:

## Getting Started

Repository documents will help you understand where to monitor or configure to prepare for your incident response tasks. Resources are organazied in multiple directories based on different step of incident handling procedure. if you are new, you should take a look at preparation directory for a start point.

### Preparation

In addition to what is required in preparation phase of incident handling (including: compile a list of all your assets,create a communication plan, develop and document IR policies and etc), this directory contain which security events or IDs, and at what thresholds, these events should be investigated.

- [Windows ATT&CK Logging Cheat Sheet (PDF)](https://github.com/ikhosravi/Incident-Response/blob/master/Preparation/Windows%2BATT%26CK_Logging%2BCheat%2BSheet_ver_Sept_2018.pdf): Map the tactics and techniques of the Mitre ATT&CK framework to Windows audit log event IDs and Sysmon unique IDs in order to know what to collect and harvest, and also what you could hunt for using Windows logging.

### Identification

- [Critical Windows Events (Powershell)](https://github.com/ikhosravi/Incident-Response/blob/master/Identification/check-critical-events.ps1): A Powershell script to report important windows events such as Successful logon,new user account created, user account enabled,password reset,local group membership changed, network share was accessed (look for suspicious C$,IPC$), new service installed, security log cleared, audit policy changed and etc.

## Disclaimer

Opinions and instructions in this repository are mine alone and do not reflect those of my current or past employers. 

## Acknowledgments

* MalwareArchaeology.com
* John Strand
