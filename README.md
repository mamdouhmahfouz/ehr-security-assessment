# Secure EHR System – Risk & Security Assessment

This repository contains a security and risk assessment of a university hospital's **Electronic Health Record (EHR) system**.  
The project applies recognized risk management and cybersecurity practices to understand threats, evaluate business impact, and propose mitigation strategies.

---

## 1. Overview

Healthcare environments depend on EHR systems to store and process sensitive patient data and support clinical workflows.  
This project analyzes the EHR system from a cybersecurity and business continuity perspective, focusing on:

- Identifying critical information assets.
- Assessing security risks and their impact.
- Evaluating business impact and recovery requirements.
- Describing realistic attack vectors and damage scenarios.
- Recommending technical, administrative, and physical controls.

The work is structured as three main milestones.

---

## 2. Project Components

### 2.1 OCTAVE Allegro Risk Assessment (Milestone 1)

- Identifies the EHR system as the primary critical information asset.
- Maps the technical, physical, and personnel environment around the EHR (servers, network, workstations, staff, vendors, etc.).
- Describes key threat scenarios such as:
  - Phishing and credential theft.
  - Ransomware against the EHR infrastructure.
  - Denial-of-service against public-facing portals.
- Assesses likelihood and impact.
- Outlines high-level mitigation actions.

### 2.2 Business Impact Analysis (Milestone 2)

- Defines critical business assets related to the EHR, including:
  - EHR database server.
  - Network infrastructure.
  - Clinical workstations.
  - Backup and recovery systems.
  - Patient portal.
  - Remote access/VPN.
- Uses a weighted scoring model to prioritize assets based on:
  - Safety and health impact.
  - Reputation impact.
  - Operational impact.
- Defines Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO) for each asset to guide disaster recovery planning.

### 2.3 Attack Profiles and Damage Assessment (Milestone 3)

- Describes realistic attack vectors against the EHR environment, including:
  - Phishing and credential theft.
  - Credential stuffing.
  - Remote access/VPN abuse.
  - Insider threat.
  - Ransomware via software vulnerabilities.
- For each vector, outlines:
  - Attacker motivation and capabilities.
  - Best-case, most likely, and worst-case scenarios.
  - Potential impact on:
    - Patient safety and continuity of care.
    - Confidentiality of health records.
    - System availability and operations.
    - Legal, regulatory, and financial exposure.
  - Recommended countermeasures.

---

## 3. Repository Structure

```text
ehr-security-assessment/
├── Milestone 1/        # OCTAVE Allegro risk assessment worksheets and documentation
├── Milestone 2/        # Business Impact Analysis (BIA) tables and recovery planning
├── Milestone 3/        # Attack profiles and potential damage assessment
└── README.md           # Project overview (this file)
