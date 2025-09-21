# HTB-machines

Penetration testing write-ups by Frans Coomans, OSCP, for retired Hack The Box (HTB) machines. 

## Write-Ups

| Machine Write-Up                     | Difficulty | Notes                                                                                                                                                                                     |
| ------------------------------------ | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Fluffy](Fluffy/README.md)           | Easy       | CVE-2025-24071, BloodHound, ADCS Shadow Credentials, ACE Abuse, ESC16,<br>PrivEsc, Password Cracking (NetNTLMv2), certipy-ad                                                              |
| [Planning](Planning/README.md)       | Easy       | Grafana, CVE-2024-9264, Reverse Shell, SSH port forwarding, Password reuse, <br>PrivEsc through Crontab UI                                                                                |
| [Environment](Environment/README.md) | Medium     | CVE-2024-52301, Reverse Shell, Authentication Bypass, Arbitrary File upload,<br>Web shell, Weak permissions, PrivEsc through environment variable, SSH                                    |
| [TheFrizz](TheFrizz/README.md)       | Medium     | CVE-2023-45878, Reverse Shell, Password Cracking (SHA256), Chisel, <br>Password reuse, Active Directory, Kerberos auth, SSH, Recycle Bin artifact recovery,<br>GPO Abuse to PrivEsc       |
| [Nocturnal](Nocturnal/README.md)     | Easy       | IDOR, Code Analysis, Command Injection, Reverse Shell, Password Cracking (MD5), <br>SSH port forwarding, Password reuse, CVE-2023-46818                                                   |
| [Code](Code/README.md)               | Easy       | Code Injection via Python sandbox bypass (`sys.modules`), Reverse Shell, <br>DB Looting, Password Cracking (MD5), SSH Lateral Move, <br>PrivEsc via backup script path traversal          |
| [Cypher](Cypher/README.md)           | Medium     | Cypher Injection, Java JAR Analysis, Command Injection, Reverse Shell, <br>PrivEsc (BBOT)                                                                                                 |
| [Dog](Dog/README.md)                 | Easy       | .git Enumeration, Backdrop RCE, PrivEsc (bee)                                                                                                                                             |
| [Cat](Cat/README.md)                 | Medium     | Fuzzing, XSS, Session Hijacking, SQLi, Credential Hunting, CVE-2024-6886, <br>Gitea Enumeration                                                                                           |
| [Haze](Haze/README.md)               | Hard       | Splunk, CVE-2024-36991, Path Traversal, Username Enumeration, BloodHound,  <br>Kerberos, AD ACE Abuse, ADCS Shadow Credentials, Credential Hunting,<br>Splunk reverse shell, PrintSpoofer |

## Contact

- GitHub: https://github.com/fcoomans
- LinkedIn: https://www.linkedin.com/in/frans-coomans/