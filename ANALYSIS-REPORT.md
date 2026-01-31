# Comprehensive Analysis Report: Hacking Resources Repository

## Executive Summary

This repository contains **500+ tools and resources** across 14 major security domains. This analysis identifies the most powerful products, their use cases, and recommendations for building a comprehensive security toolkit. An addendum covers **2025-2026 emerging tools**, including the new AI/LLM security category.

---

## Part 1: TOP-TIER TOOLS BY CATEGORY

### A. RECONNAISSANCE & OSINT (Most Essential)

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Shodan** | ★★★★★ | Internet-wide device discovery | The "Google for hackers" - finds exposed devices, services, vulnerabilities globally |
| **Maltego** | ★★★★★ | Visual link analysis & OSINT | Unmatched for mapping relationships between entities, organizations, people |
| **Recon-ng** | ★★★★★ | Automated reconnaissance | Modular framework with 80+ modules for comprehensive intel gathering |
| **theHarvester** | ★★★★☆ | Email/subdomain enumeration | Fast, effective for initial target profiling |
| **SpiderFoot** | ★★★★★ | Automated OSINT collection | 200+ modules, correlates data automatically |
| **Sherlock.py** | ★★★★☆ | Username hunting | Searches 300+ social networks simultaneously |
| **Amass** | ★★★★★ | Attack surface mapping | OWASP project, industry standard for subdomain discovery |

**Use Cases:**
- Penetration testing reconnaissance phase
- Bug bounty hunting
- Threat intelligence gathering
- Competitive intelligence
- Background investigations
- Red team operations

---

### B. NETWORK ANALYSIS & SCANNING

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Nmap** | ★★★★★ | Network discovery & security auditing | The undisputed king - port scanning, service detection, NSE scripting |
| **Wireshark** | ★★★★★ | Packet analysis | Industry standard for network forensics and troubleshooting |
| **Metasploit Framework** | ★★★★★ | Exploitation framework | Complete penetration testing platform |
| **Bettercap** | ★★★★★ | MITM attacks | Swiss Army knife for network recon and attacks |
| **Nessus** | ★★★★★ | Vulnerability scanning | Enterprise-grade vulnerability assessment |
| **OpenVAS** | ★★★★☆ | Open-source vulnerability scanning | Free alternative to Nessus with comprehensive checks |

**Use Cases:**
- Network security assessments
- Vulnerability management programs
- Incident response investigations
- Network forensics
- Compliance auditing (PCI-DSS, HIPAA)

---

### C. WEB APPLICATION SECURITY

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Burp Suite** | ★★★★★ | Web app testing | Industry standard - intercept, modify, replay HTTP traffic |
| **OWASP ZAP** | ★★★★★ | Free web app scanner | Best free alternative to Burp, excellent for automation |
| **SQLmap** | ★★★★★ | SQL injection exploitation | Automatic SQL injection detection and exploitation |
| **Nikto** | ★★★★☆ | Web server scanning | Quick identification of misconfigurations and vulnerabilities |
| **Gobuster** | ★★★★★ | Directory/file brute-forcing | Fast Go-based discovery tool |
| **WPScan** | ★★★★★ | WordPress security | Comprehensive WordPress vulnerability scanning |
| **Dirsearch** | ★★★★☆ | Web path discovery | Fast, reliable path scanner |

**Use Cases:**
- Web application penetration testing
- Bug bounty hunting
- Security code review support
- CI/CD security integration
- Web app vulnerability assessment

---

### D. MALWARE ANALYSIS & REVERSE ENGINEERING

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Ghidra** | ★★★★★ | Reverse engineering | NSA-developed, free, rivals IDA Pro |
| **IDA Pro** | ★★★★★ | Disassembly & debugging | Industry gold standard (commercial) |
| **x64dbg** | ★★★★★ | Windows debugging | Best open-source Windows debugger |
| **YARA** | ★★★★★ | Malware classification | Pattern matching for threat hunting |
| **Cuckoo Sandbox** | ★★★★★ | Dynamic analysis | Automated malware analysis platform |
| **PEStudio** | ★★★★☆ | PE file analysis | Quick malware triage and initial assessment |
| **Process Monitor** | ★★★★★ | System monitoring | Essential for behavioral analysis |
| **dnSpy** | ★★★★★ | .NET reverse engineering | Debug and decompile .NET assemblies |
| **radare2/Cutter** | ★★★★☆ | Cross-platform RE | Free, powerful, scriptable |

