🔐 Identity Governance & Privileged Access Management
Microsoft Entra ID Security Project
📌 Project Overview

This project demonstrates the implementation of Identity Governance and Privileged Access Management controls using Microsoft Entra ID.

The objective was to simulate an enterprise environment where privileged roles and security group memberships must be continuously reviewed to enforce least privilege and reduce insider threat risks.

🎯 Objectives

Monitor privileged role assignments

Conduct structured access reviews

Detect inactive users

Enforce least privilege access

Improve governance visibility

🛠 Technologies Used

Microsoft Entra ID

Privileged Identity Management (PIM)

Identity Governance

Access Reviews

Security Groups

Role-Based Access Control (RBAC)

🏗 Architecture Flow

Users
⬇
Security Group
⬇
Access Review Policy
⬇
Activity-Based Recommendations
⬇
Approve / Deny Decision
⬇
Automatic Access Update

This model ensures continuous governance of privileged access.

🔧 Implementation Steps
1️⃣ Privileged Role Review

Reviewed Global Administrator role via PIM

Evaluated assignment type (Permanent vs Eligible)

Analyzed risk exposure of permanent assignments

2️⃣ Security Group Configuration

Created a Security Group

Added test users

Simulated active and inactive account scenarios

3️⃣ Access Review Setup

Initiated Access Review for group membership

Enabled recommendation engine

Configured review scope and reviewer

4️⃣ Governance Enforcement

Evaluated system recommendations

Approved active users

Denied inactive users

Enforced automatic access updates

🛡 Security Principles Applied

Least Privilege

Zero Trust Model

Continuous Access Evaluation

Risk-Based Decision Making

Privileged Access Governance

📈 Business Impact

This implementation demonstrates how organizations can:

Reduce dormant privileged accounts

Prevent privilege creep

Strengthen identity security posture

Improve compliance readiness

Maintain structured access lifecycle control

📚 Key Learning Outcomes

Hands-on experience with PIM configuration

Practical implementation of Access Reviews

Understanding of privileged access risk mitigation

Governance lifecycle management

🚀 Future Enhancements

Enforce Just-In-Time (JIT) activation

Integrate Conditional Access policies

Implement Identity Protection

Automate reporting using Microsoft Graph AP

 Career Focus

Currently preparing for AZ-500 (Azure Security Engineer Associate) and deepening expertise in Cloud Identity & Access Management (IAM).

Open to entry-level Cloud Security / IAM roles
