# Lab Report — Network Traffic Analysis — Wireshark

## 1. Executive Summary

**Analyst:** Pham Minh Quang  
**Role target:** Cyber Security Fresher / SOC Analyst  
**Lab status:** Training environment  
**Date:** YYYY-MM-DD  

### Summary

Focus on observable evidence: protocol, endpoint, port, packet sequence, timing and why the flow is normal or suspicious.

## 2. Scope

- Lab hosts: `<LAB_HOSTS>`
- Network range / application: `<LAB_SCOPE>`
- Tools: `Wireshark, Windows/Linux VM, browser, tcpdump optional`
- Authorization: Self-owned / explicitly authorized training environment

## 3. Objectives

- Capture and inspect network traffic from a lab host.
- Explain TCP three-way handshake and connection teardown.
- Identify DNS request/response patterns.
- Filter traffic by IP, port and protocol.
- Document one anomalous or noteworthy flow with evidence.


## 4. Environment

| Component | Value |
|---|---|
| Attacker / analyst VM | `<VALUE>` |
| Target / endpoint | `<VALUE>` |
| Network | `<VALUE>` |
| Tool versions | `<VALUE>` |

## 5. Methodology

1. Start a capture on the lab interface.
2. Generate normal DNS and HTTPS browsing traffic.
3. Use display filters for dns, tcp, http and ip.addr.
4. Inspect stream-level details and packet timing.
5. Record protocol, source, destination, ports and observations.


## 6. Evidence

Replace the placeholders below with your own screenshots and filenames.

| ID | Evidence | Observation |
|---|---|---|
| E01 | `../screenshots/01-capture-overview.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E02 | `../screenshots/02-dns-filter.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E03 | `../screenshots/03-tcp-handshake.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E04 | `../screenshots/04-stream-analysis.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E05 | `../screenshots/05-finding-summary.png` | `<WHAT THE SCREENSHOT PROVES>` |


## 7. Findings

| ID | Finding | Severity | Evidence | Recommendation |
|---|---|---|---|---|
| F-01 | `<FINDING>` | Low/Medium/High | E01 | `<REMEDIATION>` |

## 8. Investigation / Analysis

### What happened?
`<Describe the observed behavior in factual terms.>`

### Why does it matter?
`<Describe security relevance and likely impact.>`

### What additional evidence would you collect?
`<Logs, process tree, DNS context, user context, endpoint details, etc.>`

## 9. False Positives / Limitations

`<Describe benign explanations, data gaps and lab limitations.>`

## 10. Remediation / Hardening

- `<ACTION 1>`
- `<ACTION 2>`
- `<ACTION 3>`

## 11. Analyst Takeaways

- `<WHAT I LEARNED>`
- `<WHAT I WOULD AUTOMATE>`
- `<WHAT I WOULD INVESTIGATE NEXT>`

## 12. Conclusion

`<2–4 sentence conclusion focused on evidence, process and next steps.>`