**Use Cases:**
- Malware incident response
- Threat intelligence production
- Security research
- CTF competitions
- Vulnerability research

---

### E. PASSWORD CRACKING & CREDENTIAL ATTACKS

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Hashcat** | ★★★★★ | GPU-accelerated cracking | Fastest password cracker, 300+ hash types |
| **John the Ripper** | ★★★★★ | Multi-platform cracking | Versatile, extensive format support |
| **Hydra** | ★★★★★ | Online brute-forcing | Parallelized login cracker for 50+ protocols |
| **Mimikatz** | ★★★★★ | Windows credential extraction | Extracts passwords, hashes, Kerberos tickets |
| **Responder** | ★★★★★ | LLMNR/NBT-NS poisoning | Captures credentials on Windows networks |

**Use Cases:**
- Password security auditing
- Penetration testing (credential attacks)
- Post-exploitation
- Active Directory security assessments
- Compliance testing

---

### F. WIRELESS SECURITY

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Aircrack-ng** | ★★★★★ | WiFi security suite | Complete 802.11 assessment toolkit |
| **Reaver** | ★★★★☆ | WPS attacks | WPS PIN brute-force attacks |
| **Bettercap** | ★★★★★ | Wireless attacks | Modern alternative for WiFi attacks |
| **Wash** | ★★★★☆ | WPS detection | Identifies WPS-enabled access points |

**Use Cases:**
- Wireless penetration testing
- WiFi security audits
- Rogue access point detection
- WPA/WPA2 security assessment

---

### G. CLOUD SECURITY

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **S3Scanner** | ★★★★☆ | AWS S3 bucket scanning | Find and dump open S3 buckets |
| **Trivy** | ★★★★★ | Container vulnerability scanning | Comprehensive container/IaC scanner |
| **Clair** | ★★★★☆ | Container static analysis | Vulnerability detection in containers |
| **GCPBucketBrute** | ★★★★☆ | GCP bucket enumeration | Google Cloud storage reconnaissance |
| **aws_pwn** | ★★★★☆ | AWS exploitation | AWS penetration testing toolkit |

**Use Cases:**
- Cloud security assessments
- DevSecOps pipeline integration
- Container security
- Cloud misconfiguration detection

---

### H. MOBILE SECURITY

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **MobSF** | ★★★★★ | Mobile app analysis | All-in-one Android/iOS security framework |
| **Frida** | ★★★★★ | Dynamic instrumentation | Runtime manipulation and analysis |
| **Apktool** | ★★★★★ | APK reverse engineering | Decode/rebuild Android apps |
| **drozer** | ★★★★☆ | Android security assessment | Framework for Android app testing |
| **Objection** | ★★★★☆ | Runtime exploration | Frida-powered mobile testing |

**Use Cases:**
- Mobile application penetration testing
- Android/iOS malware analysis
- Mobile app security auditing
- BYOD security assessment

---

### I. SOCIAL ENGINEERING

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Social Engineer Toolkit (SET)** | ★★★★★ | Social engineering attacks | Comprehensive SE attack framework |
| **Gophish** | ★★★★★ | Phishing simulations | Open-source phishing framework |
| **King Phisher** | ★★★★☆ | Phishing campaigns | Campaign management and tracking |

**Use Cases:**
- Security awareness training
- Phishing simulation programs
- Red team social engineering operations
- Security culture assessment

---

### J. FORENSICS & INCIDENT RESPONSE

| Tool | Power Rating | Use Case | Why Essential |
|------|--------------|----------|---------------|
| **Autopsy** | ★★★★★ | Digital forensics platform | Complete forensic investigation suite |
| **Volatility** | ★★★★★ | Memory forensics | Extract artifacts from memory dumps |
| **Wireshark** | ★★★★★ | Network forensics | Packet capture analysis |
| **Regshot** | ★★★★☆ | Registry comparison | Track system changes |

**Use Cases:**
- Incident response
- Digital forensic investigations
- Malware analysis support
- Evidence collection

