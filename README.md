<div align="center">

# RedTeam

  <a href=""><br><img title="Made in ISRAEL" src="https://img.shields.io/badge/MADE%20IN-ISRAEL-blue?style=for-the-badge"></a>

![image](https://user-images.githubusercontent.com/51442719/170375086-701a2ab3-7421-41d5-a61b-1b28b6018100.png)

RedTeam - Red Team Tools

# RED TEAM DEVELOPMENT CHECKLIST

</div>

- [ ] Determine required knowledge and skills
- [ ] Identify and implement alternate methods for bridging knowledge gaps
- [ ] Develop roles and responsibilities guide
- [ ] Develop red team methodology
- [ ] Develop TTP guidance for engagements
- [ ] Includes Bag of tricks
- [ ] Develop data collection guide and tools
- [ ] Develop operational process plan
- [ ] Develop communication plan template
- [ ] Develop ROE template:  [Rules of Engagement (RoE)](#rules-of-engagement-roe)
- [ ] Develop technical briefing template
- [ ] Develop report template: [Diablo](https://github.com/Anlominus/Diablo)

# Concept of Operation (CONOPS)
### There is not a set standard of a CONOPS document; 
#### Below is an outline of critical components that should be included in a CONOPS
  - [ ] Client Name
  - [ ] Service Provider
  - [ ] Timeframe
  - [ ] General Objectives/Phases
  - [ ] Other Training Objectives (Exfiltration)
  - [ ] High-Level Tools/Techniques planned to be used
  - [ ] Threat group to emulate (if any)

# Resource Plan
- Header
  - [ ] Personnel writing
  - [ ] Dates
  - [ ] Customer
- Engagement Dates
  - [ ] Reconnaissance Dates
  - [ ] Initial Compromise Dates
  - [ ] Post-Exploitation and Persistence Dates
  - [ ] Misc. Dates
- Knowledge Required (optional)
  - [ ] Reconnaissance
  - [ ] Initial Compromise
  - [ ] Post-Exploitation
- Resource Requirements
  - [ ] Personnel
  - [ ] Hardware
  - [ ] Cloud
  - [ ] Misc.

# Mission Plan
- [ ] Objectives:
- [ ] Operators
- [ ] Exploits/Attacks
- [ ] Targets 
  - [ ] Users:
  - [ ] Machines:
  - [ ] Objectives:
- [ ] Execution plan variations


# PLANNING - RED TEAM ENGAGEMENT CHECKLIST
- [ ] Engagement Planning
  - [ ] ROE
    - [ ] Event Communication plan
    - [ ] Distribute Deconfliction Process
    - [ ] Entry point/method
    - [ ] Scope
    - [ ] Goals/Objectives (should address at least one of the following)
      - [ ] Protect
      - [ ] Detect
      - [ ] Respond
      - [ ] Restore
    - [ ] Target Restrictions
    - [ ] Target Infrastructure / Asset verification / Approvals
  - [ ] Scenario Development
  - [ ] Operational Impact planning
- [ ] Develop threat profiles
    - [ ] Network and Host Activity
    - [ ] IOC Generation (incl subsequent Analysis) and Management
- [ ] Plan threat infrastructure
  - [ ] Tier 1
    - [ ] IPs
    - [ ] Systems
    - [ ] Redirectors
    - [ ] PPS
  - [ ] Tier 2
    - [ ] IPs
    - [ ] Systems
    - [ ] Redirectors
    - [ ] PPS
  - [ ] Tier 3
  - [ ] IPs
  - [ ] Systems
  - [ ] Redirectors
  - [ ] PPS
  - [ ] Deploy tools to infrastructure
- [ ] Data collection repository


## RED TEAM ENGAGEMENT GOAL PLANNING
### COMMON GOALS: MEASURE AND OBSERVE ...
- A THREAT’S ABILITY TO ACCESS TO COMMON AND RESTRICTED AREAS (PHYSICAL)
  - What ability does a threat have to access common areas?
  - What ability does a threat have to access restricted areas?
  - Can a threat use access gained to enable cyber capabilities?
  - What impacts can a threat have through gained access?

- A THREAT’S ABILITY TO ACCESS KEY/CRITICAL SYSTEMS
  - Can a threat access key/critical systems?
  - What impacts can a threat have on key/critical systems?

- A THREAT’S ABILITY TO MOVE FREELY THROUGHOUT A NETWORK
  - What ability does a threat have to freely move throughout a network?

- A THREAT’S ABILITY TO GAIN DOMAIN WIDE AND LOCAL ADMINISTRATIVE ACCESS?
  - What ability does a threat have to gain local administrative access?
  - What ability does a threat have to gain domain administrative access?
  - What ability does a threat have to gain elevated access?

- A THREAT’S ABILITY TO ACCESS OR IDENTIFY SENSITIVE INFORMATION
  - What ability does a threat have to access sensitive information?
  - What ability does a threat have to identify sensitive information?

- A THREAT’S ABILITY TO EXFILTRATE DATA OUTSIDE AN ORGANIZATION
  - What ability does a threat have to exfiltrate data outside an organization?
  - How much data must be exfiltrated to impact an organization?

- A THREAT’S ABILITY TO ACT UNDETECTED FOR A GIVEN TIME FRAME
  - How long can a threat go undetected?
  - Can a threat achieve its goals undetected?
  - What must a threat do to stimulate a reaction from an organization?

- A THREAT’S ABILITY TO PERFORM OPERATIONAL IMPACTS
  - What impacts can a threat perform against an organization?
  - How can a threat affect X?

---

# Rules of Engagement (RoE)
- Rules of Engagement
  - Executive Summary	
    - Overarching summary of all contents and authorization within RoE document
  - Purpose
    - Defines why the RoE document is used
  - References	
    - Any references used throughout the RoE document (HIPAA, ISO, etc.)
  - Scope
    - Statement of the agreement to restrictions and guidelines
  - Definitions 
    - Definitions of technical terms used throughout the RoE document
  - Rules of Engagement and Support Agreement	
    - Defines obligations of both parties and general technical expectations of engagement conduct
  - Provisions	
    - Define exceptions and additional information from the Rules of Engagement
  - Requirements, Restrictions, and Authority 
    - Define specific expectations of the red team cell
  - Ground Rules
    - Define limitations of the red team cell's interactions
  - Resolution of Issues/Points of Contact
    - Contains all essential personnel involved in an engagement
  - Authorization
    - Statement of authorization for the engagement
  - Approval 
    - Signatures from both parties approving all subsections of the preceding document
  - Appendix
    - Any further information from preceding subsections	

---

 <div align="center">


# Campaign planning 
### The campaign summary we will be using consists of four different plans varying in-depth and coverage adapted from military operations documents.

Type of Plan	| Explanation of Plan |	Plan Contents
---|---|---
Engagement Plan |	An overarching description of technical requirements of the red team. | CONOPS, Resource and Personnel Requirements, Timelines
Operations Plan	| An expansion of the Engagement Plan. Goes further into specifics of each detail. | Operators, Known Information, Responsibilities, etc.
Mission Plan |	The exact commands to run and execution time of the engagement. | Commands to run, Time Objectives, Responsible Operator, etc.
Remediation Plan |	Defines how the engagement will proceed after the campaign is finished. | Report, Remediation consultation, etc.

### Engagement Plan:

Component	| Purpose
---|---
CONOPS (Concept of Operations) | Non-technically written overview of how the red team meets client objectives and target the client.
Resource plan | Includes timelines and information required for the red team to be successful—any resource requirements: personnel, hardware, cloud requirements.

### Operations Plan:

Component	| Purpose
---|---
Personnel  | Information on employee requirements.
Stopping conditions | How and why should the red team stop during the engagement.
RoE (optional) | -
Technical requirements | What knowledge will the red team need to be successful.

### Mission Plan:

Component	| Purpose
---|---
Command playbooks (optional) | Exact commands and tools to run, including when, why, and how. Commonly seen in larger teams with many operators at varying skill levels.
Execution times | Times to begin stages of engagement. Can optionally include exact times to execute tools and commands.
Responsibilities/roles | Who does what, when.

### Remediation Plan (optional):

Component	| Purpose
---|---
Report | Summary of engagement details and report of findings.
Remediation/consultation | How will the client remediate findings? It can be included in the report or discussed in a meeting between the client and the red team.

</div>

---

- TryHackMe: [Red Team Engagements](https://tryhackme.com/room/redteamengagements): 
  - Learn the steps and procedures of a red team engagement, including planning, frameworks, and documentation.
- [Red Teaming Toolkit](https://reconshell.com/red-teaming-toolkit/)  
---

![Alt](https://repobeats.axiom.co/api/embed/fd78a1ef4e01d34a2cb9c01a0b0eba5de00d556d.svg "Repobeats analytics image")
