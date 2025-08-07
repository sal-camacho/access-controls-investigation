# 🔐 Access Controls Investigation: Payroll Incident Analysis

This project documents a cybersecurity incident involving unauthorized access to payroll systems. It analyzes the root causes, identifies access control failures, and proposes mitigation strategies using the AAA framework (Authentication, Authorization, Accounting). The format mirrors the structured approach used in the `data-handling-practices` repository.

---
| **Category**       | **Details**                                                                                                                                                     |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Notes**          | - Incident occurred on **10/03/23** at **8:29 AM**. <br> - User identified as **Robert Taylor Jr.**, a former legal contractor with **administrator access**. <br> - IP address used: `152.207.255.255`. <br> - Device name was unfamiliar, suggesting use of a **personal computer**. |
| **Issues**         | - **Access was not revoked** after contract ended in **2019**, violating the **principle of least privilege**. <br> - No audit procedures were in place to detect dormant accounts. <br> - Sensitive resources were stored in a **shared cloud drive** without role-based restrictions. |
| **Recommendations**| - Implement the **AAA framework**: Authentication, Authorization, and Accounting. <br> - Enable **multi-factor authentication (MFA)**. <br> - Enforce **role-based access controls (RBAC)**. <br> - Set **automated account expiration** (e.g., 30-day limits for contractors). <br> - Conduct **regular audits** to identify dormant or misused accounts. |



## 📊 Access Control Worksheet Table

| **Section**             | **Details**                                                                                                                                                 |
|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Incident Summary**    | On October 3, 2023, at 8:29 AM, a login occurred from IP address `152.207.255.255`. The user was Robert Taylor Jr., a former legal contractor with admin access. His contract ended in 2019, yet his account remained active and was used to access payroll systems nearly four years later. The device used had an unfamiliar name, suggesting it may have been a personal computer. |
| **Authorization Issues**| Robert Taylor Jr. retained elevated privileges long after his contract expired, violating the principle of least privilege. No audit procedures were in place to detect dormant accounts. The business also used a shared cloud drive for sensitive resources, lacking role-based restrictions and proper authorization boundaries. |
| **Recommendations**     | - Implement the AAA framework: Authentication, Authorization, and Accounting. <br> - Enable multi-factor authentication (MFA). <br> - Enforce role-based access controls (RBAC). <br> - Set automated account expiration (e.g., 30-day limits for contractors). <br> - Conduct regular audits to identify dormant or misused accounts. |
| **Reflection**          | This investigation demonstrated how poor access control hygiene can expose a business to serious risks. By analyzing event logs, identifying privilege mismanagement, and proposing targeted mitigations, I applied cybersecurity principles to a real-world scenario. The exemplar provided a solid foundation, but my approach added depth through forensic analysis and strategic control recommendations. Together, they form a comprehensive response that strengthens the business’s authentication, authorization, and accounting practices. |

---

## 📁 Repo Structure Suggestion

You can organize this in your repo like so:

