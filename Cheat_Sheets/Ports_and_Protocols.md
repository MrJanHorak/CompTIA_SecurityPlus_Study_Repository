# Cheat Sheet: Ports and Protocols (Security+ Focus)

## High-Value Port Table

| Port      | Protocol | Security Context                                    |
| --------- | -------- | --------------------------------------------------- |
| 20/21     | FTP      | Insecure file transfer; prefer SFTP/FTPS            |
| 22        | SSH/SFTP | Secure remote admin and transfer                    |
| 23        | Telnet   | Insecure remote access                              |
| 25        | SMTP     | Mail transfer; often abused in phishing campaigns   |
| 53        | DNS      | Name resolution; supports tunneling abuse scenarios |
| 67/68     | DHCP     | Dynamic addressing                                  |
| 80        | HTTP     | Unencrypted web traffic                             |
| 88        | Kerberos | Ticket-based authentication                         |
| 110       | POP3     | Legacy insecure mail retrieval                      |
| 143       | IMAP     | Mail sync; use IMAPS for secure transport           |
| 161/162   | SNMP     | Management and traps; use SNMPv3                    |
| 389       | LDAP     | Directory queries; insecure by default              |
| 443       | HTTPS    | Secure web traffic over TLS                         |
| 445       | SMB      | File sharing; common lateral movement target        |
| 514       | Syslog   | Centralized logging                                 |
| 636       | LDAPS    | Secure LDAP                                         |
| 1812/1813 | RADIUS   | Centralized AAA                                     |
| 3389      | RDP      | Remote desktop, high abuse target                   |

## Memory Grouping

- Remote access: 22, 23, 3389
- Directory/auth: 88, 389, 636, 1812/1813
- Web/data: 80, 443, 445
- Network services: 53, 67/68, 161/162, 514

---

See also: [Domain 2.1](../Domain_2_Threats_Vulnerabilities_and_Mitigations/2.1_Threat_Actors_and_Attack_Vectors.md) and [Domain 4.2](../Domain_4_Security_Operations/4.2_Monitoring_Detection_and_Analysis.md)
