### **Page 1 (Cover Page)**

**Title:**
**Security Assessment Report**
*Advanced Manual Pentest • Automated Vulnerability Scan*

**Target:**
**NuageCX Security**
Corporate Web Application

**Report Date:**
*August 13, 2025*

**Footer Disclaimer:**

> ATTENTION: This document contains proprietary and confidential information belonging to NuageCX – Cybersecurity Solutions. The information is intended solely for the client’s authorized use. By accessing this document, you agree not to copy, disclose, distribute, or reproduce its contents without prior written consent from NuageCX. Unauthorized disclosure or distribution is strictly prohibited.

---


### **Page 2 **

**Assessment Performed By**

* **Aarav Mehta**
  *Lead Security Analyst*

* **Priya Sharma**
  *Senior Penetration Tester*

---

**About NuageCX**

At **NuageCX**, we follow a comprehensive, risk-focused methodology to identify and remediate vulnerabilities in web applications before malicious actors can exploit them. Our approach combines **rigorous manual testing (80%)** with **selective automated scanning (20%)**, ensuring that every assessment is **thorough, accurate, and aligned with industry best practices**.

Our goal is to **simulate real-world cyberattacks** using advanced techniques and tools, uncovering security weaknesses that automated scanners alone often miss. The findings are then translated into **clear, actionable remediation guidance** for our clients, followed by a **post-patching re-test** to validate that all vulnerabilities have been effectively resolved.

---

**NuageCX – Cybersecurity Solutions**
📧 *[contact@nuagecx.com](mailto:contact@nuagecx.com)*
📍 Speciality Business Centre, A 108, Baner - Balewadi Rd,
  Balewadi, Pune, Maharashtra 411045

---

### **Page 3 – Table of Contents**

**Table of Contents**

**Overview**

1. Executive Summary
2. Scope of Engagement
3. Resolution Statistics

**Pentest Details**

1. Assessment Methodology
2. Assessment Timeline and Duration

**Vulnerabilities**

1. Summary Table of Findings
2. Detailed Vulnerability Analysis

**Appendix**

1. Appendix A — Measurement Scales
2. Appendix B — Resolution Status
3. Appendix C — Risk Score Calculation
4. Appendix D — Test Case References

---

### **Page 4 – Executive Summary**

**Overview**

**Executive Summary**

NuageCX – Cybersecurity Solutions was engaged by **\[Client Name]** to conduct a **comprehensive penetration test** of the target web application from **\[Start Date]** to **\[End Date]**. This engagement included **80% manual testing** and **20% automated scanning**, performed within the agreed scope.

The assessment was conducted from an external threat actor’s perspective with the following objectives:

* Identify security flaws, misconfigurations, and logical vulnerabilities that could be exploited to compromise confidentiality, integrity, or availability.
* Assess the effectiveness of existing security controls and identify potential gaps.
* Simulate real-world attack scenarios to validate potential business and technical impacts.
* Provide clear, prioritized remediation recommendations to strengthen the application’s security posture.

**Key Findings:**

* A total of **\[X] vulnerabilities/recommendations** were identified.
* Risk scores ranged from **\[lowest score]** to **\[highest score]**, with an average score of **\[average score]**.
* The most critical vulnerabilities could potentially lead to **\[data exposure, financial loss, reputational impact, etc.]** if exploited.

Following remediation, NuageCX performed a **verification retest**, confirming that all reported vulnerabilities had been successfully fixed.

---


Alright — now that I’ve seen the style of your first 4 pages, I’ll create **pages 5, 6, and 7** in the exact same **Astra-style layout** but with **NuageCX professional wording**.

---

## **Page 5 – Vulnerabilities Overview**

**Vulnerabilities**

**Overview Table**

| Severity  | Total | Resolved | Pending | Accepted Risk |
| --------- | ----- | -------- | ------- | ------------- |
| Critical  | 3     | 3        | 0       | 0             |
| High      | 4     | 4        | 0       | 0             |
| Medium    | 6     | 6        | 0       | 0             |
| Low       | 2     | 2        | 0       | 0             |
| Info      | 0     | 0        | 0       | 0             |
| **Total** | 15    | 15       | 0       | 0             |


---

## **Page 6 – Pentest Details**

