# Shankar Bettadapura | Cybersecurity & AI Governance

**M.S. Cybersecurity Studies | CompTIA Security+ | CISA (in progress) | CRISC (in progress) | ISO 42001 (in progress)**
Former U.S. Army All-Source Intelligence Analyst. Currently focused on IT GRC, AI governance, and security operations.

---

## Portfolio Projects

| #  | Project | Description | Frameworks | Date |
| --- | --- | --- | --- | --- |
| 1  | [BitNet + TurboQuant Ablation Study — Kubo Technologies](https://github.com/shankar-bettadapura/kubo-bitnet-turboquant-ablation) | Trained a 25M parameter GPT from scratch and compared BitNet ternary quantization against TurboQuant KV cache compression on an RTX 3070 | PyTorch, nanoGPT | April 2026 |
| 2  | [AI Governance & Risk Assessment — NovaSphere Technologies](https://github.com/shankar-bettadapura/ai-governance-risk-assessment) | Consulting-style AI governance assessment for a fictional mid-size SaaS company covering shadow AI, adversarial robustness, bias, and vendor risk | NIST AI RMF 1.0, ISO/IEC 42001:2023 | April 2026 |
| 3  | [Model Risk Assessment — Kubo Technologies](https://github.com/shankar-bettadapura/model-risk-assessment-kubo) | Governance assessment of the Kubo ablation study results, evaluating production deployment readiness and documenting three critical governance gaps | NIST AI RMF 1.0, ISO/IEC 42001:2023 | April 2026 |
| 4  | [Home Lab SIEM — Wazuh Threat Detection](https://github.com/shankar-bettadapura/siem-homelab-wazu) | Deployed Wazuh SIEM in a virtualized lab, simulated 4 MITRE ATT&CK techniques, and built custom detection rules across 58 generated alerts | Wazuh, MITRE ATT&CK | April 2026 |
| 5  | [Threat Intelligence Aggregator](https://github.com/shankar-bettadapura/threat-intel-aggregator) | CLI tool that queries AlienVault OTX, AbuseIPDB, and URLhaus to enrich IPs, domains, URLs, and file hashes — outputting a structured HTML report with CLEAN / SUSPICIOUS / MALICIOUS verdicts | Python, MITRE ATT&CK | April 2026 |
| 6  | [APT TTP Mapper v1.0](https://github.com/shankar-bettadapura/apt-ttp-mapper) | Python tool that extracts and maps adversary TTPs from threat intelligence reports to the MITRE ATT&CK Enterprise framework using a two-pass matching engine. Tested against CISA Advisory AA26-097A — surfaced 9 unique TTPs and identified a coverage gap between ATT&CK Enterprise and ATT&CK for ICS | Python, MITRE ATT&CK Enterprise | April 2026 |
| 7  | [APT TTP Mapper v1.1](https://github.com/shankar-bettadapura/apt-ttp-mapper-v1.1) | Refactored v1.0 into a multi-module Python package with ATT&CK for ICS dataset support, OCR for scanned PDFs, and tactic frequency chart output. Tested against the same CISA AA26-097A — achieved 4/4 explicit T-ID coverage, up from 2/4 in v1.0 | Python, MITRE ATT&CK Enterprise, MITRE ATT&CK ICS | April 2026 |
| 8  | [Wazuh IR Simulation — Operation Phantom Login](https://github.com/shankar-bettadapura/wazuh-ir-simulation) | Full incident response simulation using Wazuh 4.8 and Sysmon-enriched telemetry on a Windows 11 endpoint. Executed a MITRE ATT&CK-mapped kill chain with Atomic Red Team, generated 815 alerts including 22 high-severity detections, and produced a formal IR report with ATT&CK coverage map and detection gap analysis | Wazuh, MITRE ATT&CK, Sysmon, Atomic Red Team | May 2026 |
| 9  | [AI Bias and Fairness Auditor](https://github.com/shankar-bettadapura/bias-auditor) | Python pipeline that trains a Logistic Regression classifier on the UCI Adult Income dataset and audits it for demographic bias across sex and race attributes, producing 4 FAIL findings mapped to NIST AI RMF MEASURE 2.5 and 2.6 controls with an automated HTML findings report | Python, Fairlearn, NIST AI RMF 1.0 | May 2026 |
| 10 | [GRC Control Gap Analyzer](https://github.com/shankar-bettadapura/grc-control-gap-analyzer) | Python CLI tool that ingests a control inventory CSV, maps it against all 93 ISO 27001:2022 Annex A controls, scores residual risk using a domain-weighted model, and generates an Excel workbook and HTML report covering the executive summary, gap heatmap, control register, and prioritised remediation roadmap | Python, ISO/IEC 27001:2022 | May 2026 |
| 11 | [Phishing Analysis Report](https://github.com/shankar-bettadapura/phishing-analysis-report) | Python CLI tool that ingests a raw .eml file, parses email headers and body across a five-module pipeline, extracts IOCs across four types (URLs, IPs, domains, SHA256 hashes), enriches them against AlienVault OTX, AbuseIPDB, and URLhaus, and generates a dark-themed HTML triage report and four-sheet Excel workbook with CLEAN / SUSPICIOUS / MALICIOUS verdicts | Python, AlienVault OTX, AbuseIPDB, URLhaus | June 2026 |
| 12 | [Vulnerability Intelligence Correlator](https://github.com/shankar-bettadapura/vulnerability-intelligence-correlator) | Python pipeline that pulls freshly published CVEs from the NVD API, correlates them against the CISA Known Exploited Vulnerabilities catalog, enriches each with an EPSS exploitation-probability percentile, and computes a composite priority score to produce a prioritized patch-action report. Run against a 30-day window of 7,413 CVEs, correctly surfaced 13 CRITICAL-tier and 15 KEV-confirmed vulnerabilities, outputting both an interactive HTML dashboard and an Excel workbook with conditional formatting | Python, NVD API, CISA KEV, EPSS | June 2026 |
| 13 | [Network Traffic Anomaly Detector](https://github.com/shankar-bettadapura/network-anomaly-detector) | Five-module Python pipeline that ingests raw PCAP captures, reconstructs bidirectional network flows with Scapy, engineers per-flow/per-host/per-connection-pair statistical features, trains an unsupervised Isolation Forest on baseline traffic to score anomalous behavior, and maps flagged patterns to named MITRE ATT&CK techniques. Run against synthetic mixed traffic, correctly flagged a port scanner (T1046) and a C2 beacon (T1071) while correctly leaving normal browsing traffic unlabeled despite a marginal statistical false positive, outputting both a dark-themed HTML dashboard and an Excel workbook | Python, Scapy, scikit-learn, MITRE ATT&CK | July 2026 |

---

## Focus Areas

- IT GRC and AI Governance
- Risk register development and control gap analysis
- NIST AI RMF, ISO/IEC 42001, ISO 27001
- Security operations and threat intelligence
- All-source intelligence analysis

---

## Certifications

- CompTIA Security+
- CISA (in progress)
- CRISC (in progress)
- ISO 42001 AI Governance (in progress)

---

## Writing

I write about cybersecurity, AI governance, and national security on Substack.
🔗 [shankarbettadapura.substack.com](https://shankarbettadapura.substack.com)

---

## Connect

🔗 [LinkedIn](https://www.linkedin.com/in/shankar-bettadapura) | 🔗 [Substack](https://shankarbettadapura.substack.com)
