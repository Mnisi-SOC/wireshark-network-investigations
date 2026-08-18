# Wireshark Network Investigations

A collection of **network traffic analysis investigations** performed using Wireshark and related network-analysis tools.

This repository documents practical exercises focused on identifying suspicious activity, investigating malware infections, and solving packet-analysis challenges. The goal is to build practical skills relevant to **SOC Analyst / Blue Team** work.

## Repository Structure

```text
wireshark-network-investigations/
├── malware-infections/
│   ├── images/
│   ├── malware-traffic-analysis-01.md
│   └── malware-traffic-analysis-02.md
│
├── thm-challenges/
│   ├── images/
│   └── carnage.md
│
└── README.md
```

## Contents

### Malware Infections

Investigations based on **malware traffic analysis**. These write-ups focus on examining PCAP files, identifying infected hosts, tracing suspicious network activity, and extracting indicators of compromise (IOCs).

- `malware-infections/malware-traffic-analysis-01.md`
- `malware-infections/malware-traffic-analysis-02.md`
- Supporting screenshots are stored in `malware-infections/images/`

### TryHackMe Challenges

Write-ups for Wireshark and packet-analysis challenges completed on **TryHackMe**.

- `thm-challenges/carnage.md`
- Supporting screenshots are stored in `thm-challenges/images/`

## Skills Demonstrated

- Wireshark packet analysis
- PCAP investigation
- Network traffic filtering
- TCP/IP and protocol analysis
- HTTP/HTTPS traffic analysis
- DNS investigation
- FTP traffic analysis
- Identifying suspicious network behaviour
- Malware traffic investigation
- Host and session identification
- Extracting Indicators of Compromise (IOCs)
- Following TCP streams
- Packet-level evidence collection
- Defanging IP addresses and domains in documentation

## Tools

| Tool | Purpose |
|---|---|
| **Wireshark** | Packet capture analysis and network investigation |
| **Kali Linux** | Security testing and analysis environment |
| **TryHackMe** | Hands-on cybersecurity training |

## Investigation Methodology

The investigations in this repository generally follow a structured workflow:

1. **Understand the scenario**
   - Identify the objective and available evidence.
   - Determine what type of traffic or activity is being investigated.

2. **Inspect the PCAP**
   - Review protocols, endpoints, conversations, and packet statistics.
   - Establish a baseline of normal traffic.

3. **Filter the traffic**
   - Use Wireshark display filters to narrow down relevant packets.
   - Investigate suspicious IP addresses, domains, ports, protocols, and sessions.

4. **Follow network sessions**
   - Follow TCP/UDP streams where appropriate.
   - Examine requests, responses, commands, and transferred data.

5. **Identify Indicators of Compromise**
   - Record suspicious IP addresses, domains, URLs, filenames, user agents, ports, and other artifacts.

6. **Validate findings**
   - Correlate multiple packets and protocols before drawing conclusions.
   - Preserve packet numbers and screenshots as evidence where useful.

7. **Document the investigation**
   - Explain the findings clearly.
   - Include relevant evidence and the reasoning used to reach each conclusion.

## Documentation Format

Each investigation aims to document:

- **Objective**
- **Scenario / Background**
- **Tools Used**
- **Methodology**
- **Packet Analysis**
- **Findings**
- **Indicators of Compromise**
- **Evidence / Screenshots**
- **Conclusion**

Screenshots are kept in the corresponding `images/` directory to keep the write-ups organised.

## Why This Repository?

This repository is part of my hands-on cybersecurity learning and is intended to demonstrate practical **network investigation and SOC analysis skills**.

Rather than only recording answers, the write-ups focus on **how the evidence was found and how the investigation was performed**. This makes the repository useful as both a learning record and a cybersecurity portfolio.

## Disclaimer

All investigations and challenge material are performed in **authorised training environments**, such as TryHackMe and publicly available malware-traffic-analysis exercises.

This repository is intended for **educational and defensive security purposes**.

---

**Focus:** Network Traffic Analysis • Wireshark • SOC / Blue Team • Incident Investigation