**Pentest Details**

**Assessment Methodology**

The engagement was carried out using NuageCX’s **Hybrid Penetration Testing Framework**, blending **advanced manual testing (80%)** with **strategic automated scanning (20%)** to achieve maximum coverage and accuracy.

Testing followed globally recognized security standards, including:

* **OWASP Web Security Testing Guide (WSTG)**
* **OWASP Top 10 & API Security Top 10**
* **NIST SP 800-115**

Our methodology replicates **sophisticated real-world attack scenarios** rather than relying solely on automated tool output. This ensures the discovery of vulnerabilities often missed by traditional scanning.

**Focus Areas of Testing:**

* **Authentication & Session Management** — Broken authentication, session fixation, insecure password recovery flows.
* **Access Control** — Vertical/horizontal privilege escalation, IDOR, resource access bypass.
* **Input Validation & Injection Risks** — SQL injection, XSS, template injection, command execution.
* **Configuration & Deployment Security** — Exposed admin panels, default credentials, security misconfigurations.
* **Data Protection** — Weak encryption, improper handling of sensitive data in transit or at rest.

All identified findings were **validated manually** to eliminate false positives. Post-remediation **verification testing** was performed to confirm that vulnerabilities had been resolved effectively before closure.

---

## **Page 7 – Assessment Duration and Dates**

**Assessment Duration and Dates**

| Scan Mode             | Target Name              | Authentication | Started     | Completed   |
| --------------------- | ------------------------ | -------------- | ----------- | ----------- |
| Manual Pentest (VAPT) | Client Production WebApp | 0 users        | 03 Aug 2025 | 07 Aug 2025 |

**Certificates**

A **Remediation Validation Certificate** is issued by NuageCX when all **Critical** and **High** severity vulnerabilities have been addressed, and **at least 90%** of the total findings are resolved. Remaining issues, if any, must be classified as **Low** or **Informational**, or documented as **accepted risks** by the client.

For this engagement, the certificate will be issued **after final re-validation**, ensuring that the application meets NuageCX’s stringent security benchmarks.

---


## **Page 8 – Vulnerabilities Overview Table**

**Vulnerabilities**
**Overview Table**

| No. | Target       | Title                                                                                                  | Severity | Risk Score | Status | Link |
| --- | ------------ | ------------------------------------------------------------------------------------------------------ | -------- | ---------- | ------ | ---- |
| 1   | Demo Web App | **\[CRITICAL] Web Shell Can Be Uploaded To Gain Complete Access To Server**                            | Critical | 9.2        | Solved | Open |
| 2   | Demo Web App | **\[CRITICAL] Broken Access Control Leads to Unauthorized Privilege Escalation**                       | Critical | 8.9        | Solved | Open |
| 3   | Demo Web App | **\[CRITICAL] Admin Account Takeover On Update Contact Details**                                       | Critical | 8.7        | Solved | Open |
| 4   | Demo Web App | Unprotected Mgami – Can Be Used As A Backdoor. Full Complete Database Access.                          | High     | 6.9        | Solved | Open |
| 5   | Demo Web App | Stripe API Key Disclosed                                                                               | High     | 6.8        | Solved | Open |
| 6   | Demo Web App | Possible To Bypass Work Email Only Restriction And Gain Access To Other Domains                        | High     | 6.8        | Solved | Open |
| 7   | Demo Web App | Possible For Lower Privileged Users To See Details Of Admin Users                                      | High     | 6.6        | Solved | Open |
| 8   | Demo Web App | Outdated and Vulnerable Components In Use                                                              | Medium   | 5.0        | Solved | Open |
| 9   | Demo Web App | Reverse Tabnabbing                                                                                     | Medium   | 4.8        | Solved | Open |
| 10  | Demo Web App | Insecure HTTP Cookies                                                                                  | Medium   | 4.8        | Solved | Open |
| 11  | Demo Web App | Missing API Security Headers                                                                           | Medium   | 4.8        | Solved | Open |
| 12  | Demo Web App | Possible To Prevent Normal Users From Booking Tickets By Performing Large Number Of False Pre-Bookings | Medium   | 4.7        | Solved | Open |
| 13  | Demo Web App | Cross Domain Referrer Leakage                                                                          | Medium   | 4.3        | Solved | Open |
| 14  | Demo Web App | Secure SSH Access                                                                                      | Low      | 2.8        | Solved | Open |
| 15  | Demo Web App | No CAPTCHA Implemented                                                                                 | Low      | 2.5        | Solved | Open |

