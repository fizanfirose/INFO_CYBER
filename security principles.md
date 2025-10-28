# SECURITY PRINCIPLES
# Learning objectives
- Understanding the CIA Triad and its importance.
- explain risk. privacy , and accountability
- relate security principles to real world cyber security and trustworthy.
#CIA Triads
- Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

  | Element              | Description                                                | Example                                        |
  | -------------------- | ---------------------------------------------------------- | ---------------------------------------------- |
  | Confidentiality      | Ensures data is accessible only to authorized users.       | Encrypting files                               |
  | Integrity            | Ensures data is accurate,consistent,and not tampered with. | Using hashing,digital signatures,checksums.    |
  | Availability         | Ensures systems and data are available when needed         | Redundant servers , backups , DDoS protection. |
  
<img width="167" height="148" alt="download" src="https://github.com/user-attachments/assets/ce44b265-4d21-4c97-9aa8-f1c6b7f52261" />

 
 ## KEY CONCEPTS
 - Data breaches often occur when one or more CIA principles are compromised.
 - balance is key too much focus on one (eg. availability) can weaker another(eg. confididentiality)
## examples 
- Confidentiality Violation: Unauthorized access to customer data (e.g, Facebook-Cambridge Analytica case).
- Integrity Violation: Tampered medical data in hospitals leading to misdiagnosis.
- Availability Violation: DDoS attack on banking websites preventing service access.

## RISK 
- DEFINITION : Probability of a threat exploiting a vulnerability to cause harm

## Components
- Threat - something that can cause damage.
- Vulnerability → weakness that can be exploited
- Impact → damage if threat is realized
## formula:
Risk = threat x vulnerability x impact 
## example
- threat : phishing
- vulnerability : employee lack of awareness
- impact : creadential theft , financial loss

<img width="304" height="166" alt="download" src="https://github.com/user-attachments/assets/294025b7-48d5-4bd0-ac62-7868f2fda3c8" />

## privacy 
- Protecting personal and sensitive information of individuals.
- Governed by laws like GDPR,DRDP Act(india),HIPAA.
- freedom from unauthorized intrusion : state of being let alone and able to keep certain especially personal matters to oneself see

## KEY PRACTICES
- data minimization
- informed consent
- data anonymization
Example : A healthcare app must not share user health data without consent.

## Accountability
Ensuring every action in an IT system can be traced back to an individual.

## Achieved through:
- logging and auditing
- user access tracking
- non-repudiation mechanisms
  Examples : Audit logs in firewalls to trace malicious user actions.

## Real-world Case Studies:

| CASE | Description | VIOLATED PRINCIPLE |
|------|-------------|---------------|
| Wanna cry (2017) | Ransomware disabled hospital systems worldwide| Availability |
| Equifax Breach (2017) | Personal data of 143M users leaked | Confidentiality and integrity |
| Twitter Hack (2020) | Insider access to admin tools | Confidentiality and accountability |















