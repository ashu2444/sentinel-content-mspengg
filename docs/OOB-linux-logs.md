# OOB Analytics Rules – Linux Logs (Syslog)

**Log Source:** Linux (Auth, System, SFTP, Proxy)  
**Integration Method:** Agent Based / Syslog  
**Content Hub Solution:** Syslog

---

## Available OOB Analytics Rules

- SFTP File transfer folder count above threshold
- SFTP File transfer above threshold
- SSH - Potential Brute Force
- Failed logon attempts in authpriv
- Squid proxy events related to mining pools
- Squid proxy events for ToR proxies
- NRT Squid proxy events related to mining pools

---

## Notes
- Linux authentication and system logs are ingested using the Syslog connector.
- Proxy-related detections apply to Squid proxy logs collected via Syslog.
- These are Microsoft-managed Out-of-the-Box analytics rules.
- Rules are enabled and maintained via Content Hub in Microsoft Sentinel.
