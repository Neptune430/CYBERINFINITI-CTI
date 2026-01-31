# CYBERINFINITI-CTI
 An Enterprise Cyber Threat Intelligence Program for Cyberinfiniti Ltd using OPENCTI as a central intelligence platform and ALIENVAULT OTX CONNECTOR for live data/threat ingestion.


## 📌 Overview
**CYBERINFINITI-CTI** is an enterprise-focused Cyber Threat Intelligence (CTI) program developed by Team 8 Soc team, to support the security and risk posture of **Cyberinfiniti Ltd**, an information technology and cybersecurity services organization.

The project simulates an internal Threat Intelligence function responsible for identifying, analyzing, and contextualizing cyber threats relevant to Cyberinfiniti Ltd’s operational environment, industry sector, and geographic footprint. Using **OpenCTI**  as a central intelligence platform, deployed in a secure **AWS cloud environment** and enriched with **AlienVault Open Threat Exchange (OTX)**, this assessment correlates global threat data with business-specific intelligence requirements.

The primary objective of this CTI is to transform raw threat data into **actionable, executive-ready intelligence** that enables Cyberinfiniti Ltd’s leadership and security teams to make informed strategic, operational, and defensive decisions. The assessment covers sector-based threats, nation-state and criminal adversaries, victim profiling, and politically motivated threat actors, all aligned to established intelligence and adversary analysis frameworks.
---

## 🎯 Objectives
- Assess the **industry-specific threat landscape** impacting an IT & cybersecurity organization  
- Analyze **national-level cyber threats** affecting organizational headquarters and operations  
- Profile **recent victims**, associated threat actors, and attack campaigns  
- Investigate a **politically motivated APT group** involved in high-impact operations  
- Translate technical intelligence into **actionable executive recommendations**

---

## 🏗️ Architecture & Deployment
The OpenCTI platform was deployed in a **secure AWS cloud environment** to reflect production-grade CTI operations.

**Environment Details**
- Cloud Provider: AWS  
- Instance Type: EC2 (Ubuntu Server)  
- Deployment Model: Docker & Docker Compose  
- Intelligence Platform: OpenCTI  
- Threat Feed Integration: AlienVault OTX  

**Core Components**
- OpenCTI API & Web Interface  
- Graph Database (STIX 2.1 Data Model)  
- RabbitMQ (Message Queuing)  
- Elasticsearch, Redis, MinIO  
- AlienVault OTX Connector  

This modular architecture enables scalable ingestion, correlation, and visualization of threat intelligence.

---

## 🔍 Methodology
The assessment followed the **Threat Intelligence Lifecycle**:

1. **Direction** – Defined intelligence requirements aligned to organizational risk  
2. **Collection** – Ingested intelligence via OpenCTI and AlienVault OTX  
3. **Processing** – Normalized indicators, entities, and relationships  
4. **Analysis** – Applied structured analytical frameworks  
5. **Dissemination** – Produced analyst-level and executive-level reporting  

**Analytical Frameworks Used**
- Diamond Model of Intrusion Analysis  
- Cyber / Global Kill Chain  
- MITRE ATT&CK Framework  
- Timeline & Campaign Analysis  

---

## 🏭 Industry Sector Focus
**Sector:** Information Technology & Cybersecurity (MSSP / IT Services)

### Key Threat Categories Identified
- Ransomware & Double Extortion Campaigns  
- State-Sponsored Espionage (APT Activity)  
- Credential Compromise & Lateral Movement  
- Silent Data Exfiltration Operations  

**Notable Threat Actors**
- Akira Ransomware Group  
- APT17  
- POLONIUM  

---

## 🌍 National Threat Landscape
**Headquarters Location:** Nigeria  

### Assessed Threat Actors
- **Hilalrat (UNC788)** – Financially motivated cybercrime operations in West Africa  
- **Hoplight / APT38 (Lazarus Group)** – State-sponsored financial cyber operations  

---

## 🎯 Victim-Centric Threat Mapping
The project analyzed realistic victim profiles using OpenCTI intelligence:

- **Government Institutions**  
- **Healthcare Organizations**  
- **Defense Sector Entities**

Each profile includes:
- Diamond Model Analysis  
- Kill Chain Mapping  
- MITRE ATT&CK technique alignment  
- Detection & mitigation recommendations  

---

## ⚠️ Politically Motivated Threat Actor Assessment
### Focused Threat Group: **Sandworm (APT44 / Seashell Blizzard)**

- Russia-aligned, state-sponsored threat actor  
- Known for destructive cyber operations and wiper malware  
- Recent campaigns targeting **energy and critical infrastructure sectors**

**Analyzed Campaigns**
- Poland Energy Sector (December 2025)  
- Ukrainian Government & Energy Sectors (2025)  

---

## 🛡️ Detection & Mitigation Highlights
- Behavioral detection for credential abuse and lateral movement  
- Monitoring for living-off-the-land techniques  
- DNS, proxy, and encrypted C2 traffic visibility  
- Sector-specific defensive controls aligned with MITRE ATT&CK  

---

## 📈 Key Findings
- Credential compromise remains the dominant initial access vector  
- Ransomware and APT activity continue to converge in tooling and access methods  
- Politically motivated destructive attacks are increasing in frequency  
- Cross-sector threat reuse elevates supply-chain risk  

---

## 📚 Lessons Learned
- Threat intelligence is most effective when aligned with business context  
- Automation and enrichment significantly improve analyst efficiency  
- Executive-ready reporting is critical for informed decision-making  
- CTI platforms like OpenCTI enable meaningful correlation across threats, victims, and campaigns  

---

## 👥 Team Contributions
**Team Lead:** John Ofulue  
- Task coordination and sprint leadership  
- OpenCTI deployment support  
- Report and presentation contributions  

This project was completed collaboratively by Team 8 during the CyBlack Threat Intelligence Sprint.

---

## 🔗 References
- OpenCTI Documentation  
- AlienVault Open Threat Exchange (OTX)  
- MITRE ATT&CK Framework  
- AWS, Docker & Ubuntu Documentation  

---

## 🚀 Why This Project Matters
This repository demonstrates **real-world Cyber Threat Intelligence skills**, including:
-Cloud  
-CTI platform deployment  
- Threat actor profiling  
- Analytical framework application  
- Executive-level intelligence reporting  



It is designed to reflect the expectations of **SOC Analysts, Threat Intelligence Analysts, and Blue Team professionals**.

