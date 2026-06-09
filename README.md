# Bhavya Parvathi — Cybersecurity Portfolio

**Penetration Tester | API Security | SOC & Threat Detection**

 bhavyanagasai@gmail.com &nbsp;|&nbsp; 📍 India &nbsp;|&nbsp; [LinkedIn](www.linkedin.com/in/bhavya-naga-sai-parvathi-kshatri-3140251a2)

---

## About Me

Cybersecurity professional with hands-on experience in web application and API penetration testing, network reconnaissance, phishing threat investigation, and SIEM-based log analysis. I hold certifications from ISC², Red Team Leaders (CAISR), and Wallarm, and am currently pursuing CEH.

My engineering background (M.Tech) gives me a structured, systems-thinking approach to identifying attack chains and writing reports that both technical teams and management can act on.

---

## Certifications

| Certification | Issuer | Date |
|---|---|---|
| Certified in Cybersecurity (CC) | ISC² | Dec 2025 |
| CAISR — Adversarial Recon & Red Team Methodology | Red Team Leaders | Mar 2026 |
| API Security Certified Associate | Wallarm | Mar 2026 |
| DPDPA 2023 Certification | DPDPA Certification Body | Feb 2026 |
| Google Cybersecurity Professional Certificate | Google / Coursera | Sep 2025 |
| CEH — Certified Ethical Hacker *(in progress)* | EC-Council | Expected 2026 |

---

## Projects

### 🔴 OWASP Juice Shop — Full Vulnerability Assessment
**Target:** Juice Shop v19.1.1 &nbsp;|&nbsp; **Tools:** Burp Suite, Kali Linux &nbsp;|&nbsp; **Date:** Feb 2026

A black-box style assessment of OWASP Juice Shop covering 5 vulnerability classes:

| # | Vulnerability | Class | Severity |
|---|---|---|---|
| 1 | Authentication Bypass via Burp payload modification | Broken Authentication | High |
| 2 | IDOR — basketId manipulation (horizontal privilege escalation) | Broken Access Control | High |
| 3 | Sensitive Endpoint Exposure — /score-board unauthenticated | Security Misconfiguration | Medium |
| 4 | DOM XSS — iframe javascript: payload | XSS | Medium |
| 5 | Filter Bypass XSS — obfuscated iframe payload | XSS | Medium |

📄 **[Full Report (PDF)](SELF_PORTFOLIO_PROJECTS\OWASP_Juice_Shop_Vulnerability_Testing_Report_Parvathi.pdf)**  
*Report includes: PoC steps · Impact analysis · OWASP Top 10 mapping · Remediation recommendations*

---

### 🔴 API Penetration Testing — REST API Assessment
**Tools:** Burp Suite, Postman, OWASP ZAP &nbsp;|&nbsp; **Methodology:** OWASP API Top 10

Black-box assessment of a REST API. Identified 5 vulnerabilities including:
- **BOLA** (Broken Object Level Authorization) — unauthorised access to other users' resources
- **Broken Authentication** — weak token validation
- **Input Validation Flaws** — 2 findings rated High severity (CVSS)

📄 **[Full VAPT Report (PDF)](SELF_PORTFOLIO_PROJECTS\Wallarm_API_VAPT_Report.pdf)**

---

### 🟡 Network Reconnaissance & Vulnerability Scan
**Tools:** Nmap (NSE), Recon-ng

End-to-end footprinting and recon on an isolated lab environment:
- Mapped **12 open services** and **3 exposed ports**
- Used Nmap NSE for OS fingerprinting, service enumeration, and misconfiguration detection
- Flagged **4 exploitable vulnerabilities** with CVSS risk ratings

📄 **[Reconnaissance Report (PDF)](SELF_PORTFOLIO_PROJECTS\project_footprinting_reconnaissance_networkscanning.pdf)**

---

### 🟡 Phishing Triage & Threat Investigation
**Tools:** VirusTotal, Email Header Analyzer, MXToolbox

Investigated 10+ phishing email samples:
- Identified spoofed sender domains, malicious redirect URLs, DKIM/SPF failures
- Correlated IOCs using VirusTotal threat intelligence
- Documented attacker TTPs: domain spoofing, redirect chaining, header manipulation
- Produced structured threat report with recommended mail gateway filter rules

📄 **[Threat Investigation Report (PDF)](SELF_PORTFOLIO_PROJECTS\Phishing_Email_Detection_Guide.pdf)**

---

### 🔵 Internship: Cybersecurity Intern — Redynox *(Jan–Feb 2025)*
**Tools:** Burp Suite, OWASP ZAP, WebGoat, Wireshark, UFW/iptables, VirtualBox

- Web application security testing on OWASP WebGoat — exploited SQLi, XSS (Reflected/Stored), CSRF
- Built a VirtualBox network lab with Ubuntu router + Kali Linux client; configured iptables/UFW; captured and analysed DNS/ICMP/TCP traffic in Wireshark

---

## Technical Skills

```
Pen Testing     Burp Suite · OWASP ZAP · SQLi · XSS · CSRF · IDOR · Auth Bypass · CVSS
API Security    REST · OAuth 2.0 · JWT · BOLA · Postman · Wallarm methodology
Recon           Nmap (NSE) · Recon-ng · OpenVAS · Footprinting · Service enumeration
SOC / Detection Splunk (SIEM) · Log Analysis · Phishing Triage · IOC Documentation · VirusTotal
Network         Wireshark · TCP/IP · DNS · IDS/IPS · UFW/iptables
Scripting & OS  Python (basic) · Bash · Kali Linux · Ubuntu · Windows Security
GRC             DPDPA 2023 · Risk Assessment · Compliance Mapping
```

---

## How I Work

Every assessment I run ends with a structured report. Not just a list of findings — a document that includes:
- PoC steps (reproducible)
- CVSS severity ratings
- Root-cause analysis
- Prioritised remediation recommendations written for both developers and management

Reports are in the `/SELF_PORTFOLIO_PROJECTS` folder of each project.

---

*Open to Junior Penetration Tester, AppSec, and SOC Analyst roles. Feel free to reach out.*
