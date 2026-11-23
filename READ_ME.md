<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:00C2FF&height=210&section=header&text=PRAVEEN%20S&fontSize=48&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35&desc=Cybersecurity%20%7C%20VAPT%20%7C%20SOC%20%7C%20Network%20Security&descAlignY=60&descSize=17" alt="Profile header" />
</p>

<p align="center">
  <a href="mailto:praveen.cybersecurity28@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/praveen-s-cyber"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://komarev.com/ghpvc/?username=praveen-s-cyber&style=for-the-badge&color=1F6FEB&label=PROFILE+VIEWS" alt="Profile views" />
</p>

<p align="center">
  <b>Security-minded IT professional focused on vulnerability assessment, web security, network defense, and security operations.</b>
</p>

---

## About Me

I'm a Computer Science graduate interested in cybersecurity, security assessment, infrastructure security, and threat detection. I enjoy examining systems, documenting security observations, understanding attack surfaces, and translating technical findings into practical remediation recommendations.

- 🔎 Focus areas: **Vulnerability Assessment & Penetration Testing (VAPT), Web Security, Network Security**
- 🛡️ Secondary interests: **SOC operations, SIEM, Incident Response, Cloud Security**
- 🧰 Hands-on tools: **Nmap, OWASP ZAP, Nikto, Wireshark, Burp Suite, Wazuh**
- 🐧 Working environments: **Linux, Kali Linux, Windows**
- 📚 Continuous learning: **OWASP Top 10, traffic analysis, security monitoring, defensive controls**
- 🤝 Interested in entry-level cybersecurity opportunities and collaborative security learning

---

## Technical Skills

| Domain | Technologies / Topics |
|---|---|
| Network Security | TCP/IP, DNS, DHCP, NAT, LAN/WAN, VLAN, VPN, routing and switching fundamentals |
| Security Assessment | VAPT methodology, reconnaissance, service enumeration, security configuration review, report writing |
| Web Security | OWASP Top 10 concepts, HTTP/HTTPS, security headers, cookies, CSP, CSRF concepts |
| Security Operations | SIEM fundamentals, log analysis, alert triage, incident-response concepts, threat hunting fundamentals |
| Operating Systems | Linux, Kali Linux, Ubuntu, Windows |
| Tools | Nmap, OWASP ZAP, Nikto, Wireshark, Burp Suite, Wazuh, Metasploit, Nessus, Suricata |
| Scripting | Python fundamentals, Bash fundamentals |
| Cloud / Virtualization | AWS and Azure fundamentals, VirtualBox, VMware |

<p align="center">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-Assessment-4682B4?style=flat-square" />
  <img src="https://img.shields.io/badge/OWASP_ZAP-00549E?style=flat-square" />
  <img src="https://img.shields.io/badge/Nikto-Web_Scanner-6C3483?style=flat-square" />
  <img src="https://img.shields.io/badge/Wireshark-Traffic_Analysis-1679A7?style=flat-square&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp_Suite-Web_Testing-FF6633?style=flat-square" />
  <img src="https://img.shields.io/badge/Wazuh-SIEM-005571?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-Learning-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

---

## Featured Security Projects

> **Assessment note:** The reports linked below are preliminary, tool-based assessments. Scanner alerts and observations are not represented as confirmed exploitable vulnerabilities unless independently validated. Conduct testing only with authorization and within an agreed scope.

### 1. Xperia Mall — Preliminary Network & Vulnerability Assessment

[**📄 Read the Full Assessment Report →**](projects/XperiaMall_Preliminary_VAPT_Report.md)

| | |
|---|---|
| **Assessment focus** | Network exposure and HTTP/HTTPS response observations |
| **Tool** | Nmap 7.99 |
| **Techniques documented** | SYN scan, service detection, full TCP-port scan, selected vulnerability scripts |
| **Observed services** | TCP/80 and TCP/443 reported open |
| **Report status** | Preliminary — Nmap evidence only |

**Project overview:** Documented externally visible services, HTTP response behavior, filtered-port observations, and areas requiring further validation. The report includes limitations and recommendations for follow-up configuration review.

**Key topics:** Service enumeration · HTTP response analysis · Attack-surface observations · Report writing

---

### 2. Sarvaangi — Web Infrastructure & Exposure Review

[**📄 Read the Full Assessment Report →**](projects/Sarvaangi_Preliminary_VAPT_Report.md)

| | |
|---|---|
| **Assessment focus** | Public-facing port and service observations |
| **Tool** | Nmap 7.99 |
| **Techniques documented** | Full TCP-port scan, service/version detection, selected vulnerability scripts |
| **Notable scan output** | Multiple web/proxy-associated ports; Slowloris heuristic on TCP/8080 |
| **Report status** | Preliminary — Nmap evidence only |

