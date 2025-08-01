# Red Team Engagement Proposal Template

## [Customer Name] - Adversary Simulation Engagement

---

### 1. Executive Summary

This document outlines the objectives, scope, and rules of engagement for a Red Team engagement. The primary goal of this assessment is to test the effectiveness of **[Customer Name]'s** security program—including its people, processes, and technology—in detecting and responding to a simulated, real-world adversary. The engagement will be objective-based and focus on stealthy execution.

- **Engagement Window:** [Start Date] to [End Date]

---

### 2. Mission Objectives & Scope

#### 2.1 Primary Objectives (Flags)
The Red Team will attempt to achieve one or more of the following objectives without being detected and ejected from the network. Success is defined by capturing "flags."
- **[Flag 1 - e.g., Domain Admin Access]:** Obtain Domain Administrator privileges on the corporate network.
- **[Flag 2 - e.g., Exfiltrate Sensitive Data]:** Access and exfiltrate the contents of the `[Example Sensitive Database/File Share]`.
- **[Flag 3 - e.g., Access Executive Email]:** Gain access to the mailbox of a C-level executive.
- `[Add other objectives as needed]`

#### 2.2 Scope
- The scope for this engagement is the entire organization, including all subsidiaries and cloud environments.
- All employees are in scope for social engineering (e.g., phishing, vishing) attacks.
- Physical access attempts may be included if agreed upon.

#### 2.3 Prohibited Actions (Get-Out-of-Jail-Free Card)
- Any action that could cause a material disruption to the business or destroy data is strictly prohibited.
- The Red Team will not exploit vulnerabilities that could lead to widespread service instability (e.g., DoS).
- If the Blue Team/SOC detects the Red Team and can attribute their actions, they may contact the engagement lead with the evidence. If the evidence is confirmed, that attack path is considered "burned," and the Red Team may de-conflict to continue the engagement.

---

### 3. Rules of Engagement (RoE)

- **Stealth Operation:** The engagement is designed to be covert. Only a small, pre-approved list of customer stakeholders (the "White Cell") will be aware of the test. The Blue Team/SOC will **not** be notified.
- **Communication:** All communication will be handled exclusively through the White Cell lead: **[White Cell Contact Name/Email]**. There will be no direct communication with the Blue Team.
- **Engagement Halts:** The engagement can be paused or stopped at any time by the White Cell lead.
- **Threat Profile:** The Red Team will simulate the Tactics, Techniques, and Procedures (TTPs) of an adversary profile agreed upon during the kickoff call (e.g., a specific APT group, an organized crime syndicate).

---

### 4. Methodology & Phases

The engagement will simulate a full attack lifecycle:
1.  **Initial Reconnaissance:** Passive and active information gathering.
2.  **Initial Compromise:** Gaining an initial foothold via social engineering, an external vulnerability, or other means.
3.  **Persistence & C2:** Establishing a covert Command & Control channel.
4.  **Privilege Escalation & Lateral Movement:** Expanding access across the network.
5.  **Action on Objectives:** Attempting to achieve the defined "flags."
6.  **Reporting:** Detailing the entire attack narrative and providing strategic recommendations.

---

### 5. Deliverables

Upon completion of the engagement, the following will be provided:
1.  **Attack Narrative Report:** A chronological report detailing:
    - The full timeline of Red Team actions.
    - A mapping of TTPs to a framework like MITRE ATT&CK.
    - For each Red Team action, the corresponding Blue Team detection/response (or lack thereof).
    - Strategic recommendations for improving detection, response, and overall security posture.
2.  **Debrief Workshop:** A collaborative "Purple Team" workshop where the Red Team and Blue Team walk through the entire engagement timeline to identify specific gaps and improvement opportunities.
