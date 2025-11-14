# OmerD--portfolio

# 👋 Hi, I'm Omer
**SOC Analyst | Cybersecurity | AI Tools Builder**

📍 Central District, Israel  
📧 omersecurly@gmail.com  

---

## 🚀 About Me
I’m a SOC Analyst with hands-on experience in SIEM/EDR tools, incident handling, and building AI-driven tools that support investigation, enrichment, and reporting. I enjoy creating intelligent systems that make SOC work faster, clearer, and more consistent.

---

## 🛠 Projects

### 🔹 AI SOC Investigation Agent (Bilingual, Explainable)

A bilingual (EN/HE) autonomous investigation agent designed for MSSP environments.  
It performs triage, enrichment, correlation, MITRE ATT&CK mapping, risk scoring and
generates delivery-ready Slack, email and deep IR reports with explainable reasoning
and strict anti-hallucination logic.  
> Logic and design built, not yet wired to a SOAR platform.

**High-Level Architecture:**
```text
[Alert / Event]
      ↓
[AI Intake + Context Building]
      ↓
[Enrichment Layer]
  • IP / URL / Hash reputation
  • User / Host context
  • Geolocation / Threat Intel
      ↓
[Correlation Engine]
  • Timeline reconstruction
  • Related alerts & entities
      ↓
[MITRE ATT&CK Mapping + Risk Scoring]
      ↓
[Output Layer]
  • Slack triage message
  • Email-style IR report
  • Deep-dive investigation narrative

```
### 🔹 Natural-Language to ATP Query Generator

A tool that converts natural language into Microsoft Defender ATP KQL queries, making
investigations more intuitive and reducing time to query. Currently expanding to support
Cortex XDR and other platforms.

High-Level Architecture:
```text

text
Copy code
[Analyst Question]
      ↓
[NLP Layer]
  • Intent detection
  • Entity extraction (user, host, IP, time)
      ↓
[Query Template Selector]
      ↓
[Query Builder]
  • KQL/ATP syntax
  • Filters + time ranges
      ↓
[Output: Ready-to-run ATP query]
      ↓
[Future: Cortex XDR / other platforms]

```

🧰 Skills
SIEM: QRadar, Splunk

XDR/EDR: Cortex XDR, SentinelOne, CrowdStrike Falcon, Microsoft Defender for Endpoint (ATP)

Tools: Wireshark, Event Viewer, Python (security tools)

Domains: Incident Response, Alert Triage, Investigation Logic, MITRE ATT&CK (familiarity)

OS: Windows, Linux (fundamentals)

📬 Contact
📧 omersecurly@gmail.com
