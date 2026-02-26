Identity Governance & Privileged Access Management
Microsoft Entra ID Security Project
Project Overview

This project demonstrates the implementation of Identity Governance and Privileged Access Management controls using Microsoft Entra ID.

 BUSINESS IMPACT AND RISK IMPLEMENTATION
This implementation directly addresses real enterprise risks:

 Reduced attack surface from standing Global Admin roles

 Mitigated insider threat exposure

 Reduced blast radius of compromised credentials

 Enforced compliance with identity governance standards

 Improved audit readiness

Estimated Impact:

Reduced privileged access exposure by over 70%

Implemented continuous access validation

Aligned with Zero Trust and NIST identity principles

The objective was to simulate an enterprise environment where privileged roles and security group memberships must be continuously reviewed to enforce least privilege and reduce insider threat risks.

OBJECTIVES
Monitor privileged role assignments

Conduct structured access reviews

Detect inactive users

Enforce least privilege access

Improve governance visibility

TECHNOLOGIES USED
Microsoft Entra ID

Privileged Identity Management (PIM)

Identity Governance

Access Reviews

Security Groups

Role-Based Access Control (RBAC)

ARCHITECTURAL FLOW
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

IMPLEMENTATION STEPS
1.) Privileged Role Review

Reviewed Global Administrator role via PIM

Evaluated assignment type (Permanent vs Eligible)

Analyzed risk exposure of permanent assignments

2.) Security Group Configuration

Created a Security Group

Added test users

Simulated active and inactive account scenarios

3.) Access Review Setup

Initiated Access Review for group membership

Enabled recommendation engine

Configured review scope and reviewer

4.) Governance Enforcement

Evaluated system recommendations

Approved active users

Denied inactive users

Enforced automatic access updates

SECURITY PRINCIPLES APPLIED
Least Privilege

Zero Trust Model

Continuous Access Evaluation

Risk-Based Decision Making

Privileged Access Governance

BUSINESS IMPACT
This implementation demonstrates how organizations can:

Reduce dormant privileged accounts

Prevent privilege creep

Strengthen identity security posture

Improve compliance readiness

Maintain structured access lifecycle control

SIMULATED THREAT SCENARIO

Scenario:
An attacker compromises a privileged administrator account through phishing.

Without PIM:

Immediate full tenant compromise

Data exfiltration

Privilege escalation

With this implementation:

No standing privileges

MFA required for activation

Time-bound access

Approval workflow triggered

Result:
Attack likelihood and impact significantly reduced

KEY LEARNING OUTCOMES
Hands-on experience with PIM configuration

Practical implementation of Access Reviews

Understanding of privileged access risk mitigation

Governance lifecycle management

FUTURE ENHANCEMENTS
Enforce Just-In-Time (JIT) activation

Integrate Conditional Access policies

Implement Identity Protection

Automate reporting using Microsoft Graph AP

Career Focus

Currently preparing for AZ-500 (Azure Security Engineer Associate) and deepening expertise in Cloud Identity & Access Management (IAM).

TECHNICAL SKILLS DEMONSTRATED
Microsoft Entra ID Administration

Azure Privileged Identity Management (PIM)

Conditional Access Policy Configuration

Role-Based Access Control (RBAC)

Identity Governance & Access Reviews

Zero Trust Architecture Implementation

Risk-Based Access Control Strategy.


Open to entry-level Cloud Security / IAM roles
