No | Port | Protocol / Service | Purpose | Security Risk | Mitigation | Remark |
|----|------|--------------------|---------|---------------|------------|--------|
| 1 | 1 | TCPMUX | TCP service multiplexer | Unauthorized access | Disable if unused | Legacy |
| 2 | 2 | COMPRESSNET | Network compression | Obsolete protocol | Disable | Deprecated |
| 3 | 3 | COMPRESSNET | Compression service | Vulnerabilities | Disable | Deprecated |
| 4 | 4 | Unassigned | Reserved | Unknown usage | Block | Reserved |
| 5 | 5 | RJE | Remote Job Entry | Weak authentication | Disable | Legacy |
| 6 | 6 | Unassigned | Reserved | Unknown | Block | Reserved |
| 7 | 7 | ECHO | Echo service | DDoS reflection | Disable | Diagnostic |
| 8 | 8 | Unassigned | Reserved | Unknown | Block | Reserved |
| 9 | 9 | DISCARD | Discard service | Abuse for attack | Disable | Diagnostic |
|10 | 10 | Unassigned | Reserved | Unknown | Block | Reserved |
|11 | 11 | SYSTAT | System status | Info disclosure | Disable | Insecure |
|12 | 12 | Unassigned | Reserved | Unknown | Block | Reserved |
|13 | 13 | DAYTIME | Time service | Info leak | Disable | Obsolete |
|14 | 14 | Unassigned | Reserved | Unknown | Block | Reserved |
|15 | 15 | Unassigned | Reserved | Unknown | Block | Reserved |
|16 | 16 | Unassigned | Reserved | Unknown | Block | Reserved |
|17 | 17 | QOTD | Quote of the day | Info disclosure | Disable | Obsolete |
|18 | 18 | MSP | Message send | Rarely used | Disable | Legacy |
|19 | 19 | CHARGEN | Character generator | DDoS amplification | Disable | Dangerous |
|20 | 20 | FTP-DATA | File transfer data | Data sniffing | Use SFTP/FTPS | Insecure |
|21 | 21 | FTP | File transfer control | Brute-force | Use SFTP | Insecure |
|22 | 22 | SSH | Secure remote login | Brute-force | Use key auth | Secure |
|23 | 23 | TELNET | Remote login | Plaintext creds | Disable | Insecure |
|24 | 24 | Unassigned | Reserved | Unknown | Block | Reserved |
|25 | 25 | SMTP | Email sending | Spam relay | Use TLS | Mail |
|26 | 26 | Unassigned | Reserved | Unknown | Block | Reserved |
|27 | 27 | NSP | Network service | Obsolete | Disable | Legacy |
|28 | 28 | Unassigned | Reserved | Unknown | Block | Reserved |
|29 | 29 | MSG-ICP | Messaging | Obsolete | Disable | Legacy |
|30 | 30 | Unassigned | Reserved | Unknown | Block | Reserved |
|31 | 31 | MSG-AUTH | Message auth | Weak auth | Disable | Legacy |
|32 | 32 | Unassigned | Reserved | Unknown | Block | Reserved |
|33 | 33 | DSP | Display support | Obsolete | Disable | Legacy |
|34 | 34 | Unassigned | Reserved | Unknown | Block | Reserved |
|35 | 35 | PRINTER | Print service | Unauthorized print | Restrict | Legacy |
|36 | 36 | Unassigned | Reserved | Unknown | Block | Reserved |
|37 | 37 | TIME | Time service | Info leak | Disable | Obsolete |
|38 | 38 | RAP | Route access | Route abuse | Disable | Dangerous |
|39 | 39 | RLP | Resource location | Info leak | Disable | Obsolete |
|40 | 40 | Unassigned | Reserved | Unknown | Block | Reserved |
|41 | 41 | GRAPHICS | Graphics service | Obsolete | Disable | Legacy |
|42 | 42 | NAMESERVER | Host name service | Spoofing | Use DNSSEC | Obsolete |
|43 | 43 | WHOIS | Domain info | Data scraping | Rate limit | Public |
|44 | 44 | MPM | Messaging | Obsolete | Disable | Legacy |
|45 | 45 | MPM-FLAGS | Messaging flags | Obsolete | Disable | Legacy |
|46 | 46 | MPM-SND | Messaging send | Obsolete | Disable | Legacy |
|47 | 47 | NI-FTP | FTP alt | Insecure | Disable | Legacy |
|48 | 48 | AUDITD | Audit service | Info exposure | Restrict | Rare |
|49 | 49 | TACACS | Authentication | Weak encryption | Use TACACS+ | Legacy |
|50 | 50 | RE-MAIL-CK | Mail checking | Obsolete | Disable | Legacy |
|51 | 51 | LA-MAINT | Remote maintenance | Unauthorized | Disable | Dangerous |
|52 | 52 | XNS-TIME | Time sync | Obsolete | Disable | Legacy |
|53 | 53 | DNS | Name resolution | Cache poisoning | DNSSEC | Critical |
|54 | 54 | XNS-CH | Clearinghouse | Obsolete | Disable | Legacy |
|55 | 55 | ISI-GL | Graphics | Obsolete | Disable | Legacy |
|56 | 56 | XNS-AUTH | Auth service | Weak auth | Disable | Legacy |
|57 | 57 | MTP | Mail transfer | Insecure | Disable | Obsolete |
|58 | 58 | XNS-MAIL | Mail service | Obsolete | Disable | Legacy |
|59 | 59 | ASSEMBLER | Assembly | Obsolete | Disable | Legacy |
|60 | 60 | FTP-ALT | FTP alternate | Insecure | Disable | Legacy |
|61 | 61 | NI-MAIL | Mail | Obsolete | Disable | Legacy |
|62 | 62 | ACAS | Auth service | Weak auth | Disable | Legacy |
|63 | 63 | WHOIS++ | Extended whois | Data scrape | Rate limit | Public |
|64 | 64 | COVIA | Communication | Obsolete | Disable | Legacy |
|65 | 65 | TACACS-DS | Auth database | Sensitive data | Restrict | Legacy |
|66 | 66 | SQL-NET | SQL service | SQL injection | Firewall | Database |
|67 | 67 | BOOTP | IP assignment | Rogue DHCP | Secure DHCP | Network |
|68 | 68 | BOOTP | Client IP | Spoofing | Secure DHCP | Network |
|69 | 69 | TFTP | Trivial FTP | No auth | Disable | Insecure |
|70 | 70 | GOPHER | Document sharing | Obsolete | Disable | Legacy |
|71 | 71 | NETRJS | Remote jobs | Unauthorized | Disable | Legacy |
|72 | 72 | NETRJS-2 | Remote jobs | Unauthorized | Disable | Legacy |
|73 | 73 | NETRJS-3 | Remote jobs | Unauthorized | Disable | Legacy |
|74 | 74 | NETRJS-4 | Remote jobs | Unauthorized | Disable | Legacy |
|75 | 75 | DEOS | Distributed OS | Obsolete | Disable | Legacy |
|76 | 76 | DEOS | Distributed OS | Obsolete | Disable | Legacy |
|77 | 77 | PRIVATE-RJE | Private jobs | Obsolete | Disable | Legacy |
|78 | 78 | VETTCP | Vet protocol | Rare | Disable | Obsolete |
|79 | 79 | FINGER | User info | Info leak | Disable | Insecure |
|80 | 80 | HTTP | Web traffic | Web attacks | Use HTTPS | Public |
|81 | 81 | TORPARK | Proxy | Malware | Restrict | Proxy |
|82 | 82 | XFER | File transfer | Insecure | Disable | Rare |
|83 | 83 | MIT-ML-DEV | Dev service | Obsolete | Disable | Legacy |
|84 | 84 | CTF | Dev testing | Insecure | Disable | Dev |
|85 | 85 | MIT-ML-DEV | Dev service | Obsolete | Disable | Legacy |
|86 | 86 | MFCOBOL | Cobol | Obsolete | Disable | Legacy |
|87 | 87 | PRIVATE | Terminal | Obsolete | Disable | Legacy |
|88 | 88 | KERBEROS | Authentication | Ticket attacks | Kerberos 5 | Secure |
|89 | 89 | SU-MIT-TG | Gateway | Rare | Disable | Obsolete |
|90 | 90 | DNSIX | Secure DNS | Deprecated | Disable | Legacy |
|91 | 91 | MIT-DOV | Dev service | Obsolete | Disable | Legacy |
|92 | 92 | NPP | Network printing | Print abuse | Restrict | Printer |
|93 | 93 | DCP | Device control | Unauthorized | Restrict | Legacy |
|94 | 94 | OBJCALL | Object call | Obsolete | Disable | Legacy |
|95 | 95 | SUPDUP | Terminal | Plaintext | Disable | Insecure |
|96 | 96 | DIXIE | Info service | Obsolete | Disable | Legacy |
|97 | 97 | SWIFT-RVF | Finance | Sensitive data | Encrypt | Financial |
|98 | 98 | TACNEWS | News | Obsolete | Disable | Legacy |
|99 | 99 | METAGRAM | Metadata | Obsolete | Disable | Legacy |
|100 | 100 | NEWACCT | Account creation | Unauthorized accounts | Restrict | Security |
