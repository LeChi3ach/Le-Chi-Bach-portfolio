# Le Chi Bach's portfolio
Welcome to my technical portfolio!. My name is **Le Chi Bach**. I am an Information Technology student majoring in Cybersecurity. This repository serves as a centralized hub managing my technical reports, network defense developments and offensive security testing simulations conducted in controlled sandbox environments (**Virtual Machines**).

---

## Portfolio directory 

### 1. Network Defense & Cryptography Analysis
An engineering evaluation focusing on traffic monitoring, gateway access control lists (ACLs), cryptographic robustness and source-code auditing.
* **Intrusion Detection (Snort IDS):** Deploy and configure a Network Intrusion Detection System (**Snort**) on a gateway router to capture and log unauthorized probes.
* **Firewall Architectures (Iptables):** Engineered stateless and stateful packet filtering policies using **iptables** to block outbound movement while securing enterprise service ports.
* **Symmetric Encryption Resilience:** Evaluated the risks of **AES-128-ECB** against **AES-128-CBC** mode. Utilized hex-header manipulation to demonstrate pattern preservation vulnerabilities in ECB ciphertexts.
* **Infrastructure Auditing:** Automated active asset discovery and OS fingerprinting via **Nmap**; applied Static Application Security Testing (SAST) with **Flawfinder** to discover and remediate memory boundaries and integer overflow flaws in C source code.
* **[View Full Technical Report (PDF)](./01-Security-Testing/Network_Defense_Firewall_and_Cryptographic_Analysis.pdf)**

### 2. Web Application Penetration Testing & AI Security
A security report targeting application-layer logic flaws, modern client-side scripting exploitation, and machine learning model manipulation.
* **Advanced SQL Injection (SQL Injection):** Exploited authentication logic bypasses and leveraged stacked queries via unsafe backend string concatenation to modify remote database records.
* **Cross-Site Scripting (XSS):** Injected malicious client-side Stored XSS scripts to exfiltrate session cookies and constructed automated payloads leveraging Session GUID parameters to self-propagate profile alterations.
* **Adversarial Machine Learning:** Deployed an evasion attack against the MNIST handwritten digit neural network using the **Jacobian-based Saliency** method. Confidently manipulated critical pixel clusters to force the AI model into misclassifying a "3" as an "8" with high probability, proving model boundary structural flaws in AI deployments.
* **[View Full Technical Report (PDF)](./01-Security-Testing/Web_Application_Penetration_Testing_and_AI_Security.pdf)**

### 3. Threat Modeling & Network Attacks Simulation
A technical assessment focusing on network session vulnerabilities and architecture boundaries threat mapping.
* **STRIDE Threat Modeling:** Modeled complex application-server architectures and systematically mapped potential attacker vectors across 4 critical trust/integrity boundaries using the **STRIDE framework**.
* **Protocol Vulnerability Exploitation:** Developed Python/Scapy automation to exploit cleartext Telnet infrastructure. Executed **Packet Spoofing**, **TCP Session Reset (RST)**, and **TCP Session Hijacking** by predicting sequence numbers to inject arbitrary technical payloads into active connections.
* **[View Full Technical Report (PDF)](./01-Security-Testing/Threat_Modeling_and_Network_Attacks_Simulation.pdf)**

### 4. Digital Forensics, Incident Response & Mobile Investigation
An investigation covering file system recovery, live host volatile memory analysis, and mobile operating system artifact extraction.
* **Forensic Image Acquisition & Integrity:** Conducted physical drive stream imaging via **FTK Imager** to generate verified bit-stream raw images; validated structural integrity using **MD5** and **SHA1** cryptographic hashing checks.
* **Artifact Carving & Geo-Location Tracing:** Leveraged **Autopsy** to analyze file-system trees, recover deleted hidden image structures, and perform index keyword parsing. Extracted unallocated coordinate configurations to track a suspect's location using precise geographic telemetry mapping.
* **Volatile Memory Forensics (Volatility 3):** Dissected a live system memory dump using **Volatility 3** architecture. Executed internal kernel audits, extracted dynamic running process blocks , audited system handles, mapped active registry hives, and  loaded Dynamic Link Libraries.
* **Network Traffic Forensics (DDoS Investigation):** Analyzed live network packet captures targeting a corporate infrastructure. Developed targeted **Wireshark filters** to isolate concurrent connections, leading to the successful mitigation and identification of botnet-driven **SYN Flood** and **HTTP Flood** anomalies.
* **Low-Level Mobile Data Acquisition:** Configured an isolated testing environment using **Android Studio** to deploy an Android 14 subsystem under Google APIs. Authenticated daemon structures via root privilege execution to bypass File-Based Encryption (FBE) restrictions and safely pull logical application-layer relational database images via Android Debug Bridge (**ADB**).
* **[View Full Technical Report (PDF)](./02-Digital-Forensic/Disk_Imaging_Digital_Forensic_and_Memory_Artifacts_Analysis.pdf)**
* **[View Full Technical Report (PDF)](./02-Digital-Forensic/Network_Traffic_Forensic_and_Mobile_Artifacts_Extraction.pdf)**

## Technical Stack & Utilities
* **Operating Systems:** Linux Administration, Linux CLI.
* **Defensive Utilities:** Snort IDS, Iptables Firewall, GHex, Wireshark.
*  **Offensive & Audit Tools:** Nmap, FLawfinder, Scapy, ADB.
*  **Programming & Frameworks:** Python, Bash, HTML Web Basics

---
**Contact**
* **Email:** pedrolechi1997@gmail.com
