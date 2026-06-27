# Cisco Networking Academy: The Cybersecurity Landscape

Welcome to my repository for the **"The Cybersecurity Landscape"** course by Cisco Networking Academy. This single-page document serves as my digital notebook, where I compile key takeaways, concepts, and insights from my studies.

## 📌 Course Overview
This course explores the modern digital threat landscape, focusing on how vulnerabilities impact organizations globally, the profiles of threat actors, and the fundamentals of cybersecurity defense.

## 📖 My Study Notes & Key Concepts

### Fundamental Principles
1. **No system, no network is truly safe.**
2. The more technology evolves and the more we rely on IT, the higher the stakes are when security is compromised.
3. We must always approach new technologies with security in our minds.

---

### Understanding Cybersecurity (The CIA Triad)
Data security is built upon three core pillars, balanced against specific threat vectors:

* **Confidentiality**
  * **Ensured by:** Authentication & Authorization
  * **Threat to avoid:** Disclosure (unauthorized access)
* **Integrity**
  * **Ensured by:** Non-repudiation & Authenticity
  * **Threat to avoid:** Alteration (unauthorized modification)
* **Availability**
  * **Threat to avoid:** Denial or Destruction of data/systems

---

### Data Classification Levels

* **Restricted:** Intellectual property or other highly proprietary information.
* **Confidential:** Customer personal and payment data, as well as employees' personal information.
* **Private or Internal-only:** Internal communications and strategic organization plans.
* **Public:** Information accessible to anyone (e.g., T-shirt models, costs, and sizes).

---

### Components of a Successful Cybersecurity Strategy

A robust security posture relies on the balance of four fundamental pillars:

### Successful Cybersecurity Strategy

| **Human & Operational** | People & Policies |
| :---|  :--- |
| **Technical & Execution** | Processes & Technologies |

---

## Direct Summary of Data Categories
* **PII (Personally Identifiable Information):** Direct identifiers (name, email) or combined indirect identifiers (gender + ZIP code + date of birth).
* **PHI (Protected Health Information):** Medical records, diagnoses, and health histories linked to a patient's identity.
* **PCI (Payment Card Data):** Cardholder information (card number, expiration date) and critical authentication data (CVV, PIN).

---

## Essential Breakdown of Regulations
* **GDPR (Focus on PII):** Requires systems to be built under the *Privacy by Design* concept. It enforces **data minimization** (collecting only what is strictly necessary) and obligates engineering to guarantee the *Right to be Forgotten* (complete deletion of a user's data).
* **HIPAA (Focus on PHI):** Divided into privacy and security rules. In technical practice, it requires **end-to-end encryption**, Role-Based Access Control (RBAC), and **strict audit logs** (tracking exactly who accessed each medical record and when).
* **PCI-DSS (Focus on PCI):** A rigid industry standard. It strictly prohibits storing authentication data (such as the CVV) after a transaction is authorized. It requires isolated **network segmentation** for payments and the use of **tokenization** to protect the actual card number.

---

## Key Takeaways (The Security Challenge)
* **Security is Not Static:** There is no single tool that you can just install and forget; cybersecurity is a continuous, evolving discipline.
* **Holistic Approach:** It requires mapping data, identities, and assets to cross-reference vulnerabilities with a combined strategy of policies, processes, and technologies.
* **The Big Challenge:** A security program must constantly balance robust protection with **usability** (ensuring operations and business are not disrupted) while working within tight budget and resource limitations.

## Direct Summary of Frameworks and Controls
*   **The Purpose:** Frameworks provide structured, standardized guidelines so organizations can strategically build strong security programs, manage risks, and prove they are trustworthy to clients and regulators.
*   **Strategic Choice:** No company implements everything; each organization chooses specific frameworks based on their industry, operations, and compliance requirements.
*   **Core Organizations & Standards:**
    *   **CIS Controls V8:** A prioritized list of operational actions to stop pervasive cyberattacks.
    *   **ISO/IEC 27000 Series:** International standards for managing information security systems.
    *   **NIST (CSF & RMF):** US government-backed frameworks for managing cybersecurity risk and system lifecycles.
    *   **OWASP Top Ten:** A globally recognized awareness document focusing on critical web application vulnerabilities.

---

## Essential Breakdown of the Frameworks
*   **CIS Controls (Center for Internet Security):** Highly prescriptive and actionable. Unlike broad policy frameworks, CIS tells you *exactly* what technical defenses to implement first (e.g., inventorying assets, configuring hardware securely) based on actual threat data.
*   **ISO/IEC 27001:** The heavyweight international standard. It focuses on establishing an **ISMS (Information Security Management System)**. It is audit-heavy, meaning companies get officially certified to prove to global business partners that their data governance is mature.
*   **NIST Cybersecurity Framework (CSF):** Built around five core functions (*Identify, Protect, Detect, Respond, Recover*). It provides a common, accessible language for both technical teams and corporate boardrooms to measure risk.
*   **NIST Risk Management Framework (RMF):** A highly structured, 7-step process specifically designed for federal systems (but used elsewhere) to integrate security, privacy, and cyber risk management into system lifecycles.
*   **OWASP Top Ten:** The gold standard for **Application Security (AppSec)**. It does not look at infrastructure or policies; instead, it ranks the ten most critical coding flaws and vulnerabilities (like Injection or Broken Access Control) that developers and defenders must mitigate in software.

## Direct Summary of Risk and Communication
*   **The Risk Equation:** Risk occurs at the exact intersection where a threat matches a specific vulnerability ($\text{Risk} = \text{Threat} \times \text{Vulnerability}$).
*   **Measurement:** Risk is calculated by assessing two key metrics: the **probability** (likelihood) of an incident occurring and its potential **impact** (damage) on the organization.
*   **Strategic Blueprint:** Frameworks and controls act as standardized blueprints to help organizations systematically identify, control, and mitigate these risks.
*   **The Ultimate Goal:** Security professionals must translate technical risks into business terms to communicate persuasively with diverse audiences, ensuring leadership can make informed strategic choices.

---

## Essential Breakdown of Risk Treatment and Strategy

When a risk is identified, evaluated, and measured, an organization cannot simply ignore it. There are four distinct strategic paths (Risk Treatment Options) to handle it, and choosing the right one depends heavily on budget, resources, and operational impact:

*   **Mitigate (Reduction):** Implementing technical controls, policies, or tools to lower the probability or impact of the risk. 
    *   *Example:* Installing an EDR (*Endpoint Detection and Response*) agent on servers to reduce the impact of malware infections.
*   **Transfer (Sharing):** Shifting the financial or operational burden of the risk to a third party.
    *   *Example:* Purchasing a comprehensive **cyber insurance** policy or outsourcing infrastructure hosting to a secure cloud provider (sharing the infrastructure risk).
*   **Avoid (Elimination):** Completely removing the hazard or changing the business process to entirely eliminate the vulnerability/threat exposure.
    *   *Example:* Deciding *not* to collect customer credit card data locally (using a third-party payment gateway instead) to completely avoid PCI compliance risks.
*   **Accept (Retention):** Acknowledging that a risk exists but choosing to take no action because the cost of mitigation outweighs the potential impact. This must be a formal, documented decision by leadership.
    *   *Example:* Keeping a legacy internal tool running because it is scheduled to be decommissioned in three months and poses a very low exposure threat.

---
*Educational purpose only. Tracking my learning journey through Cisco Networking Academy.*
