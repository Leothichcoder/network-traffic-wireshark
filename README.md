# Network Traffic Analysis — Wireshark

> Analyze packet captures to understand normal TCP/IP, DNS and HTTP/HTTPS behavior and identify suspicious indicators in a controlled lab.

## Objective

This project is a controlled, authorized training lab designed to demonstrate practical Cyber Security skills relevant to a **SOC Analyst / Security Analyst Fresher** role.

## Skills demonstrated

- Security monitoring and investigation
- Wireshark, Windows/Linux VM, browser, tcpdump optional
- Evidence-driven documentation
- Basic detection / assessment methodology
- Risk and remediation thinking

## Lab objectives

- Capture and inspect network traffic from a lab host.
- Explain TCP three-way handshake and connection teardown.
- Identify DNS request/response patterns.
- Filter traffic by IP, port and protocol.
- Document one anomalous or noteworthy flow with evidence.

## Lab workflow

1. Start a capture on the lab interface.
2. Generate normal DNS and HTTPS browsing traffic.
3. Use display filters for dns, tcp, http and ip.addr.
4. Inspect stream-level details and packet timing.
5. Record protocol, source, destination, ports and observations.


## Expected deliverables

- Working lab notes
- Screenshots showing the actual lab state/results
- Findings table
- Remediation notes
- Final lab report

## Evidence policy

**Replace every screenshot placeholder with evidence from your own lab.** Never present generated or edited images as real tool output. Redact usernames, public IP addresses, tokens, API keys and other sensitive data before publishing.

## Screenshots

- `screenshots/01-capture-overview.png`
- `screenshots/02-dns-filter.png`
- `screenshots/03-tcp-handshake.png`
- `screenshots/04-stream-analysis.png`
- `screenshots/05-finding-summary.png`


## Report

See [`lab-report/LAB-REPORT.md`](lab-report/LAB-REPORT.md).

## Safety

Run this project only against systems you own or are explicitly authorized to test. The lab should be isolated from unrelated systems.

## References

- Wazuh documentation: https://documentation.wazuh.com/
- OWASP Juice Shop: https://owasp.org/www-project-juice-shop/
- Nmap documentation: https://nmap.org/book/man.html
- Wireshark User's Guide: https://www.wireshark.org/docs/
- Sysinternals Sysmon: https://learn.microsoft.com/sysinternals/downloads/sysmon
## Repository structure

```text
.
├── README.md
├── lab-report/
│   └── LAB-REPORT.md
├── screenshots/
│   ├── README.md
│   ├── 01-*.png
│   ├── 02-*.png
│   └── ...
├── docs/
│   ├── scope.md
│   ├── findings.md
│   └── remediation.md
├── evidence/
│   └── README.md
└── .gitignore
```
