<div align="center">

# 🛡️ Bonnamain Blue Team Lab 🧪 

**LINUX & FREEBSD · BLUE TEAM · THREAT HUNTING**

*Defensive Security · Detection Engineering · Incident Response · Malware Analysis*

![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red_Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![FreeBSD](https://img.shields.io/badge/FreeBSD-AB2B28?style=for-the-badge&logo=freebsd&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Shell Scripting](https://img.shields.io/badge/Shell_Scripting-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly_x86--64-525252?style=for-the-badge)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

`EXPLORE` → `INVESTIGATE` → `DETECT` → `DEFEND` → `DOCUMENT`

</div>

---

## About the Lab

Bonnamain Blue Team Lab is a personal technology laboratory focused on defensive cybersecurity, with **Linux and FreeBSD as its permanent technical foundations**. Debian GNU/Linux is the primary Linux environment, complemented by Red Hat-based distributions and FreeBSD. System administration, networking, access controls, service management, auditing, and security hardening provide the foundation for understanding and defending UNIX-like systems.

Threat hunting is a central area of focus, supported by hands-on laboratory work and experience teaching threat hunting topics. The laboratory explores detection engineering, security monitoring, incident investigation, threat intelligence, and security automation. Python and Bash support investigations, log processing, diagnostics, reporting, and the development of command-line tools.

Malware analysis and reverse engineering are areas of ongoing learning, with an initial focus on static analysis, ELF executables, file inspection, Assembly x86-64 fundamentals, and compiled program behavior. FreeBSD remains an important part of the work, particularly its networking, PF firewall, jails, ZFS, and UNIX security concepts.

Experiments use controlled environments, synthetic data, self-developed programs, and authorized educational resources. Windows and other platforms may be included when relevant to Blue Team investigations, without replacing the laboratory's Linux and FreeBSD focus.

☕ **Powered by coffee, curiosity, and a genuine passion for technology.**

---

## 🔬 Lab Workbenches

| Workbench | Focus |
|---|---|
| 🐧 **Linux Administration** | Debian, RHEL, AlmaLinux, systemd, services, permissions, SSH, package management, storage, and troubleshooting |
| 😈 **FreeBSD / UNIX** | FreeBSD administration, users, permissions, services, networking, PF firewall, jails, ZFS, and UNIX security practices |
| 🔎 **Threat Hunting & Detection Engineering** | Hypothesis-driven investigations, persistence analysis, system artifacts, MITRE ATT&CK, YARA and Sigma fundamentals, detection logic, coverage, and validation |
| 🛡️ **Blue Team & System Hardening** | Linux and FreeBSD security, access controls, SSH hardening, SELinux and AppArmor fundamentals, firewall policies, auditing, and security configuration reviews |
| 📡 **Security Monitoring & SOC** | SIEM fundamentals, log analysis, IDS/IPS, EDR/XDR concepts, event correlation, alert triage, and monitoring |
| 🚨 **Incident Response & Digital Forensics** | Incident investigation, evidence preservation, event timelines, containment, eradication, recovery, forensic fundamentals, and reporting |
| 🌐 **Networking & Threat Intelligence** | TCP/IP, DNS, HTTP/HTTPS, tcpdump, Wireshark, Suricata and Snort fundamentals, traffic investigation, threat intelligence, and vulnerability assessment concepts |
| 🐍 **Python & Shell Scripting** | Python and Bash automation, log processing, diagnostics, security checks, Docker-based environments, command-line utilities, and automated testing |
| 🦠 **Malware Analysis & Reverse Engineering — Learning** | Static file inspection, hashes, strings, ELF and PE fundamentals, YARA, Assembly x86-64, disassembly, and introductory binary analysis |

---

## 🤖 AI Usage

AI tools, including ChatGPT, assist with research, planning, scripting, debugging, documentation, and technical review.

Suggestions are reviewed, understood, and validated through testing. AI-generated explanations and proposed solutions are not treated as verified evidence.

Projects document AI-assisted work, including limitations and incorrect suggestions when relevant.

AI usage follows confidentiality, data protection, and responsible security practices.

---

## 📝 Lab Notes

The laboratory follows an evidence-first approach to technical investigation and documentation.

- **Reproducibility:** Published experiments describe objectives, environments, dependencies, configurations, commands, tests, and results.
- **Evidence:** Investigations document hypotheses, observable artifacts, alternative explanations, and supported conclusions.
- **Detection quality:** Results distinguish detected, not detected, not tested, and inconclusive scenarios. False positives, false negatives, and coverage limitations are documented.
- **Transparency:** Planned activities are distinguished from implemented and validated work. Unexpected behavior, failed tests, and incorrect assumptions are documented.
- **Responsible experimentation:** Only authorized environments and resources are used. Confidential information, production credentials, unauthorized data, and sensitive third-party materials are never published.

*Experiments are published here only after their repositories are available and their documented results have been verified.*

---

<!--
EXPERIMENTS - INTERNAL PLANNING

This section is intentionally hidden from the rendered README.
It remains visible in the public Markdown source.

Keep planned experiments out of the rendered project list until
their repositories are available and results have been verified.

Replace repository placeholders with actual URLs.
Do not present planned work as completed experiments.

When a repository becomes available, consider a visible table:
ID | Experiment | Focus | Status | Repository

Use accurate status labels such as In Progress or Validated.
A published repository does not automatically mean its results
have been validated.

## 🧪 Experiments

### LAB-001 - Debian Persistence Zoo

Environment:
- Disposable Debian virtual machine

Stack:
- Python
- Bash
- systemd

Focus:
- Benign Linux persistence simulations
- Threat hunting and detection engineering
- Detection coverage
- False positives and false negatives
- Security event investigation

Techniques:
- Scheduled tasks
- Service configurations
- User startup mechanisms

Detection:
- Python-based inspection and reporting

Reference:
- MITRE ATT&CK for Linux

Deliverables:
- Reproducible benign test scenarios
- Reversible laboratory setup and cleanup
- Persistence detection tool
- Detection coverage matrix
- Automated tests
- Technical documentation

Safety:
- No malicious payloads
- Disposable and authorized environments only

Repository:
- Add repository URL

Status:
- Planned

### LAB-002 - FreeBSD Containment Range

Environment:
- Dedicated FreeBSD laboratory

Stack:
- FreeBSD
- ZFS
- PF
- bhyve
- Python

Focus:
- Network isolation
- Containment validation
- Traffic monitoring
- Reproducible security experiments

Techniques:
- ZFS snapshots
- Virtual machines
- Firewall policies
- Controlled traffic generation

Detection:
- Analysis of synthetic network activity
- Periodic communication pattern detection

Deliverables:
- Documented laboratory architecture
- Network isolation configuration
- Snapshot and rollback procedures
- Egress filtering validation tests
- Traffic analysis reports
- Detection results
- Threat model and documented limitations

Safety:
- Benign programs and synthetic traffic only
- No assumption of absolute isolation security

Repository:
- Add repository URL

Status:
- Planned

### LAB-003 - Binary Provenance Lab

Environment:
- Debian GNU/Linux

Stack:
- C
- Python
- GCC
- Clang
- pyelftools
- Assembly x86-64

Focus:
- ELF inspection
- Compiler characteristics
- Binary analysis
- Assembly fundamentals

Techniques:
- Compilation variants
- Symbol inspection
- Executable metadata
- Disassembly
- Comparison of build configurations

Detection:
- Experimental classification of compiler
  characteristics and build configurations

Deliverables:
- Reproducible compilation corpus
- Python ELF inspection tool
- Experimental binary classification tool
- Build configuration comparison matrix
- Documented classification errors
- Automated tests
- Technical reports

Safety:
- Self-developed benign executables only
- No real malware samples required

Repository:
- Add repository URL

Status:
- Planned

END OF INTERNAL PLANNING
-->

---

<div align="center">

**"What worries me isn't the advancement of artificial intelligence,**  
**but the decline of natural human intelligence."**

*— Original author unknown*

</div>

---

## 📫 Contact

**LinkedIn:** [Alexandre Bonnamain](https://www.linkedin.com/in/alexandre-bonnamain/)

**GitHub:** [alexbonnamain](https://github.com/alexbonnamain)