---

## Part 2: DIVERSIFIED TOOLKIT BY JOB ROLE

### For PENETRATION TESTERS

**Core Tools:**
1. Nmap - Network discovery
2. Metasploit Framework - Exploitation
3. Burp Suite - Web app testing
4. Hashcat/John - Password cracking
5. Mimikatz - Credential extraction
6. Gobuster - Directory discovery
7. SQLmap - SQL injection
8. Aircrack-ng - Wireless testing
9. Bettercap - MITM attacks
10. PEASS Suite - Privilege escalation

**Supporting Resources:**
- Cheat sheets: `nmap-cheat-sheet.md`, `hacking-web-cheat-sheet.md`, `system-hacking-cheat-sheet.md`
- OS: Kali Linux, Parrot OS

---

### For MALWARE ANALYSTS

**Core Tools:**
1. Ghidra/IDA Pro - Disassembly
2. x64dbg - Debugging
3. YARA - Pattern matching
4. Cuckoo Sandbox - Dynamic analysis
5. PEStudio - PE analysis
6. Process Monitor - Behavioral monitoring
7. dnSpy - .NET analysis
8. Volatility - Memory forensics
9. VirusTotal - Multi-scanner
10. REMnux - Analysis OS

**Supporting Resources:**
- Malware databases: MalwareBazaar, theZoo, vx-underground
- Bibliography: `bibliography-tutorials-conferences.md` (extensive RE resources)

---

### For BUG BOUNTY HUNTERS

**Core Tools:**
1. Amass - Subdomain enumeration
2. Subfinder - Subdomain discovery
3. Burp Suite - Web testing
4. Nuclei - Vulnerability scanning
5. Gobuster/Dirsearch - Path discovery
6. SQLmap - SQL injection
7. XSStrike - XSS detection
8. Waybackurls - Historical URL discovery
9. httprobe - Live host probing
10. EyeWitness - Screenshot capture

**Supporting Resources:**
- The Bug Hunters Methodology
- Bug bounty platforms: HackerOne, Bugcrowd, Intigriti

---

### For SECURITY OPERATIONS CENTER (SOC) ANALYSTS

**Core Tools:**
1. Wireshark - Network analysis
2. Snort/Suricata - IDS/IPS
3. Wazuh - SIEM/FIM
4. Volatility - Memory analysis
5. YARA - Threat detection
6. Splunk - Log analysis
7. Autopsy - Forensics
8. VirusTotal - Malware checking
9. Shodan - Threat intelligence
10. Process Monitor - System monitoring

**Supporting Resources:**
- Security Onion 2 OS
- Threat intelligence feeds

---

### For RED TEAM OPERATORS

**Core Tools:**
1. Metasploit - Exploitation
2. Cobalt Strike (commercial)/Covenant - C2
3. Mimikatz - Credential theft
4. BloodHound - AD analysis
5. PowerSploit - Post-exploitation
6. Veil/Phantom-Evasion - AV bypass
7. SET - Social engineering
8. Bettercap - Network attacks
9. Responder - Credential capture
10. PEASS - Privilege escalation

**Supporting Resources:**
- Atomic Red Team - Detection testing
- MITRE ATT&CK framework

---

### For SECURITY RESEARCHERS

**Core Tools:**
1. Ghidra - Reverse engineering
2. Frida - Dynamic instrumentation
3. Radare2/Cutter - Analysis
4. AFL++ - Fuzzing
5. Wireshark - Protocol analysis
6. Burp Suite - Web research
7. QEMU - Emulation
8. Docker - Isolated environments
9. Git - Version control
10. Python - Scripting

---

## Part 3: ESSENTIAL COMPREHENSIVE SUITE

### If Building ONE Complete Toolkit, Include These:

#### Tier 1: MUST HAVE (Universal)
| Category | Tool | Reason |
|----------|------|--------|
| Recon | **Nmap** | Foundation of network assessment |
| Recon | **Shodan** | Internet-scale intelligence |
| Web | **Burp Suite** | Web testing standard |
| Exploitation | **Metasploit** | Complete exploitation framework |
| Analysis | **Wireshark** | Network forensics |
| RE | **Ghidra** | Free, powerful RE tool |
| Passwords | **Hashcat** | Fastest cracker |
| Credentials | **Mimikatz** | Windows credential extraction |