**Project overview:** Recorded port and service observations, reviewed a scanner-generated Slowloris alert for validation, and documented the `/crossdomain.xml` path observation. No denial-of-service impact is claimed as verified.

**Key topics:** Port exposure · Proxy fingerprints · Scanner alert validation · Defensive recommendations

---

### 3. Sagar Resort — HTTP Configuration Assessment

[**📄 Read the Full Assessment Report →**](projects/SagarResort_Preliminary_VAPT_Nikto_Report.md)

| | |
|---|---|
| **Assessment focus** | HTTP configuration and security-header observations |
| **Tool** | Nikto 2.6.0 |
| **Scope represented** | HTTP service on TCP/80 |
| **Reported observations** | ETag metadata, security-header checks, HTTP method observations |
| **Report status** | Preliminary — scanner findings not independently validated |

**Project overview:** Reviewed scanner observations involving ETag metadata, Referrer-Policy, HSTS, X-Content-Type-Options, CSP, Permissions-Policy, and reported HTTP methods.

**Key topics:** HTTP headers · Server configuration · ETag review · Security hardening

---

### 4. Pigeon India — Web Application Passive Scan

[**📄 Read the Full Assessment Report →**](projects/PigeonIndia_Preliminary_VAPT_ZAP_Report.md)

| | |
|---|---|
| **Assessment focus** | Passive web application security observations |
| **Tool** | OWASP ZAP 2.17.0 |
| **Scan type** | Automated passive scan |
| **Reported alert categories** | PII-pattern alert, CSRF, CSP, cross-domain, cookie, HSTS, SRI |
| **Report status** | Preliminary — alerts require validation |

**Project overview:** Organized the ZAP alert inventory and remediation priorities, including cautious handling of a scanner-generated PII-pattern alert, CSP policy concerns, cookie attributes, cross-origin configuration, and CSRF-related observations.

**Key topics:** Passive scanning · Security headers · Cookie configuration · Alert triage · Validation

---

## Project Reports

<details>
<summary><b>📁 Browse assessment reports</b></summary>

| Project | Report |
|---|---|
| Xperia Mall | [Open report](projects/XperiaMall_Preliminary_VAPT_Report.md) |
| Sarvaangi | [Open report](projects/Sarvaangi_Preliminary_VAPT_Report.md) |
| Sagar Resort | [Open report](projects/SagarResort_Preliminary_VAPT_Nikto_Report.md) |
| Pigeon India | [Open report](projects/PigeonIndia_Preliminary_VAPT_ZAP_Report.md) |

</details>

---

## Work Experience

<details>
<summary><b>Cyber Security & Network Engineer Intern — Kaashiv Infotech, Chennai | Jun 2024 – Dec 2024</b></summary>

- Worked with networking concepts and infrastructure including LAN, WAN, VLAN, WLAN, routers, switches, and wireless devices.
- Studied firewall, IDS/IPS, VPN, and ACL security controls.
- Practiced security monitoring and log-management workflows using Wazuh SIEM.
- Participated in vulnerability-assessment and penetration-testing learning activities across networks, web applications, and systems.
- Explored cloud networking and security fundamentals in AWS and Azure environments.
- Prepared technical documentation and network/security reporting.
- Practiced security analysis, log review, and threat-hunting concepts.

</details>

---

## Education

**B.Sc. Computer Science**  
AVVM Sri Pushpam College, Thanjavur, Tamil Nadu

---

## Certifications & Training

- CompTIA Security+ (SY0-601) *(as listed in my credentials)*
- Cisco Networking Basics
- CEHPT Certificate — Cappriciosec University
- Kaashiv Infotech Internship Certification
- Orbit Academy — HDCA
- Junior Red Cross — First Aid Training Certification

---

## Achievements

- 🥇 1st Place — Shoot Me (Web Warriors), Inter-College Event (2023)
- 🥇 1st Place — Code Logic, Inter-College Symposium (2024)
- 🎯 Event Organizer — Inter-College Symposium (2025)

---

## Currently Learning

- Web application security and OWASP Top 10
- Reconnaissance and traffic analysis
- Web and application reverse-engineering fundamentals
- Threat hunting and threat intelligence
- Red Team / Blue Team workflows
- AWS and Azure security fundamentals
- Zero Trust architecture

---

## GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=praveen-s-cyber&show_icons=true&theme=transparent&hide_border=true" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=praveen-s-cyber&layout=compact&theme=transparent&hide_border=true" height="165" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=praveen-s-cyber&theme=transparent&hide_border=true" alt="GitHub streak" />
</p>

---

## Contact

<p align="center">
  <a href="mailto:praveen.cybersecurity28@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/praveen-s-cyber"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center">
  <i>Build. Analyze. Secure. Document. Keep learning.</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:00C2FF&height=100&section=footer" alt="Footer" />
</p>