---

## **Page 9 – Details of Vulnerabilities Found**

**1. \[CRITICAL] Web Shell Can Be Uploaded To Gain Complete Access To Server**
**Severity:** Critical
**Status:** Solved
**Risk Score:** 9.2/10
**CVSS:** (CVSS:3.1/AV\:N/AC\:H/PR\:N/UI\:N/S\:C/C\:H/I\:H/A\:H)
**CWE:** 434: Unrestricted Upload of File with Dangerous Type
**Labels:** HIPAA, PCI DSS, ISO 27001, GDPR, SOC 2, SOC 2 – Security, OWASP 2021, OWASP 2021 – A01: Broken Access Control

---

### **Description**

During the pentest, we observed that it is possible for attackers to create a new account on the website and **upload a web-shell** through the profile photo upload feature.

Using the upload areas available on the website, it is possible to upload **Web Shells** i.e., executable PHP/ASPX/Python files. With this vulnerability, a hacker can modify/delete/steal files & access the database on the website. This means that user passwords, payment gateway keys, etc., are compromised.

A web shell is a script that can be uploaded to a web server to enable remote administration of the machine. Infected web servers can be either Internet-facing or internal to the network, where the web shell is used to pivot further to internal hosts.

File type checks & MIME checks should be performed BOTH on the client-side (JavaScript) & on the server-side (PHP, ASPX). Note that file type checks implemented in JavaScript can easily be bypassed.

---

### **Impact**

Web shells are frequently used in compromises due to the combination of remote access and functionality. Even simple web shells can have a considerable impact and often maintain a minimal presence. Web shells are utilized for the following purposes:

* To harvest and exfiltrate sensitive data and credentials
* To upload additional malware for infection and scanning of further victims
* To use as a relay point to issue commands to hosts inside the network without direct Internet access
* To use as command-and-control infrastructure, potentially in the form of a bot in a botnet or in support of compromises to additional external networks. This could occur if the adversary intends to maintain long-term persistence

---

### **Affected Components**

* [https://phps.example.com/2/welcome/3](https://phps.example.com/2/welcome/3)
* POST [https://phps.example.com/2/settings/account?id=47789](https://phps.example.com/2/settings/account?id=47789)
* [https://phps.example.com/2/settings/account-branding-email?id=47789](https://phps.example.com/2/settings/account-branding-email?id=47789)

---

### **Steps to Reproduce**

(These are shown with screenshots on Page 10)

---

## **Page 10 – Steps to Reproduce & Suggested Fix**

### **Steps to Reproduce**

1. Visit `https://example.com/account/create` and create a free account
2. Navigate to the **Profile page** where the profile photo can be uploaded
3. Click on **Browse for Photo** button to open the file upload modal
4. In the window that opens, select and upload any PHP file/web-shell
5. Even though an error is displayed, it was found that the file was indeed uploaded to `/public_html/2/uploads/profile_photos` folder
6. Now open the PHP file through the web browser by Direct Object Reference such as:
   `https://example.com/uploads/profile_photos/johnDoe.jpg()`

---

### **Suggested Fix**

* Once the issue has been verified, perform an exhaustive search of `.php`, `.aspx` and other executable files in the uploads folder
* Executable file types should be rejected server-side (`.php`, `.php3`, `.php4`, `.phtml`, `.pl`, `.py`, `.jsp`, `.asp`, `.htm`, `.shtml`, `.sh`, `.cgi`)
* Only allow whitelisted extensions (like `.pdf`, `.jpg`, `.png`)
* File type checking should be performed server-side
* Files should be checked for ‘double extensions’
* MIME type should be checked to allow only the image
* Disable code execution in the uploads folder by adding the following to the `.htaccess` file:

```apache
<Files ~ "\.php|\.php3|\.php4|\.phtml|\.pl|\.py|\.jsp|\.asp|\.htm|\.shtml|\.sh|\.cgi$">
  Order allow,deny
  Deny from all
</Files>
```

---


