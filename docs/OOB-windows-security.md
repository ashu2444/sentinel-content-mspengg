# OOB Analytics Rules – Windows Security Events

**Log Source:** Windows Security Events  
**Integration Method:** Agent Based (AMA)  
**Source:** Microsoft Sentinel Content Hub

---

## Available OOB Analytics Rules

- NRT Security Event log cleared
- Excessive Windows Logon Failures
- NRT Base64 Encoded Windows Process Command-lines
- New EXE deployed via Default Domain or Default Domain Controller Policies
- Gain Code Execution on ADFS Server via SMB + Remote Service or Scheduled Task
- Starting or Stopping HealthService to Avoid Detection
- Process Execution Frequency Anomaly
- AD FS Remote Auth Sync Connection
- Potential Fodhelper UAC Bypass
- AD user enabled and password not set within 48 hours
- Scheduled Task Hide
- Potential re-named sdelete usage
- NRT Process executed from binary hidden in Base64 encoded file
- Microsoft Entra ID Local Device Join Information and Transport Key Registry Keys Access
- Non Domain Controller Active Directory Replication
- SecurityEvent - Multiple authentication failures followed by a success
- AD FS Remote HTTP Network Connection
- Sdelete deployed via GPO and run recursively
- ADFS Database Named Pipe Connection
- Exchange OAB Virtual Directory Attribute Containing Potential Webshell

---

## Notes
- These are Microsoft-managed Out-of-the-Box analytics rules.
- Rule availability depends on the Windows Security Events data connector.
- These rules are enabled/disabled via Content Hub, not deployed via GitHub.
