# Engagement Assessment Planner

Welcome to the Engagement Assessment Planner! This repository provides a clear path for stakeholders to determine if they require a **Penetration Test** or a **Red Team Assessment**. It's designed to help your organization select the most suitable offensive security assessment by evaluating your unique goals, security maturity, and desired outcomes.

Should you conduct a **Penetration Test** or a **Red Team Engagement**?

---

### Think of it this way...

***Penetration Testing** answers the question: Can an attacker find vulnerabilities in these specific systems?* It's a broad, noisy search for security flaws.

***Red Teaming** answers the question: How effective are our people, processes, and technology at detecting and responding to a stealthy, objective-driven attack?*

* **A Penetration Test** is like a building inspector checking every window and door of a building, looking for any possible unlocked entry point. They'll shake every handle and check every lock, providing a big list of all the weak spots.

* **A Red Team Engagement** is like a team of simulated burglars trying to steal a specific high-value painting from inside the building. They will use a single, unlocked window, move silently, avoid guards, and disable cameras, all to test the building's security guards, camera systems, and response procedures. Their goal isn't to find every unlocked window, but to achieve their objective without being caught.

---

## Key Differences at a Glance

| Feature               | Penetration Test                                                              | Red Team Engagement                                                                   |
| :-------------------- | :---------------------------------------------------------------------------- | :------------------------------------------------------------------------------------ |
| **Primary Goal** | Find and document as many vulnerabilities as possible.                        | Test the organization's detection and response capabilities (the "Blue Team").        |
| **Scope** | **Narrow and well-defined** (e.g., a specific web app, an IP range).          | **Broad and flexible**, often encompassing the entire organization (digital & physical). |
| **Methodology** | Can be "noisy" with automated scanning mixed with manual testing.             | **Stealth and evasion** are paramount. Simulates a real adversary's Tactics (TTPs).   |
| **Primary Target** | **Technology** (servers, applications, networks).                             | **People, Processes, and Technology (PPT)**.                                          |
| **Typical Timeframe** | 1-4 weeks.                                                                    | 3-8 weeks or longer.                                                                  |
| **Primary Deliverable** | A comprehensive report of technical vulnerabilities and remediation steps.    | A strategic report on the Blue Team's performance and security gaps.                  |

---

## Assessment Questionnaire

Answer the following questions to determine the right engagement for you.

#### 1. What is your primary objective for this assessment?
* **(A)** We need a comprehensive list of vulnerabilities in a specific system or application to prioritize our patching and defensive efforts.
* **(B)** We want to test our security team's (SOC/Blue Team) real-world ability to detect and respond to a sophisticated, objective-driven attack.

> **Result:** If you chose **(A)**, a **Penetration Test** is likely the best fit. If you chose **(B)**, you are leaning towards a **Red Team Engagement**.

#### 2. What is your organization's current security maturity?
* **(A)** We are in the early stages. We may not have a 24/7 security monitoring capability, a formal Security Operations Center (SOC), or a tested incident response (IR) plan.
* **(B)** We have a mature security program, including a dedicated Blue Team/SOC, advanced security tools (like EDR, SIEM), and an established IR plan we want to validate.

> **Result:** If you chose **(A)**, a **Penetration Test** is the most valuable starting point. The value of a Red Team is lost if no one is there to detect their activity. If you chose **(B)**, your organization is ready for a **Red Team Engagement**.

#### 3. Is this assessment primarily for compliance?
* **(A)** Yes, we need to satisfy a requirement for a regulatory or compliance framework (e.g., PCI DSS, HIPAA, SOC 2).
* **(B)** No, this assessment is driven by our internal goal to improve our security posture.

> **Result:** If you chose **(A)**, you most likely need a **Penetration Test**. Most compliance frameworks explicitly require a "pentest" or "vulnerability assessment." If you chose **(B)**, either assessment could be appropriate, so your other answers are more important.

#### 4. What is the desired scope of the assessment?
* **(A)** We want to test a limited set of assets, such as a new web application, our external network perimeter, or a specific mobile app.
* **(B)** We want to test our organization as a whole. The scope could include our employees (via social engineering), physical locations, and all digital infrastructure.

> **Result:** If you chose **(A)**, you are describing the scope of a **Penetration Test**. If you chose **(B)**, you are describing a **Red Team Engagement**.

---

## Conclusion

* If your answers were mostly **(A)**, you should start with a **Penetration Test**. It will provide the foundational vulnerability data you need to strengthen your defenses.
* If your answers were mostly **(B)**, your organization is ready to be challenged by a **Red Team Engagement** to truly test your defensive capabilities.

Use the templates in the `/TEMPLATES` directory to help you scope your chosen assessment.