#### Tier 2: HIGHLY RECOMMENDED
| Category | Tool | Reason |
|----------|------|--------|
| Recon | Amass, Subfinder | Subdomain enumeration |
| Web | OWASP ZAP, SQLmap | Web vulnerability testing |
| Network | Bettercap | MITM and network attacks |
| Wireless | Aircrack-ng | WiFi assessment |
| Malware | Cuckoo, YARA | Malware analysis |
| Mobile | MobSF, Frida | Mobile testing |
| Forensics | Autopsy, Volatility | Incident response |

#### Tier 3: SPECIALIZED
| Category | Tool | Reason |
|----------|------|--------|
| Cloud | Trivy, S3Scanner | Cloud security |
| AD | BloodHound | Active Directory attacks |
| Social | SET, Gophish | Social engineering |
| Containers | Clair, Dagda | Container security |

---

## Part 4: OPERATING SYSTEMS & LAB SETUP

### Recommended OS by Purpose

| OS | Purpose | Key Features |
|----|---------|--------------|
| **Kali Linux** | Penetration testing | 600+ tools pre-installed, industry standard |
| **Parrot OS** | Pentesting + Privacy | Lighter than Kali, better privacy tools |
| **REMnux** | Malware analysis | Pre-configured analysis environment |
| **Security Onion 2** | Blue team/SOC | Threat hunting, network monitoring |
| **flare-vm** | Windows malware analysis | Windows-based analysis environment |
| **BlackArch** | Advanced pentesting | 2500+ tools, Arch-based |

### Lab Setup Recommendations
- **OSBoxes** - Pre-built VMs for quick deployment
- **DVWA** - Vulnerable web app for practice
- **HackTheBox/TryHackMe** - Online practice labs

---

## Part 5: LEARNING RESOURCES

### Certifications Covered
- **CEH** (Certified Ethical Hacker) - Comprehensive study guides
- **OSCP** (Offensive Security) - Practice resources
- **Security+** - Foundational knowledge

### Top Learning Platforms
1. HackTheBox
2. TryHackMe
3. Web Security Academy (PortSwigger)
4. PentesterLab

### YouTube Channels for Learning
- John Hammond
- NetworkChuck
- 13Cubed (Forensics)
- IppSec (HackTheBox)
- LiveOverflow

### Podcasts
- Darknet Diaries
- Risky Business
- SANS StormCast
- Cyberwire Daily

---

## Part 6: QUICK REFERENCE - TOOL SELECTION BY SCENARIO

| Scenario | Primary Tools |
|----------|---------------|
| "I need to map a network" | Nmap, Angry IP Scanner, Masscan |
| "I need to test a web app" | Burp Suite, OWASP ZAP, SQLmap, Nikto |
| "I need to crack passwords" | Hashcat, John the Ripper, Hydra |
| "I found malware, need to analyze it" | Ghidra, Cuckoo, PEStudio, YARA |
| "I need to find subdomains" | Amass, Subfinder, Sublist3r |
| "I need to test WiFi security" | Aircrack-ng, Reaver, Wash |
| "I need to investigate an incident" | Autopsy, Volatility, Wireshark |
| "I need to find exposed data" | Shodan, S3Scanner, theHarvester |
| "I need to test for privilege escalation" | PEASS, PowerUp, BeRoot |
| "I need to set up phishing simulation" | Gophish, King Phisher, SET |

---

## Part 7: 2025-2026 EMERGING TOOLS & UPDATES

### 7.1 AI-POWERED PENTESTING TOOLS (NEW CATEGORY)

