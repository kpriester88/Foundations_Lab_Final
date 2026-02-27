# Lab Report: Cybersecurity Foundations Intensive
## Foundations_Lab_Final

**Author:** Kevon Priester  
**Institutional Affiliation:** [The Knowledge House]  
**Course:** Night 1: The Professional Identity & Workbench  
**Instructor:** Night 1 Cyber Tutor  
**Date:** February 23, 2026  

---

### Project Overview
This repository serves as the primary technical workbench for the 2026 Cybersecurity Foundations course. It establishes a version-controlled environment for deploying network security configurations, cloud security assessments, and GRC compliance documentation.

### System Specifications
The following hardware and network metrics define the local environment for this technical baseline:

* **Operating System:** Windows 11 Pro (64-bit)
* **System Memory (RAM):** 32 GB DDR4
* **Graphics Memory (VRAM):** 12 GB Dedicated GDDR6
* **Network Throughput:** 929.78 Mbps Download / 932.00 Mbps Upload (Symmetric Fiber-Optic Baseline)

## Hello World


# Lab Report: Network Analysis & Threat Modeling
## Lab_01_Network_Analysis

**Author:** Kevon Priester  
**Institutional Affiliation:** [The Knowledge House]     
**Course:** Night 2: The Digital Landscape & Threat Modeling  
**Date:** February 24, 2026  

---

### I. Executive Summary
*Reviewing the Data Breach of Petco in December 2025

### II. Security Philosophy 
My security philosophy centers on the principle of continuous governance. As seen in the December 2025 Petco data breach, the exposure of sensitive PII, including Social Security numbers and driver’s licenses, was not the result of a hack, but a 'misconfigured setting' (TechCrunch, 2025). This underscores that confidentiality is often lost through internal drift rather than external force. In my lab environment, I will implement CIS Control #12 by enforcing strict configuration baselines to ensure that no 'inadvertent setting' compromises the integrity of the environment."
|

### III. Technical Findings & Metrics

* **Observation 1:** NIST CSF Standards - This falls under the Protect (Data Security) and Govern (Risk Management Strategy) functions. A robust "Govern" function would have had "Drift Detection" to catch that setting change.
* 
* **Observation 2:** CIS Control Mapping: - This maps directly to Control #3: Data Protection and Control #12: Network Infrastructure Management (specifically secure configuration).
* 
* ### IV. The CIA Triad Assessment
*Identify which pillar was the focus of this lab:*
* **Confidentiality:** [High Risk] An inadvertent software setting in a Petco application made highly sensitive personal identifiable information accessible via the Internet
* **Integrity:** [Medium Risk] An open setting often implies that the 'write' permissions may have been poorly guarded as 'read' permissions. 
* **Availability:** [Medium Risk] Because of the breach, Petco had to take down parts of its Vetco Clinics website offline to remediate the vulnerability.

---
### V. Conclusion & Mitigation
This data breach can be seen as a governance drift, not a hack. The software worked as designed but a setting had ultimately failed, leading to the leaked information. There should have been a Principle of Least Exposure put into place, to minimize the access of sensitive data being leaked on the Internet. Also there should have been a stronger accountability at hand to monitor when settings have been changed. 

### VI. APA References
TechCrunch. (2025, December 8). Petco's security lapse affected customers' SSNs, drivers' licenses and more. https://techcrunch.com/2025/12/08/petcos-security-lapse-affected-customers-ssns-drivers-licenses-and-more/

