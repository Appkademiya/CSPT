# Appkademiya Certified OT/SCADA Penetration Tester (CSPT)
## Practical Examination Environment

## 📋 Overview
Welcome to the practical examination environment for the **Certified OT/SCADA Penetration Tester (CSPT)** certification. This lab simulates a fully segmented, multi-tiered industrial enterprise network, ranging from Corporate IT infrastructure down to the Operational Technology (OT) floor and physical control processes. 

Candidates are tasked with performing an authorized security assessment, demonstrating the ability to pivot across network boundaries, identify web and application flaws, analyze industrial protocols, and evaluate cyber-physical risks within a simulated smart-manufacturing facility.

---

## 🎯 What Is Tested
This examination rigorously evaluates a candidate's practical proficiency across several key cybersecurity domains:

* **Enterprise-to-OT Network Pivoting:** Navigating through strict network boundaries (Corporate IT, Industrial DMZ, Supervisory Control, and Basic Control segments) using advanced tunneling and proxy techniques.
* **Web & API Application Security:** Identifying and exploiting input validation flaws, authentication bypasses, and session management vulnerabilities in corporate and supervisory web interfaces.
* **Industrial Protocol Analysis:** Interacting with Modbus/TCP communications, analyzing packet captures, and auditing industrial telemetry services.
* **Industrial Control Systems (ICS) Security:** Assessing Programmable Logic Controllers (PLCs), Safety Instrumented Systems (SIS), and human-machine interfaces (HMI) to understand how digital exploits translate into physical process impacts.

---

## 🛡️ Rules of Engagement (ROE)
To maintain the integrity of the examination and simulate a professional red-team engagement, all candidates must adhere to the following rules:

1. **Scope Limitation:** Testing is strictly restricted to the local containerized environment deployed via this repository. Any scanning or interaction outside your local lab network is strictly prohibited.
2. **Flag Submission:** Findings are validated through unique flag strings discovered during the assessment. Do not share, publish, or discuss flag formats or discovery paths with other candidates.
3. **Integrity of Environment:** Do not attempt to intentionally corrupt, destabilize, or execute denial-of-service (DoS) attacks against the shared infrastructure services or host daemon.
4. **Tooling Freedom:** Candidates are permitted to use any tools available within their provided attack container or standard penetration testing toolsets (e.g., `nmap`, `curl`, `proxychains`, custom scripts).

---

## 🚀 Quick Start & Deployment

### Prerequisites
* A system with **Docker** and **Docker Compose** installed.
* Adequate system resources to run a 9-container segmented network topology.
