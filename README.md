# Microsoft SC-300: Identity and Access Administrator Study Notes (2026)

Open-source revision notes, domain weightings, and configuration checklists for the **Microsoft Certified: Identity and Access Administrator Associate (SC-300)** exam.

For interactive scenario questions, solution explanations, and mock exam simulations, visit **[CertInsights](https://certinsights.com/exams/microsoft/sc-300-practice-questions/)**.

---

## Official Exam Domain Weightings

| Domain | Weight | Key Technologies Evaluated |
| :--- | :---: | :--- |
| **Implement Identities in Microsoft Entra ID** | 25–30% | Users, Dynamic Groups, Administrative Units, Entra Connect Sync, B2B/B2C |
| **Implement Authentication and Access Management** | 25–30% | Phishing-Resistant MFA, Conditional Access, Identity Protection (User & Sign-in Risk) |
| **Implement Access Management for Apps** | 10–15% | Enterprise Applications, App Registrations, SAML/OIDC, Application Proxy |
| **Plan and Implement Identity Governance** | 25–30% | Privileged Identity Management (PIM), Access Reviews, Entitlement Management |

---

## Core Architectural Study Guides

* **[Microsoft Entra Conditional Access Study Guide](https://certinsights.com/guides/sc-300/microsoft-entra-conditional-access-sc-300-study-guide/)** – Policy evaluation logic, blocking legacy authentication, and report-only testing.
* **[Microsoft Entra Access Reviews & Guest Lifecycle Guide](https://certinsights.com/guides/sc-300/microsoft-entra-access-reviews/)** – Multi-stage reviews, reviewer selection, and automated inactive guest cleanup.
* **[SC-300 30-Day Study Plan](https://certinsights.com/guides/sc-300/sc-300-study-plan/)** – Week-by-week preparation schedule and hands-on lab objectives.
* **[How to Pass SC-300 on Your First Attempt](https://certinsights.com/guides/sc-300/how-to-pass-sc-300/)** – Case study navigation rules, time management, and using Microsoft Learn during the test.

---

## Quick Exam-Day Checkpoints

1. **Case Studies Are Locked Upon Submission:** Once you finish a case study section and move forward, you cannot return to review those questions.
2. **User Risk vs. Sign-in Risk:** User risk indicates compromised credentials (remediate via password change + MFA); sign-in risk indicates an anomalous authentication attempt (remediate via MFA).
3. **PIM Assignments:** Always select **Eligible** (rather than Active) when a scenario requires Just-in-Time (JIT) elevation and least-privilege enforcement.

---

Maintained by the contributors at **[CertInsights.com](https://certinsights.com/)**.
