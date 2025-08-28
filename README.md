# Activity Overview

In this activity, you will assess the access controls used by a business. You’ll analyze their current process, identify issues, and make recommendations to improve their security practices.
Previously, you learned that access controls are security controls that manage access, authorization, and accountability of information. Authentication controls are used to verify who someone is, whereas authorization controls are used to grant a user permissions and set limits on the things they’re allowed to do. When done well, access controls are the key to decreasing the likelihood of a security risk.

## Scenario

You’re the first cybersecurity professional hired by a growing business.

Recently, a deposit was made from the business to an unknown bank account. The finance manager says they didn’t make a mistake. Fortunately, they were able to stop the payment. The owner has asked you to investigate what happened to prevent any future incidents.

To do this, you’ll need to do some accounting on the incident to better understand what happened. First, you will review the access log of the incident. Next, you will take notes that can help you identify a possible threat actor. Then, you will spot issues with the access controls that were exploited by the user. Finally, you will recommend mitigations that can improve the business' access controls and reduce the likelihood that this incident reoccurs.

## What’s Included

- Root cause analysis and control recommendations  
- Reflection on AAA framework and least privilege enforcement  
- Table summarizing notes, issues, and recommendations  

---

## Access Controls Investigation

This project documents the cybersecurity assignment: **Improve Authentication, Authorization, and Accounting for a Small Business**. It focuses on internal access control failures and applies the AAA framework to prevent unauthorized access and privilege misuse.

The task involved analyzing a real-world incident involving lingering administrator access, evaluating the root causes, and proposing security control enhancements based on the AAA model and least privilege principles.


## My Contributions

- Identified core causes: dormant administrator account and lack of access audits  
- Applied AAA framework to recommend:  
  - Multi-factor authentication (MFA)  
  - Role-based access controls (RBAC)  
  - Automated account expiration  
  - Regular access audits  

## Access Control Worksheet Table

This analyzes a real-world incident involving unauthorized payroll access, where the failure to revoke permissions led to a near financial breach. It applies the AAA framework and least privilege principles to propose remediation strategies.

| **Section**       | **Content**                                                                                                                                                     |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Notes**         | - Incident occurred on **10/03/23** at **8:29 AM**. <br> - User: **Robert Taylor Jr.**, former legal contractor with **administrator access**. <br> - IP address: `152.207.255.255`. <br> - Device name was unfamiliar, suggesting use of a **personal computer**. |
| **Issues**        | - **Access was not revoked** after contract ended in **2019**, violating the **principle of least privilege**. <br> - No audit procedures were in place to detect dormant accounts. <br> - Sensitive resources were stored in a **shared cloud drive** without role-based restrictions. |
| **Recommendations** | One technical control that could have prevented this incident is the implementation of the **AAA framework** — Authentication, Authorization, and Accounting. <br><br> Recommended actions: <br> - **Enable multi-factor authentication (MFA)**. <br> - **Enforce role-based access controls (RBAC)**. <br> - **Set automated account expiration** (e.g., 30-day limits for contractors). <br> - **Conduct regular audits** to identify and deactivate dormant or misused accounts. |

## Reflection

This activity reinforced the importance of combining technical controls with procedural oversight. By applying the AAA framework and least privilege principles, I demonstrated the ability to assess access risks, propose structured mitigations, and strengthen internal security posture. These recommendations align with cybersecurity best practices and help reduce the likelihood of future incidents.

---

## Screenshot of Completed Access Controls Worksheet, Event Log & Employee Directory
![Access Control](images/image/access-control.png)
> This image captures the full response submitted as part of the Google Cybersecurity Certificate access control activity.

<img width="945" height="713" alt="31" src="https://github.com/user-attachments/assets/525440b4-c027-41ce-8062-c6899c076dbe" />
<img width="1405" height="866" alt="32" src="https://github.com/user-attachments/assets/66e63e88-cbe6-4242-82f6-edfc134bed7e" />
<img width="1502" height="878" alt="33" src="https://github.com/user-attachments/assets/091ae91e-1af4-4898-a23f-d3d9c43ff142" />
