# TryHackMe – Intro to Cyber Threat Intel Writeup

**Room Name:** Intro to Cyber Threat Intel
**Type:** Theory / Reading  
**Difficulty:** Beginner  
**Room Link:** [https://tryhackme.com/room/cyberthreatintel](https://tryhackme.com/room/cyberthreatintel)
**Focus Areas:** SOC Operations, CTI Basics, Intelligence Frameworks

---

## Room Purpose

This room introduces Cyber Threat Inelligence and frameworks that are used to share intelligence.

---

## Key Takeaways

### Section 1: [Cyber Threat Intelligence]
- CTI primarily allows cyber professionals to understand how your operational environment and your adversary interacts and also how to defend that environment against any and all attacks
- Threat intelligence can be gathered internally, community-based, and externally.
- Threat intel can be broken up into 4 classifications: Strategic, Technical, Tactical, and Operaational

### Section 2: CTI Lifecycle
- This is a six-phase cycle that takes raw data and converts into information that can be used into triaging security incidents.
- These steps are:
  - Direction: Objectives and goals that pose questions related to incident investigation
  - Collection: Gathering data using different resources to address the objectives from the Direction step
  - Processing: Taking data then sorting and organizing the data into a useable and understandable format
  - Analysis: Taking the organized data and gaining insights and decisiions related to your objective
  - Dissemination: Providing the intelligence in different formats that are in relation to how each shareholder group can understand it
  - Feedback: Gaining feedback from stakeholders to improve the intellgence process and the loop starts over again
 
### Section 3: [CTI Standards & Frameworks]
- MTIRE ATT&CK: Takes Tactics, Techniquest, and Procedures and categorizes them in order to understand how adversaries conduct themselves during cyberattacks.
- TAXII: A protocol that defines how CTI can be exchanged between different organizations and systems.
- STIX: Standardized language to help specify, capture, characterize, and share threat intelligence in a readable and consistent format.
- Cyber Kill Chain: Breaks down adversary actions into steps to help identify which activities occurred during which stage during an attack.
- Diamond Model: Analyzes cyberattakcs by breaking down cyber intrusions into four elements: Adversary, Victim, Infrastructure, and Capability. Helps understand comlex attack scenarios and identifying Indicators of Compromise. 

---

## Real-World Application

Let's say an organization experiences a ransomware attack. By using CTI and the outlined lifecycle, the security team can identify the objective on how the attack occured and start the process. 

They will collect data from many sources, like system logs and threat feeds and process and analyze them. They use the ATT&CK framework to map the attack to known tactics and techniques. The then use STIX and TAXII to share IoC with other organizations and law enforcement to help keep everyone in the loop.

The organization then will receive the feedback from other th eother groups to help mitigate the curren issue but also strengthen against future attacks.


---

## Author
Joshua Lee – [[LinkedIn Profile](https://www.linkedin.com/in/joshua-michael-lee/)] – [[GitHub Profile](https://github.com/JoshuaLeeBSCSIA)]
