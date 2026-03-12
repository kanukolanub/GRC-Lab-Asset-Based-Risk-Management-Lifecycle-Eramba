# GRC-Lab-Asset-Based-Risk-Management-Lifecycle-Eramba-

🎯 Overview
This project demonstrates the end-to-end configuration of a Risk Management Framework using the Eramba Community Edition. The lab bridges the gap between organizational structure and technical risk by establishing a mathematical foundation for risk analysis and linking it to physical business assets.

By defining a formal Risk Appetite, this lab simulates a real-world corporate environment where security decisions are driven by data and organizational thresholds rather than guesswork.

🛠️ Technology Stack
GRC Platform: Eramba Community Edition

Framework Reference: ISO 27005 (Information Security Risk Management)

Environment: Self-hosted Virtualized GRC Lab

🚀 Lab Workflow
Phase 1: Risk Strategy & Configuration
Before identifying risks, I established the "Rules of Engagement" within the platform:

Risk Classifications: Defined a 3x3 matrix for Likelihood (1-3) and Impact (1-3).

Calculation Methodology: Configured the system to use Multiplication (L × I) to determine the Raw Risk Score.

Risk Appetite: Set a threshold of 5. This acts as the automated "Alert" system; any risk scoring 6 or higher is flagged as "Above Appetite," requiring immediate remediation.

Phase 2: Building Organizational Context
Risks were mapped to the following organizational hierarchy to ensure accountability:

Business Unit: IT Operations

Business Process: User Identity Management

Asset: Active Directory Server (Systems/Hardware)

Phase 3: Risk Identification and Analysis
I conducted a targeted risk assessment for the primary asset:

Identified Risk: Unauthorized access to Active Directory via compromised credentials.

Qualitative Analysis: * Likelihood: 2 (Possible)

Impact: 3 (High)

Result: The system calculated a Risk Score of 6.

Outcome: Because the score (6) exceeded the defined Appetite (5), Eramba automatically moved the risk into a "High/Critical" status, signaling a need for control implementation.

🧠 Key Skills & Takeaways
Methodology Design: Demonstrated the ability to configure the mathematical "brain" of a GRC tool.

Asset-Risk Linkage: Proved that technical risks (Compromised AD) have direct business owners (IT Ops), facilitating better communication between technical and executive teams.

Threshold Management: Showcased how "Risk Appetite" is used in a professional setting to prioritize budget and labor toward the most critical threats.

Tool Proficiency: Gained advanced hands-on experience with Eramba’s logic, settings, and reporting dashboards.
