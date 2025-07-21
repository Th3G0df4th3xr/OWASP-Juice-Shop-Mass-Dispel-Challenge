# OWASP Juice Shop: Mass Dispel Challenge - Advanced Exploitation Techniques

## A Deep Dive into 14 Methodologies for Mass Session Invalidation

This repository serves as a comprehensive collection of advanced offensive security research, detailing 14 distinct methodologies to successfully complete the 'Mass Dispel' challenge within the OWASP Juice Shop application. My objective with this project is to showcase profound understanding and practical application of various cybersecurity concepts, ranging from common web vulnerabilities to more complex, timing-sensitive, and logic-abusing exploitation vectors.

Each method is meticulously documented in its dedicated subfolder, providing:
* A 'README.md' with an in-depth, technical explanation of the vulnerability, its underlying principles, and its specific application within the Juice Shop context.
* A 'TODO.md' file outlining the step-by-step process for successful exploitation, including commands, expected outputs, and intricate technical details.

This research highlights the critical importance of secure coding practices, robust authentication and authorization mechanisms, and comprehensive security testing. By demonstrating these diverse attack paths, this repository aims to contribute to the broader understanding of web application security and foster a proactive approach to vulnerability remediation.

---

## Challenge Overview: 'Mass Dispel'

The 'Mass Dispel' challenge in OWASP Juice Shop requires an attacker to invalidate or remove a significant number of user sessions or comments, typically without direct, authorized administrative access. This challenge is designed to test an attacker's ability to identify and exploit vulnerabilities that allow for large-scale impact on user data or system state. It pushes beyond simple single-instance exploitation, requiring a deeper understanding of how batch operations, session management, and underlying application logic can be leveraged for mass actions.

---

## Table of Contents (Exploitation Methodologies):

Each link below points to a dedicated folder containing the detailed explanation and step-by-step guide for that specific method.

1.  [Method-1-Insecure-Direct-Object-Reference-IDOR-for-Deletion](./Method-1-Insecure-Direct-Object-Reference-IDOR-for-Deletion/README.md)
2.  [Method-2-Batch-API-Mass-Deletion](./Method-2-Batch-API-Mass-Deletion/README.md)
3.  [Method-3-CSRF-on-Session-Ending-Endpoints](./Method-3-CSRF-on-Session-Ending-Endpoints/README.md)
4.  [Method-4-SQL-Injection-on-Deletion-Endpoint](./Method-4-SQL-Injection-on-Deletion-Endpoint/README.md)
5.  [Method-5-NoSQL-Injection-for-Session-Deletion](./Method-5-NoSQL-Injection-for-Session-Deletion/README.md)
6.  [Method-6-Privilege-Escalation-to-Admin-Functionality](./Method-6-Privilege-Escalation-to-Admin-Functionality/README.md)
7.  [Method-7-XSS-Leading-to-Session-Deletion](./Method-7-XSS-Leading-to-Session-Deletion/README.md)
8.  [Method-8-Race-Condition-for-Deletion](./Method-8-Race-Condition-for-Deletion/README.md)
9.  [Method-9-Predictable-Public-Session-Destruction-Links](./Method-9-Predictable-Public-Session-Destruction-Links/README.md)
10. [Method-10-JWT-Forgery-or-Key-Confusion](./Method-10-JWT-Forgery-or-Key-Confusion/README.md)
11. [Method-11-UI-Logic-Abuse-Shift-Click-Notification-Dismissal](./Method-11-UI-Logic-Abuse-Shift-Click-Notification-Dismissal/README.md)
12. [Method-12-DOM-Mutation-via-DevTools-or-Self-XSS](./Method-12-DOM-Mutation-via-DevTools-or-Self-XSS/README.md)
13. [Method-13-Admin-API-Enumeration-Hidden-Endpoint-Access](./Method-13-Admin-API-Enumeration-Hidden-Endpoint-Access/README.md)
14. [Method-14-Cache-Invalidation-Session-Store-Poisoning](./Method-14-Cache-Invalidation-Session-Store-Poisoning/README.md)

---

## How to Use This Repository:

1.  **Clone:** `git clone https://github.com/Th3G0df4th3xr/OWASP-Juice-Shop-Mass-Dispel-Challenge.git`
2.  **Navigate:** `cd OWASP-Juice-Shop-Mass-Dispel-Challenge`
3.  **Explore:** Dive into each method's folder to understand the attack vectors, technical explanations, and detailed exploitation steps.
4.  **Practice:** Spin up your own OWASP Juice Shop instance (highly recommended) and attempt to replicate these attacks to solidify your understanding.

---

## Disclaimer:

This repository is created for educational and research purposes only. The information provided herein is intended to demonstrate potential vulnerabilities and advanced exploitation techniques in a controlled environment (OWASP Juice Shop). Any attempts to use this information for malicious activities on systems you do not own or have explicit authorization to test are strictly prohibited and illegal. Always act ethically and responsibly.

---

## Author:

**Th3G0df4th3xr**
* GitHub: [https://github.com/Th3G0df4th3xr](https://github.com/Th3G0df4th3xr)

---

## License:

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