| Tool | Type | Description |
|------|------|-------------|
| **[PentestGPT](https://github.com/GreyDGL/PentestGPT)** | LLM-Assisted | Uses GPT-4 to guide through recon, exploitation, post-exploitation |
| **[PentAGI](https://github.com/vxcontrol/pentagi)** | Autonomous Agent | AI agent that selects and executes testing steps in sandboxed Docker with 20+ built-in tools |
| **[Nebula](https://github.com/berylliumsec/nebula)** | CLI AI Assistant | Integrates AI models into command line for real-time security analysis |
| **[Strix](https://strix.security/)** | Autonomous System | AI agents that behave like human attackers, produces real evidence not theoretical alerts |
| **[Penligent.ai](https://www.penligent.ai/)** | Force Multiplier | Automates 80% of repetitive recon/scanning, freeing humans for complex logic flaws |

---

### 7.2 AI/LLM RED TEAMING TOOLS (ENTIRELY NEW CATEGORY)

These tools address an attack surface that did not exist when the repository was last updated:

| Tool | Developer | Key Features |
|------|-----------|--------------|
| **[DeepTeam](https://github.com/confident-ai/deepteam)** | Confident AI | 40+ vulnerability types, 10+ attack methods, OWASP LLM Top 10 and NIST AI RMF support |
| **[Garak](https://github.com/NVIDIA/garak)** | NVIDIA | 100+ attack modules from prompt injection to data extraction |
| **[PyRIT](https://github.com/Azure/PyRIT)** | Microsoft | Python Risk Identification Toolkit - the de facto standard for orchestrating LLM attack suites |
| **[ARTKIT](https://github.com/BCG-X-Official/artkit)** | BCG | Multi-turn adversarial simulation framework |
| **[Mindgard DAST-AI](https://mindgard.ai/)** | Mindgard | Continuous automatic red teaming (CART), Dynamic Application Security Testing for AI |
| **[AutoRTAI](https://hiddenlayer.com/)** | HiddenLayer | Agent-based automated AI red teaming at scale |

**Regulatory drivers:** EU AI Act (Art. 15) requires adversarial testing evidence for high-risk AI by mid-2026. US Executive Order 14110 requires frontier model developers to share red-team results with federal agencies.

**Related frameworks:**
- MITRE ATLAS - Knowledge base of adversarial AI tactics (like ATT&CK but for AI)
- OWASP Gen AI Red Teaming Guide
- NIST AI Risk Management Framework

---

### 7.3 UPDATED VULNERABILITY SCANNING

| Tool | Stars | What It Does | Status |
|------|-------|--------------|--------|
| **[Nuclei](https://github.com/projectdiscovery/nuclei)** | 22k+ | YAML-based community-driven vuln scanner, AI template editor | v10.3.8 (Jan 2026), 10k+ templates |
| **[Katana](https://github.com/projectdiscovery/katana)** | 12k+ | Next-gen web crawling and spidering framework | Active |
| **[httpx](https://github.com/projectdiscovery/httpx)** | 8k+ | Fast multi-purpose HTTP toolkit | Active |
| **[Dalfox](https://github.com/hahwul/dalfox)** | 4k+ | XSS scanner with automated bypass techniques | Active |
| **[Wapiti](https://wapiti-scanner.github.io/)** | Updated | Now supports SSTI, JWT fuzzing (2025) | v3.2+ |
| **OWASP ZAP** | Updated | v2.16.1 (March 2025) | Active |

**Nuclei highlight:** 243 new templates added in October 2025 alone, covering 44 actively exploited CISA KEVs. Template Bounty Program launched for community contributions.

---

### 7.4 CLOUD SECURITY TOOLS (EXPANDED)

#### AWS
| Tool | Description |
|------|-------------|
| **[Pacu](https://github.com/RhinoSecurityLabs/pacu)** | AWS exploitation framework (actively maintained) |
| **[Prowler](https://github.com/prowler-cloud/prowler)** | CIS, NIST, PCI benchmark auditing for AWS/Azure/GCP |
| **[CloudMapper](https://github.com/duo-labs/cloudmapper)** | AWS environment visualization and auditing |

#### Azure
| Tool | Description |
|------|-------------|
| **[MicroBurst](https://github.com/NetSPI/MicroBurst)** | PowerShell toolkit for Azure pentesting |
| **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** | Multi-cloud security auditing (AWS, Azure, GCP, Oracle) |

#### Multi-Cloud
| Tool | Description |
|------|-------------|
| **[CloudSploit](https://github.com/aquasecurity/cloudsploit)** | Open-source cloud misconfiguration scanner |
| **[Trivy](https://github.com/aquasecurity/trivy)** | Containers, IaC, Kubernetes, cloud scanning |

---

### 7.5 OSINT TOOLS (2025-2026 ADDITIONS)

| Tool | Description |
|------|-------------|
| **[SL Crimewall](https://sociallinks.io/)** | Next-gen all-in-one OSINT investigation platform |
| **[ShadowDragon](https://shadowdragon.io/)** | 225+ data sources, real-time monitoring |
| **[Babel X](https://babelstreet.com/)** | AI-powered, 200+ languages, dark web support |
| **[OSINT-BIBLE](https://github.com/frangelbarrera/OSINT-BIBLE)** | Comprehensive 2026 OSINT guide with tools, methodologies, ethics |

---

### 7.6 MALWARE ANALYSIS UPDATES

| Tool | What Changed |
|------|-------------|
| **Ghidra 11.x** | AI hints for function naming, crypto routine detection |
| **[YARA-X](https://github.com/VirusTotal/yara-x)** | Complete Rust rewrite - significantly faster |
| **[ANY.RUN](https://any.run/)** | Cloud-based interactive sandbox with live VM interaction |
| **Cuckoo Sandbox** | Windows 11 guest support, Docker deployment |

---

### 7.7 COMPREHENSIVE GITHUB COMPILATIONS (RECENTLY UPDATED)

| Repository | Description |
|------------|-------------|
| **[eudk/awesome-cybersecurity-tools](https://github.com/eudk/awesome-cybersecurity-tools)** | Large, comprehensive, updated Sept 2025 |
| **[Hack-with-Github/Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking)** | Meta-list of awesome hacking lists |
| **[vavkamil/awesome-bugbounty-tools](https://github.com/vavkamil/awesome-bugbounty-tools)** | Bug bounty focused compilation |
| **[amrelsagaei/Bug-Bounty-Hunting-Methodology-2025](https://github.com/amrelsagaei/Bug-Bounty-Hunting-Methodology-2025)** | Complete 2025 methodology |
| **[requie/AI-Red-Teaming-Guide](https://github.com/requie/AI-Red-Teaming-Guide)** | Guide to adversarial AI testing |

---

### 7.8 KEY TRENDS FOR 2025-2026

1. **AI Integration Everywhere** - Every major tool is adding AI/LLM features
2. **Autonomous Pentesting Agents** - Tools that run entire assessments with minimal human input
3. **LLM as Attack Surface** - Prompt injection, jailbreaking, data exfiltration from AI systems
4. **Compliance-Driven Tooling** - EU AI Act & NIST AI RMF driving new tool adoption
5. **Cloud-Native Testing** - IAM privilege chaining, serverless exploitation, Kubernetes attacks
6. **Supply Chain Security** - SBOM enforcement, dependency confusion detection

---

## Conclusion

This repository provides a comprehensive arsenal for security professionals. The key to effectiveness is:

1. **Master the fundamentals first** (Nmap, Burp Suite, Metasploit)
2. **Specialize based on your role** (use the role-specific recommendations above)
3. **Build layered knowledge** (combine tools for comprehensive assessments)
4. **Integrate AI tools** (PentestGPT, Nuclei AI, DeepTeam for LLM work)
5. **Practice continuously** (HackTheBox, TryHackMe, CTFs)
6. **Stay current** (follow the blogs and news sources listed in the repo)

The most powerful combination is not any single tool, but understanding how to **chain multiple tools together** for comprehensive assessments.

---

*Report generated from analysis of the hacking-resources repository*
*Tools count: 500+ (repo) + 40+ new (2025-2026) | Categories: 14 + 2 new | Cheat sheets: 10*

---

## Support This Research

If this briefing was useful, consider supporting independent OSINT research:

| Network | Address |
|---------|---------|
| Lightning | `lesslace72@walletofsatoshi.com` |
| Bitcoin | `bc1qh2cnzmrp2pj0x2n22gfhshjnlzya9aagpuntyg` |
| Ethereum (ERC20) | `0xd6aCF08BE2fCC2cB1f443d620d5DDe93ba02aDfA` |
| BNB (BEP20) | `0xd6aCF08BE2fCC2cB1f443d620d5DDe93ba02aDfA` |

---

*This document is provided for defensive and educational purposes. Stay vigilant.*

**[An0myl0u5 Research and Development](https://github.com/An0myl0u5-Lite)**
