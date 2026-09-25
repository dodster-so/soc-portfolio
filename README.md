# SOC Portfolio

## About
My home SOC lab for learning SOC L1 skills.

## Lab Environment
- Ubuntu Server 26.04
- Wazuh SIEM (manager, indexer, dashboard)
- Windows 11 agent (DESKTOP-VAHTOSI)

## Cases
1. **WHOIS check** — IP 98.85.38.9:9000 → Amazon AWS. False positive.
2. **Event ID 4625** — Failed logon for Admin. Normal.
3. **Event ID 4624** — Successful logon for Admin. Legitimate.
4. **Nmap Scan**
- Source: Nmap + Wireshark
- Target: 192.168.1.44
- Result: 22/tcp open ssh, 443/tcp open ssl/https, 998 closed ports
- Conclusion: Only SSH and HTTPS open. Normal for Wazuh server.

## Skills
- Windows Event Logs (4624, 4625, 4634)
- Wazuh SIEM
- WHOIS, VirusTotal
- MITRE ATT&CK
